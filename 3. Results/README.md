# `Descriptive_Statistics.xlsx`
This file provides a detailed analysis and comparison of data selection strategies and optimization techniques, presented across four distinct tabs.   

**Tabs**: 
- **Random**:    
This tab contains data and results derived from a random selection method. It includes statistical summaries, performance metrics, or comparisons that showcase the baseline or unbiased outcomes of a non-deterministic approach.

- **Greedy K**:   
This section focuses on a "Greedy K" sampling method, which prioritizes local optimization for selecting a subset of size 𝐾. It highlights metrics that illustrate how this strategy performs relative to the random selection method, particularly in terms of efficiency and accuracy.

---

# `Greedy_Method_Analysis.xlsx`  
This file provides a comprehensive analysis of different methods and models applied under balanced and imbalanced data conditions. It compares the performance of various deep learning architectures using the `Random Selection` and `Greedy K` sampling methods . It evaluates their training and untrained states across multiple scenarios.

**Tabs**:  
- **Balance-Greedy K-CNN**:  
This tab contains results and metrics for the "Greedy K" algorithm applied to a Convolutional Neural Network (CNN) under balanced data conditions. It includes performance metrics such as accuracy, precision, recall, or other model evaluation measures.

- **Imbalance-Greedy K-CNN**:  
This section focuses on the "Greedy K" algorithm applied to CNNs under imbalanced data scenarios. It explores how the model performs when data distribution is skewed, providing insights into robustness and generalization.

- **Balanced-VGG**:  
This tab presents results for the VGG architecture trained using balanced data. It highlights the impact of shorter training durations on performance under ideal data conditions.

- **Imbalanced-VGG**:  
This section contains results for the VGG model trained on imbalanced data. It demonstrates how data imbalance influences the training outcomes and generalization ability of the architecture.

- **Balanced-ResNet**:  
This tab focuses on the performance of a ResNet model trained on balanced datasets. It includes metrics like accuracy, loss, and convergence patterns for balanced training scenarios.

- **Imbalanced-ResNet**:  
This tab evaluates ResNet's performance on imbalanced data after training, analyzing its robustness and handling of skewed distributions.

- **Balanced_Untrained_VGG**:  
This section explores the behavior or predictions of an untrained VGG model on balanced data, offering baseline insights into model initialization and random predictions.

- **Imbalanced_Untrained_VGG**:  
This tab examines the untrained VGG model's performance on imbalanced datasets, serving as a control or baseline for comparison with trained models.

---

# `Random_Method_Analysis.xlsx`  
This file provides a detailed analysis of random selection methods applied across various deep learning models under balanced and imbalanced data conditions. It highlights the performance differences in trained and untrained states, offering a baseline comparison for the random selection strategy.

**Tabs**:  
- **Balance-Rand-CNN**:  
This tab contains results and metrics for a CNN model trained using a random selection method on balanced data. It provides performance insights under ideal data distribution conditions.

- **Imbalance-Rand-CNN**:  
This section focuses on CNN performance under imbalanced data scenarios when a random selection method is applied. It explores the effect of data skewness on model behavior.

- **Balanced-VGG**:  
This tab presents results for the VGG architecture trained on balanced datasets. It highlights how this model performs under balanced training conditions using a random method.

- **Imbalanced-VGG**:  
This section evaluates the VGG model trained on imbalanced data using random selection. It provides insights into the challenges posed by data imbalance.

- **Balanced-ResNet**:  
This tab contains metrics for a ResNet model trained on balanced data, showcasing its ability to learn effectively under random sampling and balanced conditions.

- **Imbalanced-ResNet**:  
This section examines ResNet's performance on imbalanced datasets using a random selection method. It provides a view into the model's robustness.

- **Balanced_Untrained_VGG**:  
This tab analyzes the predictions or behavior of an untrained VGG model on balanced datasets. It serves as a baseline for comparison with trained counterparts.

- **Imbalanced_Untrained_VGG**:  
This section investigates the untrained VGG model's behavior on imbalanced datasets, offering insights into its initialization and random predictions.

---

# `Quality_Check_Analysis.xlsx`  
This file focuses on evaluating the quality of models or methods using key performance metrics. It includes detailed analyses of accuracy and FID (Fréchet Inception Distance) across various scenarios or models.

**Tabs**:  
- **Accuracy**:  
This tab contains accuracy metrics to evaluate the similarity between generated images and original ones. The results are for the model (pretrained VGG16) trained on original data and tested on generated images produced by both DDPM and PGGANs.

- **FID**:  
This section focuses on the Fréchet Inception Distance (FID), a widely used metric for evaluating the quality of generated data, particularly in generative models. It compares FID scores across models or datasets, providing insights into the fidelity and diversity of generated outputs. Lower score means more similar to original data.

