545_Local (1) is the file for only data processing. <br>
In 545_FP, we complete data processing, hypothesis testing and ER graph. <br>
In 545_ER, it only includes our ERD. <br>
Ecommerce_Delivery_Analytics_New.csv is the raw data. <br>
In Ecommerce_With_Sentiment_GPU.csv, we convert customers' feedbacks to numerical features. <br>
Ecommerce_Final.csv is the final version after data processing. <br>
All of the csv files are too large, so we also upload zip (should be okay to download). <br> 
For training models, you can directedly use Ecommerce_final.csv, we've already processed it. <br>
To automatically download the notebook file from this repository in Google Colab, run the following command: <br>

```python <br>
!pip install -q nbconvert && curl -O https://raw.githubusercontent.com/asdsjc12315/CIS5450_final/main/545_FP.ipynb 

