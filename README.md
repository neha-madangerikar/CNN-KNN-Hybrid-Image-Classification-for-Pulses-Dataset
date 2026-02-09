# CNN–KNN Hybrid Image Classification of Pulses

This project implements a hybrid image classification model where a
Convolutional Neural Network (CNN) is used for feature extraction and a
K-Nearest Neighbors (KNN) classifier is used for final prediction of pulse types.

## Methodology
- Image preprocessing and resizing (64×64)
- CNN-based feature extraction
- Feature flattening
- KNN classification
- Train–test evaluation

## Dataset
- 800 images (100 per class)
- Google Drive folder: `comp_bio_database_pulses`
- Image formats: .jpg, .jpeg, .png

### Classes
Split Chickpeas, Green Gram, Red Lentils, Yellow split peas, Split green gram, Kidney beans, Pigeon Peas, Black gram

*Dataset not included due to size limitations.*

## Execution
1. Upload dataset to Google Drive
2. Open the notebook in Google Colab
3. Ensure the path is set to:
```python
data_dir = '/content/drive/MyDrive/comp_bio_database_pulses'

