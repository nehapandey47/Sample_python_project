from flask import Flask

app = Flask(__name__)

@app.route( '/' )
def hello():

  return "Hi! This is all about Jenkins pipeline"
if __name__ == "__main__":

     app.run()