Vanna is a python package that uses retrieval augmentation to help you generate accurate SQL queries for your database using LLMs.

<center><img src="https://vanna.ai/docs/img/how-vanna-works.gif" width="500" height="350"></center>

Why Vanna?:<br>
1)Limited SQL proficiency among stakeholders which allows only technical query language to generate insights<br>
2)Manual process is painful which has long wait time periods and follow-ups hinder the decisions<br>
3)Data analysts are overloaded with requsts which slows their core work<br>
4)AI unlocks the power for immediate access of information<br>

It relies on 2 components:<br>
1)Retrieval: It searches for relevant information from database based on question using vn.train(...)<br>
2)Generation: It uses a large language model (LLM) to translate the retrieved information into a well-formed SQL query using vn.ask(...)

It can be integrated with various databases with frontends and can learn from itself.
It is open-souce which can be used for various applications like analyzing sales and revenue data, enahancig customer satisfaction in enterprises.
