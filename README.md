# AI_Code_Reviewer-advance
 This repository contains an automated code review tool that leverages the OpenAI API for suggesting changes to code based on chat interactions.The tool uses the `tenacity` library for retry logic, `dotenv` for environment variable management, and other Python libraries for handling code modifications and interactions with the OpenAI API.

 ## Features

- Automated code review using OpenAI API
- Retry logic with exponential backoff using `tenacity` library
- Environment variable management with `dotenv`
- For Security reasons .env file is removed from project
- Colorized diff output for code changes using `difflib` for improved readability
