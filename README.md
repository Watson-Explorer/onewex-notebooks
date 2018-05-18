# Jupyter Notebook examples using Watson Explorer oneWEX

## Sample notebooks
To use the sample notebooks, you must import the notebook files into your Jupyter Notebook environment.
* [Using Watson Explorer for Sentiment Analysis](notebook/Using+Watson+Explorer+for+Sentiment+Analysis.ipynb) : An example notebook shows how to use Watson Explorer to analyze unstructured content to perform sentiment analysis.

## Install Watson Explorer Python client stub
The sample notebooks use the Watson Explorer Python client stub. You must download and install the Watson Explorer Python client stub to make it available on your notebooks. You can find the WEX Python client stub package at `https://WEX-SERVER:PORT/docs/wex-python-api.zip`.

To install the Python package on your IBM Data Science Experience Local environment, please refer to [Install global libraries and packages on the cluster](https://content-dsxlocal.mybluemix.net/docs/content/local/admin-libraries.html)

## Specify endpoint and access information to your Watson Explorer deployment
The sample notebooks contain the following codes to specify the endpoint and access information to your Watson Explorer deployment. Change them accordingly to access your Watson Explorer deployment from the notebook.

```
# Specify the endpoint and access information
configuration = ibmwex.Configuration()
configuration.host = 'https://WEX-SERVER:PORT'
configuration.username = 'admin'
configuration.password = 'admin'
configuration.verify_ssl = False
```
