CrossRegionSharing
Notebook to demonstrate how data products can be listed and shared to other regions and clouds using Cross Region AutoFulfillment

You will need 2 Snowflake accounts to properly demonstrate this functionality. We will refer to them as the Provider and Consumer accounts

Download the .ipynb and .png files from this repo
Use Snowsight to access your Provider Snowflake account.
Click Projects->Notebooks in the left pane
Click the down arrow under +Notebook in the upper left and select "Import .ipynb file"
Navigate to the notebook file CROSSREGIONSHARE.ipynb that you downloaded
Open the notebook CROSSREGIONSHARE
Open the left pane. Select the "Files" tab
Click the "+" sign and select Upload from Local
Navigate to the XRegionSharing.png file you downloaded from the repo
Now you are ready to execute the demo. Execute each cell in the notebook. It will walk through documented steps to create the environment, test data, create and publish the listing, and access it from the consumer account
