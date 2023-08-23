# News Article Summarizer

This Python script fetches and summarizes news articles based on a given query. It uses the GNews API to fetch articles and OpenAI's GPT-3 model to generate summaries.

## Dependencies

- Python 3.6+
- `requests`
- `newspaper3k`
- `python-dotenv`
- `openai`

## Environment Variables

The script requires the following environment variables:

- `OPENAI_API_KEY`: Your OpenAI API key.
- `GNEWS_API_KEY`: Your GNews API key.

You can set these in a `.env` file at the root of your project:

