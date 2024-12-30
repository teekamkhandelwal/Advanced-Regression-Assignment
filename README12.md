## Overview
This project provides a solution for parsing, indexing, and querying information from an HDFC Policy PDF document using LlamaIndex. The system allows for efficient retrieval of policy details based on user queries.

## Project Goals
- Parse the HDFC Policy PDF to extract relevant information.
- Index the extracted data for efficient querying.
- Handle user queries and provide relevant information from the policy document.

## Prerequisites to Run the Semantic Spotter

1. **Install Required Libraries and Dependencies**:  
   Run all the cells that install the necessary libraries and code dependencies.

## Steps to Run the Semantic Spotter

1. **Mount Google Drive**:  
   Mount Google Drive and change the path to where the files are stored. Execute the next block to read all the PDF files.

2. **Set API Keys**:  
   Read the `OPENAI_API_KEY`.

3. **Create Nodes**:  
   Create nodes from the read documents and store them in a vector index.

4. **Query the Index**:  
   - Create templates and pass those templates to the index as a query engine.
   - Start querying the indexed data.

5. **Extract Query Response Details**:  
   Extract source node, filename, page number, and text from the response provided by the query engine.

6. **Loop Through Multiple Questions**:  
   Create a function to loop through multiple questions and process them.

8. **Collect User Feedback**:  
   Ask the user to provide feedback on their experience and satisfaction with the answer for future improvements.
   
## Technologies Used

- Python 3.9+
- LlamaIndex
- OpenAI
- pandas

## Credits

Ayushi Pitchika, ACP Gen AI C10, UpGrad
