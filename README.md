# Load-Testing-Using-Locust
A simple demo on how to perform load testing  on flask API using Locust.

## How to run the tests ##
#### Run the Flask App ###
 ```
 git clone 
 cd Load-Testing-Using-Locust
 pip install -r requirements.txt
 python3 app/app.py  (For python Version 3.x)
 python app/app.py   (For python version 2.x)
 ```
 ### Run Locust ###
 ```
 locust --host=http://localhost:5000  
 ```
 Navigate to the web interface of Locust  which by default is at http://localhost:8089
 
 Tests the Load e.g If our API supports 1000 users and a hatch rate of 500 (number of users spawned by second)
 
 
 
 
 
