# Selenium Basics

We will exercize in utilizing the selenium basic tools :
- finding css selectors
- writing vallue-added UI tests


## Preliminary steps
- You need to download the latest Chrome driver. 
In linux :
```
sudo apt-get install -y chromium-browser
```
- Then execute the steps in **deployment_local.txt**.
- Make sure you add the path to **ChromeSetup.exe** in PATH environment variable.


## Steps
- modify **test.py** to use **Selenium** functionalities.
- Run python **test.py**. This will take you to *http://automationpractice.com/index.php* 


It is useful to understand how to use the css selector in the chrome console : 
```
$$("input[id='element_id']")
$$("a[title='Women']")
```

