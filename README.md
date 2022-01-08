# Health Bot Container

A simple web page that allows users to communicate with the [Azure Health Bot](https://azure.microsoft.com/en-us/services/bot-services/health-bot/) through a WebChat.

**Note:** In order to use this Web Chat with the Health Bot service, you will need to obtain your Web Chat secret by going to `Integration/Secrets` on the navigation panel.

![Secrets](/secret.png)

1.Deploy the website:

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2FHealthBotContainerSample%2Fmaster%2Fazuredeploy.json)

2.Set the following environment variables:

`APP_SECRET`

`WEBCHAT_SECRET`


**Note:** If you are deploying the code sample using the "Deploy to Azure" option, you should add the above secrets to the application settings for your App Service.

[To access the Virtual Health Assistant click on the link](http://healthcare-bot-ugensz4vmdckq.azurewebsites.net/)

This Will open the Health bot where the user can diagnoses the symptoms and get the report of the problem.

![webhealth](/webhealth.jpg)


A Sample Conversation with the Virtual Health Assistant

![Conversation](/Conversation.jpg)

