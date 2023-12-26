# API

## Creating an API token

To create an API token, login and click your name in the top right corner, then click on the **API Tokens** menu. In the ***Create API Token*** section you will be asked to enter a name for your token. Once you have entered a name and selected the permissions you want to give the token, click on the `Create` button.

**Our suggestion:**
> Create one token for each project or one token for each environment.

## Authentication

To authenticate your requests, you need to add the `Authorization` header to your request. The value of the header should be `Bearer {token}`. Replace `{token}` with your token.
