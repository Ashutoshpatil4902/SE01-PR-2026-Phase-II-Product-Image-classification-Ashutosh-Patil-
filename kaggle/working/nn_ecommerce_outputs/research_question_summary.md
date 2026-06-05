
### Research Question Summary

**RQ1. Custom CNN accuracy:** The custom CNN achieved 0.4547 accuracy and 0.3858 weighted F1-score.

**RQ2. Transfer learning improvement:** Compare MobileNetV2 and ResNet50 against the custom CNN in the final table. A higher weighted F1-score indicates better classification performance.

**RQ3. Best performance-cost trade-off:** Use F1-score, training time, and parameter count together. The best model is not always the largest model.

**RQ4-RQ5. Grad-CAM attention:** Inspect Figures 5 and 6 to compare which image regions each model uses for correct and incorrect predictions.

**RQ6. SHAP evidence:** Inspect Figure 7 to identify positive and negative image regions influencing predictions.

**RQ7. Misclassification diagnosis:** Use the Grad-CAM misclassification figure and SHAP results to explain whether the model focused on the product, background, shape, color, logo, or misleading visual features.
