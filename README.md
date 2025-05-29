# Data Fusion Methods on SisFall Dataset for Fall Detection

## Overview

This project explores various data fusion techniques applied to the [SisFall dataset](https://github.com/sisfall/sisfall), aiming to enhance fall detection accuracy. By implementing methods such as bagging, boosting, stacking, and deep learning models, the project evaluates the effectiveness of different fusion strategies at various levels.

## Dataset

The [SisFall dataset](https://github.com/sisfall/sisfall) is designed for fall detection research, particularly focusing on the elderly population. It comprises:

* **Participants**: Data from 38 subjects, including 23 young adults and 15 elderly individuals.
* **Activities**: 15 types of falls and 19 activities of daily living (ADLs).
* **Sensors**: Data collected using two types of accelerometers and one gyroscope.
* **Sampling Rate**: 200 Hz.

For more details and to download the dataset, visit the [SisFall GitHub repository](https://github.com/sisfall/sisfall).

## Project Structure

The repository includes the following Jupyter notebooks:

* `SisFall-Preprocessing.ipynb`: Data loading, cleaning, and preprocessing steps.
* `SisFall-SVM.ipynb`: Implementation of Support Vector Machine classifier.
* `SisFall-RF.ipynb`: Implementation of Random Forest classifier.
* `SisFall-XGB.ipynb`: Implementation of XGBoost classifier.
* `SisFall-CNN.ipynb`: Implementation of Convolutional Neural Network.
* `SisFall-Bagging.ipynb`: Bagging ensemble method.
* `SisFall-Boosting.ipynb`: Boosting ensemble method.
* `SisFall-Stacking.ipynb`: Stacking ensemble method combining multiple classifiers.

## Requirements

Ensure you have the following packages installed:

* Python 3.x
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* PyTorch
* Matplotlib
* Seaborn

You can install the required packages using:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/ErfanJoodi/Data-Fusion-methods-on-Sis-Fall-dataset.git
   cd Data-Fusion-methods-on-Sis-Fall-dataset
   ```

2. **Download the SisFall Dataset**:

   Follow the instructions provided in the [SisFall GitHub repository](https://github.com/sisfall/sisfall) to download and place the dataset in the appropriate directory.

3. **Run the Notebooks**:

   Open the Jupyter notebooks in the following order for a comprehensive understanding:

   * `SisFall-Preprocessing.ipynb`
   * `SisFall-SVM.ipynb`
   * `SisFall-RF.ipynb`
   * `SisFall-XGB.ipynb`
   * `SisFall-CNN.ipynb`
   * `SisFall-Bagging.ipynb`
   * `SisFall-Boosting.ipynb`
   * `SisFall-Stacking.ipynb`

   Each notebook contains detailed explanations and code implementations for the respective methods.

## Results

The project evaluates the performance of various models and fusion techniques using metrics such as accuracy, precision, recall, and F1-score. Comparative analyses are provided to demonstrate the effectiveness of data fusion methods in improving fall detection accuracy.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.