# clinical-llm-benchmark
Keeping track of LLM performances on various Clinical NLP tasks and datasets. 

## Question Answering
task definition comes here
dataset1 details comes here
dataset2 details comes here
| Model | MedQA (USMLE) | PubMedQA | MedMCQA | MMLU (Clinical Knowledge) | MMLU (Professional Medicine) |
|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| GPT-4 (Medprompt) | **90.2** | **82** | **79.1** | **95.8** | **95.2** |
| Med-PaLM 2 | 86.5 | 81.8 | 72.3 | 88.7 | **95.2** |
| GPT-4 (5-shot) | 81.4 | 75.2 | 72.4 | 86.4 | 93.8 |
| MEDITRON-70B (CoT + SC) | 70.2 | 81.6 | 66 | - | - |
| Llama-2-70B (CoT + SC) | 63.8 | 80 | 62.6 | - | - |
| Clinical Camel-70B (5-shot) | 60.7 | 77.9 | 54.2 | 72.8 | 75.0 |
| Apollo-7B | 56 | - | 58.21 | - | - |
| BioMistral 7B | 50.6 | 77.5 | 48.1 | 59.9 | 54.7 |
| Mistral 7B Instruct | 42 | 75.7 | 46.1 | 62.9 | 57.2 |
| BERT | 44.6 | 51.6 | 43 | - | - |
| RoBERTa | 43.3 | 52.8 | - | - | - |
| BioBERT | 30.1 | 60.2 | - | - | - |
| PubMedBERT | 38.1 | 55.8 | - | - | - |

## Entity Extraction (NER)
task definition comes here
dataset1 details comes here
dataset2 details comes here
| Model | NCBI Disease | BC5CDR Disease | BC5CDR Drug/Chem | JNLPBA |
|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| BARD (5-shot) | 95.60 | - | **98.30** | - |
| BARD (zero-shot) | **96.00** | - | 97.70 | - |
| GPT-4 (1-shot) | 48.37 | - | 82.07 | - |
| GPT-4 (zero-shot) | 56.73 | - | 74.43 | - |
| ChatGPT | 50.49 | 51.77 | 60.30 | 41.25 |
| BioELECTRA | 89.38 | 85.84 | 93.60 | **80.17** |
| PubMedBERT | 87.82 | 85.62 | 93.33 | 79.10 |
| BioBERT | 89.36 | 86.56 | 93.44 | 77.59 |
| SciBERT | 88.57 | **90.01** | 90.01 | 77.28 |
| BERT | 85.63 | 82.41 | 91.16 | 74.94 |





 
 
