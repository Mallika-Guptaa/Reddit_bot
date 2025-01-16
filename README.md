# Reddit_bot
A simple Reddit bot that uses Groq AI to generate and post content automatically.

This Reddit bot automatically generates and posts stories to a specified subreddit using the Groq AI and Reddit APIs. The bot schedules posts to be made at a specific time every hour, ensuring fresh content is delivered without manual intervention.

Prerequisites
Before you set up your bot, ensure you have the following:

Python 3.6 or newer.

PIP for package installation.

A Reddit account with API credentials.

An API key from Groq AI.

Configuration
Reddit API Setup:

Create a Reddit application here to get your client_id and client_secret.
Update the praw.Reddit instance in the script with your Reddit client_id, client_secret, username, and password.
Groq API Setup:

Sign up for Groq API and obtain your API key.
Replace "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" in the Groq client initialization with your actual Groq API key.

Logging
Logs are written to the console and include information on each post made and any errors encountered.

Maintenance
Regularly check the logs for any errors or issues.
Update the dependencies and test the bot after making any changes to the code or environment.


