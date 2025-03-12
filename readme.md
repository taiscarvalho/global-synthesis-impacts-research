### Global synthesis of peer-reviewed articles reveals blind spots in climate impacts research

This repository contains the code supporting the paper "Global synthesis of peer-reviewed articles reveals blind spots in climate impacts research." It includes scripts for text preprocessing, annotation processing, and information extraction from scientific papers:

* tokenize_papers.ipynb – Tokenizes full-text papers into sentences and preprocesses text.
* read_annotated_papers.ipynb – Reads annotated papers from the annotation software Inception.
* extract_hazard_information_abstract.ipynb – Uses LLMs to extract hazard-related information from abstracts.
*`text_classification.ipynb`* – Provides the base code for classifying text, used both for detecting relevant papers and selecting impact sentences.

## Data

- *`labelled_relevant_papers.csv`* – A dataset of papers labeled as relevant or not.  
- *`labelled_sentences.csv`* – Sentences labeled into impact-related and other categories.  
- *`labelled_sentences_impact_classes.csv`* – Impact sentences further categorized into specific impact classes.  
- *`classified_sentences.csv`* – The final classification of sentences into impact classes. 

The repository enables systematic analysis of climate impact research coverage and gaps.