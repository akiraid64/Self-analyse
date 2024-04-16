# [Welcome Athena](https://github.com/markdown-it/markdown-it-container)
## To get started, follow these steps

## 1. Granting Access to Team Leader

- The team leader will be granted access to the repository to manage collaboration.

## 2. Forking the Repository

- **Team Leader** needs to __[Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)__ the repository to your own GitHub account. This step is crucial for adding collaborators.

## 3. Adding Collaborators

- **Team Leader** needs to add collaborators to their forked repository. Collaborators can then contribute to the project.

## 4. Making Changes

- Collaborators can start making changes to the repository as needed.

## 5. Syncing Changes

- To ensure that updates are synced properly:
  - Navigate to the "Code" tab in your forked repository.
  - Click on the "Sync Fork" button to sync the changes with the original repository.

---

# [Write your Product description here-](https://github.com/markdown-it/markdown-it-container)

# Akira - Your personal Data Analyst

## CSV Visualization and Chatbot
This project provides a Streamlit-based application that allows users to visualize data from CSV files and interact with a chatbot to ask questions about the data.In short your personal Data Analyst.

## Features
**-Data Visualization:** -Users can upload their own CSV files or select from pre-loaded datasets.
The application generates appropriate data visualizations based on the chosen dataset.
Users can choose from multiple models (e.g., Code Llama) to generate the visualizations.

**-Chatbot:** -Users can ask questions about the data and receive answers from the chatbot.
The chatbot uses a ConversationalRetrievalChain from LangChain to provide context-aware responses.
The chatbot is powered by a locally loaded LLM (Language Model), such as LLaMA or Vicuna.
Installation.

## Getting Started:

**Clone the repository:**
```sh
git clone https://github.com/your-username/csv-visualization-chatbot.git
```
**Change to the project directory:**
```sh
cd csv-visualization-chatbot
```
**Install the required dependencies:**
```sh
pip install -r requirements.txt
```


Ensure you have the necessary local model files (e.g., "codellama-34b-instruct.Q2_K.gguf") in the appropriate directory.

**Start the Streamlit application:**
```sh
streamlit run app.py
```
