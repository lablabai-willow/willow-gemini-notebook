# Google Gemini Mindfulness Counselor

Uses a combination of Google Gemini vision model and GPT-4 Turbo with LlamaIndex to perform sentiment analysis of images and suggest mindfulness exercises.

## Get API keys
Before you can use the Gemini API, you must first obtain an API key. If you don't already have one, create a key with one click in Google AI Studio. You'll also need an OpenAI API key.

Once you have your API keys create the following Google Colab "secrets" GOOGLE_API_KEY and OPENAI_API_KEY which will contain your respective keys.

## Generating Embeddings

Embeddings are generated from the PDFs in the data folder and stored in the storage folder.
