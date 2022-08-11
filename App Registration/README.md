# Register a web application

## Register a application
Go in your Azure AD B2C directory and click on "App registrations".

![image](./images/App-Registration-1.png)

## Enter all informations
- Enter the name of your app
- Select the third option
- Under "Redirect URI", select "Web" and enter the URL of your app
- Click on "Register"

![image](./images/App-Registration-2.png)

## Create a client secret
In your app, go to "Certificates & secrets".

![image](./images/App-Registration-3.png)

![image](./images/App-Registration-4.png)

- Click on "New client secret" to create a new one.

![image](./images/App-Registration-5.png)

- Enter the name of your secret and define the expiration. Please do not select more than 12 months.

![image](./images/App-Registration-6.png)

- keep the secret value in a vault. We will use it later.

![image](./images/App-Registration-7.png)

## Enable ID token
For this app, it's required to enable "ID tokens".

![image](./images/App-Registration-8.png)


# Disclaimer
See [DISCLAIMER](./DISCLAIMER.md).