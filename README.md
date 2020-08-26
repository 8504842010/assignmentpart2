# API written in Python and Flask
A project who return a capital of the country.

Note it's preferred to use Git bash terminal when on Windows. You can download it from [here](https://git-scm.com/downloads).

Also, Python3.7 should be installed and added to PATH.
 
    $ python --version
    Python 3.7.3
    
Also, setup Uvicorn (The Lightning-fast ASGI server).You can check it from [here](https://github.com/encode/uvicorn/blob/master/README.md).

### Goal
* Fork the project.
* Clone the repo.
* Share the link to your repo.


### How to run code locally
Before running tests locally make sure, you have forked the project to create your own copy of the repo. Then clone the repo into your local machine.

Cd into your local repo
     
    $ cd country-capital-api
    
Make sure you are in the root directory of the project

    $ ls
    src/  

Run the server:

$ uvicorn example:app

Run the code

    $ python api_code.py
    
Now navigate to browser and type 
    https://localhost:port-no/country-capital/<query-params> 
 
    <query-params> write the Country-Name
     port-no: which you used in code
    
There is a microservice endpoint for this API available at

    https://example.com/country-capital/<query-params>
