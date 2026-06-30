# Scalable and Robust Named Entity Recognition in Audio Data : A Hybrid Pipeline Approach

**Author:** Lucas Lamisse

## Context
This research was conducted as part of an academic internship at the **Data Science Laboratory** within the Faculty of Information Technology at the **Industrial University of Ho Chi Minh City (IUH)**. 

*Note: Due to intellectual property guidelines, the source code for the hybrid pipeline is not publicly available in this repository.*

## Abstract
The exponential growth of audiovisual content necessitates robust automated Information Extraction systems. While Named Entity Recognition (NER) models achieve near-human performance on well-formatted written text, their accuracy degrades significantly when applied to Automatic Speech Recognition (ASR) transcripts due to the absence of punctuation and structural casing. Consequently, standard models often erroneously merge consecutive entities into semantic chimeras. Furthermore, relying entirely on Large Language Models (LLMs) to process massive audio datasets is computationally prohibitive. 

In this paper, we propose a highly scalable, hybrid NER pipeline tailored for television broadcast audio. Our approach integrates a heavy baseline utilizing a customized strict BIO-tag aggregation strategy on CamemBERT alongside a grammatical filter with the targeted deployment of an LLM (Llama 3) acting as a semantic judge. This dual architecture drastically reduces API calls and computational overhead while effectively disambiguating and splitting complex overlapping entities. We demonstrate the efficiency of our checkpointing batch-processor on a large real-world dataset, establishing a robust methodology for evaluating audio-derived NLP tasks.

## Access the Research Paper
To read the full methodology, architectural details, and evaluation metrics, please click on the PDF document provided in this repository.
