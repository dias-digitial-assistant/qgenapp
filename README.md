# Question Generation and Answer Analysis App

## Project Description

This project contains a jupyter notebook file which interacts with the TogetherAI's language models to generate a list of questions based on a given prompt and paragraph. It may be used to test comprehension skills, generate quiz questions from a given text, and much more.

The script also enables users to evaluate an answer given to a question in terms of the 'contradiction', 'neutrality', and 'entailment' probabilities using OpenAI's GPT-4. Following this, it generates suggestions for answer improvement and the reasoning behind its grading assessment.

## Usage

To use this script:

1. You need to have Python installed.
2. Install the necessary packages listed in the file. You can do it using pip (Pip Installs Packages), which comes installed with Python. For example, to install 'dotenv', use:
```
pip install python-dotenv
```
3. Replace 'TOGETHER_AI_BEARER_TOKEN' and 'OPENAI_API_KEY' with your own keys in the .env file.
4. Run the Jupyter Notebook
```

```
## Libraries Used

* os
* openai
* dotenv
* requests
* json
* collections

## Features

1. Custom prompts: Specify the prompt as per your preference to guide the generation of questions. 
2. Answer evaluation: Allows the grading of an answer along parameters 'contradiction', 'neutrality', and 'entailment'.
3. Useful for exam and quiz creation: Can be used to create questions for a test or quiz from a given passage or text.
4. JSON output: Provides easy-to-parse JSON output with the relevant information.

## API Reference

The python script uses TogetherAI's API and OpenAI's API, which requires an API token. This can be obtained from TogetherAI's website and OpenAI's website respectively.

For more information on making calls and specifications for parameters, please visit their official API documentation.
