# Translate-Your-Stuff-with-MS-Azure-Translate-API
This notebook was coded and deployed using Microsoft Azure API. You can use it to translate text to the languages offered in Microsoft Azure Translate API.

Prerequisites
You need an active Azure subscription. If you don't have an Azure subscription, you can create one for free.

Once you have your Azure subscription, create a Translator resource in the Azure portal.

After your resource deploys, select Go to resource and retrieve your key and endpoint.

You need the key and endpoint from the resource to connect your application to the Translator service. You paste your key and endpoint into the code later in the quickstart. You can find these values on the Azure portal Keys and Endpoint page:

Screenshot: Azure portal keys and endpoint page.

 Note

For this quickstart it is recommended that you use a Translator text single-service global resource.
With a single-service global resource you'll include one authorization header (Ocp-Apim-Subscription-key) with the REST API request. The value for Ocp-Apim-Subscription-key is your Azure secret key for your Translator Text subscription.
If you choose to use an Azure AI multi-service or regional Translator resource, two authentication headers will be required: (Ocp-Api-Subscription-Key and Ocp-Apim-Subscription-Region). The value for Ocp-Apim-Subscription-Region is the region associated with your subscription.
For more information on how to use the Ocp-Apim-Subscription-Region header, see Text Translation REST API headers.
