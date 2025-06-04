📂 Overview
This repository contains datasets and modeling resources related to the classification of motor faults using machine learning. It is designed to support research and development in predictive maintenance, particularly within high-risk environments such as radiopharmaceutical facilities.

📝 Abstract
Induction motors are critical components in HVAC and ventilation systems within radiopharmaceutical facilities, where even minor electrical faults can lead to airflow disruptions, compromise contaminant containment, and elevate safety risks for both personnel and the environment. This study presents a machine learning-based approach for accurately classifying motor faults using simulated signal data. The model demonstrates high classification accuracy under controlled conditions. Further validation using real-world fault data or simulated noise is recommended to improve robustness and applicability.

📁 Dataset Structure
✅ Separated Datasets – Case by Case
In this approach, the dataset is divided based on individual cases or scenarios, with each subset representing a distinct operating condition, fault type, or system behavior. This separation allows for targeted analysis, training, and validation of machine learning models on specific categories, ensuring that the model learns the unique characteristics of each case. It is particularly useful when evaluating model generalization across diverse situations or when simulating real-world deployment where faults or conditions occur independently.

✅ Combined Dataset File – Tabulated Format
This file consolidates all individual datasets into a single, unified table, where each row represents a data instance and columns capture relevant features such as signal measurements, timestamps, fault types, or operating conditions. A label or identifier is included for each entry to distinguish between different cases or scenarios. This format enables streamlined preprocessing, visualization, and batch training of machine learning models, while also facilitating comparative analysis across various fault or operating conditions.
