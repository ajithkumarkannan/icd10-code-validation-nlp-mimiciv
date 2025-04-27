**ICD-10 Code Validation and Clinical Text Analysis Using NLP Techniques**

This project explores the application of multiple natural language processing (NLP) techniques for validating and analyzing ICD-10-CM and ICD-10-PCS codes using the MIMIC-IV clinical dataset and CMS ICD-10 descriptions.

**Project Overview**

The goal of the project is to enhance code validation, identify semantic similarities between diagnosis and procedure codes, extract medical entities, and analyze textual patterns in standardized clinical coding systems.

**Techniques used:**

* ICD-10 Prefix Validation: Matching diagnosis and procedure codes based on shared ICD prefixes to identify clinical relationships.

* Semantic Similarity Analysis: Embedding code descriptions using ClinicalSentenceTransformers_mpnet_base_v2 and calculating cosine similarity scores.

* Named Entity Recognition (NER): Extracting clinical concepts from ICD-10-CM descriptions using SciSpaCy's en_core_sci_md model.

* Bigram Frequency Analysis: Identifying common two-word phrase patterns using statistical N-gram modeling.

**Dataset Sources**

* MIMIC-IV (v3.1): Publicly available clinical database of hospital admissions (access approved via PhysioNet).

* CMS ICD-10-CM and ICD-10-PCS Descriptions (2025 edition): Official diagnosis and procedure code descriptions.

**Tools and Libraries**

* Python (pandas, scikit-learn, matplotlib, seaborn, spaCy, SciSpaCy, sentence-transformers)

* NLP Models: ClinicalSentenceTransformers_mpnet_base_v2, SciSpaCy (en_core_sci_md)

* Word Embedding: Word2Vec Google News pretrained model

**Visualization:** Matplotlib, Seaborn

**Skills Demonstrated**

* Natural Language Processing (NLP)

* Clinical Data Analysis

* Cosine Similarity Computation

* Named Entity Recognition (NER)

* Bigram and N-gram Text Mining

* Healthcare Informatics

* Data Preprocessing

* Data Visualization

**Future Directions**

* Expansion to full clinical notes using transformer-based models (e.g., ClinicalBERT).

* Fine-tuning models for specialized tasks like procedure recommendation.

* Integration with real-world EHR data for validation.
