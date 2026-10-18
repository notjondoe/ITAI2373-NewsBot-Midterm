# ITAI2373-NewsBot-Midterm
# NewsBot Intelligence System: End-to-End NLP Pipeline

## Project Overview
The NewsBot Intelligence System is an automated media monitoring and text analytics pipeline designed to ingest unstructured news articles and transform them into structured business insights[cite: 1, 2]. Built entirely in Google Colab using free-tier resources, the system implements text preprocessing, multi-class classification, named entity recognition (NER), part-of-speech (POS) analysis, and sentiment evaluation across a 2,000-article corpus[cite: 3, 13].

## Architecture & Module Integration
* **Module 1: Real-World NLP Context:** Business case and architecture design for automated competitive intelligence and media monitoring[cite: 1, 2].
* **Module 2: Preprocessing Pipeline:** Text normalization (regex cleaning, lowercasing, HTML/URL removal), tokenization, stop word filtering, and lemmatization with spaCy.
* **Module 3: TF-IDF Extraction & Feature Analysis:** Parameter-optimized unigram/bigram vectorization, chi-squared category correlation, and mean TF-IDF distribution mapping[cite: 1, 16].
* **Module 4: POS Pattern Analysis:** Grammatical tagging to evaluate stylistic patterns and frequency distribution of nouns, verbs, adjectives, and adverbs across news domains[cite: 1, 16].
* **Module 5: Syntax Parsing & Semantic Extraction:** spaCy dependency parsing tracking structural subjects (`nsubj`, `nsubjpass`) and objects (`dobj`, `pobj`)[cite: 1, 16].
* **Module 6: Sentiment & Emotion Analysis:** Article-level compound scoring via NLTK VADER and tone classification[cite: 1, 16].
* **Module 7: Multi-Class Text Classification:** Implementation, evaluation, and comparative benchmarking of Multinomial Naive Bayes, Logistic Regression, and Random Forest models[cite: 1, 16].
* **Module 8: Named Entity Recognition:** Entity extraction targeting `PERSON`, `ORG`, `GPE`, `DATE`, and `MONEY` tags with cross-category aggregation[cite: 1, 16].

## Key Results
* **Best Performing Model:** Logistic Regression achieved highest overall accuracy (70.0%), narrowly outperforming Naive Bayes (69.25%) and Random Forest (68.75%).
* **Sentiment Analysis:** Politics generated the highest negative tone (35.25%), whereas Sports and Entertainment exhibited strong positive skews (79.41% and 76.06%, respectively).
* **Entity Extraction:** Primary entities reflected UK/global media coverage, led by geopolitical locations (US: 526, UK: 467) and high-frequency organizations (BBC: 247, Microsoft: 116, Sony: 104).

## Individual Contributions & Ownership
* **Developer:** Jonathan Aldana
* **Scope of Work:** Sole author and implementer across all 8 modules—handled Kaggle dataset acquisition/merging, Google Colab environment engineering, pipeline scripting, visual analytics generation, and documentation[cite: 16, 21].
