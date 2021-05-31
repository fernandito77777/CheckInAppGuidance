# Check In App Guidance

## This is a guideline for check In App [here](https://aws.amazon.com/solutions/implementations/auto-check-in-app/?nc1=h_ls#) Please refer to the implementation guide at the page for more detail information.

Check In App is an implementation to compare faces for check-in events. During event registration, users need to take a picture, and the picture will be validated once the users would like to log in or enter to the event.

Here's the reference architecture for the event check in.
![](images/Architecture.jpg)

---
## Prerequisites
1. AWS CLI version 1.16.243 or recent
2. Python version 3.7 or recent
3. OpenCV version 4.1.0 or recent
4. Boto3 python installed
5. git installed to access repository locally

---
## Prerequisites version that has been used for current demo
1. AWS CLI version 2.0.4
2. Python version 3.7.4
3. Open CV version 4.5.2
4. Boto3 version 1.17.73
5. git version 2.23.0
6. Tested on MacOS environment

---

## Agenda
0. Install prerequisites
1. Run CloudFormation Stack template for infrastructure
2. Upload Registration Image to Amazon S3
3. Download and configure the app
4. Launch and run the App

---
## 0. Install prerequisites
- AWS CLI
    to install AWS CLI, please refer to [this page](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html) And choose which version you would like to install (Version 2 is recommended)
- Python
    Please refer to this page for [python installation](https://www.python.org/downloads/)
- OpenCV
    on MacOS, open your terminal and type `python3 -m pip install opencv-python`
    on Windows, open your command prompt and type `python3 -m pip install opencv-python`. Please refer to [this page](https://docs.opencv.org/master/d5/de5/tutorial_py_setup_in_windows.html) for more detail.
- Boto3
    MacOs: on your terminal, please type `python3 -m pip install boto3`
    Windows: on your command prompt, please type `python3 -m pip install boto3`
- Git
    refer to this page for [installing git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) on your local computer

---
## 1. Run CloudFormation Stack template for infrastructure


---
## 2. Upload Registration Image to Amazon S3


---
## 3. Download and configure the app


---
## 4. Launch and run the App
