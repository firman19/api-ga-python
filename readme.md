# API for Google Analytic 4 using Python  

### Official Documentation
https://developers.google.com/analytics/devguides/reporting/core/v4/quickstart/service-py

### Steps
1. Enable API and create service account in https://console.cloud.google.com/  
2. Add service account to GA 4 view  
3. Move the previously downloaded client_secrets.json to the same directory as the code
4. Install client library  
Mac/Linux  
```
pip install virtualenv
virtualenv <your-env>
source <your-env>/bin/activate
<your-env>/bin/pip install google-analytics-data
```
Windows  
```
pip install virtualenv
virtualenv <your-env>
<your-env>\Scripts\activate
<your-env>\Scripts\pip.exe install google-analytics-data
```
5. Set your VIEW ID  
6. Run ```py HelloAnalytics.py```
