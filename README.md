# Lockout-Bot

The lockout bot is a discord bot that basically automates the process of conducting a 1v1 competitive programming tournament. The bot functions by hosting tournaments, registering people, scheduling matches, and fetching problems based on the difficulty level specified by two of the most popular CP websites, Codeforces and Atcoder. The bot can also differentiate between the tournament hosts and participants so that no participant can control the bot. After a match, the bot updates the standings and tournament brackets on its own and the process continues until a final lockout champion remains!

During a match, both players are given 5 questions of varying difficulties and points that haven't previously been solved by both of the users. The first person to solve a question right gets the point for that question. The bot can automatically track the submission status of each question and updates the standings. The person to get the most points qualifies for the next round.

# Tech - stack used : 

Python - Basis of the code

Discord.py - Integrating the bot with discord

MongoDB - To store the data of the participants in the tournament

Beautiful Soup - To parse the web scrapped data to fetch problems from Atcoder

Codeforces API - To fetch problems from Codeforces
