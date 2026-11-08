# LemGendizedAIHelperLemGend

> Fine-tuning prompt-completion instructions and technical documentation for the
> LemGendary AI Assistant.

## Dataset Overview

- **Category:** Technical Documentation & AI Assistant Training
- **Total Samples:** 1,140
- **Architecture Base:** Transformer-Based Causal Language Model (Fine-Tuned
  Instruction Head)
- **Primary Task:** Answer architectural, operational, and development inquiries
  across the LemGendary ecosystem.

## Composition & Lineage

This manifold is a high-fidelity merge of the following original sources:

| Source Dataset | Train | Val | Total Contribution |
| :--- | :--- | :--- | :--- |
| **LemGendary AI Documentation Hub** | 804 | 168 | 1,140 samples |
| **General AI Training Knowledge Ref...** | 804 | 168 | 1,140 samples |
| **Ecosystem Architecture and Curren...** | 804 | 168 | 1,140 samples |
| **Master Operations Manuals** | 804 | 168 | 1,140 samples |
| **Dataset Compiler and Environment...** | 804 | 168 | 1,140 samples |
| **Training Suite and Training Patho...** | 804 | 168 | 1,140 samples |
| **Model-Family Architecture Whitepa...** | 804 | 168 | 1,140 samples |
| **Canonical Glossary and AI Helper...** | 804 | 168 | 1,140 samples |
| **Curated AI LemGend instruction an...** | 804 | 168 | 1,140 samples |

## Model Training Profiles

No models are explicitly bound to this dataset in models_metadata.yaml.

## Repository Structure

Standardized directory logic for seamless integration into the **LemGendary
Training Suite**.

- **`data/`**: Dataset component.
- **`ai_helper_lemgend_colab_training.ipynb`**: Auto-generated Google Colab
  notebook for cloud training.
- **`ai_helper_lemgend_kaggle_training.ipynb`**: Auto-generated Kaggle notebook
  for cloud training.
- **`AIHelperLemGend.jpg`**: Dataset component.
- **`build_manifest.json`**: Dataset component.
- **`category.txt`**: Top-level categorization tag.
- **`classes.txt`**: Class labels mapping.
- **`dataset-metadata.json`**: Kaggle Frictionless metadata manifest, licensing,
  and schema column definitions.
- **`dataset_info.yaml`**: Manifest metadata for automated PyTorch loaders.
- **`index.json`**: Compiled metadata index mapping all dataset samples.
- **`quality_report.json`**: Dataset component.
- **`README.md`**: This documentation file.
- **`rejected_records.jsonl`**: Dataset component.
- **`source_manifest.json`**: Dataset component.

## Physical Data Manifest

| Folder | Train | Val |
| :--- | :--- | :--- |
| **data/ai_helper_train.jsonl** | 7,236 | - |
| **data/ai_helper_val.jsonl** | - | 1,512 |

---

**Kaggle Native Source**: [Access Dataset][kaggle-source]

[kaggle-source]:
  https://www.kaggle.com/datasets/lemtreursi/lemgendizedaihelperlemgend
