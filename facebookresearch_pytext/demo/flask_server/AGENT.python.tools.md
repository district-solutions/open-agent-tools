# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/demo/flask_server/atis.py

Prompts

```
['run the ATIS model to predict city names from a text string and return token ranges', 'run the tokenize function to split text into lowercase tokens with character offset ranges', 'review the predict function that runs the Caffe2 ATIS model and extracts city name token ranges', 'review the tokenize function that splits text by whitespace and returns tokens with ranges', 'summarize the loaded Caffe2 ATIS joint prediction network used for city name entity recognition', 'run the flask server on host 0.0.0.0 port 3000 for ATIS intent prediction', 'predict the intent of input text via the ATIS model using the predict endpoint', 'create a flask route that accepts text query params and returns ATIS predictions as JSON', 'refactor the flask server to run on a configurable host and port']
```

Usage

```
{'run_predict_city_names': 'run the ATIS model to predict city names from a text string and return token ranges', 'run_tokenize_text': 'run the tokenize function to split text into lowercase tokens with character offset ranges', 'review_predict_function': 'review the predict function that runs the Caffe2 ATIS model and extracts city name token ranges', 'review_tokenize_function': 'review the tokenize function that splits text by whitespace and returns tokens with ranges', 'summarize_predict_net': 'summarize the loaded Caffe2 ATIS joint prediction network used for city name entity recognition'}
```

## File: facebookresearch_pytext/demo/flask_server/server.py

Prompts

```
['run the ATIS model to predict city names from a text string and return token ranges', 'run the tokenize function to split text into lowercase tokens with character offset ranges', 'review the predict function that runs the Caffe2 ATIS model and extracts city name token ranges', 'review the tokenize function that splits text by whitespace and returns tokens with ranges', 'summarize the loaded Caffe2 ATIS joint prediction network used for city name entity recognition', 'run the flask server on host 0.0.0.0 port 3000 for ATIS intent prediction', 'predict the intent of input text via the ATIS model using the predict endpoint', 'create a flask route that accepts text query params and returns ATIS predictions as JSON', 'refactor the flask server to run on a configurable host and port']
```

Usage

```
{'run_flask_server': 'run the flask server on host 0.0.0.0 port 3000 for ATIS intent prediction', 'predict_intent': 'predict the intent of input text via the ATIS model using the predict endpoint', 'create_flask_route': 'create a flask route that accepts text query params and returns ATIS predictions as JSON', 'review_predict_function': 'review the predict function that calls atis.predict on request query parameters', 'refactor_server_port': 'refactor the flask server to run on a configurable host and port'}
```

