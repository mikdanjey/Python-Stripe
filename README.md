# Accept a Payment

Build a simple checkout form to collect payment details. Included are some basic
build and run scripts you can use to start up the application.

## Running the sample

1. Build the server

~~~
pipenv install
pipenv shell
~~~

2. Run the server

~~~
export FLASK_APP=server.py
export FLASK_ENV=development
export FLASK_DEBUG=true

flask run --host=0.0.0.0 --port=5000
~~~

3. Go to [http://localhost:5000](http://localhost:5000)