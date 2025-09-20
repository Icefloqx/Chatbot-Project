## CREATING A CHATBOT


## **Project Overview**
 
-This project is about generating a chatbot via RAG process toand the chatbot should be able to answer questions from the pdf provided.
-The project involves;

- Installing the required modules at your terminal/powershell/gitbash/cmd.
- Creating an environment where you'll store your API key.
- Loading the data which our case was the pdf.
- Splitting the pdf into small chunks.
- Generating embeddings such as the huggingface but there are others.
- Comming up with a  vectordatabase(e.g. Chroma)
- Add a retrieval process.
- Calling in the LLM process in this case I used llama model.
- Prompting the chatbot on how it'll answer questions when asked.
- Used the chaining process using a function.
- Interacting with a bot by asking it questions. 


## **Dataset**

The dataset consists of all laws that Govern Kenya as a country.
Basically, the Constitution Of Kenya of the Year 2010.
 

**Something to note**

- The dataset only answers questions within Kenya. Not everything about Kenya but almost everything about Kenya.

## **Models Used**

The following are some of the models  that were used:

- **Embeddings models such as the Groq**  
- **Large Language Models e.g llama**
- **Vector database such as the chroma**  
- **Textsplitters**  

**Observations:**

- The chatbot answered questions promptly.  
- The chatbot could not answer questions that were not from the knowledge it was fed.

## **Evaluation Metrics**

Libraries used to evaluate models:

- **PyPDF2** – Extracting text from a pdf. 
- **Python dotenv** – for managing environment.
- **LangChain** – popular and used to call in LLM so as to chain models together.

**Technologies used**

-Python(LangChain,os,PyPDFLoader)

-Jupyter Notebook.

-Groq-to get the API Keys and also call in our LLM.

-Git Bash & Github.

