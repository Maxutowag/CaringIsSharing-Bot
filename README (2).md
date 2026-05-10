# Skincare Bot by Caring is Sharing

A Telegram bot that asks 11 questions about your skin and generates a personalized skincare routine.

## Features
- 11-step inline survey
- Personalized morning and evening routines
- Products across 3 budget tiers (Budget / Mid-range / Premium)
- Prices in KZT for every product + total cost
- Save and retrieve routine with /myroutine
- Ingredient encyclopedia with /ingredient
- SOS emergency skin help with /sos
- WhatsApp order button at the end of survey

## Project Structure
- main.py — Bot entry point, all handlers
- survey.py — Survey questions and inline keyboards
- recommender.py — Routine building logic and products
- database.py — JSON-based data persistence
- README.md — This file

## How to Run
1. Open Google Colab: colab.research.google.com
2. Install dependencies: pip install python-telegram-bot==20.7 nest_asyncio
3. Add your bot token in main.py
4. Run: python main.py

## Commands
- /start — Take the 11-step skin survey
- /myroutine — View your saved routine
- /ingredient — Learn about skincare ingredients
- /sos — Emergency skin help

## Budget Tiers
- Budget: 7,000 - 9,000 KZT per product
- Mid-range: 15,000 - 20,000 KZT per product
- Premium: 60,000 - 120,000 KZT per product

## Team
Caring is Sharing

**Demegen Amina** 
- Edited the video presentation
- Responsible for presentation slides: "Existing Problems" and "Target Audience"
- Provided and fact-checked background information
- ...
- ...


**Maxutova Gulden — main.py, recommender.py, README.md, Google colab**
- Built the main bot entry point and all command handlers
- Implemented /start, /myroutine, /ingredient, /sos commands
- Created ingredient encyclopedia with inline buttons
- Added SOS emergency skin help feature
- Integrated WhatsApp order button at end of survey
- Built the product recommendation engine
- Created product database for 3 budget tiers (Budget, Mid-range, Premium)
- Implemented morning and evening routine builder
- Added KZT pricing and total cost calculation
- Wrote full project documentation in README.md
- Maintained the Google Colab notebook
- Presentation slides: 'How it works?' part
  
**Rakhman Aidana — survey.py, database.py**
- Designed all 11 survey questions and answer options
- Built inline keyboard buttons for each question
- Implemented multi-select functionality for vitamins question
- Implemented JSON-based data storage system
- Built save, retrieve and delete functions for user routines
- Handled file reading and writing with error protection
- Added climate and sun exposure questions for SPF recommendations
- Designed budget tier options (Budget, Mid-range, Premium)
- Implemented allergy filtering to exclude unsafe ingredients
- Ensured data persistence across bot sessions using JSON file
  
| Talap Akbota |
