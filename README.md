# README for EngGraph Dataset

## Overview
This dataset consists of 9,641 British English words sourced from the most frequently used terms on webpages indexed by Google. Each word has been hand-transcribed into its grapheme representation, following the transcription rules outlined in Brooks (2019). The dataset is derived from the research presented in Rose et al. (2024), titled One-Vs-Rest Neural Network English Grapheme Segmentation: A Linguistic Perspective, published in CoNLL 2024. This dataset is designed for researchers and practitioners in linguistics, natural language processing, and computational linguistics.

## Dataset Contents
Total Words: 9,641
Language: British English
Transcription Method: Manual grapheme transcription based on Brooks (2019) grapheme list and transcription rules.

## Purpose
The dataset aims to support various linguistic and computational research applications, including but not limited to:
  Language modeling
  Phonetic transcription studies
  Grapheme-to-phoneme conversion
  Natural language processing (NLP) tasks

## Dataset Format
The dataset is provided in a CSV file format with the following structure:

|Column	|Description|
|-------|-----------|
| Word | The British English word |
| Grapheme Transcription | The grapheme transcription of the word |
| Word Length | The total number of characters in the word |
| Number of Graphemes | The count of graphemes in the transcription |
| Number of Vowels | The count of vowels (a,e,i,o,u) in the word |
| Number of Consonants | The count of consonants in the word |
| Characters per Grapheme | The average number of characters per grapheme |

Example Entries are as follows:

| Word | Graphemes | Word Length | Number of Graphemes | Number of Vowels | Number of Consonants | Characters per Grapheme |
|------|-----------|-------------|---------------------|------------------|----------------------|-------------------------|
| penalty | pe-n-al-t-y | 7 | 5 | 2 | 5 | 1.4 |
| horizontal | ho-r-i-z-o-nt-al | 10 | 7 | 4 | 6 | 1.42857 |
| trustee | t-r-u-st-ee | 7 | 5 | 3 | 4 | 1.4 |

 ## Citation
If you use this dataset in your research, please cite it as follows:

Rose, S., Dethlefs, N., Kambhampati, C., 2024. One-Vs-Rest Neural Network English Grapheme Segmentation: A Linguistic Perspective, Proceedings of the 28th Conference on Computational Natural Language Learning (CoNLL). Presented at the CoNLL 2028, Association for Computational Linguistics, Miami, pp. ___-___. DOI HERE

## Licensing
This dataset is licensed under the Creative Commons Attribution 4.0 International License. You are free to share and adapt the material for any purpose, even commercially, as long as you provide appropriate credit to the original source.

## Contact Information
For inquiries or feedback regarding the dataset, please contact:

Name: Samuel Rose
Email: s.p.rose-2017@hull.ac.uk
Institution: University of Hull
