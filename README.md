# 🦅 Eagles Daily Challenge — FREE Edition

This version costs **$0** to run: no OpenAI API, no server, no database.

## Setup
1. Replace your current repository files with these files.
2. Commit them to `main`.
3. Go to **Settings → Pages** and select **GitHub Actions**.
4. The `Deploy Eagles Daily` workflow will deploy the site.

You can delete the old `OPENAI_API_KEY` secret because this version does not use it.

## Daily questions
The app contains an Eagles trivia bank in `data/questions.json`. The current date automatically selects one question, so everyone gets the same daily challenge without a server or paid API.

## Important
This is designed for a friends-and-family game. Because it is a static site, the question bank can be inspected by someone who knows how to use browser developer tools.
