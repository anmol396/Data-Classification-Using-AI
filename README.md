# Data Classification Using AI

A clean, beginner-friendly AI classification project using the classic Iris dataset from `scikit-learn` and a Decision Tree Classifier.

## Objective
To build a basic, step-by-step machine learning workflow including dataset loading, understanding, exploratory data analysis (EDA), plotting visualizations, training a model, evaluating accuracy, and inspecting predictions.

## Dataset
- **Name**: Iris Dataset (from `sklearn.datasets`)
- **Records**: 150 (50 per species)
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Classes**: setosa, versicolor, virginica

## Algorithm
- **Decision Tree Classifier**: A supervised learning algorithm used for classification. The model tree depth is restricted to `max_depth=3` to control complexity and prevent overfitting.

## Accuracy
- **Training Accuracy**: 95.83%
- **Testing Accuracy**: 100.00%

## Visualizations
The script creates and saves the following plots in the `graphs/` folder:
- `histogram.png`: Shows feature distribution by species.
- `boxplot.png`: Shows feature spreads by species.
- `heatmap.png`: Correlation matrix heatmap.
- `pairplot.png`: Pairwise relationship grids.
- `scatterplot.png`: Petal length vs Petal width scatterplot.

## Results
- The model successfully classifies test instances with 100.00% accuracy.
- An **Overfitting Check** is performed to ensure the difference between training and testing accuracy does not indicate significant generalization error.
- Detailed classification reports and confusion matrices are printed to the console.
- Feature importances show that petal features are the most critical predictors.

## Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
Run the classification pipeline script:
```bash
python classification.py
```

## Folder Structure
```
Data-Classification-Using-AI/
│
├── classification.py        # Main classification script
├── README.md                # Documentation
├── requirements.txt         # Dependencies
└── graphs/                  # Generated plots
    ├── histogram.png
    ├── boxplot.png
    ├── heatmap.png
    ├── pairplot.png
    └── scatterplot.png
```

## Learning Outcomes
- Load and inspect datasets using `pandas`.
- Build visualizations using `matplotlib` and `seaborn`.
- Prepare data and split it into training and testing sets.
- Train and evaluate a Decision Tree classifier using `scikit-learn`.
- Analyze model features and importance.
