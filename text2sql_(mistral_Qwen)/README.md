There is data provided by the company in the "db" folder.<br>

text2SQL:<br>
The program generates SQL code to obtain the necessary data from the database.<br>
The SQLite database is used, the text is vectorized using the "Qwen/Qwen2-1.5B-Instruct" model.<br>
The SQL code is generated using the Mistarl model.<br>
The Qwen model produces an answer using the received SQL code.<br>

RAG:<br>
The program generates a response based on data received from the company's vectorized database.<br>
The Neon database is used, the text is vectorized using the MistralAIEmbeddings.<br>
The Qwen model produces an answer using the received SQL code.<br>

*To use the code for your own purposes, you must add YOUR API KEY and YOUR HUGGINGFACE TOKEN.<br>
*In the code, tokenizer is not passed to the generate_answer() function. In order for the model to generate not only SQL code, but also data using SQL, this part of the code should be corrected.
