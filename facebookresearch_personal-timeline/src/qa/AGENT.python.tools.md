# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/qa/chatgpt_engine.py

Prompts

```
['build a ChatGPTEngine instance with OpenAI LLM and conversation memory', 'query the ChatGPTEngine with a message and get an AI response', 'create a ConversationChain with ChatPromptTemplate and ConversationBufferMemory', 'refactor the ChatGPTEngine system prompt to customize AI conversation behavior', 'review the ChatGPTEngine ConversationBufferMemory to manage chat history across queries', 'build a QAEngine instance from a data path containing episodes.csv to enable RAG-based question answering', 'run a retrieval-based query against the QAEngine to answer questions using FAISS vector search and LLM', 'run a view-based query against the QAEngine using the optional ViewEngine for structured data lookups', 'create verbalized text from an episodes DataFrame by converting dates and descriptions into natural language', 'review the QAEngine initialization that loads episodes, builds FAISS embeddings, and sets up the LangChain QA chain', 'run the flask server on port 8085 with debug mode enabled', 'launch the QA engine and ChatGPT engine by calling the /launch endpoint', 'query the QA engine with a question and method via the /query endpoint', 'test the server by sending GET requests to the /test endpoint', 'configure cross-origin resource sharing on the flask app using flask_cors', 'run a ViewEngine query to answer a natural language question using the View-based QA method', 'run the ViewEngine verbalize method to summarize a query and answer into a single sentence', 'run the ViewEngine flatten method to recursively flatten a nested list of tuples', 'review the ViewEngine class that wraps PostText and OpenAI LLM for personal timeline QA', 'review the ViewEngine constructor that loads config.ini and initializes PostText and OpenAI']
```

Usage

```
{'build_chatgpt_engine': 'build a ChatGPTEngine instance with OpenAI LLM and conversation memory', 'query_chatgpt_engine': 'query the ChatGPTEngine with a message and get an AI response', 'create_conversation_chain': 'create a ConversationChain with ChatPromptTemplate and ConversationBufferMemory', 'refactor_chatgpt_prompt': 'refactor the ChatGPTEngine system prompt to customize AI conversation behavior', 'review_chatgpt_memory': 'review the ChatGPTEngine ConversationBufferMemory to manage chat history across queries'}
```

## File: facebookresearch_personal-timeline/src/qa/qa_engine.py

Prompts

```
['build a ChatGPTEngine instance with OpenAI LLM and conversation memory', 'query the ChatGPTEngine with a message and get an AI response', 'create a ConversationChain with ChatPromptTemplate and ConversationBufferMemory', 'refactor the ChatGPTEngine system prompt to customize AI conversation behavior', 'review the ChatGPTEngine ConversationBufferMemory to manage chat history across queries', 'build a QAEngine instance from a data path containing episodes.csv to enable RAG-based question answering', 'run a retrieval-based query against the QAEngine to answer questions using FAISS vector search and LLM', 'run a view-based query against the QAEngine using the optional ViewEngine for structured data lookups', 'create verbalized text from an episodes DataFrame by converting dates and descriptions into natural language', 'review the QAEngine initialization that loads episodes, builds FAISS embeddings, and sets up the LangChain QA chain', 'run the flask server on port 8085 with debug mode enabled', 'launch the QA engine and ChatGPT engine by calling the /launch endpoint', 'query the QA engine with a question and method via the /query endpoint', 'test the server by sending GET requests to the /test endpoint', 'configure cross-origin resource sharing on the flask app using flask_cors', 'run a ViewEngine query to answer a natural language question using the View-based QA method', 'run the ViewEngine verbalize method to summarize a query and answer into a single sentence', 'run the ViewEngine flatten method to recursively flatten a nested list of tuples', 'review the ViewEngine class that wraps PostText and OpenAI LLM for personal timeline QA', 'review the ViewEngine constructor that loads config.ini and initializes PostText and OpenAI']
```

Usage

```
{'build_QAEngine': 'build a QAEngine instance from a data path containing episodes.csv to enable RAG-based question answering', 'run_query_retrieval': 'run a retrieval-based query against the QAEngine to answer questions using FAISS vector search and LLM', 'run_query_view': 'run a view-based query against the QAEngine using the optional ViewEngine for structured data lookups', 'create_verbalize': 'create verbalized text from an episodes DataFrame by converting dates and descriptions into natural language', 'review_QAEngine_init': 'review the QAEngine initialization that loads episodes, builds FAISS embeddings, and sets up the LangChain QA chain'}
```

## File: facebookresearch_personal-timeline/src/qa/server.py

Prompts

```
['build a ChatGPTEngine instance with OpenAI LLM and conversation memory', 'query the ChatGPTEngine with a message and get an AI response', 'create a ConversationChain with ChatPromptTemplate and ConversationBufferMemory', 'refactor the ChatGPTEngine system prompt to customize AI conversation behavior', 'review the ChatGPTEngine ConversationBufferMemory to manage chat history across queries', 'build a QAEngine instance from a data path containing episodes.csv to enable RAG-based question answering', 'run a retrieval-based query against the QAEngine to answer questions using FAISS vector search and LLM', 'run a view-based query against the QAEngine using the optional ViewEngine for structured data lookups', 'create verbalized text from an episodes DataFrame by converting dates and descriptions into natural language', 'review the QAEngine initialization that loads episodes, builds FAISS embeddings, and sets up the LangChain QA chain', 'run the flask server on port 8085 with debug mode enabled', 'launch the QA engine and ChatGPT engine by calling the /launch endpoint', 'query the QA engine with a question and method via the /query endpoint', 'test the server by sending GET requests to the /test endpoint', 'configure cross-origin resource sharing on the flask app using flask_cors', 'run a ViewEngine query to answer a natural language question using the View-based QA method', 'run the ViewEngine verbalize method to summarize a query and answer into a single sentence', 'run the ViewEngine flatten method to recursively flatten a nested list of tuples', 'review the ViewEngine class that wraps PostText and OpenAI LLM for personal timeline QA', 'review the ViewEngine constructor that loads config.ini and initializes PostText and OpenAI']
```

Usage

```
{'run_flask_server': 'run the flask server on port 8085 with debug mode enabled', 'launch_qa_engines': 'launch the QA engine and ChatGPT engine by calling the /launch endpoint', 'query_qa_engine': 'query the QA engine with a question and method via the /query endpoint', 'test_server_endpoint': 'test the server by sending GET requests to the /test endpoint', 'configure_cors': 'configure cross-origin resource sharing on the flask app using flask_cors'}
```

## File: facebookresearch_personal-timeline/src/qa/view_engine.py

Prompts

```
['build a ChatGPTEngine instance with OpenAI LLM and conversation memory', 'query the ChatGPTEngine with a message and get an AI response', 'create a ConversationChain with ChatPromptTemplate and ConversationBufferMemory', 'refactor the ChatGPTEngine system prompt to customize AI conversation behavior', 'review the ChatGPTEngine ConversationBufferMemory to manage chat history across queries', 'build a QAEngine instance from a data path containing episodes.csv to enable RAG-based question answering', 'run a retrieval-based query against the QAEngine to answer questions using FAISS vector search and LLM', 'run a view-based query against the QAEngine using the optional ViewEngine for structured data lookups', 'create verbalized text from an episodes DataFrame by converting dates and descriptions into natural language', 'review the QAEngine initialization that loads episodes, builds FAISS embeddings, and sets up the LangChain QA chain', 'run the flask server on port 8085 with debug mode enabled', 'launch the QA engine and ChatGPT engine by calling the /launch endpoint', 'query the QA engine with a question and method via the /query endpoint', 'test the server by sending GET requests to the /test endpoint', 'configure cross-origin resource sharing on the flask app using flask_cors', 'run a ViewEngine query to answer a natural language question using the View-based QA method', 'run the ViewEngine verbalize method to summarize a query and answer into a single sentence', 'run the ViewEngine flatten method to recursively flatten a nested list of tuples', 'review the ViewEngine class that wraps PostText and OpenAI LLM for personal timeline QA', 'review the ViewEngine constructor that loads config.ini and initializes PostText and OpenAI']
```

Usage

```
{'run_ViewEngine_query': 'run a ViewEngine query to answer a natural language question using the View-based QA method', 'run_ViewEngine_verbalize': 'run the ViewEngine verbalize method to summarize a query and answer into a single sentence', 'run_ViewEngine_flatten': 'run the ViewEngine flatten method to recursively flatten a nested list of tuples', 'review_ViewEngine_class': 'review the ViewEngine class that wraps PostText and OpenAI LLM for personal timeline QA', 'review_ViewEngine_init': 'review the ViewEngine constructor that loads config.ini and initializes PostText and OpenAI'}
```

