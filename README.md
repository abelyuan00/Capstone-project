# Capstone-project
# Piano Note Sequence Classification Report

## Overview

This report presents the evaluation of four different models for processing and classifying piano note sequences. The models compared include a traditional RNN, a CNN, a Transformer, and a Hybrid Transformer-RNN model. The Hybrid Model emerged as the most effective, achieving the highest test accuracy.

## Models Evaluated

1. **RNN (Recurrent Neural Network)**
2. **CNN (Convolutional Neural Network)**
3. **Transformer**
4. **Hybrid Transformer-RNN Model**

## Key Findings

- **Hybrid Transformer-RNN Model**: Achieved the highest test accuracy of 70.05%. This model combined the strengths of Transformer and RNN architectures, incorporating convolutional layers and an attention mechanism for improved feature extraction and sequence learning.
- **Data Augmentation and Early Stopping**: Essential for preventing overfitting across all models.
- **Optimizer and Learning Rate**: Significant impact on training dynamics and final performance.
- **Architectural Choices**: Crucial for effective feature learning and overall performance in music sequence classification tasks.

## Detailed Insights

- The Hybrid Model's success is attributed to its ability to capture long-range dependencies through the Transformer component while effectively handling sequential data with the RNN component. The convolutional layers further enhanced feature extraction, and the attention mechanism allowed the model to focus on the most relevant parts of the input sequences.
- The traditional Transformer model did not show significant improvement after alterations, likely due to constraints related to dataset size and complexity, highlighting the importance of data volume and quality.

## Future Directions

- **Regularization Techniques**: Further exploration of additional regularization methods to enhance model robustness.
- **Optimizers and Learning Rates**: Experimentation with different optimizers and learning rate schedules to improve training efficiency and performance.
- **Architectural Innovations**: Continued investigation into novel architectural designs to further improve feature learning and generalization capabilities in music sequence processing tasks.

## Conclusion

The Hybrid Transformer-RNN Model demonstrated superior performance in classifying piano note sequences, underscoring the importance of combining diverse architectural elements to leverage their respective strengths. This approach offers a promising direction for future research in music sequence classification and other similar tasks.

