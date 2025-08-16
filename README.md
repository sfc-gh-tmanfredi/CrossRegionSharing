CrossRegionSharing
Notebook to demonstrate how data products can be listed and shared to other regions and clouds using Cross Region AutoFulfillment

You will need 2 Snowflake accounts to properly demonstrate this functionality. We will refer to them as the Provider and Consumer accounts

1. Download the .ipynb and .png files from this repo
2. Use Snowsight to access your Provider Snowflake account.
3. Click Projects->Notebooks in the left pane
4. Click the down arrow under +Notebook in the upper left and select "Import .ipynb file"
5. Navigate to the notebook file CROSSREGIONSHARE.ipynb that you downloaded
6. Open the notebook CROSSREGIONSHARE
7. Open the left pane. Select the "Files" tab
8. Click the "+" sign and select Upload from Local
9. Navigate to the XRegionSharing.png file you downloaded from the repo

Now you are ready to execute the demo. Execute each cell in the notebook. It will walk through documented steps to create the environment, test data, create and publish the listing, and access it from the consumer account
