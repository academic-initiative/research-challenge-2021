# Welcome to the CFC Research Challenge - Technical Details
Here's a list of the climate-related Assets we are making available for this challenge as well as the host to Jupiter notebook infrastructure. The only requirement for the challenge is that you use at least one of these assets in your solution.

## Contents
- [Hosted Jupyter Notebooks](#Jupyter-Environment) - We are providing a hosted Jupyter notebook platform for your use. 
- [IBM Environmental Intelligence Suite](#IBM-Environmental-Intelligence-Suite) - IBM's integrated  weather and climate suite
  - [PAIRS](#ibm-Pairs) - IBM's Geospatial Analytics package
  - [The Weather Company](#weather-company) - the worlds most use weather resource
 - [TAHMO Weather Stations](#TAHMO-Weather-stations) - IBM Sponsored weather station that are part of the Trans-African Hydro-Meteorological Observatory (TAHMO)
 - [Open source climate repositories](#Additonal-Open-Source-Climate-Data-Repository) - A few open source climate data repositories.. there are many more out there 

## IBM Environmental Intelligence Suite 

The [IBM Environmental Intelligence Suite (EIS) ](https://www.ibm.com/products/environmental-intelligence-suite) is IBM's premier tool for climate analysis it includes a rich set of  components including  geospatial–temporal climate data analysis and historical weather data and weather prediction. For our Call For Code Research Challenge we will be using two components of EIS: the [PAIRS](https://www.ibm.com/products/environmental-intelligence-suite/geospatial-analytics)  for Geospatial-temporal analytics  and [The Weather Company (TWC)](https://www.ibm.com/products/environmental-intelligence-suite/data-packages) for historical weather and predictions. Here's a helpful getting started guide 

- [EIS Getting Started Guide](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/Getting%20Started%20-%20Call%20For%20Code%20Research%20Challenge%202021.pdf) - Start here to learn how to use the power of all of the EIS Components. **Note: start with this document**
- [The Weather Operations Center](http://weatheroperationscenter.ibm.com) - the Dashboard of the  [IBM Environmental Intelligence Suite (EIS)](https://www.ibm.com/products/environmental-intelligence-suite) 

### IBM Pairs
IBM PAIRS is the [Geospatial Analytics component](https://www.ibm.com/products/environmental-intelligence-suite/geospatial-analytics)  of the [IBM Environmental Intelligence Suite](https://www.ibm.com/products/environmental-intelligence-suite) It has a very rich set of visualization interfaces, API's,  geo-spatial-temporal datasets and analytics tools.

**Note: your PAIRS API credentials will be emailed to you separately from the email noreply@wsitrader.com **

- [PAIRS Interactive Tutorial](https://pairs.res.ibm.com/tutorial/tutorials/gui/index.html) - Powerful user interface that can be used to view data sets, data layers and analytics results
-  [PAIRS User Interface](https://ibmpairs.mybluemix.net/) - logon here to use the interactive PAIRS user experience
- PAIRS API Usage
  - [PAIRS API Tutorial](https://pairs.res.ibm.com/tutorial/tutorials/api/index.html#) - API used to access PAIRS Data, Layers and Analytics Functions progrmatically
  - [PAIRS API SWAGGER](https://pairs.res.ibm.com/manual/api-doc/#) - Detailed API Docs
  - [PAIRS Installation guide](https://github.com/ibm/ibmpairs) - needed only if not using our hosted Jupyter notebooks
  - [PAIRS Dataset List](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/EIS%20DataSet%20Report%20July%202021.pdf)  - description of the many datasets and data set numbers for PAIRs           
- [PAIRS Start here Notebook Examples](https://github.com/IBM/ibmpairs/tree/master/examples) - some simple climate-related examples of Jupyter notebooks with PAIRS API usage
<!--- 
- PAIRS Start here Notebook Examples - 3 Simple examples of Jupyter notebooks with PAIRS API usage
  - [Climate_change](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/PAIRS%20Examples/Climate_change.ipynb) - look at climate change over time
  - [Standardized_Precipitation_Index](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/PAIRS%20Examples/Standardized_Precipitation_Index.ipynb) - look at rainfall patterns over time in the US
  - [WildfireAnalytics (still being updated)](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/PAIRS%20Examples/WildfireAnalytics.ipynb) - look at Wildfire statistics in the world.
--->
### Weather Company
The Weather Company (TWC) is IBM's  premier weather platform and  the largest commercial weather platform in the world. It  used by more people than any other weather data source in the world.  The  has a huge collection of weather history, current weather and forcasts.  

**Note:your Weather Company API credentials can be found in [EIS Getting Started Guide](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/EISGettingStartedGuide.pdf)** Please use the key thats assigned to your team !

- [The Weather Company (TWC)](https://www.ibm.com/products/environmental-intelligence-suite/data-packages) - Here's a quick overview of The Weather Company from a programmers perspective. 

- [TWC  Getting Started Guide for Call for Code](https://developer.ibm.com/blogs/call-for-code-the-weather-company-and-you/) - a comprehensive guide how to use the Weather company in variety of programming models. It's full of API documents, tutorials and examples
- TWC API Usage
  - [TWC API Docs](https://docs.google.com/document/d/15Ru_3wdMgpbM4aOCm-4qNAnRfjx2w-Ruw3lnr8Hnodk/edit#)
  - [TWC API SWAGGER](https://twcservice.mybluemix.net/rest-api/) - Detailed API Docs

- TWC Tutorials
  - [Call-for-code-the-weather-company-and-you](https://developer.ibm.com/blogs/call-for-code-the-weather-company-and-you/)
  - [weather-api-nodejs](https://github.com/Call-for-Code/weather-api-nodejs)
  - [weather-api-python](https://github.com/Call-for-Code/weather-api-python)
  - [Node-RED-Severe-Weather-Alert-Map](https://github.com/johnwalicki/Node-RED-Severe-Weather-Alert-Map)
  - [Node-RED-TWC-Weather-Radar-Map](https://github.com/johnwalicki/Node-RED-TWC-Weather-Radar-Map)
  - [Node-RED-Weather-Routing-Logistics](https://github.com/johnwalicki/Node-RED-Weather-Routing-Logistics)

- TWC Notebook Examples
  - [Simple TWC data download example](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/download_twc.ipynb)- fetch and viaualize TWC data

## TAHMO Weather stations
Over the past several years IBM  has  supported [Trans-African Hydro-Meteorological Observatory (TAHMO)](http://tahmo.org) in their creation of a network of high accuracy weather stations in sub-Saharan Africa. IBM  has sponsored the creation and maintenance of over 300 stations who's Data flows into The Weather Company databases. Thanks to  the TAHMO organization,  we will have unlimited access to one year of hostorical data from all of the TAHMO weather stations in Kenya for the  duration of our Call for Code Research Challenge.
 
- [Current Weather Data from IBM Sponsored TAHMO Stations](https://www.google.com/maps/d/u/0/edit?mid=121QEOy-mkS2S9VHn0rjk-X2xUuMc2O-9&ll=6.263995812154352%2C5.355502397297634&z=3) - here's a map where you can see the IBM Sponsored TAHMO weather stations as they appear in the IBM weather company data interface
- [Example code to accces TAHMO data](https://github.com/TAHMO/API-V2-Python-examples) - examples  to get historical data for all of the  weather stations in Kenya for the past year directly from TAHMO. Includes python and notebook examples. 


## Additonal Open Source Climate Data Repository
As part of the Call for Code Research Challenge you are required to use at least one of the IBM  climate components described above . In addition you're able to use any number of open source climate and weather data sets available on the Internet. Here are a few examples
- [Copernicus  Climate repository](https://cds.climate.copernicus.eu/#!/home_) - Great world climate databases proviceded by the European Union
- [US Geologic Survey open World explorer](https://earthexplorer.usgs.gov/.)

## Jupyter Environment

Our jupyter notebook environement is available at [ibm.biz/cfcnotebook](http://ibm.biz/cfcnotebook).  A set of step-by-step instructions on how to access the environment are available [here](https://github.com/academic-initiative/research-challenge-2021/blob/main/jupyter-platform/how-to-access.md).

We'll start with a very quick tour of the Jupyter Interface for those who may not be familiar with JupyterHub.  The Jupyter Environment is made of two primary components.  The main editing window

![image1](images/welcome1.png)

And the file navigation area where you can upload, rename, copy, delete the files you are working with.

![image2](images/welcome2.png)

## Getting help

In the Slack workspace, you’ll be able to find other participants, join or build teams, brainstorm and collaborate on ideas, and communicate with the challenge Champions and Subject Matter Experts for mentoring and technical guidance. [Join the Slack](https://join.slack.com/t/callforcodere-ju79661/shared_invite/zt-uc2w9nn4-zEf9urnpE1c7~EIGJblx_Q)

Please join the following channels in the workspace:

[#2021-research-challenge](https://callforcode-research.slack.com/archives/C02BVGGJDJ7)

For more information regarding logistics, submissions, judging etc. Please visit our main page at [ibm.biz/cfc-research-challenge](https://ibm.biz/cfc-research-challenge)


[Back to the main Research Challenge page](https://github.com/academic-initiative/research-challenge-2021)
