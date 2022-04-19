# SYDE-675-Final-Project

Link to original paper: https://arxiv.org/pdf/2111.10207v1.pdf

Link to original repository: https://github.com/aeesha-T/parkinsons_prediction_using_speech

## How to run the code:
  1. Open the SYDE_675_Project.ipynb file in Google colab or any other environment that supports Jupyter notebooks
  2. Run the first cell (contains the pip install command) - You will have to restart the runtime after the Autogluon library is installed 
  3. If you are using Colab, upload both of the csv files present inside this repository into your Colab environment, otherwise make sure those files are present within the root folder of any other environment you are using
  4. Select the Runtime tab -> Select "Run All" to run all the cells in the file - It will take over an hour to run everything due to the computational requirements of ensemble learning and because the 6-fold validation is run 10 times for every experiment
  5. As the cells finish running, the correct tables and figures will appear 
