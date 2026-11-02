# LemGendizedAIHelperLemGend

> Fine-tuning prompt-completion instructions and technical documentation for the LemGendary AI Assistant.

## Dataset Overview

- **Category:** Technical Documentation & AI Assistant Training
- **Total Samples:** 1150 (923 train / 227 val)
- **Architecture Base:** Transformer-Based Causal Language Model (Fine-Tuned Instruction Head)
- **Primary Task:** Answer architectural, operational, and development inquiries across the LemGendary ecosystem.
- **Format:** Standard JSONL supervised dialogue (`messages`: `system`, `user`, `assistant`).

## Task Category Distribution & Provenance Breakdown

This manifold is derived directly from the verified **LemGendary AI Documentation Hub** (release `v16.9.27-STABLE`):

| Task Category | Train | Val | Total Contribution |
| :--- | :--- | :--- | :--- |
| **`api_procedure`** | 14 | 5 | 19 samples |
| **`cli_procedure`** | 12 | 4 | 16 samples |
| **`cross_document_pipeline`** | 170 | 38 | 208 samples |
| **`gui_procedure`** | 29 | 8 | 37 samples |
| **`model_selection`** | 39 | 11 | 50 samples |
| **`terminology_and_invariants`** | 49 | 13 | 62 samples |
| **`troubleshooting_diagnostics`** | 91 | 22 | 113 samples |
| **`unsupported_and_negative`** | 16 | 4 | 20 samples |
| **Total Corpus** | **923** | **227** | **1150 samples** |

## Source Document Lineage

Every technical answer is strictly traceable to authoritative ecosystem documents:

1. **LemGendary AI Documentation Hub** (`index.html`)
2. **Ecosystem Architecture & Current State Manifest** (`ECOSYSTEM_ARCHITECTURE.md`, `LEMGENDARY_CURRENT_STATE.md`)
3. **Master Operations Manuals** (`MANUAL_AI_STUDIO_GUI.md`, `MANUAL_CLI.md`, `MANUAL_API.md`)
4. **Dataset Compiler & Environment Manager Whitepapers** (`PAPER_DATASET_COMPILER.md`, `PAPER_ENV_MANAGER.md`)
5. **Training Suite & Pathology Documentation** (`PAPER_TRAINING_SUITE.md`, `PAPER_TRAINING_PATHOLOGY.md`)
6. **Model-Family Architecture Whitepapers** (`PAPER_LEMGENDARY_*.md`, `PAPER_NIMA_*.md`)
7. **Canonical Glossary & AI Helper Troubleshooting Knowledge Base** (`GLOSSARY.md`, `AI_HELPER_TROUBLESHOOTING_KNOWLEDGE.md`)

## Repository Structure

Standardized directory layout for seamless integration into the **LemGendary Training Suite**:

- **`ai_helper_train.jsonl`**: Supervised instruction training split (923 dialogue records).
- **`ai_helper_val.jsonl`**: Held-out evaluation benchmark split (227 dialogue records).
- **`AIHelperLemGend.jpg`**: Visual preview and architecture banner.
- **`category.txt`**: Top-level categorization tag (`Technical Documentation & AI Assistant Training`).
- **`classes.txt`**: Target classification domains.
- **`dataset-metadata.json`**: Kaggle frictionless metadata manifest and JSONL conversation schema specification.
- **`dataset_info.yaml`**: Machine-readable manifest for automated PyTorch dataset loaders.
- **`index.json`**: Master sample inventory mapping all 1150 records.
- **`README.md`**: Authoritative manifold documentation and category distribution.

## Physical Data Manifest

| File | Partition | Samples | Format |
| :--- | :--- | :--- | :--- |
| **`data/ai_helper_train.jsonl`** | Train | 923 | JSONL (OpenAI / ChatML message schema) |
| **`data/ai_helper_val.jsonl`** | Val | 227 | JSONL (OpenAI / ChatML message schema) |

---

**Kaggle Native Source**: [Access Dataset](https://www.kaggle.com/datasets/lemtreursi/lemgendizedaihelperlemgend)
