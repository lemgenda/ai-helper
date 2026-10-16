# LemGendizedAIHelperLemGend

> Fine-tuning prompt-completion instructions and technical documentation for the LemGendary AI Assistant.

## Dataset Overview

- **Category:** Technical Documentation & AI Assistant Training
- **Total Samples:** 80 (52 train / 28 val)
- **Architecture Base:** Transformer-Based Causal Language Model (Fine-Tuned Instruction Head)
- **Primary Task:** Answer architectural, operational, and development inquiries across the LemGendary ecosystem.
- **Format:** Standard JSONL supervised dialogue (`messages`: `system`, `user`, `assistant`).

## Task Category Distribution & Provenance Breakdown

This manifold is derived directly from the verified **LemGendary AI Documentation Hub** (release `v16.9.26-STABLE`):

| Task Category | Train | Val | Total Contribution |
| :--- | :--- | :--- | :--- |
| **`api_procedure`** | 5 | 2 | 7 samples |
| **`cli_procedure`** | 5 | 3 | 8 samples |
| **`cross_document_pipeline`** | 15 | 7 | 22 samples |
| **`gui_procedure`** | 5 | 2 | 7 samples |
| **`model_selection`** | 5 | 3 | 8 samples |
| **`terminology_and_invariants`** | 5 | 2 | 7 samples |
| **`troubleshooting_diagnostics`** | 7 | 6 | 13 samples |
| **`unsupported_and_negative`** | 5 | 3 | 8 samples |
| **Total Corpus** | **52** | **28** | **80 samples** |

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

- **`ai_helper_train.jsonl`**: Supervised instruction training split (52 dialogue records).
- **`ai_helper_val.jsonl`**: Held-out evaluation benchmark split (28 dialogue records).
- **`AIHelperLemGend.jpg`**: Visual preview and architecture banner.
- **`category.txt`**: Top-level categorization tag (`Technical Documentation & AI Assistant Training`).
- **`classes.txt`**: Target classification domains.
- **`dataset-metadata.json`**: Kaggle frictionless metadata manifest and JSONL conversation schema specification.
- **`dataset_info.yaml`**: Machine-readable manifest for automated PyTorch dataset loaders.
- **`index.json`**: Master sample inventory mapping all 80 records.
- **`README.md`**: Authoritative manifold documentation and category distribution.

## Physical Data Manifest

| File | Partition | Samples | Format |
| :--- | :--- | :--- | :--- |
| **`ai_helper_train.jsonl`** | Train | 52 | JSONL (OpenAI / ChatML message schema) |
| **`ai_helper_val.jsonl`** | Val | 28 | JSONL (OpenAI / ChatML message schema) |

---

**Kaggle Native Source**: [Access Dataset](https://www.kaggle.com/datasets/lemtreursi/lemgendizedaihelperlemgend)
