# Pneumonia Detection

A neural network (CNN) that can detect wether a patient has pneumonia or not.
For the data I used: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia. 
The Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

Here is an example of a patient with and without pneumonia:
<p align="center">
  <img src="Normal.png" width="250" height="250" align="center"> 
</p>

<p align="center">
  <img src="pneumonia.png" width="250" height="250" align="center"> 
</p>


For the model I used a Covolutional Neural Network (CNN), you can learn more about it here: https://en.wikipedia.org/wiki/Convolutional_neural_network
## Prerequisites

- Python 3.7 or later
- Numpy
- Seaborn
- Matplotlib
- Pandas
- Keras
- Cv2



## Installation

Clone the repository to your local machine:

```bash
 git clone https://github.com/NicolasCort/Sentimental-tweets.git

```
Install the required packages using pip:

```bash
 pip install -r requirements.txt


```

## Usage

To use the sentiment analysis tool, you need to provide your Twitter API credentials. You can obtain these credentials by creating a Twitter Developer account and creating a new app.

```bash
consumer_key = "YOUR-CONSUMER-KEY"
consumer_secret = "YOUR-CONSUMER-SECRET"
access_token = "YOUR-ACCESS-TOKEN"
access_token_secret = "YOUR-ACCESS-TOKEN-SECRET"


```

To change the topic for the sentimental tweets you change the variable "q"

```bash
tweets = api.search(q="Ukraine", lang="en", count=100)

```
![Screenshot](Normal.png)
