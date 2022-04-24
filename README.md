# Correlation-Heatmap-Matrix
![image](https://user-images.githubusercontent.com/77221025/164954339-71ece39c-5b34-4e64-b73b-8355126f8a30.png)

## Table of Contents
* [Overview](#Overview)
* [Steps](#Steps)
* [Technologies](#Technologies)
* [Resources](#Resources)

## Overview
As part of a case assignment, I was asked to put together a data visualization model known as a *correlation heatmap matrix* in order to be able to identify some of the main correlations occuring between events. For this, I found some helpful resources and after compiling all of the data into an excel spreadsheet I was able to produce the heatmap matrix. The process was relatively easy & straightforward to follow, so I decided to put together this helpful little guide for anyone who wishes to put together a similar model to the one shown above!   

## Steps
*Note*: In order to be able to follow this guide, make sure you have Jupyter Notebook setup and able to run with Python.     

First, make sure to place all of your data into columns into excel spreadsheet with the first row containing the columns names:      
<img width="528.768" height="297.432" src="https://user-images.githubusercontent.com/77221025/164954818-db6ff46b-2398-4250-922e-da25ed8607ab.png">        

Next, create & open a new jupyter notebook, and begin typing and running the following lines as follows:
- First, make sure to import the following libraries: <br/>
![image](https://user-images.githubusercontent.com/77221025/164955017-9f01f404-de84-41af-b2f7-00cf0b5c51f4.png)   

- Next, read in your Excel file and use the .head() function to check if the output is correct:
![image](https://user-images.githubusercontent.com/77221025/164955193-9817ddd3-7b9c-4f84-872c-1e3999258b47.png)   

- After that, generate the correlation weights using .corr():
![image](https://user-images.githubusercontent.com/77221025/164955276-3eee29d1-e318-47c2-b6a7-dfe6c4143ddb.png)  

- Lastly, use the following lines and voilà, you have your heatmap!
![image](https://user-images.githubusercontent.com/77221025/164955347-2c1e4e8b-894d-42a9-8957-5b37c989aab6.png)  


## Technologies
- Anaconda
- Jupyter Notebook
- GitHub
- GitHub Desktop

## Resources
- Credit goes to [RegenerativeToday](https://www.youtube.com/channel/UCzJgOvsJJPCXWytXWuVSeXw/featured) for the helpful video tutorial I used in generating this heatmap!
