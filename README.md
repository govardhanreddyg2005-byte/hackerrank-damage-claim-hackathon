# Damage Claim Processing Pipeline

This project was built as part of the 24-hour HackerRank AI Hackathon.

## What it does
- Reads claim data from CSV files
- Extracts issue type and object part from user claim text using keyword matching
- Generates the required output.csv format

- ## Problem:
- Build a system that verifies damage claims using images, a short claim conversation, user history, and minimum evidence requirements.

## Action: 
- Programmed a Python parsing engine utilizing Python's native csv and string manipulation tools to clean user data, parse multiple dynamic image path arrays, and - run keyword-matching NLP algorithms to extract specific object parts and issues (e.g., detecting a "scratch" on a "car bumper").

## Result: 
Built a functional end-to-end framework that takes real-time user inputs, and outputs standardized audit logs (output.csv) capturing initial risk factors and claim justifications.

## Tech used
- Python
- CSV processing
- Rule-based text extraction

## How to run
- Clone the repository ```git clone https://github.com/govardhanreddyg2005-byte/hackerrank-damage-claim-hackathon.git```
- Create and Place your input CSV files in the `dataset/output.csv ` directory
- Run the `main.py` script
