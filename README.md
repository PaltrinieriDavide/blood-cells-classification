# Blood Cell Classification Dataset

This dataset contains images designed for the classification of different types of blood cells. Each image is labeled with one of eight classes, representing various blood cell types, including basophils, neutrophils, and lymphocytes. The dataset is intended to assist in the development and training of machine learning models for automatic blood cell classification.

## Dataset Details

- **Image Size:** 96x96 pixels
- **Color Space:** RGB (3 channels)
- **Input Shape:** (96, 96, 3)
- **File Format:** npz (Numpy archive)
- **Number of Classes:** 8

## Class Labels

Each image belongs to one of the following eight classes:

- **0:** Basophil
- **1:** Eosinophil
- **2:** Erythroblast
- **3:** Immature Granulocytes
- **4:** Lymphocyte
- **5:** Monocyte
- **6:** Neutrophil
- **7:** Platelet

## Usage

The dataset is stored in the `.npz` format, which can be easily loaded using Numpy's `load` function. Each image has a corresponding label indicating the class it belongs to. The dataset is suitable for training machine learning models for classification tasks in medical image analysis.
