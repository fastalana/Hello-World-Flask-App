# "Hello, World!" Flask App
This is a simple, "Hello World" Flask App.  

### Development Setup

First, [install Flask](http://flask.pocoo.org/docs/1.0/installation/#install-flask) if you haven't already.

  ```
  $ cd ~
  $ sudo pip3 install Flask
  ```

To start and run the local development server,

1. Install the dependencies:
  ```
  $ pip install -r requirements.txt
  ```

2. Run the development server:
  ```
  $ FLASK_APP=app.py FLASK_DEBUG=true flask run
  ```

3. Navigate to Home page [http://localhost:5000](http://localhost:5000)
