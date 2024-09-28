Slack Cryptocurrency Bot </br></br>

A real-time cryptocurrency analysis bot for Slack that provides market snapshots, candlestick pattern detection, price alerts, and summarized news with key insights. This bot is designed to help users track cryptocurrency prices, analyze market trends, and make informed trading decisions directly from Slack.</br>

Features

	•	Cryptocurrency Market Snapshots: Fetch and display real-time market data (price, volume, bids/asks) for selected cryptocurrencies.
	•	Candlestick Pattern Analysis: Detect and display common candlestick patterns to identify market trends or reversals.
	•	Interactive Slack Interface: Allows users to select cryptocurrency symbols from a dropdown and get detailed analysis in the channel.
	•	Real-time Price Alerts: Set up notifications for significant market changes.
	•	News Summaries & Insights: Fetch the latest cryptocurrency news from CoinGecko and provide summarized insights using OpenAI’s GPT-4 model.
	•	Scheduled Email Reports: Automatically send cryptocurrency news summaries and market insights to an email address every 12 hours.

Getting Started </br>

Prerequisites</br>

	1.	Slack API: Create a Slack app and generate an OAuth token. Ensure your app has the necessary permissions (e.g., chat:write, commands, interactivity).
	2.	CoinGecko API: No API key is required for CoinGecko, but make sure you read their API documentation for rate limits.
	3.	OpenAI GPT-4 API: Create an account and get your API key from OpenAI to generate news summaries and insights.
	4.	Gmail API: Set up OAuth credentials to enable email sending via the Gmail API.

Future Enhancements I am working on:</br>

I am working on tracking user information and using content based filtering to have customized news and ticker information based on users past interests.</br>
Making this automated using Github actions or Google Cloud Functions etc. to automate updates, recording user's likes.</br>
