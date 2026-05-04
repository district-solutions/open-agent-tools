# Agent Python Tools

- repo: open-webui/openapi-servers
- repo_uri: https://github.com/open-webui/openapi-servers

## File: open-webui_openapi-servers/servers/summarizer-tool/summarizers/base.py

Prompts

```
['create a subclass of BaseSummarizer that implements the abstract summarize method to return a summary dict', 'review the BaseSummarizer abstract base class and its summarize method signature', 'summarize a block of text by sending it to an LLM endpoint via the TextSummarizer class', 'create a TextSummarizer instance that extends BaseSummarizer and calls an Ollama-style generate API', 'review the SUMMARIZE_PROMPT system prompt used to instruct the LLM to sanitize and summarize text', 'refactor the TextSummarizer summarize method to support streaming responses or different LLM providers', 'test the TextSummarizer summarize method error handling when the LLM endpoint returns a non-200 status code']
```

Usage

```
{'implement_basesummarizer': 'create a subclass of BaseSummarizer that implements the abstract summarize method to return a summary dict', 'review_basesummarizer': 'review the BaseSummarizer abstract base class and its summarize method signature'}
```

## File: open-webui_openapi-servers/servers/summarizer-tool/summarizers/text_summarizer.py

Prompts

```
['create a subclass of BaseSummarizer that implements the abstract summarize method to return a summary dict', 'review the BaseSummarizer abstract base class and its summarize method signature', 'summarize a block of text by sending it to an LLM endpoint via the TextSummarizer class', 'create a TextSummarizer instance that extends BaseSummarizer and calls an Ollama-style generate API', 'review the SUMMARIZE_PROMPT system prompt used to instruct the LLM to sanitize and summarize text', 'refactor the TextSummarizer summarize method to support streaming responses or different LLM providers', 'test the TextSummarizer summarize method error handling when the LLM endpoint returns a non-200 status code']
```

Usage

```
{'summarize_text_with_llm': 'summarize a block of text by sending it to an LLM endpoint via the TextSummarizer class', 'create_text_summarizer_instance': 'create a TextSummarizer instance that extends BaseSummarizer and calls an Ollama-style generate API', 'review_summarize_prompt': 'review the SUMMARIZE_PROMPT system prompt used to instruct the LLM to sanitize and summarize text', 'refactor_summarize_method': 'refactor the TextSummarizer summarize method to support streaming responses or different LLM providers', 'test_summarize_error_handling': 'test the TextSummarizer summarize method error handling when the LLM endpoint returns a non-200 status code'}
```

