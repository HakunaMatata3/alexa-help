# alexa-help

### Requirements

* An Amazon Developer account. This is required to create and configure Alexa skills.
* An Amazon Web Services (AWS) account. This is required for hosting a skill on AWS Lambda.
* pip
* python 2.7
* virtual enviroment

### SDK setup in virtual enviroment

### Prerequisites

The ASK SDK for Python requires Python 2 (>= 2.7) or Python 3 (>= 3.6). Before continuing, make sure you have a supported version of Python installed. To show the version, from a command prompt run the following command:

* python --version

### Set up the SDK in a virtual environment

* pip install virtualenv (if not installed)

### create a create a new folder for your Alexa skill and navigate to the folder:
*  mkdir skill

* cd skill

### create a virtual environment called skill_env by issuing the following command:

* virtualenv skill_env

### Run the following command to activate your virtual environment:

* source skill_env/bin/activate

### The command prompt should now be prefixed with (skill_env), indicating that you are working inside the virtual environment. Use the following command to install the ASK Python SDK:

* pip install ask-sdk

### copying the python code in the respective folder

* Depending on the version of Python you are using, the SDK will be installed into the skill_env/lib/Python3.6/site-packages folder.

* copy the hello_world.py file into the site-packages folder and create a .zip file of the contents of the folder (not the folder itself). Name the file skill.zip. 

* Now upload the skill.zip in the lambda function.


