# Project Title

This project is a machine learning application that predicts crop yield. It uses various models and data preprocessing techniques to achieve this.

## Directory Structure

- `.ipynb_checkpoints/`: Contains checkpoints for Jupyter notebooks and CSV files.
- `CatBoostTest/`: Contains files related to the CatBoost regression model, including the model notebook (`CatBoostReg.ipynb`), the original and transformed crop yield datasets (`crop_yield.csv` and `transformed_df.csv`), and predictions from a neural network model (`Neural_pred.csv`).
- `models/`: Contains Jupyter notebooks for different versions of the machine learning model (`ML_version_1.ipynb`, `ML_version_2.ipynb`, `ML_version_3.ipynb`) and a comparison of these models (`comparison_of_models.ipynb`).
- `predictions/`: Contains prediction files.
- `TF_data_preprocessing.ipynb`: A Jupyter notebook for data preprocessing using TensorFlow.
- `pipeline_definitions.ipynb`: A Jupyter notebook defining the data processing pipelines.
- `cleaned_crop.csv`, `crop_yield.csv`, `Merged_df_test.csv`: Various CSV files used in the project.

## Getting Started

To get started with this project, open the `pipeline_definitions.ipynb` notebook to understand the data processing pipelines. Then, you can explore the different model versions in the `models/` directory. The `CatBoostTest/CatBoostReg.ipynb` notebook contains the CatBoost regression model, and `TF_data_preprocessing.ipynb` notebook shows how data preprocessing is done using TensorFlow.

## Prerequisites

This project requires Python and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [TensorFlow](https://www.tensorflow.org/)
- [CatBoost](https://catboost.ai/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.