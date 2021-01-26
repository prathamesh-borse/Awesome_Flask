## How to execute the Your First Flask Website

Step 1:- Clone this Repositry using below command.
`git clone git@github.com:viraldevpb/Awesome_Flask.git`

Step 2:- To execute your first flask website you will need flask to be installed on your local machine, 
         you can use below commands to install flask in your machine.
         
Step 3: Open Command Prompt or Terminal of your Project where you want to install flask then copy below commands.
`pip install flask` - for using this you will need python to be installed on your macine. for installing python use below website.

Step 4. [Download](https://www.python.org/downloads/) Click on this link to install Python.

Step 5. Create a file named tutorial1.py then copy below code 

`from flask import Flask`

`app = Flask(__name__)`

`if __name__ == "__main__":`

`app.run()`
    
Step 6. Then create a Web Page by copying below code

`@app.route("/")` - this sets the route to this page

`def home():`

  `return "Hello! this is the main page <h1>HELLO</h1>"` - some basic inline html
  
  Step 7: For Running your first Flask Website follow below Steps:-
  
   Step 7.1. Open Terminal or Command Prompt of Your Project then execute your program by below command
   `python "tutorial1.py"` - check your file name will be different first check it then execute the program by that name.
          
   Step2. Go to below url on your local Machine from a web browser.
   `https://127.0.0.1:5000/`
          
   Note: Since this is being run locally only the machine running the python script will be able to access the website.
