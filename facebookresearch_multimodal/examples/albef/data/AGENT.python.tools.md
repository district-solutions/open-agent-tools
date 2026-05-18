# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/albef/data/retrieval_datamodule.py

Prompts

```
['create a RetrievalDataModule instance with train and test file paths for image-text retrieval training', 'build a training DataLoader from RetrievalDataModule with distributed sampler support and custom collate function', 'build an image-only DataLoader from RetrievalDataModule for image-to-text retrieval inference', 'build a text-only DataLoader from RetrievalDataModule for text-to-image retrieval inference', 'create a collate function that stacks images, pads text sequences, and generates attention masks for retrieval training', 'create an ALBEFTextTransform instance to tokenize text into BERT token id tensors with preprocessing', 'run ALBEFTextTransform on input text to get a tensor of BERT token ids', 'run the pre_process method to remove punctuation and trailing spaces from text', 'create a training image transform pipeline with random crop, flip, and augmentation for ALBEF', 'create a testing image transform pipeline that resizes and normalizes images for ALBEF inference', 'create a VQADataModule instance with train and test file paths for visual question answering', 'run the train_dataloader method to get a DataLoader with images, questions, answers, and attention masks', 'run the test_dataloader method to get a DataLoader with images, questions, and question IDs', 'refactor the vqa_train_collate_fn to stack images and pad questions and answers for training batches', 'review the vqa_test_collate_fn to stack images and pad questions for testing batches']
```

Usage

```
{'create_RetrievalDataModule': 'create a RetrievalDataModule instance with train and test file paths for image-text retrieval training', 'build_train_dataloader': 'build a training DataLoader from RetrievalDataModule with distributed sampler support and custom collate function', 'build_image_dataloader': 'build an image-only DataLoader from RetrievalDataModule for image-to-text retrieval inference', 'build_text_dataloader': 'build a text-only DataLoader from RetrievalDataModule for text-to-image retrieval inference', 'create_retrieval_train_collate_fn': 'create a collate function that stacks images, pads text sequences, and generates attention masks for retrieval training'}
```

## File: facebookresearch_multimodal/examples/albef/data/transforms.py

Prompts

```
['create a RetrievalDataModule instance with train and test file paths for image-text retrieval training', 'build a training DataLoader from RetrievalDataModule with distributed sampler support and custom collate function', 'build an image-only DataLoader from RetrievalDataModule for image-to-text retrieval inference', 'build a text-only DataLoader from RetrievalDataModule for text-to-image retrieval inference', 'create a collate function that stacks images, pads text sequences, and generates attention masks for retrieval training', 'create an ALBEFTextTransform instance to tokenize text into BERT token id tensors with preprocessing', 'run ALBEFTextTransform on input text to get a tensor of BERT token ids', 'run the pre_process method to remove punctuation and trailing spaces from text', 'create a training image transform pipeline with random crop, flip, and augmentation for ALBEF', 'create a testing image transform pipeline that resizes and normalizes images for ALBEF inference', 'create a VQADataModule instance with train and test file paths for visual question answering', 'run the train_dataloader method to get a DataLoader with images, questions, answers, and attention masks', 'run the test_dataloader method to get a DataLoader with images, questions, and question IDs', 'refactor the vqa_train_collate_fn to stack images and pad questions and answers for training batches', 'review the vqa_test_collate_fn to stack images and pad questions for testing batches']
```

Usage

```
{'create_ALBEFTextTransform': 'create an ALBEFTextTransform instance to tokenize text into BERT token id tensors with preprocessing', 'run_ALBEFTextTransform_call': 'run ALBEFTextTransform on input text to get a tensor of BERT token ids', 'run_ALBEFTextTransform_pre_process': 'run the pre_process method to remove punctuation and trailing spaces from text', 'create_training_image_transform': 'create a training image transform pipeline with random crop, flip, and augmentation for ALBEF', 'create_testing_image_transform': 'create a testing image transform pipeline that resizes and normalizes images for ALBEF inference'}
```

## File: facebookresearch_multimodal/examples/albef/data/vqa_datamodules.py

Prompts

```
['create a RetrievalDataModule instance with train and test file paths for image-text retrieval training', 'build a training DataLoader from RetrievalDataModule with distributed sampler support and custom collate function', 'build an image-only DataLoader from RetrievalDataModule for image-to-text retrieval inference', 'build a text-only DataLoader from RetrievalDataModule for text-to-image retrieval inference', 'create a collate function that stacks images, pads text sequences, and generates attention masks for retrieval training', 'create an ALBEFTextTransform instance to tokenize text into BERT token id tensors with preprocessing', 'run ALBEFTextTransform on input text to get a tensor of BERT token ids', 'run the pre_process method to remove punctuation and trailing spaces from text', 'create a training image transform pipeline with random crop, flip, and augmentation for ALBEF', 'create a testing image transform pipeline that resizes and normalizes images for ALBEF inference', 'create a VQADataModule instance with train and test file paths for visual question answering', 'run the train_dataloader method to get a DataLoader with images, questions, answers, and attention masks', 'run the test_dataloader method to get a DataLoader with images, questions, and question IDs', 'refactor the vqa_train_collate_fn to stack images and pad questions and answers for training batches', 'review the vqa_test_collate_fn to stack images and pad questions for testing batches']
```

Usage

```
{'create_VQADataModule': 'create a VQADataModule instance with train and test file paths for visual question answering', 'run_train_dataloader': 'run the train_dataloader method to get a DataLoader with images, questions, answers, and attention masks', 'run_test_dataloader': 'run the test_dataloader method to get a DataLoader with images, questions, and question IDs', 'refactor_vqa_train_collate_fn': 'refactor the vqa_train_collate_fn to stack images and pad questions and answers for training batches', 'review_vqa_test_collate_fn': 'review the vqa_test_collate_fn to stack images and pad questions for testing batches'}
```

