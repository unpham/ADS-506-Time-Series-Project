# **API Instructions**

### Follow these instructions to set up and run the API:

1. Clone the repository to your local machine.

2. Open a command line interface and navigate to the directory of the API folder within the cloned repository.

3. Ensure that all dependencies are installed. The following dependencies are required if not use `pip install fastapi pickle Jinja2 uvicorn`

4. Run the following command to start the local server: `uvicorn main:app --reload`
5. Once the server is running, open your web browser and enter the following URL: http://127.0.0.1:8000
6. You will be directed to the API application interface. To analyze reviews, follow these steps:
     Enter the reviews in the input field provided. The reviews should be in the following format:
     Review 1
     ---
     Review 2
     ---
     Review n
    Ensure that there are at least 10 reviews for accurate analysis.
    Click the "Submit" button to initiate the analysis.
7. The API will process the reviews and provide the following results:
  - Sentiment analysis: Each review will be classified as "good" or "bad" based on sentiment.
  - Important words: The API will display the words that contribute to the sentiment classification.
  - Review themes: The API will provide insights into the underlying themes discovered through topic modeling.
     
