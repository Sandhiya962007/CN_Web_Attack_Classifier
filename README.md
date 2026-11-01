Web Attack Classification Using Supervised Machine Learning

Project Overview

Classifies network traffic into BENIGN, Brute Force, SQL Injection and
XSS using Random Forest and Decision Tree classifiers.

Dataset

-   Dataset: CIC-IDS2017
-   Selected CSV: Thursday-WorkingHours-Morning-WebAttacks.pcap_ISCX.csv
-   Source: Canadian Institute for Cybersecurity, University of New
    Brunswick
-   Official dataset page: [https://www.unb.ca/cic/datasets/ids-2017.html](https://www.unb.ca/cic/datasets/ids-2017.html?utm_source=chatgpt.com)

Download CIC-IDS2017 from the official page and use the selected CSV
file.

Tools

Python 3, Google Colab, Pandas, NumPy, Matplotlib and Scikit-learn.

How to Run

1.  Open the project notebook in Google Colab.
2.  Upload or mount the dataset CSV file.
3.  Update the dataset path in the notebook if needed.
4.  Run all cells in order to preprocess the data, train the models and
    evaluate them.

Results

-   Random Forest accuracy: approximately 99.75%
-   Decision Tree accuracy: approximately 99.77%

Note: The test set contains only four SQL Injection samples, so its
class-wise metrics should be interpreted cautiously due to class
imbalance.

Outputs

Classification reports, confusion matrices, trained model files and an
algorithm comparison.
