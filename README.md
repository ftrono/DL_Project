# Deep Learning Project
*Eliana Battisti (223701) - Davide Dalla Stella (223727) - Francesco Trono (221723)*

**University of Trento - Deep Learning Course - MSc in Artificial Intelligence Systems (A.Y. 2020/2021)**

### Instructions:

The software has been developed in Google Colaboratory using Python 3.8 and the following libraries:
* [PyTorch](https://pytorch.org/) 1.11.0
* [TorchVision](https://pytorch.org/vision/stable/index.html) 0.12.0
* [Pandas](https://pandas.pydata.org/) 1.3.5

The libraries versions used are the ones of December 2021.

### Repo structure:

The repo contains the following files and folders:
* **_223701_223727_221723_report.pdf_**: project report;
* **_source_code_**: contains the _.ipynb_ file with our code, named _APRNet.ipynb_. The file and contains both tasks, thanks to the unified network architecture we built;
* **_Output_**: contains the output of our neural network: (i) **_classification_test.csv_**: output file for Task 1; (ii) **_reid_test.txt_** output file for Task 2; (iii) **_best_model_parameters.pt_**, containing the set of weights used by our network in the latest best training run;
* **_dataset.zip_**: original archive with the *Market-1501_Attribute* dataset;
* **_Dataset_**: empty directory in which the content of the _dataset.zip_ archive will be extracted.

### Instructions:
To run the code, simply open the _APRNet.ipynb_ file available in the _source_code_ folder. The file can be executed either on a local GPU, or using Google Colaboratory - in this later case, simply click on the **_"Open in Google Colab"_** badge on top of the Jupyter notebook to launch it. Once run, the notebook will automatically clone the GitHub repo to the local machine, without the need to access Google Drive.

The main directories and the full list of hyperparameters are available at the beginning of the file and can be tweaked for custom tests.

**IMPORTANT NOTE:** a boolean switch named **_load_pretrained_** is available at the beginning of the file. If set to **_True_**, it can be used to skip the training phase and directly load the weights saved from our latest best training run (file _Output/best_model_parameters.pt_).

All the details about the implementation of the architecture are available in our PDF report.
