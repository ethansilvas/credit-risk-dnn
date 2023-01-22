# Credit Risk DNN

This is my DNN used to try to find the optimal machine learning model that gets the highest accuracy for the [credit risk dataset.](./Resources/credit_data.csv)

The provided notebook [credit_risk_dnn.ipynb](./credit_risk_dnn.ipynb) can be ran in Jupyter Lab but please note the CPU selector line in the first cell if you are **not** running on an M1 mac. 

You can also view on Google Colab -> <a href="https://colab.research.google.com/github/ethansilvas/credit-risk-dnn/blob/main/GC_credit_risk_dnn.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

I have saved a version of the model that gets 92% accuracy as [credit_dnn.h5](./Models/credit_dnn.h5) in the `Models` folder. Depending on each run I've seen this model produce accuracy values from around 88-92%. 