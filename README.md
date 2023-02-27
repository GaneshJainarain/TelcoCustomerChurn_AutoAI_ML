## Telco Customer Churn

#### `Context`

Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs. 

#### `Content`

Each row represents a customer, each column contains customer’s attributes described on the column Meta-data.

The data set includes information about:

- Customers who left within the last month – the column is called `Churn`
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

#### `Inspiration`

To explore this type of models and learn more about the subject.


### `Downloading our dataset`

![Dataset](env/ReadMePhotos/DatasetDownload.png)

### `IBM Watson Studios`

![Watson Studio](env/ReadMePhotos/IBMWatsonStudiosCreateProject.png)


### `Create a new project`
![Watson Studio](env/ReadMePhotos/NewProject.png)

### `Creating a new asset AutoAI`
![Auto AI](env/ReadMePhotos/NewAssetAutoAI.png)


### `Creating a new asset AutoAI II`
![Auto AI II](env/ReadMePhotos/CreatingOurAutoAIAsset.png)


### `Predicting on Churn with Binary Classification`
![Predicting on Churn](env/ReadMePhotos/BinaryClasssification.png)

As you can see as soon as we uploaded our dataset and selected what column 
we wanted to predict on, the experiment automatically gave us the best
prediction type to use on the data, in this case `Binary Classification`
and is optimized for accuracy and runtime

### `Progress Map of various Pipelines`
![Progress Map](env/ReadMePhotos/ProgressMap.png)

Here we can see various amounts of pipelines, each one using a different algorithm,
at the bottom we see a comparison of the pipelines and we can see that they choose the most optimal one for our task

### `Pipeline Comparison`
![Pipeline Comparison](env/ReadMePhotos/Pipelines.png)

Here we can see that Pipeline 4 has been chosen to be the best measured on accuracy,
lets take a look inside the pipeline












