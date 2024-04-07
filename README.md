# KuBERT-Central-Kurdish-BERT-Model

## Introduction
KuBERT-Central-Kurdish-BERT-Model harnesses the BERT framework to enhance computational linguistics for the Central Kurdish language. This initiative is a response to the scarcity of resources and computational models for Kurdish, which is a language with substantial linguistic diversity.

## Data Acquisition for Model Training
Data collection is a significant hurdle in training deep learning models, especially for low-resource languages like Kurdish. Sourcing sufficient data is essential for the efficacy of complex models such as BERT. The scarcity of digital resources makes accumulating Kurdish data more challenging than for many other languages. To amass a comprehensive word vector dataset for Kurdish, substantial efforts were made to compile information from various sources.

### Corpus Compilation
Three main corpora were utilized to train the Kurdish BERT model, amounting to 296.5 million tokens:

- **AsoSoft corpus**: With 188 million tokens, it includes data from websites, textbooks, and magazines.
- **AramRafeq and Muhammad Azizi corpus**: A collection of over 60 million tokens gathered from Kurdish websites.
- **Oscar 2019 corpus**: Comprising 48.5 million words, it further enriches the dataset.

This comprehensive text corpus ensures that the KuBERT model is well-equipped to understand and process Kurdish at a high level.

## Overview
The project uses the latest advances in BERT technology to better understand and process Kurdish language data. The model training incorporates a Kurdish-specific tokenizer and various classifiers, demonstrating BERT's adaptability to linguistic intricacies.

## Contributions
The integration of BERT represents a significant step forward in computational linguistics for Kurdish, providing a much-needed benchmark for future NLP efforts in under-represented languages. By leveraging a large corpus of Kurdish text, this project addresses critical gaps in language processing tools for Kurdish.

## Training Details
The BERT model undergoes extensive fine-tuning with the curated Kurdish dataset, ensuring optimal performance. Through rigorous training and evaluation, the model is prepared to handle a variety of linguistic tasks.

## Final Remarks
This README encapsulates the essence of the KuBERT-Central-Kurdish-BERT-Model project, its data acquisition efforts, and the innovative use of BERT for the Kurdish language. For a full understanding of the model's capabilities and comprehensive training details, the full documentation and accompanying study materials should be consulted.

### Relevant Links and References
- Oscar 2019 corpus: [https://oscar-corpus.com/post/oscar-2019/](https://oscar-corpus.com/post/oscar-2019/)
- AsoSoft Kurdish Text Corpus: [https://github.com/AsoSoft/AsoSoft-Text-Corpus](https://github.com/AsoSoft/AsoSoft-Text-Corpus)
- Kurdish Resources by Muhammad Azizi and AramRafeq: [https://github.com/DevelopersTree/KurdishResources/](https://github.com/DevelopersTree/KurdishResources/)

---

*Epochs: 3
*Max Token Length: 256
*Learning Rate: 1.00E-05
*Dropout Rate: 0.3
*Batch Size: 8
*GPU Utilization: Yes

---

The corpus data tables and the detailed methodology can be found in the full research paper and are summarized here for quick reference:

### Corpus Data Tables Summary

**Table 2: AsoSoft Kurdish Text Corpus**
| Source                    | Number of Tokens |
|---------------------------|------------------|
| Crawled From Websites     | 95M              |
| Text Books                | 45M              |
| Magazines                 | 48M              |
| **Sum**                   | **188M**         |

**Table 3: Muhammad Azizi and AramRafeq Text Corpus**
| Source               | Number of Tokens |
|----------------------|------------------|
| Wikipedia            | 13.5M            |
| Wishe Website        | 11M              |
| Speemedia Website    | 6.5M             |
| Kurdiu Website       | 19M              |
| Dengiamerika Website | 2M               |
| Chawg Website        | 8M               |
| **Sum**              | **60M**          |

**Table 4: The Kurdish Text Corpus Used to Train BERT**
| Corpus Name                        | Number of Tokens |
|------------------------------------|------------------|
| Oscar 2019 corpus                  | 48.5M            |
| AsoSoft corpus                     | 188M             |
| Muhammad Azizi and AramRafeq corpus| 60M              |
| **Sum**                            | **296.5M**       |
"""

