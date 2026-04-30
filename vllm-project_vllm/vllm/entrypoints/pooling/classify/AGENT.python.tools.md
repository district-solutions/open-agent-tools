# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/pooling/classify/api_router.py

Prompts

```
['create a FastAPI endpoint that handles POST requests to /classify for model classification', 'test the create_classify endpoint handles requests with ClassificationRequest and returns a Response', 'review the classify helper function that retrieves ServingClassification from request app state', 'summarize the APIRouter configuration with /classify POST route and JSON validation dependency', 'build a classification handler that delegates to ServingClassification when the model supports it', 'build a ClassificationCompletionRequest to send text for classification via completion API', 'build a ClassificationChatRequest to send chat messages for classification', 'build TokenizeParams from a ClassificationCompletionRequest using a ModelConfig', 'build a ClassificationResponse containing a list of ClassificationData with labels and probabilities', 'build ClassificationData with index, label, probabilities, and number of classes', 'build a ServingClassification instance to serve text classification requests via vLLM pooling endpoint', 'create a ClassifyIOProcessor to handle input and output processing for classification tasks', 'build a ClassificationResponse containing classification results with labels, probabilities, and usage info', 'build a ClassificationData item with index, label, probability scores, and number of classes', 'test the _build_response method of ServingClassification to verify JSONResponse output format']
```

Usage

```
{'create_classify_endpoint': 'create a FastAPI endpoint that handles POST requests to /classify for model classification', 'test_create_classify': 'test the create_classify endpoint handles requests with ClassificationRequest and returns a Response', 'review_classify_helper': 'review the classify helper function that retrieves ServingClassification from request app state', 'summarize_router': 'summarize the APIRouter configuration with /classify POST route and JSON validation dependency', 'build_classify_handler': 'build a classification handler that delegates to ServingClassification when the model supports it'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/classify/protocol.py

Prompts

```
['create a FastAPI endpoint that handles POST requests to /classify for model classification', 'test the create_classify endpoint handles requests with ClassificationRequest and returns a Response', 'review the classify helper function that retrieves ServingClassification from request app state', 'summarize the APIRouter configuration with /classify POST route and JSON validation dependency', 'build a classification handler that delegates to ServingClassification when the model supports it', 'build a ClassificationCompletionRequest to send text for classification via completion API', 'build a ClassificationChatRequest to send chat messages for classification', 'build TokenizeParams from a ClassificationCompletionRequest using a ModelConfig', 'build a ClassificationResponse containing a list of ClassificationData with labels and probabilities', 'build ClassificationData with index, label, probabilities, and number of classes', 'build a ServingClassification instance to serve text classification requests via vLLM pooling endpoint', 'create a ClassifyIOProcessor to handle input and output processing for classification tasks', 'build a ClassificationResponse containing classification results with labels, probabilities, and usage info', 'build a ClassificationData item with index, label, probability scores, and number of classes', 'test the _build_response method of ServingClassification to verify JSONResponse output format']
```

Usage

```
{'build_classification_request': 'build a ClassificationCompletionRequest to send text for classification via completion API', 'build_chat_classification_request': 'build a ClassificationChatRequest to send chat messages for classification', 'build_tok_params': 'build TokenizeParams from a ClassificationCompletionRequest using a ModelConfig', 'build_classification_response': 'build a ClassificationResponse containing a list of ClassificationData with labels and probabilities', 'build_classification_data': 'build ClassificationData with index, label, probabilities, and number of classes'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/classify/serving.py

Prompts

```
['create a FastAPI endpoint that handles POST requests to /classify for model classification', 'test the create_classify endpoint handles requests with ClassificationRequest and returns a Response', 'review the classify helper function that retrieves ServingClassification from request app state', 'summarize the APIRouter configuration with /classify POST route and JSON validation dependency', 'build a classification handler that delegates to ServingClassification when the model supports it', 'build a ClassificationCompletionRequest to send text for classification via completion API', 'build a ClassificationChatRequest to send chat messages for classification', 'build TokenizeParams from a ClassificationCompletionRequest using a ModelConfig', 'build a ClassificationResponse containing a list of ClassificationData with labels and probabilities', 'build ClassificationData with index, label, probabilities, and number of classes', 'build a ServingClassification instance to serve text classification requests via vLLM pooling endpoint', 'create a ClassifyIOProcessor to handle input and output processing for classification tasks', 'build a ClassificationResponse containing classification results with labels, probabilities, and usage info', 'build a ClassificationData item with index, label, probability scores, and number of classes', 'test the _build_response method of ServingClassification to verify JSONResponse output format']
```

Usage

```
{'build_ServingClassification': 'build a ServingClassification instance to serve text classification requests via vLLM pooling endpoint', 'create_ClassifyIOProcessor': 'create a ClassifyIOProcessor to handle input and output processing for classification tasks', 'build_ClassificationResponse': 'build a ClassificationResponse containing classification results with labels, probabilities, and usage info', 'build_ClassificationData': 'build a ClassificationData item with index, label, probability scores, and number of classes', 'test_build_response': 'test the _build_response method of ServingClassification to verify JSONResponse output format'}
```

