#Create Azure Cosmos DB account
1. From the Azure Portal, click on the **Create a resource** link
2. Click on the Azure Cosmos DB link (or search for it in the Marketplace if it is not showing)
3. From the Basic page:
- Select the appropriate Subscription
- Select or create the appropriate Resource Group
- Supply the Account Name
- Select the API you wish to use (remember you CANNOT change this later on)
- Determine whether to turn on Notebooks
- Choose the Location with the most approximately to primary base
- Choose the appropriate Cpaacity mode (Provisioned throughput or serverless)
- Click on the Review + create
- Click on the Create button
4. Wait for the the Azure Cosmos DB account to be created

#Create Azure Cosmos DB database
1. Go to your newly created Azure Cosmos DB account
2. Click on the Data Explorer menu option
3. Click New Container
- Specify the database and container identifiers and enter /Item for the partion key
