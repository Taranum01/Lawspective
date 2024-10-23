# Lawspective - Your Legal Consultancy

## Overview

Lawspective is an AI-powered legal consultancy platform aimed at assisting individuals, especially those without legal expertise, in understanding and navigating the Indian judicial system. This project leverages machine learning (ML) and deep learning (DL) models to automatically identify legal charges based on the facts of a case and match them to the relevant sections of the Indian Penal Code (IPC).

### Key Features:
- Automatic Charge Identification based on provided case facts.
- Legal charge predictions linked to IPC sections such as 302, 368, and 376.
- Machine learning models trained on real-world case datasets for accuracy.
- Interactive online platform designed for legal consultation and support.

## Objectives

The project aims to:
1. Study the Indian judicial system and understand the IPC sections in detail.
2. Create a machine learning model to automatically identify legal charges based on case facts.
3. Match these identified charges to relevant IPC sections.
4. Build an online platform that legal professionals, as well as laypeople, can use for consultancy and charge identification.
5. Test the model on real-world legal cases for accuracy validation.

## Methodology

### PHASE 1: Data Collection and Preprocessing
- Data was collected from the official Supreme Court website, focusing on sections 302, 368, and 376 of the IPC.
- Keywords like "rape," "sexual harassment," "kidnapping," and "murder" were used for extracting relevant data.
- The preprocessed data was manually fed into machine learning models.

### PHASE 2: Model Building and Training
- The ML models used for charge identification were:
  - **GRU** (Gated Recurrent Units)
  - **LSTM** (Long Short-Term Memory)
  - **BERT** (Bidirectional Encoder Representations from Transformers)
  
- After comparative analysis, **BERT** was found to provide superior performance.

### PHASE 3: Model Evaluation
- The trained models were evaluated on a dataset of 350 cases. Accuracy, F1 score, recall, precision, and loss metrics were calculated to compare model performance.

| Model | Accuracy | F1 Score | Recall | Precision | Loss |
|-------|----------|----------|--------|-----------|------|
| GRU   | 0.84     | 0.59     | 0.65   | 0.54      | 0.63 |
| LSTM  | 0.87     | 0.63     | 0.72   | 0.60      | 0.31 |
| BERT  | 0.92     | 0.83     | 0.83   | 0.83      | 0.27 |

## Results

- The models showed varying degrees of success in accurately predicting charges and matching them to IPC sections.
- **BERT** achieved the highest accuracy at 92%, demonstrating the effectiveness of transformer-based architectures for charge identification.

## Conclusion

This project demonstrates the use of ML and DL techniques in predicting legal charges based on case facts. By leveraging GRU, LSTM, and BERT models, we developed a system capable of identifying the legal charges and associating them with the appropriate IPC sections. The final model, BERT, performed exceptionally well in terms of accuracy and other performance metrics, making it the model of choice for further deployment.

## Future Scope

- Include more IPC sections to cover a broader range of legal scenarios.
- Extend the platform to support different stakeholders, including legal firms.
- Collaborate with law firms to include real-world feedback and improve model accuracy.
- Conduct further testing and deploy the platform for professional use.



<img src="https://github.com/Taranum01/Lawspective-CAPSTONE/blob/main/Poster%20154..PNG" alt="Keeper App Demo" />



