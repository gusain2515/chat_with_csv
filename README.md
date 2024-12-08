## Conversational Data Analysis with LangChain
This project leverages LangChain to perform conversational retrieval and simple data analysis tasks, including histograms, scatter plots, and line plots, using a CSV dataset. It integrates advanced conversational capabilities with HuggingFace embeddings and FAISS for efficient retrieval.
# Features
Conversational Data Retrieval: Ask questions about the data in natural language.
Visualization Options:
Histograms
Scatter Plots
Line Plots
Embedding Storage: Store and load embeddings with FAISS for efficient data queries.

# Usage Instructions
Start the script.
Interact with the system:
Input a natural language query (e.g., "What is the GDP per capita of Finland?")
Use the following commands for visualizations:
h: Create a histogram for a specified column.
s: Create a scatter plot for two specified columns.
l: Create a line plot for a specified column.
Exit the script: Type exit.
Example Interaction
Natural Language Query
plaintext
Copy code
Input Prompt: What is the GDP per capita of Finland?
Response: The GDP per capita of Finland is 47,433 USD.
