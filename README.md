# RAG-Question-Answer-Model
Traditional language models generate responses based on patterns and information they have learned during their training phase. However, these models are constrained by the data they were exposed to, which can result in responses that lack specificity or comprehensive knowledge. RAG (Retrieval-Augmented Generation) overcomes this limitation by incorporating external data during the response generation process. When a query is presented, the RAG system retrieves pertinent information from an extensive dataset or knowledge base. This retrieved information is then utilized to enhance and refine the response generation, ensuring more accurate and informed answers.

![image](https://github.com/user-attachments/assets/944bed34-3651-4770-91e2-b701b24ece0c)

# Steps and end-to-end pipeline of RAG
![image](https://github.com/user-attachments/assets/7ae3db97-08d1-4f87-9ca9-dba024a846b4)
Step 1: User Enters a prompt/query
Step 2: The retriever searches and fetches information relevant to the prompt (e.g., from the internet or internet data warehouse).
Step 3: Retrieved relevant information is augmented to the prompt as context.
Step 4: LLM is asked to generate a response to the prompt in the context (augmented information).
Step 5: User response generation.

# What is a source in RAG?
![image](https://github.com/user-attachments/assets/1af53772-01ef-447b-a29c-c838851e243e)

In Retrieval-Augmented Generation (RAG), the source refers to the external repository of information that the model retrieves from to enhance its language generation capabilities. These sources can include:
1. Databases: Structured repositories of information, such as SQL databases or knowledge graphs.
Example: A product catalog or customer information database.

2. APIs: Dynamic sources of real-time data, such as weather APIs, financial data APIs, or search engines.
Example: A live API providing the latest stock market prices.

3. Web Pages: Information is scraped or fetched from the web, often via tools like web crawlers or search engines.
Example: Retrieving data from Wikipedia or news websites.

4. Document Repositories: Collections of documents like PDFs, Word files, or text files stored in a local or cloud-based repository.
Example: Internal company policies or scientific papers.

5. Dense Vector Index: A pre-processed index of textual data (e.g., Wikipedia) is created using dense embeddings from models like BERT or DPR.
Example: A vectorized knowledge base for efficient retrieval.

6. Knowledge Bases: Domain-specific structured or semi-structured knowledge bases like Wikidata or proprietary business knowledge systems.
Example: Industry-specific regulatory documents.

7. Enterprise Content Management Systems: Organizational repositories of structured and unstructured data.
Example: SharePoint or Atlassian Confluence.

# Referense
1. https://anurag25.hashnode.dev/retrieval-augmented-generation-the-magic-behind-intelligent-chatbots
2. https://anurag25.hashnode.dev/retrieval-augmented-generation-vs-fine-tuning
3. https://anurag25.hashnode.dev/understanding-openai-model-pricing-a-comprehensive-guide
