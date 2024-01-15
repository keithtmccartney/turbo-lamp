# turbo-lamp
[C#] (Microsoft AZ-204 certification) Exercise: Send and receive message from a Service Bus queue by using .NET

# Notes
[https://learn.microsoft.com/en-us/training/modules/discover-azure-message-queue/6-send-receive-messages-service-bus](https://learn.microsoft.com/en-us/training/modules/discover-azure-message-queue/6-send-receive-messages-service-bus)

# Commands
* az login;
* az group create --name az204-svcbus-rg --location uksouth;
* az servicebus namespace create --resource-group az204-svcbus-rg --name turbolamp --location uksouth;
* az servicebus queue create --resource-group az204-svcbus-rg --namespace-name turbolamp --name az204-queue;
* az group delete --name az204-svcbus-rg --no-wait;
