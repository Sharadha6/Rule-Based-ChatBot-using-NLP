# Rule-Based-ChatBot-using-NLP
A Rule-Based ChatBot made using Natural Language Processing techniques.
## Overview
In this project, we explore the advantages of a rule-based chatbot. While most chatbots these days utilise Artificial Intelligence, there are many cases where we just want simple information retrieval from a source. Using NLP is a great alternative to AI when the use case is simple. It requires less computing and costs a lot less as well.

The project uses an example application of having a chatbot to answer FAQs regarding the deposit agreement of Chase Bank. This information was found on the bank's website.

## Project Structure
### Slides
- Rule-Based ChatBot.pptx: Slides that explain the project
### Data
- deposit-account-agreement.pdf: Input data file used in both python notebooks. Contains the deposit agreement of Chase Bank.
- paragraphs.csv: Cleaned and Processed data file created in Text Analytics.ipynb and accessed in Chatbot_functions.ipynb
- Highlighted_deposit-account-agreement.pdf: Output file created when you run the chatbot and ask a question. This specific output file used the test question "What is a substitute check?" on the chatbot.
- Questions - text file containing a few sample questions you can ask the chatbot to get you started.
### Notebooks
- Text Analytics.ipynb: Notebook where data is loaded, cleaned, manipulated and EDA is done. This notebook creates the output csv file paragraphs.csv which we will use for our chatbot.
- Chatbot_functions.ipynb: Notebook where data in the right format (paragraphs.csv) is loaded, all necessary algorithms and functions for chatbot are created, and final chatbot is called using Gradio.
## Correct Order of Execution
1. View "Rule-Based ChatBot.pptx" slides
2. Run Text Analytics.ipynb (make sure data file deposit-account-agreement.pdf is saved in the same folder)
3. Confirm you got the "paragraphs.csv" output file after step 2
4. Run Chatbot_functions.ipynb
5. Use the ChatBot in notebook or open Gradio ChatBot in seperate tab using link displayed upon execution.
