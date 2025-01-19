**INFO-H420 Management of Data Science and  Business Workflows - Project on Responsible Data Science**
Work: PHAM DANG PHI L. , ELEZI HERMA , BOUDJEMA MEHDI,COQUEREAU ARISTIDE, SY MOHAMED, DEMONCEAU QUENTIN

<div align="center">
    <img src="https://actus.ulb.be/medias/photo/logo-universite-libre-bruxelles_1661952138925-png?ID_FICHE=19524" alt="ULB Logo" width="300"/>
</div>
The goal of this project is to combine principles from responsible data science to study an ML 
pipeline. Specifically, you will study a classifier that predicts whether someone will have 
income “>50K” on the Adult data set.  The project asks you to investigate several responsible 
data science aspects of the ML pipeline. 
---

## Requirements

The following are required to set up and run the project:

### Software
- Python (>=3.8)
- Jupyter Notebook
- LM Studio (for local LLM exploration) [Download here](https://lmstudio.ai)

### Python Libraries
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `fairlearn` (for fairness analysis)
- `diffprivlib` (for differential privacy)
- `shap` (for explainability)
- `nltk` or `transformers` (for natural language interface)

---
## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd responsible-data-science
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Install LM Studio for local LLM usage:
   - Download and install from [LM Studio's website](https://lmstudio.ai).

---

## Usage

1. Open the project notebook:
    ```bash
    jupyter notebook responsible_data_science.ipynb
    ```

2. Follow the instructions in the notebook to complete the tasks.

3. For LLM-based explainability, ensure LM Studio is running and configured.

---

## Features

- **Classification:** End-to-end ML pipeline for the Adult dataset.
- **Fairness Analysis:** Tools to assess and improve fairness in ML models.
- **Privacy Protection:** Implementation of local differential privacy techniques.
- **Explainability:** Visualization and analysis of model decisions.
- **Natural Language Interface:** Generate textual explanations using small local LLMs.

---

## Acknowledgements

This project was completed as part of the INFO-H420 Management of Data Science and Business Workflows course.

---
