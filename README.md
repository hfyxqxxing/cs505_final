# CS505 Final Project: Text Generation Model Comparison

author: Xiao Zhang, Lihao Zheng

## Environment

Based on python 3.10.6 

Requirements: CS505 basic requirements adding 

transformers \
datasets \
sentencepiece

(If not enough, please follow the running bug alert to install the packages)

## File description
GPT_train: The file containing the GPT-2 model training with process wikitext, also the text generation \

BB_train, T5_train, bioGPT_train: The same as above only changing the model. \

Data Analysis: Preprocess the data from wikitext and do some analysis help us to tune the parameters.(max_length) \

Saved_models: Trained GPT-2 and BioGPT models can be directly used in this file to check the results and do some generation. The other two are not good enough so not considered. \

data: Datasets after preprocessing. \

model_save_GPT/BB/T5/Bio: trained in local computer for results. \
model_save: for any future training to save the model.

model_save_GPT/BB/T5/Bio: Sorry for inconvenience, these models are too large to upload to gitHub. So I saved all in my google drive. You can check it in the following link:
https://drive.google.com/drive/folders/1Gc6oBctJUzhGE-b82oMHa3VhsYQ_qccb


## RUN
open the ipynb, click the play button one by one or RUN ALL
