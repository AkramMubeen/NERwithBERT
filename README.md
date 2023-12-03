# NERwithBERT
**Named Entity Recognition with BERT**

**Problem Statement:**
This project focuses on performing one of the most renowned tasks in natural language processing, namely Named Entity Recognition (NER).

**Overview:**
Named Entity Recognition (NER) stands as a fundamental task in Natural Language Processing (NLP). The objective is to identify entities such as person names, locations, and organization names within a given corpus. As the number of these entities continues to grow, exhaustive listing in a dictionary becomes impractical. The constituent methods of these entities often exhibit regularities. Consequently, recognizing these words is typically integrated into tasks like morphological processing (e.g., Chinese segmentation) and is treated as independent processing, referred to as named entity recognition.

Named entity recognition technology plays an indispensable role in various natural language processing applications, including information extraction, information retrieval, machine translation, and question-answering systems.

Named entities, the subjects of research in named entity recognition, generally fall into three categories (entity, time, and number) and seven categories (person, place, institution, time, date, currency, and percentage). Evaluating the correctness of a named entity identification involves two key aspects: verifying the correctness of the entity's boundaries and ensuring the accurate labeling of its type.

Common errors in named entity recognition encompass correctly identified text that may be of the wrong type. Conversely, text boundaries may be incorrect, leading to inaccuracies in the identification of main entity words and part-of-speech tokens.

**Technology Utilized:**
For this project, the technology stack involves Anaconda Python 3.6, PyTorch 1.10 with GPU support (CUDA 10), and CuDNN 10. Ensure to use the latest versions of these technologies for optimal performance and compatibility.