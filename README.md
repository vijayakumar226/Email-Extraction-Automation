# Project 2: Email Extraction Automation (Gmail → Google Sheets)

## Overview
This project automates the extraction of key information from incoming Gmail messages and organizes it into Google Sheets. It is designed to streamline manual data entry, specifically useful for scenarios like healthcare staffing or application tracking.

## Tech Stack
- **Automation Tool:** n8n
- **AI Model:** GPT-4o-mini (for intelligent data parsing)
- **APIs:** Gmail API, Google Sheets API

## How it Works
1. **Trigger:** The workflow monitors Gmail for specific new emails.
2. **AI Processing:** The AI Agent (GPT-4o-mini) reads the email content and extracts data in a structured JSON format.
3. **Storage:** The extracted data is automatically appended to a designated Google Sheet.

## How to Use
1. Import the `workflow.json` file into your n8n instance.
2. Set up your Credentials for Gmail and Google Sheets.
3. Replace the Sheet ID with your own.

## Project Demo
You can watch the full video demonstration of the workflow here: [View Demo on Google Drive](https://drive.google.com/file/d/17-SOwBvg3FGOXwlCEHbaZu-rj4B0BzYY/view?usp=sharing)
