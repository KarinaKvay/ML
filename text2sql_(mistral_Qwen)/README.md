text2sql\n
There is data provided by the company in the "db" folder.
The program generates SQL code to obtain the necessary data from the database.
The SQLite database is used, the text is vectorized using the "Qwen/Qwen2-1.5B-Instruct" model.
The SQL code is generated using the Mistarl model.
The Qwen model produces an answer using the received SQL code.

*To use the code for your own purposes, you must add YOUR API KEY and YOUR HUGGINGFACE TOKEN.

*In the code, tokenizer is not passed to the generate_answer function. In order for the model to generate not only SQL code, but also data using SQL, this part of the code should be corrected.
