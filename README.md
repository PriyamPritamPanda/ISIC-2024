# **ISIC-2024**
•**Developed models using both tabular and image data to classify whether a skin lesion is cancerous**.

•Initially trained a ***CatBoost classifier*** on tabular data alone after normalizing feature distributions, achieving a pROC-AUC of **0.17938**.

•Applied upsampling and downsampling techniques to address the extreme class imbalance in the image data (~250 lesion images out of 401,059), followed by training a ***ResNet-18*** model on the processed data, which achieved a pROC-AUC of **0.08701**.

•Developed an ensemble of ***XGBoost***, ***CatBoost***, and ***LightGBM*** on feature-engineered tabular data, improving performance to a pROC-AUC of **0.18412**.
