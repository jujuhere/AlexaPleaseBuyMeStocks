# AlexaPleaseBuyMeStocks - Trading with Amazon Echo
Code Snippet which is part of the Alexa implementation to execute trading with Amazon's virutal assistant and using the lemon.markets API. 

## Instructions for Use
This script can be used as a starting point to implement your own trading service with lemon.markets for your virtual assistant from Amazon.
As you can already see, it only contains the Python code that you can use for the Alexa Developer Console.
The Alexa Developer Console is the environment which allows you to add new skills(including intents + sets) for the Alexa home service. 

I'd recommend you to check out the video tutorial "Zero to Hero" from Amazon to understand the use of the Alexa Developer Console. 
-> https://www.youtube.com/watch?v=CzTKDu7Qgjs

Also, if you're not sure about how to use the lemon.markets API for the project, I'd recommend you to read the document to learn more about how to implement the lemon.markets API into your projects.
-> https://docs.lemon.markets

** Environmental Variables ** 
You'll notice that the script uses several environment variables. Please define the following in an .env file or within your IDE:

- API_KEY - Your lemon.markets API key
- MIC - Market Identifier Code of chosen Trading Venue
- BASE_URL_TRADING - The base URL of the lemon.markets Trading API
- BASE_URL_DATA - The base URL of the lemon.markets Market Data API
- SPACE_ID - ID of your space

## Interested in contributing?
This (and all lemon.markets open source projects) is work in progress. 
If you are interested in contributing to this repository, simply create a PR and/or contact the team of lemon.markets at support@lemon.markets.
To learn more about the usage of the Alexa Developer Console, feel free to contact me (mojomailservice@gmail.com) and I'll send you the presentation with a step-by-step tutorial of getting into the Console. 

Looking forward to building lemon.markets with you 🍋
