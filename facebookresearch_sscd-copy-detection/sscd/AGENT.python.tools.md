# Agent Python Tools

- repo: facebookresearch/sscd-copy-detection
- repo_uri: https://github.com/facebookresearch/sscd-copy-detection

## File: facebookresearch_sscd-copy-detection/sscd/copydays_eval.py

Prompts

```
['run the copydays evaluation script to compute strong mAP and macro AP metrics on image embeddings', 'run the evaluate function to search embeddings using a FAISS index and compute retrieval metrics', 'run evaluate_all to compute metrics across multiple FAISS codecs and return a pandas DataFrame', 'run get_transforms to build image preprocessing transforms with resize, tensor conversion, and normalization', 'run main to perform end-to-end copydays evaluation with inference on copydays, distractors, and optional training data', 'run DISC copy detection evaluation on a dataset and save retrieval metrics to CSV', 'run retrieval evaluation across multiple FAISS codecs and score normalization settings', 'run score normalization on query and reference embeddings using a trained FAISS index', 'review the Embeddings class project method that encodes embeddings via a FAISS codec index', 'review the ScoreNormalization parse method that parses weight and index range from a spec string', 'run the SSCD copy detection model training with argparse CLI arguments for dataset paths and hyperparameters', 'build a DISCData LightningDataModule to load training and validation datasets with repeated augmentation transforms', 'create an SSCD LightningModule that computes InfoNCE loss with cross-GPU similarity and entropy regularization', 'review the SSCD cross_gpu_similarity method that gathers embeddings across GPUs and computes match matrices', 'test the SSCD loss function that combines InfoNCE contrastive loss with differential entropy regularization']
```

Usage

```
{'run_copydays_evaluation': 'run the copydays evaluation script to compute strong mAP and macro AP metrics on image embeddings', 'run_evaluate_function': 'run the evaluate function to search embeddings using a FAISS index and compute retrieval metrics', 'run_evaluate_all_function': 'run evaluate_all to compute metrics across multiple FAISS codecs and return a pandas DataFrame', 'run_get_transforms_function': 'run get_transforms to build image preprocessing transforms with resize, tensor conversion, and normalization', 'run_main_function': 'run main to perform end-to-end copydays evaluation with inference on copydays, distractors, and optional training data'}
```

## File: facebookresearch_sscd-copy-detection/sscd/disc_eval.py

Prompts

```
['run the copydays evaluation script to compute strong mAP and macro AP metrics on image embeddings', 'run the evaluate function to search embeddings using a FAISS index and compute retrieval metrics', 'run evaluate_all to compute metrics across multiple FAISS codecs and return a pandas DataFrame', 'run get_transforms to build image preprocessing transforms with resize, tensor conversion, and normalization', 'run main to perform end-to-end copydays evaluation with inference on copydays, distractors, and optional training data', 'run DISC copy detection evaluation on a dataset and save retrieval metrics to CSV', 'run retrieval evaluation across multiple FAISS codecs and score normalization settings', 'run score normalization on query and reference embeddings using a trained FAISS index', 'review the Embeddings class project method that encodes embeddings via a FAISS codec index', 'review the ScoreNormalization parse method that parses weight and index range from a spec string', 'run the SSCD copy detection model training with argparse CLI arguments for dataset paths and hyperparameters', 'build a DISCData LightningDataModule to load training and validation datasets with repeated augmentation transforms', 'create an SSCD LightningModule that computes InfoNCE loss with cross-GPU similarity and entropy regularization', 'review the SSCD cross_gpu_similarity method that gathers embeddings across GPUs and computes match matrices', 'test the SSCD loss function that combines InfoNCE contrastive loss with differential entropy regularization']
```

Usage

```
{'run_disc_eval': 'run DISC copy detection evaluation on a dataset and save retrieval metrics to CSV', 'run_evaluate_all': 'run retrieval evaluation across multiple FAISS codecs and score normalization settings', 'run_apply_score_norm': 'run score normalization on query and reference embeddings using a trained FAISS index', 'review_Embeddings_project': 'review the Embeddings class project method that encodes embeddings via a FAISS codec index', 'review_ScoreNormalization_parse': 'review the ScoreNormalization parse method that parses weight and index range from a spec string'}
```

## File: facebookresearch_sscd-copy-detection/sscd/train.py

Prompts

```
['run the copydays evaluation script to compute strong mAP and macro AP metrics on image embeddings', 'run the evaluate function to search embeddings using a FAISS index and compute retrieval metrics', 'run evaluate_all to compute metrics across multiple FAISS codecs and return a pandas DataFrame', 'run get_transforms to build image preprocessing transforms with resize, tensor conversion, and normalization', 'run main to perform end-to-end copydays evaluation with inference on copydays, distractors, and optional training data', 'run DISC copy detection evaluation on a dataset and save retrieval metrics to CSV', 'run retrieval evaluation across multiple FAISS codecs and score normalization settings', 'run score normalization on query and reference embeddings using a trained FAISS index', 'review the Embeddings class project method that encodes embeddings via a FAISS codec index', 'review the ScoreNormalization parse method that parses weight and index range from a spec string', 'run the SSCD copy detection model training with argparse CLI arguments for dataset paths and hyperparameters', 'build a DISCData LightningDataModule to load training and validation datasets with repeated augmentation transforms', 'create an SSCD LightningModule that computes InfoNCE loss with cross-GPU similarity and entropy regularization', 'review the SSCD cross_gpu_similarity method that gathers embeddings across GPUs and computes match matrices', 'test the SSCD loss function that combines InfoNCE contrastive loss with differential entropy regularization']
```

Usage

```
{'run_sscd_training': 'run the SSCD copy detection model training with argparse CLI arguments for dataset paths and hyperparameters', 'build_disc_data_module': 'build a DISCData LightningDataModule to load training and validation datasets with repeated augmentation transforms', 'create_sscd_lightning_module': 'create an SSCD LightningModule that computes InfoNCE loss with cross-GPU similarity and entropy regularization', 'review_cross_gpu_similarity': 'review the SSCD cross_gpu_similarity method that gathers embeddings across GPUs and computes match matrices', 'test_loss_function': 'test the SSCD loss function that combines InfoNCE contrastive loss with differential entropy regularization'}
```

