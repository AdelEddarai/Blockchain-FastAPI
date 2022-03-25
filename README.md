
https://github.com/AdelEddarai/Blockchain-FastAPI/
# Getting started with Python Blockchain and FastAPI
This FastAPI application implements some Algorand blockchain processes.

---
**Security warning**

This project has not been tested and should never be used in production

---

# Requirements

You must have python 3 installed on your system. Also for this tutorial you will need `python3-venv`. This package can be installed with the following command. 
```bash
$ sudo apt-get install python3-venv
```

# Setup
First create a root folder for the project
```bash
cd ~
mkdir Block-FastApi
cd Block-FastApi
```
Then clone this repository into it
```bash

cd Block-FastApi
```
Then create and activate a new virtual environment
```bash
python3 -m venv Block-FastApi
./Block-FastApi/bin/activate
```
Then install all dependencies with the following command
```bash
(Block-FastApi) $ pip3 install -r requirements.txt
```
Now you can run the application with this command
```bash
(Block-FastApi) $ uvicorn main:app --reload
```
As soon as the application starts, you will have access to the online documentation at http://127.0.0.1:8000/docs#/
