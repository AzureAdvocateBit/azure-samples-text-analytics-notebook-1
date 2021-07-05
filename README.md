# Cognitive Services Text Analytics Sample

This sample uses 10 random Tweets that use the #vscode hashtag to analyze key words and sentiment with Azure Cognitive Services' [Text Analytics](https://azure.microsoft.com/services/cognitive-services/text-analytics/?WT.mc_id=academic-0000-jasmineg) service, using the Python API.

## How to use

- Load this [notebook in VSCode](https://code.visualstudio.com/docs/languages/python?WT.mc_id=academic-26005-jasmineg) or your favorite notebook platform. **Recommended**: use a [virtual environment](https://python.land/virtual-environments/virtualenv)
- Create a text analytics resource in Azure. The Free F0 pricing tier will work for this sample. [Start here](https://ms.portal.azure.com/?WT.mc_id=academic-0000-jasmineg#create/Microsoft.CognitiveServicesTextAnalytics)
- When the resource is created, open the resource and go to the “keys and endpoint blade” in the left of the page. Copy the key and endpoint. 
- Update the environment variables in the .env_sample file with your copied values from the last step
- Rename .env_sample to .env
