# Fraud Ring Detection and Investigation Platform

A machine learning and graph analytics project for identifying potentially coordinated financial fraud and supporting evidence-based investigation.

## Problem Statement

Traditional transaction-level fraud detection may overlook relationships among accounts, payment cards, devices, and merchants. This project explores whether graph-based learning can improve the detection of coordinated fraud while controlling false-positive alerts for legitimate shared-entity activity.

## Objectives

- Generate reproducible synthetic transaction data containing legitimate activity and simulated fraud rings.
- Build transaction-level fraud prediction models using Logistic Regression, Random Forest, and XGBoost.
- Represent relationships among accounts, cards, devices, and merchants as a graph.
- Implement a Graph Convolutional Network (GCN) using PyTorch.
- Compare classical machine learning and graph-based approaches.
- Evaluate precision, recall, F1-score, PR-AUC, and false-positive rates.
- Develop an investigation dashboard with evidence-based risk explanations.
- Add a GenAI assistant to summarize available evidence and suggest investigation steps.

## Planned Technology Stack

- **Language:** Python
- **Data processing:** Pandas, NumPy
- **Machine learning:** Scikit-learn, XGBoost
- **Graph learning:** PyTorch and Graph Convolutional Networks
- **Backend:** FastAPI
- **Database:** PostgreSQL
- **Dashboard:** Streamlit
- **Generative AI:** LLM API integration
- **Version control:** Git and GitHub

## Project Status

Initial repository setup completed. Dataset generation, model development, graph construction, evaluation, backend, dashboard, and GenAI integration are planned development stages.

## Evaluation Approach

Models will be evaluated using labelled synthetic scenarios, including coordinated fraud rings and legitimate accounts that share devices or merchants. Results will be reported with the limitations of synthetic data clearly stated.

## Responsible Use

The platform is intended to support investigation, not independently declare that a person or account is fraudulent. Alerts require appropriate review, and shared relationships alone are not proof of fraud.

## Reproducibility

Setup instructions, dependencies, dataset documentation, experiments, and evaluation results will be added as implementation progresses.

## License

No license has been selected yet.