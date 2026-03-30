# Deploy Your AI Bot to Azure

## One-Click Deployment

Click the button below to deploy this AI bot to your Azure subscription:

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fiampranjal-dev%2Fteams-bot-deployment%2Fmain%2Fdeployment%2Fazuredeploy.json)

## What This Will Create

- **Azure Web App**: Hosts your AI bot
- **Azure Bot Service**: Enables Teams integration  
- **Managed Identity**: Secure authentication
- **App Service Plan**: Compute resources

## Prerequisites

Before clicking deploy, you need:

1. **Azure Subscription** with permissions to create resources
2. **Azure OpenAI Service** already set up with a deployed model
3. **Resource Group** (can be existing or create new during deployment)

## Deployment Steps

1. Click the "Deploy to Azure" button above
2. Sign in to your Azure account
3. Fill in the required parameters:
   - **Resource Base Name**: Unique name for your resources (4-20 characters)
   - **Bot Display Name**: Name shown in Teams
   - **Azure OpenAI Endpoint**: Your OpenAI endpoint URL
   - **Azure OpenAI Key**: Your OpenAI API key  
   - **Azure OpenAI Deployment Name**: Your model deployment name
   - **Web App SKU**: Choose B1 (Basic) or higher for production
4. Click "Review + Create"
5. Click "Create" to start deployment

## After Deployment

1. Note the **Bot ID** from deployment outputs
2. Install the Teams app package (provided separately)
3. Your bot will be ready to use in Microsoft Teams!

## Cost Estimate

- **App Service Plan B1**: ~$13/month
- **Bot Service**: Free tier available
- **Azure OpenAI API**: Pay per usage

## Support

If you encounter issues during deployment, contact your solution provider.
