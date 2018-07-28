# Hacking 101 Demos

This repository contains Python Flask applications which will be provided as demos during the Girls in Tech Hackathon on July 28th, 2018.

### Getting Started

You will need Python 2 installed on your development computer to run these demos.

In addition to Python, you will need to install the dependencies/requirements for each project individually.

To do this, `cd` into the directory of the project you would like to run. In each directory, there is a *requirements.txt* file which contains the name of each package you will need.

*We recommend creating and activating a virtual environment before moving forward, but this is an optional step. [Read more about Python virtual environments here](https://virtualenv.pypa.io/en/stable/).*

Use pip to install these requirements recursively:

```
(env) $ pip install -r requirements.txt
```

Next, you should create a `secrets.sh` file with the necessary environment variables for each project. 

_Refer to each directory's sample-secrets.sh to see what's needed to run a given project_.

After creating your own `secrets.sh`, source it:

```
(env) $ source secrets.sh
```


Finally, you can run the application with:

```
(env) $ python server.py
```

Once the application is running, you can navigate to [localhost:5000](localhost:5000) in your browser to view the behavior.

You will use this same process to run each of the applications.

###### That's all you need! Get coding :star: