# Hand Gesture Recognition Project

This project focuses on identifying hand gestures from landmark coordinate data. It uses a dataset of labeled hand landmarks to detect various gestures.

## Project Overview

Hand gesture recognition is a fundamental task in human-computer interaction. This project leverages landmark detection (likely from tools like MediaPipe) to classify gestures based on the relative positions of fingers and joints.

### Dataset Information

The project uses `hand_landmarks_data.csv`, which contains:
- **Total Entries**: 25,675
- **Features**: 64 Landmark coordinate columns
- **Label**: Target gesture classification
- **Data Quality**: 0 null values and 0 duplicate entries.

## Prerequisites

To run this project, you need the following Python libraries:

- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `torch`

You can install these dependencies using the provided `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis**:
   Open `Hand gestures.ipynb` in your Jupyter environment and run the cells to explore the dataset and see the visualization samples.

## Methodology

The project follows a standard machine learning pipeline:
1. **Data Loading**: Reading landmark coordinates from CSV.
2. **Preprocessing**: Verifying data integrity (no missing values/duplicates).
3. **Exploration**: Visualizing landmark distributions and sample gestures.
4. **Classification**: Implementing models to recognize gestures based on feature inputs.

## Visualizations

The notebook includes several visualizations of the landmark data, illustrating the spatial distribution of gestures and the clarity of the dataset.
