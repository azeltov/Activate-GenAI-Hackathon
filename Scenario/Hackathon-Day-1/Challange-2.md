# Challenge 02: Implement Document Search with Azure AI Search

### Estimated Time: 120 minutes

## Introduction:

Contoso is leveraging Azure AI Search and Azure OpenAI (GPT-3.5-Turbo) to create a document search solution that not only makes support documents easily searchable but also uses OpenAI's powerful language model to understand and process customer queries effectively. This integration will enable Contoso to provide accurate and relevant responses, thereby streamlining their support services.

Azure AI Search will be used to organize and index Contoso's large volumes of support documents, while Azure OpenAI will interpret customer queries for semantic search, improving the search results' relevance. This fusion of technologies will assist in making informed decisions and extracting vital information from unstructured data, ultimately providing a seamless information retrieval system that enhances Contoso's customer support experience.

In this challenge, you'll clone a provided repository to set the groundwork with Azure AI Search, integrate it with Azure AI Services, and create a powerful indexer for advanced search capabilities. Finally, you'll work on refining search queries and kickstart the development of a search application that leverages both Azure AI Search and OpenAI's language model.

## Challenge Objectives:

> **Important**: When deploying services in this challenge, please make sure to use the resource group named **<inject key="Resource Group Name"/>** !

1. **Clone the Repository:**
   - Clone the repository within Visual Studio Code: `https://github.com/MicrosoftLearning/AI-102-AIEngineer`.

2. Setup Azure Resources
   - Create an Azure AI Search resource with the Standard S0 SKU.
   - Create an Azure AI Service with basic pricing.
   - Create an Azure Storage Account with the Standard tier.
3. Prepare Document Upload:
   - In Visual Studio Code, within the cloned repository, navigate to the 22-create-a-search-solution folder.
   - Edit the UploadDocs.cmd batch file with the required values.
4. Execute Upload Script:
   - Open and examine the UploadDocs.cmd batch file using VS Code.
   - Execute the batch file to ensure that the necessary resources and files are created in Azure.
   - Hint: Ensure you are logged into Azure in the command prompt to execute the file.
5. Data Import and Indexing:
   - Import data for AI Search using Blob Storage.
   - Link with Azure AI Services and customize the index.
   - Create an indexer for seamless data integration.
6.Query Indexed Documents:
   - Tweak queries to include counts and specific fields.
   - Define search components.
   - Query the modified index to retrieve refined and targeted information.
7. Deploy & test a Search Client Application:
   - Update application settings and configure the web app.
   - Run the application locally to test the search functionality.
   - Hint: The app is available in two languages; use the one that aligns with your scope.
   
## Success criteria:
To successfully complete this challenge, you must:

   - Deploy the Azure Search Service and Azure Storage Account.
   - Add data into the storage account.
   - Index the documents in Azure AI Search using the Azure portal.
   - Customize the index and configure the indexer in Azure AI Search.
   - Modify and explore search components using JSON definitions.
   - Utilize the Azure AI Search SDK to create a client application for search.
   - Run the web application locally, perform searches, and refine search results effectively.


## Additional Resources:

- Refer to [What is Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search) for reference.
- [What are Indexes in Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-an-index)
- [Searching document text at scale using Azure Cognitive Search](https://benalexkeen.com/searching-document-text-at-scale-using-azure-cognitive-search/)

## Challenge Validation
 
1. After completing the challenge, you need to visit the **Lab Validation (1)** tab and click on the **VALIDATE (2)** button under Actions to perform the validation steps. Verify that you have met the success criteria of the challenge. 
 
    ![](../media/validate01.png "Validation")
 
1. If the validation status displays **Success** for all the validation steps, **congratulations!**. This means that you have completed the challenge and have unlocked the next challenge.
 
     ![](../media/validate02.png "Validation")

1. If the validation status displays **Fail**, **don't worry!** This could mean that you did not perform the challenge correctly.
 
     ![](../media/validate03.png "Validation")
 
1. Hover your mouse over the `i` **(1)** icon to see the error message and determine the root cause of the failure. Based on the error message, revisit the challenge as necessary, and redo the validation by clicking on the **VALIDATE (3)** button again.

   ![](../media/validate04.png "Validation")
 
1. If you are still having trouble, you can reach out to the support team via `labs-support@spektrasystems.com` for further assistance. The support team is available to help you to troubleshoot and resolve any technical issues or validation issues that may arise while the lab environment is live.