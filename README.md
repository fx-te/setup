# UI Test Framework
This is a documentation to help you to setup UI test environment with Fusionex Test Framework.

## Prerequisites
* Install [Anaconda](https://docs.anaconda.com/anaconda/install/windows/)
* After installation of Anaconda in previous step, launch `Anaconda Navigator` from Windows menu
* Create virual environment (with Python 3.6)
    * TODO: 
* Install JupyterLab
    * Click side menu `Home`
    * Select the new environment from previous step `python_36` from dropdown `Applications on`


    
    ![jupyterlab.PNG](./images/jupyterlab.PNG)
    * Click `Install` from `JupyterLab`



## Step 2
Press windows button and launch anaconda navigator, click on the environment tab on the left, and create an environment with python ver 3.6

![anaconda_environment.PNG](./images/anaconda_environment.PNG)

## Step 3 

On that new environment, install jupyter lab

![jupyterlab.PNG](./images/jupyterlab.PNG)

## Step 4

Download chromedriver based on the link below: 
https://chromedriver.chromium.org/downloads

Note: Check your google chrome version by clicking on the 3 dots on the top right -> help -> about google chrome and download the correct driver. 

## Step 5 

Open up anaconda command prompt, and execute the below commands. 
![anaconda_prompt.PNG](./images/anaconda_prompt.png)

```
 pip install selenium 
 conda install -c anaconda beautifulsoup4
```




