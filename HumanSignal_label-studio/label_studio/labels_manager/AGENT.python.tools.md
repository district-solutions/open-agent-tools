# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/labels_manager/api.py

Prompts

```
['create a REST API endpoint for managing custom labels with CRUD operations on a Django project', 'create a REST API endpoint for linking custom labels to project labeling configuration', 'create a REST API endpoint for bulk updating labels in saved annotations', 'review the LabelAPI viewset that provides list, create, retrieve, update, and delete operations for custom labels', 'review the LabelLinkAPI viewset that manages label-to-project links with filtering and webhook notifications', 'refactor the bulk_update_label function to support batch label replacement across annotations', 'run bulk_update_label to replace an old label with a new label across all annotations in an organization', 'test the bulk_update_label function with project-scoped and organization-scoped label updates', 'review the bulk_update_label function for atomic transaction safety and bulk_update efficiency', 'summarize the bulk_update_label function that bulk-replaces label values in annotation results', 'create a Django model for Label with title, value, description, approval status, and organization fields', "test the Label model's has_permission method to verify organization-based access control", 'create a Django model for LabelLink to associate labels with projects and tag names', "review the LabelLink model's has_permission method for project-based permission delegation", 'refactor the Label model to enforce unique title per organization via UniqueConstraint', 'create a bulk label creation endpoint using LabelCreateSerializer with existing label deduplication', 'build a LabelListSerializer that validates all labels belong to the same project in a bulk request', 'test the LabelLinkSerializer with expandable label field and annotations_count read-only integer', 'review the LabelSerializer with expandable links field and read-only many-to-many PrimaryKeyRelatedField', 'summarize the LabelBulkUpdateSerializer that validates old_label and new_label JSON fields for project updates']
```

Usage

```
{'create_LabelAPI': 'create a REST API endpoint for managing custom labels with CRUD operations on a Django project', 'create_LabelLinkAPI': 'create a REST API endpoint for linking custom labels to project labeling configuration', 'create_LabelBulkUpdateAPI': 'create a REST API endpoint for bulk updating labels in saved annotations', 'review_LabelAPI': 'review the LabelAPI viewset that provides list, create, retrieve, update, and delete operations for custom labels', 'review_LabelLinkAPI': 'review the LabelLinkAPI viewset that manages label-to-project links with filtering and webhook notifications'}
```

## File: HumanSignal_label-studio/label_studio/labels_manager/functions.py

Prompts

```
['create a REST API endpoint for managing custom labels with CRUD operations on a Django project', 'create a REST API endpoint for linking custom labels to project labeling configuration', 'create a REST API endpoint for bulk updating labels in saved annotations', 'review the LabelAPI viewset that provides list, create, retrieve, update, and delete operations for custom labels', 'review the LabelLinkAPI viewset that manages label-to-project links with filtering and webhook notifications', 'refactor the bulk_update_label function to support batch label replacement across annotations', 'run bulk_update_label to replace an old label with a new label across all annotations in an organization', 'test the bulk_update_label function with project-scoped and organization-scoped label updates', 'review the bulk_update_label function for atomic transaction safety and bulk_update efficiency', 'summarize the bulk_update_label function that bulk-replaces label values in annotation results', 'create a Django model for Label with title, value, description, approval status, and organization fields', "test the Label model's has_permission method to verify organization-based access control", 'create a Django model for LabelLink to associate labels with projects and tag names', "review the LabelLink model's has_permission method for project-based permission delegation", 'refactor the Label model to enforce unique title per organization via UniqueConstraint', 'create a bulk label creation endpoint using LabelCreateSerializer with existing label deduplication', 'build a LabelListSerializer that validates all labels belong to the same project in a bulk request', 'test the LabelLinkSerializer with expandable label field and annotations_count read-only integer', 'review the LabelSerializer with expandable links field and read-only many-to-many PrimaryKeyRelatedField', 'summarize the LabelBulkUpdateSerializer that validates old_label and new_label JSON fields for project updates']
```

Usage

```
{'refactor_bulk_update_label': 'refactor the bulk_update_label function to support batch label replacement across annotations', 'run_bulk_update_label': 'run bulk_update_label to replace an old label with a new label across all annotations in an organization', 'test_bulk_update_label': 'test the bulk_update_label function with project-scoped and organization-scoped label updates', 'review_bulk_update_label': 'review the bulk_update_label function for atomic transaction safety and bulk_update efficiency', 'summarize_bulk_update_label': 'summarize the bulk_update_label function that bulk-replaces label values in annotation results'}
```

## File: HumanSignal_label-studio/label_studio/labels_manager/models.py

Prompts

```
['create a REST API endpoint for managing custom labels with CRUD operations on a Django project', 'create a REST API endpoint for linking custom labels to project labeling configuration', 'create a REST API endpoint for bulk updating labels in saved annotations', 'review the LabelAPI viewset that provides list, create, retrieve, update, and delete operations for custom labels', 'review the LabelLinkAPI viewset that manages label-to-project links with filtering and webhook notifications', 'refactor the bulk_update_label function to support batch label replacement across annotations', 'run bulk_update_label to replace an old label with a new label across all annotations in an organization', 'test the bulk_update_label function with project-scoped and organization-scoped label updates', 'review the bulk_update_label function for atomic transaction safety and bulk_update efficiency', 'summarize the bulk_update_label function that bulk-replaces label values in annotation results', 'create a Django model for Label with title, value, description, approval status, and organization fields', "test the Label model's has_permission method to verify organization-based access control", 'create a Django model for LabelLink to associate labels with projects and tag names', "review the LabelLink model's has_permission method for project-based permission delegation", 'refactor the Label model to enforce unique title per organization via UniqueConstraint', 'create a bulk label creation endpoint using LabelCreateSerializer with existing label deduplication', 'build a LabelListSerializer that validates all labels belong to the same project in a bulk request', 'test the LabelLinkSerializer with expandable label field and annotations_count read-only integer', 'review the LabelSerializer with expandable links field and read-only many-to-many PrimaryKeyRelatedField', 'summarize the LabelBulkUpdateSerializer that validates old_label and new_label JSON fields for project updates']
```

Usage

```
{'create_model_Label': 'create a Django model for Label with title, value, description, approval status, and organization fields', 'test_model_Label_has_permission': "test the Label model's has_permission method to verify organization-based access control", 'create_model_LabelLink': 'create a Django model for LabelLink to associate labels with projects and tag names', 'review_model_LabelLink_has_permission': "review the LabelLink model's has_permission method for project-based permission delegation", 'refactor_model_Label_unique_constraint': 'refactor the Label model to enforce unique title per organization via UniqueConstraint'}
```

## File: HumanSignal_label-studio/label_studio/labels_manager/serializers.py

Prompts

```
['create a REST API endpoint for managing custom labels with CRUD operations on a Django project', 'create a REST API endpoint for linking custom labels to project labeling configuration', 'create a REST API endpoint for bulk updating labels in saved annotations', 'review the LabelAPI viewset that provides list, create, retrieve, update, and delete operations for custom labels', 'review the LabelLinkAPI viewset that manages label-to-project links with filtering and webhook notifications', 'refactor the bulk_update_label function to support batch label replacement across annotations', 'run bulk_update_label to replace an old label with a new label across all annotations in an organization', 'test the bulk_update_label function with project-scoped and organization-scoped label updates', 'review the bulk_update_label function for atomic transaction safety and bulk_update efficiency', 'summarize the bulk_update_label function that bulk-replaces label values in annotation results', 'create a Django model for Label with title, value, description, approval status, and organization fields', "test the Label model's has_permission method to verify organization-based access control", 'create a Django model for LabelLink to associate labels with projects and tag names', "review the LabelLink model's has_permission method for project-based permission delegation", 'refactor the Label model to enforce unique title per organization via UniqueConstraint', 'create a bulk label creation endpoint using LabelCreateSerializer with existing label deduplication', 'build a LabelListSerializer that validates all labels belong to the same project in a bulk request', 'test the LabelLinkSerializer with expandable label field and annotations_count read-only integer', 'review the LabelSerializer with expandable links field and read-only many-to-many PrimaryKeyRelatedField', 'summarize the LabelBulkUpdateSerializer that validates old_label and new_label JSON fields for project updates']
```

Usage

```
{'create_label_bulk': 'create a bulk label creation endpoint using LabelCreateSerializer with existing label deduplication', 'build_label_list_validation': 'build a LabelListSerializer that validates all labels belong to the same project in a bulk request', 'test_label_link_serialization': 'test the LabelLinkSerializer with expandable label field and annotations_count read-only integer', 'review_label_serializer': 'review the LabelSerializer with expandable links field and read-only many-to-many PrimaryKeyRelatedField', 'summarize_label_bulk_update': 'summarize the LabelBulkUpdateSerializer that validates old_label and new_label JSON fields for project updates'}
```

