# ICSE-2024-ONNX
The artifacts for this paper are placed into two main folders:
-  `Theme 1: Retrospective Analysis`: The data and code used for the retrospective analysis is within the `Theme1` folder, please examine the `README` for that.
-  `Theme 2: Prospective Analysis`: The data and code used for the Prospective analysis is within the `Theme1` folder, please examine the `README` for that.

## Theme 1 - Index
|Data|Data Description|
|----|-----------------|
|[Issue Data](/Theme1/issue-data/)| The GitHub issues that we downloaded and filtered.|
|[Issue Downloader](/Theme1/issue-downloader/)| Our scripts to download.|
|[Pilot Study](/Theme1/pilot-study/)| Pilot study data.|
|[Data Analysis](/Theme1/data_analysis.ipynb)| This jupyter notebook contains our analysis of our data. It generates Tables 4, 5, 6, and 7. Additionally it generates Figures 6a and 6b.|
|[Failure Analysis Data](/Theme1/FailureAnalysis.xlsx)| Our failure analysis classifications.|
|[Data Collected for Frameworks and DL compilers](/Theme1/FWs%20and%20DL%20compilers%20data.xlsx)| This excel file contains the data we collect for frameworks and deep learning compilers. (§2.1.2)|

## Theme 2 - Index

### Theme 2 Data - Real Models
|File/Folder|Data Description|
|----|-----------------|
|[`pytorch_conv_results.json`](/Theme2/real-models/pytorch_conv_results.json)| This JSON file the PyTorch testing data.|
|[`tf2onnx_conv_results.json`](/Theme2/real-models/tf2onnx_conv_results.json)| This JSON file the TensorFlow testing data.|
|[`analyze.ipynb`](/Theme2/real-models/analyze.ipynb)| This JSON file contains the processed data for the PyTorch synthetic model test.|
|[`convert.py`](/Theme2/real-models/convert.py)| This is the script we used to convert the PyTorch and TensorFlow models.|

###  Theme 2 Data - Synthetic Models
|File/Folder|Data Description|
|----|-----------------|
|[`random_tf.json`](/Theme2/synthetic-models/random_tf.json)| This JSON file contains the processed data for the TensorFlow synthetic model test.|
|[`random_tf_con.json`](/Theme2/synthetic-models/random_tf_con.json)| This JSON file contains the processed data for the TensorFlow constrained synthetic model test.|
|[`random_pt.json`](/Theme2/synthetic-models/random_pt.json)| This JSON file contains the processed data for the PyTorch synthetic model test.|
|[`random_pt_con.json`](/Theme2/synthetic-models/random_pt_con.json)| This JSON file contains the processed data for the PyTorch constrained synthetic model test.|
|[`data_analysis.ipynb`](/Theme2/synthetic-models/data_analysis.ipynb)| This is the notebook used to analyse the data mentioned above.|
|[`test.ipynb`](/Theme2/synthetic-models/test.ipynb)| This is the notebook used to test the synthetically generated models.|
|[`/nnsmith`](/Theme2/synthetic-models/nnsmith/)| This folder the modified NNSmith used to generate models.|