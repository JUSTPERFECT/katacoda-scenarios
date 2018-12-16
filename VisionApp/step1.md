This is your first step.

Installing python3.7 runtime on ubuntu
## Task

Perform updates on ubuntu

`apt update && apt upgrade -y` {{execute}}

Downloading python3 dependencies

`apt install build-essential -y`{{execute}} 
`apt install libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev -y`{{execute}}

downloading the python source

`wget https://www.python.org/ftp/python/3.7.0/Python-3.7.0.tgz`{{execute}}

extracting the python source

`tar -xzvf Python-3.7.0.tgz`{{execute}}

change to extracted directory

`cd Python-3.7.0` {{execute}}

building from the source

`./configure`{{execute}}
`make`{{execute}}
`make install`{{execute}}

Now type python3 on the prompt

`python3`{{execute}}

Now you successfully Installed the python3 on ubuntu.
