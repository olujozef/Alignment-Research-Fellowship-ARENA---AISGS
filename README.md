# Alignment-Research-Fellowship-ARENA---AISGS


This repository contains the datasets, analysis notebooks, and research report produced as part of the Alignment Research Fellowship (ARENA) under the AI Safety Global Society.

The project examines the potential for large language models (LLMs) to embed and transmit covert signals in informal and low-resource language settings, with a focus on Pidgin English.

---

## Research Overview

**Title:**  
Embedding and Detecting Hidden Signals in Informal / Low-Resource Language (Pidgin English) Using Large Language Models

Steganography involves hiding information within ordinary communication.
With the growing deployment of LLMs, there is increasing concern that such models could be misused to embed covert signals in natural language outputs.

While most prior work has focused on high-resource languages such as English,this project investigates whether similar risks exist in informal and low-resource languages like Pidgin English.

Using rule-based encoding methods and different prompting strategies, the project evaluates both the feasibility of hidden signal embedding and the effectiveness of simple detection techniques.

Results show that LLMs can reliably embed covert signals in Pidgin English when prompted appropriately, and that even subtle encodings can be detected with high accuracy using basic statistical classifiers.

---

## Repository Structure

- `data/`  
  Datasets generated and used in the experiments (JSON format).

- `notebooks/`  
  Google Colab / Jupyter notebooks used for data generation, analysis, and evaluation.

- `docs/`  
  Research report and supporting documentation (PDF).

---

## How to Use This Repository

1. Read the research report in `docs/` for full context, methodology, and results.
2. Open the notebook in `notebooks/` using Google Colab or Jupyter Notebook.
3. Ensure dataset file paths are correctly set when running the notebook.

---

## Key Contributions

- First systematic study of linguistic steganography in Pidgin English.
- Open-source dataset and analysis pipeline for low-resource language settings.
- Comparative evaluation of prompting strategies for covert signal embedding.
- Empirical insights into AI safety risks beyond high-resource languages.

---

## Notes

This repository is intended for research transparency, reproducibility, and knowledge sharing. Questions or feedback can be raised via GitHub Issues.

---

## License

License information will be added.