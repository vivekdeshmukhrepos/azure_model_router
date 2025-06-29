# README - Azure AI Foundry Model Router POC

## Overview  
This project demonstrates how to interact with **Azure AI Foundry's Model Router** using the OpenAI SDK. It initializes an Azure OpenAI client, configures a deployment, and sends a prompt for text generation.

## Setup Instructions  

### Prerequisites  
- Python 3.8+  
- OpenAI Python SDK (`pip install openai`)  
- An **Azure OpenAI** account with API key access  

### Configuration  
Ensure your environment variables are set correctly:

```sh
export ENDPOINT_URL="https://moderrouteraifoundry.openai.azure.com/"
export DEPLOYMENT_NAME="model-router"
export AZURE_OPENAI_API_KEY="YOUR_KEY_HERE"
```
## Resources
- https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/model-router 
- https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/model-router