# Arabic-dialect
This project aims to build a model that predicts arabic dialect given the text.
First by attempting some classical ML models .Then moving to deep learning approach through finetuning an [Multi-dialect-Arabic-BERT]

Our dataset has 2 columns, id and dialect ,The “id” column will be used to retrieve the text, to do that, we need to call  API by a POST request by running Data_fetching to get the data that will has 2 columns, text and dialect.

You can see our ML & DL models in  arabic-dialect-prediction file

I used the Heroku app to deploy my model. Here is the link (https://arabicdialect.herokuapp.com/)
