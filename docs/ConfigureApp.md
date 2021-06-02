## Download and configure the app

1. On the laptop, run the following command in your preferred directory to clone the application source code from GitHub

```
git clone https://github.com/awslabs/auto-check-in-app.git
```

2. open the folder using your favourite text editor. In this demo, I use Visual Studio Code
3. After the code is cloned, navigate to the `auto-check-in-app/source/frontend` directory on your terminal.
4. Run the following command `chmod +x register-operator.sh`
5. open `register-operator.sh` file
6. edit the `REGION` to `us-east-1`
7. edit the stack name to `AutoCheckInAppStack` and save the file

Now, we need to create the access key and secret access key to access for AWS CLI
8. go to [IAM console](https://console.aws.amazon.com/iam/home?region=us-east-1)
9. click `Users` and click your username.
10. click `Security Credentials`
11. in access keys, click `Create access key`
12. click `Download .csv file` and open that file.
13. in your terminal, type `aws configure`
14. fill the Access key ID match with the .csv file.
14. fill the Secret Access Key match with the .csv file.
15. fill the default region name as `us-east-1`
16. click enter for default output format.

Now, we can run the script.

17. Run the following command `./register-operator.sh <your E-mail address>`
18. Enter your password. Please remember it.
19. Open the default.env.json file and copy it to env.json.
20. Modify the file with the applicable values.
Note: You can find the applicable values in the stack Outputs tab.
The following table shows the applicable output keys and values. 

[BACK TO WORKSHOP GUIDE](../README.md)