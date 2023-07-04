# Comparing Toxic Texts

The datasets in this project are:

1. The Ruddit dataset which can be obtained from here: https://www.kaggle.com/datasets/rajkumarl/ruddit-jigsaw-dataset

2. The Kaggle validation dataset for Jigsaw Rate Severity of Toxic Comments which can be found here: https://www.kaggle.com/competitions/jigsaw-toxic-severity-rating

There are 3 notebooks in `src` directory of this project responsible for preprocessing the datasets and fine-tuning DistilBERT model for classification and regression to perform comparing toxic texts and identifying which one is more toxic.

Table: The result of regression and pair classification methods.

|                      | Ruddit Test | Kaggle Validation |
|----------------------|-------------|-------------------|
| Regression           | -           | 0.67364           |
| Pair Classification  | 0.79179     | 0.65072           |

### Installing Required dependencies:
Based on the platform that you are running the codes on, you might need different dependencies, but generally you can install packages in `requirements.txt` file using the following command:

```bash
pip install -r requirements.txt
```

### Running the code:
To run the code, you need to first download the datasets and put them in `data` directory inside `src` directory. Then you can run the notebooks in `src` directory.
