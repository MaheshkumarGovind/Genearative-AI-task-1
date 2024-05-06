# Webpage Question Answering API

This API takes a webpage URL and a question as input and responds with the answer to the question.

## Usage

1. Install the dependencies by running `pip install -r requirements.txt`
2. Run the API by running `python main.py`
3. Send a POST request to `http://localhost:5000/answer` with the following JSON payload:
```json
{
    "url": "https://en.wikipedia.org/wiki/Generative_artificial_intelligence",
    "question": "What are the concerns around Generative AI?"
}
