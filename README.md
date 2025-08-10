# 🏦 Beta Bank Customer Churn Prevention System

## Project Overview
Advanced machine learning system for predicting and preventing customer churn in banking, implementing class imbalance techniques and ensemble methods to identify at-risk customers and enable proactive retention strategies.

## Business Context
Beta Bank was experiencing gradual monthly customer attrition, making customer acquisition more expensive than retention. The bank needed a predictive system to identify customers likely to churn, enabling targeted retention campaigns and preserving customer lifetime value.

## Industry Challenge
Banking customer churn presents unique challenges:
- **Class Imbalance**: Churning customers represent minority class (~20% of dataset)
- **High Acquisition Costs**: New customer acquisition 5-7x more expensive than retention
- **Regulatory Environment**: Strict data privacy and model interpretability requirements
- **Customer Lifetime Value**: Long-term relationship impact of churn decisions

## Methodology & Approach
- **Imbalanced Data Handling**: Systematic comparison of oversampling vs undersampling
- **Feature Engineering**: Customer demographic and behavioral pattern analysis
- **Class Balance Optimization**: Multiple techniques to address minority class prediction
- **Model Validation**: F1-score optimization with AUC-ROC validation
- **Business Metrics**: Focus on precision-recall balance for actionable insights

## Technical Implementation

### Data Balancing Techniques
1. **Oversampling Strategy**: Synthetic minority class generation
2. **Undersampling Strategy**: Majority class reduction with stratified sampling
3. **Comparative Analysis**: Systematic evaluation of balance techniques

### Machine Learning Pipeline
- **Data Preprocessing**: Missing value imputation, feature scaling, encoding
- **Feature Selection**: Customer behavior and demographic variables
- **Model Training**: Ensemble methods optimized for imbalanced classification
- **Evaluation Framework**: F1-score, precision, recall, AUC-ROC metrics

### Models Implemented
1. **Logistic Regression**: Interpretable baseline with class weights
2. **Random Forest**: Ensemble method with bootstrap sampling optimization
3. **Class Balance Variants**: Each model tested with different sampling strategies

## Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn
- **Imbalanced Learning**: Custom sampling techniques, class weight optimization
- **Ensemble Methods**: Random Forest with hyperparameter tuning
- **Evaluation**: ROC curves, confusion matrices, classification reports
- **Visualization**: Matplotlib, Seaborn for model performance analysis

## Key Technical Achievements
- **F1-Score Excellence**: Achieved 0.617 F1-score (exceeding 0.59 requirement)
- **Class Imbalance Mastery**: Optimal undersampling strategy identification
- **Model Performance**: AUC-ROC of 0.861 indicating strong discriminative ability
- **Precision-Recall Balance**: 52% precision with 73% recall for business actionability

## Results & Business Value
- **Churn Prediction Accuracy**: 61.7% F1-score with high recall for customer retention
- **Retention Campaign Targeting**: Identification of high-risk customers for proactive intervention
- **Cost Optimization**: Reduced acquisition costs through improved retention
- **Customer Lifetime Value**: Preservation of long-term customer relationships

## Industry Impact
- **Banking Sector**: Direct application to retail and commercial banking churn
- **Financial Services**: Credit card, loan, and investment account retention
- **Insurance**: Policy holder churn prediction and retention
- **Subscription Services**: Customer retention across recurring revenue models

## Applications Across Industries
- **Telecommunications**: Mobile service churn prediction and retention
- **E-commerce**: Customer loyalty and subscription retention
- **SaaS**: Software subscription churn and upgrade predictions
- **Healthcare**: Patient retention and engagement optimization

## Key Achievements
- **Technical Excellence**: Mastery of imbalanced classification techniques
- **Business Impact**: Actionable churn predictions with high recall
- **Industry Application**: Production-ready framework for banking churn prevention
- **Methodological Rigor**: Systematic comparison of sampling strategies
