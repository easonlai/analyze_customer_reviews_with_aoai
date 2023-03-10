# Analyze Customer Reviews with Azure OpenAI Service (AOAI)

This demo repository demonstrates how to analyze customer reviews with [Azure OpenAI Service (AOAI)](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/overview). I leveraged ["ASOS Customer Review"](https://www.kaggle.com/datasets/mahirahmzh/asos-customer-review-in-trustpilot) from [Kaggle](https://www.kaggle.com/) to obtain valuable insight from the customer review content, such as Sentiment, Summarize the review content in one sentence, Summarize as keywords, Generate the response message, and Summarize multiple review content with [AOAI GPT-3 model](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/models#gpt-3-models).

Content:
* [data/asos_transform.csv](https://github.com/easonlai/analyze_customer_reviews_with_aoai/blob/main/data/asos_transform.csv) <-- Customer Review dataset of ASOS. It contains 2,000 records.
* [data/analyzed_review_content.csv](https://github.com/easonlai/analyze_customer_reviews_with_aoai/blob/main/data/analyzed_review_content.csv) <-- Dataframe export of insight from customer review content with AOAI.
* [analyze_customer_reviews_with_aoai.ipynb](https://github.com/easonlai/analyze_customer_reviews_with_aoai/blob/main/analyze_customer_reviews_with_aoai.ipynb) <-- Notebook to perform insight extraction from customer review content with AOAI.

![alt text](https://github.com/easonlai/analyze_customer_reviews_with_aoai/blob/main/git-images/git-image-1.png)

Enjoy!