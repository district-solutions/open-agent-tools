# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/webhooks/api.py

Prompts

```
["list all webhooks set up for the authenticated user's organization", "create a new webhook for the authenticated user's organization", 'retrieve detailed info for a specific webhook by ID', 'update or delete a specific webhook by ID', 'get all available webhook action types and their descriptions', 'create a Django webhook model with URL, headers, and active state fields', 'validate webhook actions to ensure project webhooks do not contain organization-only actions', 'set webhook actions by syncing new and removed WebhookAction entries for a webhook', 'build a registry of webhook action constants with serializer and model metadata', 'check if a user has permission to access a webhook via its organization membership', "read a webhook's serialized representation including its actions and metadata", 'create a DRF serializer that serializes only the id field for webhook payloads', 'build a DRF model serializer for Project that includes annotation counts and task statistics', 'test the TaskWebhookSerializer that resolves $undefined$ keys in task data using label config', 'review the AnnotationWebhookSerializer that serializes all Annotation model fields for webhooks', 'summarize the webhook serializer classes that serialize Project, Task, and Annotation models for event payloads', 'run a single webhook synchronously for a given action with optional payload data', 'emit all active webhooks for an organization and project filtered by action name', 'emit webhooks for an action using model instances as payload with optional batching', 'decorate an APIView post, put, or patch method to emit webhooks after successful responses', 'retrieve a nested field from a single object or list of objects using dot-separated path']
```

Usage

```
{'list_webhooks': "list all webhooks set up for the authenticated user's organization", 'create_webhook': "create a new webhook for the authenticated user's organization", 'get_webhook': 'retrieve detailed info for a specific webhook by ID', 'update_webhook': 'update or delete a specific webhook by ID', 'get_webhook_actions': 'get all available webhook action types and their descriptions'}
```

## File: HumanSignal_label-studio/label_studio/webhooks/models.py

Prompts

```
["list all webhooks set up for the authenticated user's organization", "create a new webhook for the authenticated user's organization", 'retrieve detailed info for a specific webhook by ID', 'update or delete a specific webhook by ID', 'get all available webhook action types and their descriptions', 'create a Django webhook model with URL, headers, and active state fields', 'validate webhook actions to ensure project webhooks do not contain organization-only actions', 'set webhook actions by syncing new and removed WebhookAction entries for a webhook', 'build a registry of webhook action constants with serializer and model metadata', 'check if a user has permission to access a webhook via its organization membership', "read a webhook's serialized representation including its actions and metadata", 'create a DRF serializer that serializes only the id field for webhook payloads', 'build a DRF model serializer for Project that includes annotation counts and task statistics', 'test the TaskWebhookSerializer that resolves $undefined$ keys in task data using label config', 'review the AnnotationWebhookSerializer that serializes all Annotation model fields for webhooks', 'summarize the webhook serializer classes that serialize Project, Task, and Annotation models for event payloads', 'run a single webhook synchronously for a given action with optional payload data', 'emit all active webhooks for an organization and project filtered by action name', 'emit webhooks for an action using model instances as payload with optional batching', 'decorate an APIView post, put, or patch method to emit webhooks after successful responses', 'retrieve a nested field from a single object or list of objects using dot-separated path']
```

Usage

```
{'create_webhook_model': 'create a Django webhook model with URL, headers, and active state fields', 'validate_webhook_actions': 'validate webhook actions to ensure project webhooks do not contain organization-only actions', 'set_webhook_actions': 'set webhook actions by syncing new and removed WebhookAction entries for a webhook', 'build_webhook_action_registry': 'build a registry of webhook action constants with serializer and model metadata', 'check_webhook_permission': 'check if a user has permission to access a webhook via its organization membership'}
```

## File: HumanSignal_label-studio/label_studio/webhooks/serializers.py

Prompts

```
["list all webhooks set up for the authenticated user's organization", "create a new webhook for the authenticated user's organization", 'retrieve detailed info for a specific webhook by ID', 'update or delete a specific webhook by ID', 'get all available webhook action types and their descriptions', 'create a Django webhook model with URL, headers, and active state fields', 'validate webhook actions to ensure project webhooks do not contain organization-only actions', 'set webhook actions by syncing new and removed WebhookAction entries for a webhook', 'build a registry of webhook action constants with serializer and model metadata', 'check if a user has permission to access a webhook via its organization membership', "read a webhook's serialized representation including its actions and metadata", 'create a DRF serializer that serializes only the id field for webhook payloads', 'build a DRF model serializer for Project that includes annotation counts and task statistics', 'test the TaskWebhookSerializer that resolves $undefined$ keys in task data using label config', 'review the AnnotationWebhookSerializer that serializes all Annotation model fields for webhooks', 'summarize the webhook serializer classes that serialize Project, Task, and Annotation models for event payloads', 'run a single webhook synchronously for a given action with optional payload data', 'emit all active webhooks for an organization and project filtered by action name', 'emit webhooks for an action using model instances as payload with optional batching', 'decorate an APIView post, put, or patch method to emit webhooks after successful responses', 'retrieve a nested field from a single object or list of objects using dot-separated path']
```

Usage

```
{'create_webhook': 'create a webhook serializer instance with URL, actions, and payload settings for a project', 'update_webhook': "update an existing webhook's URL, actions, headers, and active status", 'validate_webhook_actions': 'validate webhook actions against the allowed WebhookAction.ACTIONS choices', 'list_webhooks': 'list all webhook configurations for an organization or project', 'read_webhook': "read a webhook's serialized representation including its actions and metadata"}
```

## File: HumanSignal_label-studio/label_studio/webhooks/serializers_for_hooks.py

Prompts

```
["list all webhooks set up for the authenticated user's organization", "create a new webhook for the authenticated user's organization", 'retrieve detailed info for a specific webhook by ID', 'update or delete a specific webhook by ID', 'get all available webhook action types and their descriptions', 'create a Django webhook model with URL, headers, and active state fields', 'validate webhook actions to ensure project webhooks do not contain organization-only actions', 'set webhook actions by syncing new and removed WebhookAction entries for a webhook', 'build a registry of webhook action constants with serializer and model metadata', 'check if a user has permission to access a webhook via its organization membership', "read a webhook's serialized representation including its actions and metadata", 'create a DRF serializer that serializes only the id field for webhook payloads', 'build a DRF model serializer for Project that includes annotation counts and task statistics', 'test the TaskWebhookSerializer that resolves $undefined$ keys in task data using label config', 'review the AnnotationWebhookSerializer that serializes all Annotation model fields for webhooks', 'summarize the webhook serializer classes that serialize Project, Task, and Annotation models for event payloads', 'run a single webhook synchronously for a given action with optional payload data', 'emit all active webhooks for an organization and project filtered by action name', 'emit webhooks for an action using model instances as payload with optional batching', 'decorate an APIView post, put, or patch method to emit webhooks after successful responses', 'retrieve a nested field from a single object or list of objects using dot-separated path']
```

Usage

```
{'create_serializer_only_id_webhook': 'create a DRF serializer that serializes only the id field for webhook payloads', 'build_serializer_project_webhook': 'build a DRF model serializer for Project that includes annotation counts and task statistics', 'test_serializer_task_webhook': 'test the TaskWebhookSerializer that resolves $undefined$ keys in task data using label config', 'review_serializer_annotation_webhook': 'review the AnnotationWebhookSerializer that serializes all Annotation model fields for webhooks', 'summarize_serializer_webhooks': 'summarize the webhook serializer classes that serialize Project, Task, and Annotation models for event payloads'}
```

## File: HumanSignal_label-studio/label_studio/webhooks/utils.py

Prompts

```
["list all webhooks set up for the authenticated user's organization", "create a new webhook for the authenticated user's organization", 'retrieve detailed info for a specific webhook by ID', 'update or delete a specific webhook by ID', 'get all available webhook action types and their descriptions', 'create a Django webhook model with URL, headers, and active state fields', 'validate webhook actions to ensure project webhooks do not contain organization-only actions', 'set webhook actions by syncing new and removed WebhookAction entries for a webhook', 'build a registry of webhook action constants with serializer and model metadata', 'check if a user has permission to access a webhook via its organization membership', "read a webhook's serialized representation including its actions and metadata", 'create a DRF serializer that serializes only the id field for webhook payloads', 'build a DRF model serializer for Project that includes annotation counts and task statistics', 'test the TaskWebhookSerializer that resolves $undefined$ keys in task data using label config', 'review the AnnotationWebhookSerializer that serializes all Annotation model fields for webhooks', 'summarize the webhook serializer classes that serialize Project, Task, and Annotation models for event payloads', 'run a single webhook synchronously for a given action with optional payload data', 'emit all active webhooks for an organization and project filtered by action name', 'emit webhooks for an action using model instances as payload with optional batching', 'decorate an APIView post, put, or patch method to emit webhooks after successful responses', 'retrieve a nested field from a single object or list of objects using dot-separated path']
```

Usage

```
{'run_webhook_sync': 'run a single webhook synchronously for a given action with optional payload data', 'emit_webhooks_sync': 'emit all active webhooks for an organization and project filtered by action name', 'emit_webhooks_for_instance_sync': 'emit webhooks for an action using model instances as payload with optional batching', 'api_webhook': 'decorate an APIView post, put, or patch method to emit webhooks after successful responses', 'get_nested_field': 'retrieve a nested field from a single object or list of objects using dot-separated path'}
```

