# 🎬 Multi-Label Movie Genre Classification

This project applies **multi-label classification** on movie posters using **transfer learning** with pretrained CNN architectures like **ResNet50**, **VGG16**, and **EfficientNet**. The goal is to predict multiple genres per poster image using visual features only.

## 📁 Files

- `CS566_TermProject_EfeTolga_BurakArayit.ipynb` – Main training and evaluation notebook  
- `CS556_Term_Project_Report.pdf` – Project report  
- `CS566_TermProject_EfeTolga_BurakArayit(printed).pdf` – Printed version of the notebook  
- *(Optional)* `baseline_model_epoch12.pth` – Trained model weights

## 🧠 Model Highlights

- **ResNet50** baseline and fine-tuned models  
- **EfficientNetB0** and **EfficientNetV2**  
- **VGG16** with best multi-label performance  
- Class weighting and threshold optimization per genre

## 📊 Evaluation

Metrics used:
- Macro / Micro F1-score
- Sample-based F1-score
- Genre-specific Precision/Recall/F1
- Threshold tuning for each class

## 🧪 Dataset

- Source: [Kaggle - Movie Posters by Genre](https://www.kaggle.com/datasets/lovesunkyu/movie-posters-by-genre)
- 33,000+ labeled poster images
- Multi-hot encoded labels for 19 genres

## 👥 Authors

- Burak Arayıt — [`burak.arayit@ozu.edu.tr`](mailto:burak.arayit@ozu.edu.tr)  
- Efe Tolga — [`efe.tolga@ozu.edu.tr`](mailto:efe.tolga@ozu.edu.tr)

## multi-label-genre-classification
