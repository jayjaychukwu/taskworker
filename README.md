# taskworker

#### Download or clone this repository

#### Create and activate your virtual environment.

Use pip install -r requirements.txt in your command line to install the necessary packages. 

[install redis](https://redis.io/topics/quickstart) and start it locally at port 6379 in one terminal

Open another terminal and navigate to the project folder where manage.py is located and run:
#### celery -A celery_tutorial.celery worker --loglevel=info
               
Open another terminal and navigate to your project folder and run the django server.

In your browser and  put your django local server host followed by '/fib/list'
eg: 127.0.0.1:8000/fib/list

If everything is up and running, you should see the page on your browser.
