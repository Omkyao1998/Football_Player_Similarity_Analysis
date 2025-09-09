This project combines Cosine Similarity and a Neural Network Autoencoder to measure football player similarity based on position-specific features. To ensure transparency and interpretability, the system integrates SHAP (SHapley Additive exPlanations), providing insights into why players are considered similar.
**Features**:
Position-Aware Feature Engineering – different feature sets for forwards, midfielders, and defenders.
Dual Similarity Models – Cosine Similarity (fast & interpretable), Neural Network Autoencoder (captures deeper latent patterns)
Explainable AI with SHAP – highlights the most influential features driving similarity.
Visualization Tools – similarity rankings, SHAP bar & waterfall plots.

**System Architecture**:
Data Collection & Preprocessing: Player statistics, cleaning, normalization.
Position-Specific Feature Selection: Tailored attributes for each role.
Similarity Modelling: Cosine Similarity & Autoencoder embeddings.
Explainability Layer: SHAP analysis to interpret similarity outcomes.
User Interface :Command-line input for player names and similarity search.

**Results**:
Cosine Similarity provided interpretable results but limited abstraction.
Neural Network Autoencoder captured non-linear latent patterns, improving similarity accuracy.
SHAP explanations revealed position-specific influential features (e.g., Shots on Target for forwards, Interceptions for defenders).
