# SX4

## Short Description
### What's the problem?
We will be tackling on the problem on Climate Change. There's a phenomenon called the Urban Heat Island Effect that results in tougher training and higher risk of heat related injury, namely heat exhaustion and heat stroke.

### The idea
Our solution focus on decreasing and preventing heat injury incidents. We came up with the idea of variables that can detect factors leading to heat injury, such as body temperature and heart rate.

1. Device that can track body temperature, heart rate and activity tracker.
2. Possibility of sending data to a database for analysis of data.
3. Having a dashboard to clearly shows analyzed data.

## Video
<a href="https://www.youtube.com/watch?v=-OnpFI7G4Ak&feature=youtu.be" target="_blank"><img src="https://lh3.googleusercontent.com/proxy/41fVbpwuov0rvZXeAv3FKqVRqYXdDql-ZrtGt7m4a6srQXOJz6-i9qNUGfOcIEtPqdTEsw8j6IIvHe96l1xyAEjzMhL8K2KjiIobmsVyhFAmL14u-PObfSWbLaxn1eU9C-rqXVZ8slqeEmYZlMc0uG9WuUZP-px9T133n_68J1ypsxEbJImFrgwzT72EwPyHuILfv70OK16RasPR" width="240" height="180" border="10" /></a>

## The Architecture

## Long Description
Our solution to the problem Climate Change can help SCDF training to be better than ever. Our idea consists of having a device worn by the first responders to send data such as body temperature and heart rate to a database, while analysing the data and present them neatly into a dashboard.

We hope that by doing that, we can early deter preventable injuries and incident, to provide relief and enhancement in harsh operating conditions and maximise the safety, health and performance of first responders during training and operations.

### Tracking
#### Temperature:
A device to be worn like an ear piece to take ear temperature regularly.
#### Heart rate:
Device for the wrist / chest to count the heart rate.

### Dashboard
#### [Dashboard Example](https://dataplatform.cloud.ibm.com/dashboards/ef63fafe-f903-4d14-9d81-17e81c929840/view/5b17ab3c31970bc355d4eee40790255779362708b0bbd20a878d7b495b337197a86a1a99c8791f528c155437f4b91b51c8)
In the dashboard will show the temperature / the heart rate of many first responders by using a bar chart, while on the left will show the number of first responder under the different risk that may result in differnet injury.
Bottom of the dashboard will be a table list of all the first reponders and their current location / activity.

### Code
The code submitted uses the API provided by [Data.gov.sg](https://data.gov.sg/) to get air temperature of Singapore locations and uses it to calculate the heat index in order to determine if the weather in that location is suitable for activity.
#### Note: 
We are unable to get the API for humidity thus humidity will be randomly generated in the code.

## Getting Started
[Installing Jupyter Notebook](https://jupyter.org/install)

#### Prerequisite: Python
While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater, or Python 2.7) for installing the JupyterLab or the classic Jupyter Notebook.
#### conda
If you use conda, you can install it with:
```
conda install -c conda-forge notebook
```
#### pip
If you use pip, you can install it with:
```
pip install notebook
```
#### run
Run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):
```
jupyter notebook
```
Download the ipynb file from this repository and run it with Jupyter Notebook

## Built With
* [IBM Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - Data preparation
* [IBM Cognos Dashboard Embedded](https://console.bluemix.net/catalog/services/ibm-cognos-dashboard-embedded?cm_mc_uid=72340057091015874639499&cm_mc_sid_50200000=13853551592124695862&_ga=2.125891533.1351422093.1591961396-1070825662.1587463949) - Dashboard solution
