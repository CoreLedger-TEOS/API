# CoreLedger TEOS API

This repository contains postman examples for CoreLedger TEOS API. This guide explains how to import the collection to Postman from Github and how to get an API-Key from CoreLedger support to use with the API. Additionally, we will go over the prerequisites for running requests.

## Importing the Collection to Postman

1. Clone the repository by running `git clone https://github.com/CoreLedger-TEOS/API.git` in your terminal or by downloading the repository as a ZIP file.
2. Open Postman and click on the **Import** button in the top left corner.
3. Select **Import From Folder** and navigate to the cloned repository folder.
4. Make sure that `Teos.Api` collection and `TEOS API [PILOT]-Api-Key` environment  are selected and click on **Import** button.

You should now have the collection and environment imported into your Postman workspace.

## Getting an API-Key

To use the CoreLedger TEOS API, you will need an API-Key. You can request an API-Key by emailing support@coreledger.net. Once you have received your API-Key, you will need to add it to your Postman environment.

1. Click on the **Environments** tab in the left sidebar.
2. Click on `TEOS API [PILOT]-Api-Key` environment.
3. Change the current value of the **env.authToken** variable to your API key token.
4. Save all the changes by pressing the **Ctrl + S** combination or clicking the **Save** button in the top right corner of the environment window.

You can now select the `TEOS API [PILOT]-Api-Key` environment when making requests to the CoreLedger TEOS API.

## Prerequisites for Running Requests

Before running requests, you will need to ensure that you are using the `TEOS API [PILOT]-Api-Key` environment:

- Click on the Environment dropdown in the top right corner of the screen and change the current environment (**No Environment** by default) to `TEOS API [PILOT]-Api-Key`.

And we're done! Now you can use the `Teos Api` Collection to explore our API.
