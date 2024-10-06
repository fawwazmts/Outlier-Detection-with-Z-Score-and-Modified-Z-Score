
# Outlier Detection using Z-Score & Modified Z-Score

This repository provides implementations of outlier detection methods using both traditional Z-Score and Modified Z-Score in Python. These methods are widely used in statistical analysis to identify outliers in datasets, which can be crucial in data preprocessing.

## Overview

Outlier detection is an essential step in many data analysis and machine learning tasks, as outliers can distort results and reduce the effectiveness of models. This project implements two main methods for detecting outliers:

1. **Z-Score**: A standard statistical method based on the mean and standard deviation.
2. **Modified Z-Score**: A robust method based on the median and median absolute deviation (MAD), which is more suitable for non-normal distributions or smaller datasets.

The repository includes:

* A Jupyter Notebook (`outlier_detection_zscore_modifiedzscore.ipynb`) demonstrating the use of these methods on sample datasets.
* Implementation of outlier detection functions using both Z-Score and Modified Z-Score.

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/fawwazmts/outlier_detection_zscore_modifiedzscore.git
cd outlier_detection_zscore_modifiedzscore
```

## Requirements

To run this project, you will need to have Python installed along with the required libraries. The following libraries are used in this project:

```
seaborn==0.13.2
matplotlib==3.9.2
pandas==2.2.2
scipy==1.14.1
```

## How to Use

1. **Clone the repository** :

   ```bash
   git clone https://github.com/fawwazmts/outlier_detection_zscore_modifiedzscore.git
   cd outlier_detection_zscore_modifiedzscore
   ```
2. **Install the required packages**
3. **Run the Jupyter Notebook** :
   To explore the code and run the examples, launch Jupyter Notebook in the project directory:

   ```bash
   jupyter notebook outlier_detection_zscore_modifiedzscore.ipynb
   ```
4. **Explore and Experiment** :
   The notebook demonstrates how to use Z-Score and Modified Z-Score for detecting outliers. You can experiment with different datasets or modify the thresholds to observe how it affects outlier detection.

## Contributing

Contributions are welcome! Feel free to fork this project, open an issue, or submit a pull request if you have ideas for improvements or new features. Make sure to follow the code of conduct when contributing.
