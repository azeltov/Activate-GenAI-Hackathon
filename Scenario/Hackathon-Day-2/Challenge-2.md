# Challenge 02: Implement Document Search with Azure AI Search

### Estimated Time: 120 minutes

## Introduction:

Contoso is leveraging Azure AI Search and Azure OpenAI (GPT-3.5-Turbo) to create a document search solution that not only makes support documents easily searchable but also uses OpenAI's powerful language model to understand and process customer queries effectively. This integration will enable Contoso to provide accurate and relevant responses, thereby streamlining its support services.

Azure AI Search will be used to organize and index Contoso's large volumes of support documents, while Azure OpenAI will interpret customer queries for semantic search, improving the search results' relevance. This fusion of technologies will assist in making informed decisions and extracting vital information from unstructured data, ultimately providing a seamless information retrieval system that enhances Contoso's customer support experience.

In this challenge, you'll clone a provided repository to lay the groundwork for Azure AI Search, integrate it with Azure AI Services, and create a powerful indexer for advanced search capabilities. Finally, you'll work on refining search queries and kickstart the development of a search application that leverages both Azure AI Search and OpenAI's language model.

## Challenge Objectives:

> **Important**: When deploying services in this challenge, please make sure to use the resource group named **<inject key="Resource Group Name"/>** !

1. **Clone the Repository:**
   - Clone the repository within Visual Studio Code: `https://github.com/MicrosoftLearning/AI-102-AIEngineer`.
   > Hint : You can utilize the following repository, https://github.com/MicrosoftLearning/AI-102-AIEngineer, to explore and perform the scenarios listed below.

2. **Setup Azure Resources:**
   - Create an Azure AI Search resource with basic pricing.
        > **Note:** If you encounter the error **Cannot get costs for subscription** on the top while creating the search service, please ignore it.
   - Create an Azure AI Service with the Standard S0 SKU.
        > **Important**: Your **Azure AI Search** and **Azure AI Service** resources must be in the same location.
        
        > Please find this link and use any regions which supports Azure AI Services. https://learn.microsoft.com/en-us/azure/search/search-region-support#americas
   - Create an Azure Storage Account with the Standard Tier.
        > **Note:** Check the box next to **Allow enabling anonymous access on individual containers**.

3. **Prepare Document Upload:**
   - In Visual Studio Code, within the cloned repository, navigate to the 22-create-a-search-solution folder.
   - Edit the UploadDocs.cmd batch file with the required values.

4. **Execute the Upload Script:**
   - Open and examine the UploadDocs.cmd batch file using VS Code.
   - Execute the batch file to ensure that the necessary resources and files are created in Azure.

   > Hint: Begin by ensuring you have the proper credentials. This command will guide you through logging into your Azure account using the Azure CLI

6. **Data Import and Indexing:**
   - Import data for AI Search using Blob Storage.
   - Link with Azure AI Services and customize the index.
   - Create an indexer for seamless data integration.

7. **Query Indexed Documents:**
   - Tweak queries to include counts and specific fields.
   - Define search components.
   - Query the modified index to retrieve refined and targeted information.

   > Hint: Refine your queries to count results, choose specific fields, configure search components, and use the updated index for detailed and focused information retrieval.

9. **Deploy & Test a Search Client Application:**
   - Update application settings and configure the web app.
   - Run the application locally to test the search functionality.

   > Hint: The application supports multiple languages; choose the one that suits your project's requirements. Adjust your application settings and configure the web application as needed. Then, run the application locally to test the search functionality before proceeding with deployment. 

      <validation step="00185b3f-b0cd-4db1-87bf-d782f730cf95" />
   
## Success criteria:

To successfully complete this challenge, you must:

   - Deploy the Azure Search Service and Azure Storage Account.
   - Add data to the storage account.
   - Index the documents in Azure AI Search using the Azure portal.
   - Customize the index and configure the indexer in Azure AI Search.
   - Modify and explore search components using JSON definitions.
   - Utilize the Azure AI Search SDK to create a client application for search.
   - Run the web application locally, perform searches, and refine search results effectively.

## Additional Resources:

- Refer to [What is Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search) for reference.
- [What are Indexes in Azure AI Search?](https://learn.microsoft.com/en-us/azure/search/search-what-is-an-index)
- [Searching document text at scale using Azure Cognitive Search](https://benalexkeen.com/searching-document-text-at-scale-using-azure-cognitive-search/)
