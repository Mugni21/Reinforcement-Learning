# Project 1 — Mario Level CNN Classifier

Binary image classification using CNNs to distinguish between **Level 1** and **Level 8** screenshots from *Super Mario Bros*.

## Results

| | Model 1 (Deep) | Model 2 (Lighter) |
|---|---|---|
| Parameters | ~80M | ~31M |
| Training time | ~22 min | ~3 min |
| Test accuracy | **100%** | **99.87%** |

## How to Run

### 1. Clone or download this repo

### 2. Add the dataset

Download the dataset from Google Drive:

📁 **[Download SuperMarioBros Dataset](https://drive.google.com/drive/folders/1aeO00PO_waH5QI8PLEW2JH2kz-OMDwQD?usp=sharing)**

Once downloaded, place the images inside the `data/` folder following this structure:
```
data/
├── TrainImages/
│   ├── TrainLvl1/
│   └── TrainLvl8/
├── ValidationImages/
│   ├── ValidationLvl1/
│   └── ValidationLvl8/
└── TestImages/
    ├── TestLvl1/
    └── TestLvl8/
```

### 3. Install dependencies
```bash
pip install tensorflow keras opencv-python scikit-learn matplotlib numpy
```

### 4. Open the notebook
Open `notebooks/CNN_Classifier.ipynb` in Jupyter and run all cells.

## Dependencies
- Python 3.10+
- TensorFlow 2.x / Keras
- OpenCV, NumPy, Matplotlib, scikit-learn
