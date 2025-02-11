# Make Sense Of The Copyright Office Comments

An application to summarize and create useful metadata from the comments made on Regulations.gov. This will be useful to the Copyright Office and other people trying to understand the Comments as a demonstration of the utility of computational analysis of the text.

## Getting started

### Clone project
Open the terminal and run the command to download the project
```sh
 $ git clone [https://github.com/atlp-rwanda/rca-phantom-team1-fe.git](https://github.com/Cyebukayire/mscc.git)
```

### Go to the project folder
Use the 'cd' command to navigate to where the project folder is
```sh
 $ cd mscc
```

### Open working environment
Check if 'pip' is already installed on your device with this command: ``` pip version```

If the output does not run successfully to show the version of pip, then install pip with the command below.

Choose the command to run based on your computer's Operating System.

. Install pip on Linux: ``` python get-pip.py```

. Install pip on MAC OS: ``` python get-pip.py```

. Install pip on Linux OS: ``` C:> py get-pip.py```


Still in the 'mscc' folder, create a virtual environment where the project runs. All dependencies and packages required to run the project will automatically be installed in the virtual environment. 

```sh
 $ pipenv shell
```

### Run the project
In the same terminal, run the following command to start the project, replace the DEMO_KEY with your API Key from [Regulations.gov](https://open.gsa.gov/api/regulationsgov/). 

#### If you don't have the key already, the command below can still work using a DEMO_KEY.

```sh
 $ API_KEY="DEMO_KEY" uvicorn main:app --reload
```


#### On successful execution, this link(http://127.0.0.1:8000) will appear in your terminal. Open the link in your browser.

This is the current output in the browser:

![image](https://github.com/Cyebukayire/mscc/assets/55869293/2b987518-d16a-49d9-b611-02b51aa54648)


#### Navigate to the documentation of the API (http://127.0.0.1:8000/docs)

Below is a screenshot of the current API documentation:

![image](https://github.com/Cyebukayire/mscc/assets/55869293/3e6873ac-847e-46f8-afc5-70602ef1135b)
