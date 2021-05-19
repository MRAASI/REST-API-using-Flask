# REST-API-using-Flask  


# What is an API 
Application Programming interface is a part of a computer program to be used by another program 

# API Terminologies 
1.HTTP ('GET','POST') 
2.URL
3.JSON
4.REST

# what is REST 
REST is basically a set of rules followed to make an API


# What is REST API
RESTFul API is an advance concept of web development that implemented at server and used with HTTP method (GET/ POST/ PUT/ DELETE) to handle the data. The HTTP request methods and resources are identified using URIs and handled functionality accordingly. 

# What is Flask 
flask is a microframework in Python. 


# Running the Application
In the command line, navigate to your api folder.Once you’re in your project directory, run the Flask application with the command:
python app.py
You should see output similar to this:
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit) 


# A route to return all of the available entries in our catalog.

@app.route('/all', methods=['GET'])  

for running: http://127.0.0.1:5000/all

# A route to return certain  entries in our catalog.

@app.route('/booksid', methods=['GET']) 

 for running : http://127.0.0.1:5000/booksid?id=0   
 
 If the id given is not in catalog Each , which should return an empty list: []

# To insert new entry into catalog
@app.route('/insert',methods=['GET','POST']) 

http://127.0.0.1:5000/insert
