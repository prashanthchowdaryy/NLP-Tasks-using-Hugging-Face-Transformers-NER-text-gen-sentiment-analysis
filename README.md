NLP Tasks using Hugging Face Transformers

This project demonstrates multiple Natural Language Processing (NLP) tasks using the Hugging Face Transformers library.
The notebook explores how pre-trained transformer models can perform powerful language tasks with just a few lines of Python.

The project covers:

Text Generation

Named Entity Recognition (NER)

Sentiment Analysis

Simple Interface using Gradio

 Features

✔️ Text Generation
Generate human-like text using pre-trained transformer models.

✔️ Named Entity Recognition (NER)
Identify entities such as:

Person names

Locations

Organizations

Dates

✔️ Sentiment Analysis
Analyze text and determine whether the sentiment is:

Positive

Negative

✔️ Gradio Interface
Create a simple interactive UI to test NLP models directly from the browser.

🛠️ Technologies Used

Python

Hugging Face Transformers

PyTorch

Gradio

Jupyter Notebook

📂 Project Structure
text_gen NER sentiment_analysis.ipynb
README.md
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

Install required libraries:

pip install transformers
pip install torch
pip install gradio
▶️ Running the Project

Open the notebook:

jupyter notebook

Run all the cells to:

Load pre-trained transformer models

Perform NLP tasks

Launch the Gradio interface

🧠 Example Tasks
Text Generation

Generate meaningful sentences using transformer models.

Named Entity Recognition

Input:

Elon Musk founded SpaceX in the United States.

Output:

Elon Musk → PERSON  
SpaceX → ORGANIZATION  
United States → LOCATION
Sentiment Analysis

Input:

I love learning AI and Machine Learning!

Output:

Positive Sentiment
📊 Use Cases

NLP learning projects

AI demos

Chatbot building blocks

Text analytics

Educational demonstrations

🔮 Future Improvements

Add more NLP tasks like:

Text summarization

Question answering

Deploy as a web app

Add a Streamlit interface

Integrate with a chatbot system

👨‍💻 Author

Prashanth Chowdary
