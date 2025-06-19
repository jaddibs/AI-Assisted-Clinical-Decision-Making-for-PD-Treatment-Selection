# `AI-Assisted Clinical Decision Making for PD Treatment Selection`

A machine learning approach to optimize Parkinson's disease treatment recommendations using artificial neural networks.

## `Overview`

This project develops an AI model to assist healthcare providers in selecting optimal treatments for Parkinson's disease (PD) patients. The system aims to reduce medication errors and minimize pharmaceutical industry bias in treatment decisions.

## `Problem Statement`

- Medication errors in PD treatment are frequent, leading to improper patient care
- Pharmaceutical industry influence can bias treatment selection toward less effective options
- Current clinical decision-making lacks systematic, unbiased treatment optimization

## `Methodology`

The project implements three prototype artificial neural networks (ANNs):

1. **Prototype 1**: Original ANN with basic classification
2. **Prototype 2**: ANN with class weight adjustments to handle data imbalance
3. **Prototype 3**: Rules-based ANN combining simulated patient history with clinical guidelines

## `Features`

- **`Patient Factors`**: Age, sex, PD stage, contraindications
- **`Treatment Options`**: Levodopa, Dopamine Agonists, Deep Brain Stimulation, Duopa
- **`Performance Metrics`**: Accuracy, precision, recall, F1-score analysis

## `Results`

`Prototype 3` achieved the best performance:
- `Binary Accuracy`: 99.59%
- `Average F1 Score`: 92.48%

## `Dataset`

Uses a simulated dataset of 10,000+ patients with realistic statistical distributions for:
- Demographic information
- Disease severity staging
- Treatment contraindications
- Historical treatment responses

## `Future Development`

- Integration with real hospital patient data
- Development of comprehensive clinical rule sets
- Implementation in healthcare provider workflows
- Validation in clinical settings

## `Tech Stack`

- `Python`
- `TensorFlow/Keras` for neural network implementation
- Multi-label classification architecture
- Statistical simulation for dataset generation

## `Academic Recognition`

This project earned the `Best Project in Category of Computer Science (EPIC Award)` at the Region 6 IJAS Science and Engineering Fair in March, 2024.
