# Agent Python Tools

- repo: facebookresearch/nougat
- repo_uri: https://github.com/facebookresearch/nougat.git

## File: facebookresearch_nougat/app.py

Prompts

```
['run the nougat fastapi server on port 8503 using uvicorn', 'send a PDF file to the predict endpoint to extract text in markdown format', 'send a PDF file with start and stop page numbers to extract a specific page range', 'load the nougat pretrained model on device during fastapi startup event', 'call the root endpoint to verify the nougat api server is running', 'build a NougatModelPLModule Lightning module from config to train a document OCR model', 'run a training step on batched image tensors and decoder input IDs to compute loss', 'run a validation step to infer predictions from images and compute metrics against ground truth', 'configure an AdamW optimizer with an exponential learning rate scheduler and warmup steps', 'create a NougatDataPLModule Lightning data module with train and validation dataloaders', 'install the nougat-ocr python package with pip using setup.py and all core dependencies', 'install the nougat-ocr package with api extras for fastapi and uvicorn server support', 'install the nougat-ocr package with dataset extras for pytesseract and pdfminer dependencies', 'run the nougat console script entry point from predict:main to convert PDFs to LaTeX', 'run the nougat model evaluation on a dataset and compute edit distance, BLEU, and METEOR scores', 'test the NougatModel inference on image tensors and compare predictions against ground truth labels', 'run the test function with a pretrained checkpoint and dataset to generate predictions and metrics', 'compute metrics using multiprocessing Pool to evaluate predictions against ground truth in parallel', 'save evaluation results including predictions, ground truths, and accuracy scores to a JSON file', 'train a Nougat model using a config file with --config and optional --exp_version flags', 'save a PyTorch checkpoint to a specified path using CustomCheckpointIO save_checkpoint method', 'load a checkpoint from a file or directory path using CustomCheckpointIO load_checkpoint method', 'log the L2 gradient norm of a model after backward pass using GradNormCallback', 'save a training configuration as a YAML file to the experiment output directory']
```

Usage

```
{'run_nougat_api_server': 'run the nougat fastapi server on port 8503 using uvicorn', 'predict_pdf_to_markdown': 'send a PDF file to the predict endpoint to extract text in markdown format', 'predict_pdf_page_range': 'send a PDF file with start and stop page numbers to extract a specific page range', 'load_model_on_startup': 'load the nougat pretrained model on device during fastapi startup event', 'health_check_root': 'call the root endpoint to verify the nougat api server is running'}
```

## File: facebookresearch_nougat/lightning_module.py

Prompts

```
['run the nougat fastapi server on port 8503 using uvicorn', 'send a PDF file to the predict endpoint to extract text in markdown format', 'send a PDF file with start and stop page numbers to extract a specific page range', 'load the nougat pretrained model on device during fastapi startup event', 'call the root endpoint to verify the nougat api server is running', 'build a NougatModelPLModule Lightning module from config to train a document OCR model', 'run a training step on batched image tensors and decoder input IDs to compute loss', 'run a validation step to infer predictions from images and compute metrics against ground truth', 'configure an AdamW optimizer with an exponential learning rate scheduler and warmup steps', 'create a NougatDataPLModule Lightning data module with train and validation dataloaders', 'install the nougat-ocr python package with pip using setup.py and all core dependencies', 'install the nougat-ocr package with api extras for fastapi and uvicorn server support', 'install the nougat-ocr package with dataset extras for pytesseract and pdfminer dependencies', 'run the nougat console script entry point from predict:main to convert PDFs to LaTeX', 'run the nougat model evaluation on a dataset and compute edit distance, BLEU, and METEOR scores', 'test the NougatModel inference on image tensors and compare predictions against ground truth labels', 'run the test function with a pretrained checkpoint and dataset to generate predictions and metrics', 'compute metrics using multiprocessing Pool to evaluate predictions against ground truth in parallel', 'save evaluation results including predictions, ground truths, and accuracy scores to a JSON file', 'train a Nougat model using a config file with --config and optional --exp_version flags', 'save a PyTorch checkpoint to a specified path using CustomCheckpointIO save_checkpoint method', 'load a checkpoint from a file or directory path using CustomCheckpointIO load_checkpoint method', 'log the L2 gradient norm of a model after backward pass using GradNormCallback', 'save a training configuration as a YAML file to the experiment output directory']
```

Usage

```
{'build_nougat_lightning_module': 'build a NougatModelPLModule Lightning module from config to train a document OCR model', 'run_training_step': 'run a training step on batched image tensors and decoder input IDs to compute loss', 'run_validation_step': 'run a validation step to infer predictions from images and compute metrics against ground truth', 'configure_optimizers_with_scheduler': 'configure an AdamW optimizer with an exponential learning rate scheduler and warmup steps', 'create_nougat_data_module': 'create a NougatDataPLModule Lightning data module with train and validation dataloaders'}
```

## File: facebookresearch_nougat/setup.py

Prompts

```
['run the nougat fastapi server on port 8503 using uvicorn', 'send a PDF file to the predict endpoint to extract text in markdown format', 'send a PDF file with start and stop page numbers to extract a specific page range', 'load the nougat pretrained model on device during fastapi startup event', 'call the root endpoint to verify the nougat api server is running', 'build a NougatModelPLModule Lightning module from config to train a document OCR model', 'run a training step on batched image tensors and decoder input IDs to compute loss', 'run a validation step to infer predictions from images and compute metrics against ground truth', 'configure an AdamW optimizer with an exponential learning rate scheduler and warmup steps', 'create a NougatDataPLModule Lightning data module with train and validation dataloaders', 'install the nougat-ocr python package with pip using setup.py and all core dependencies', 'install the nougat-ocr package with api extras for fastapi and uvicorn server support', 'install the nougat-ocr package with dataset extras for pytesseract and pdfminer dependencies', 'run the nougat console script entry point from predict:main to convert PDFs to LaTeX', 'run the nougat model evaluation on a dataset and compute edit distance, BLEU, and METEOR scores', 'test the NougatModel inference on image tensors and compare predictions against ground truth labels', 'run the test function with a pretrained checkpoint and dataset to generate predictions and metrics', 'compute metrics using multiprocessing Pool to evaluate predictions against ground truth in parallel', 'save evaluation results including predictions, ground truths, and accuracy scores to a JSON file', 'train a Nougat model using a config file with --config and optional --exp_version flags', 'save a PyTorch checkpoint to a specified path using CustomCheckpointIO save_checkpoint method', 'load a checkpoint from a file or directory path using CustomCheckpointIO load_checkpoint method', 'log the L2 gradient norm of a model after backward pass using GradNormCallback', 'save a training configuration as a YAML file to the experiment output directory']
```

Usage

```
{'install_nougat_ocr_package': 'install the nougat-ocr python package with pip using setup.py and all core dependencies', 'install_nougat_api_extras': 'install the nougat-ocr package with api extras for fastapi and uvicorn server support', 'install_nougat_dataset_extras': 'install the nougat-ocr package with dataset extras for pytesseract and pdfminer dependencies', 'run_nougat_console_script': 'run the nougat console script entry point from predict:main to convert PDFs to LaTeX', 'run_nougat_api_server': 'run the nougat_api console script entry point from app:main to start the FastAPI server'}
```

## File: facebookresearch_nougat/test.py

Prompts

```
['run the nougat fastapi server on port 8503 using uvicorn', 'send a PDF file to the predict endpoint to extract text in markdown format', 'send a PDF file with start and stop page numbers to extract a specific page range', 'load the nougat pretrained model on device during fastapi startup event', 'call the root endpoint to verify the nougat api server is running', 'build a NougatModelPLModule Lightning module from config to train a document OCR model', 'run a training step on batched image tensors and decoder input IDs to compute loss', 'run a validation step to infer predictions from images and compute metrics against ground truth', 'configure an AdamW optimizer with an exponential learning rate scheduler and warmup steps', 'create a NougatDataPLModule Lightning data module with train and validation dataloaders', 'install the nougat-ocr python package with pip using setup.py and all core dependencies', 'install the nougat-ocr package with api extras for fastapi and uvicorn server support', 'install the nougat-ocr package with dataset extras for pytesseract and pdfminer dependencies', 'run the nougat console script entry point from predict:main to convert PDFs to LaTeX', 'run the nougat model evaluation on a dataset and compute edit distance, BLEU, and METEOR scores', 'test the NougatModel inference on image tensors and compare predictions against ground truth labels', 'run the test function with a pretrained checkpoint and dataset to generate predictions and metrics', 'compute metrics using multiprocessing Pool to evaluate predictions against ground truth in parallel', 'save evaluation results including predictions, ground truths, and accuracy scores to a JSON file', 'train a Nougat model using a config file with --config and optional --exp_version flags', 'save a PyTorch checkpoint to a specified path using CustomCheckpointIO save_checkpoint method', 'load a checkpoint from a file or directory path using CustomCheckpointIO load_checkpoint method', 'log the L2 gradient norm of a model after backward pass using GradNormCallback', 'save a training configuration as a YAML file to the experiment output directory']
```

Usage

```
{'run_nougat_model_evaluation': 'run the nougat model evaluation on a dataset and compute edit distance, BLEU, and METEOR scores', 'test_NougatModel_inference': 'test the NougatModel inference on image tensors and compare predictions against ground truth labels', 'run_test_with_checkpoint': 'run the test function with a pretrained checkpoint and dataset to generate predictions and metrics', 'compute_metrics_multiprocessing': 'compute metrics using multiprocessing Pool to evaluate predictions against ground truth in parallel', 'save_evaluation_results': 'save evaluation results including predictions, ground truths, and accuracy scores to a JSON file'}
```

## File: facebookresearch_nougat/train.py

Prompts

```
['run the nougat fastapi server on port 8503 using uvicorn', 'send a PDF file to the predict endpoint to extract text in markdown format', 'send a PDF file with start and stop page numbers to extract a specific page range', 'load the nougat pretrained model on device during fastapi startup event', 'call the root endpoint to verify the nougat api server is running', 'build a NougatModelPLModule Lightning module from config to train a document OCR model', 'run a training step on batched image tensors and decoder input IDs to compute loss', 'run a validation step to infer predictions from images and compute metrics against ground truth', 'configure an AdamW optimizer with an exponential learning rate scheduler and warmup steps', 'create a NougatDataPLModule Lightning data module with train and validation dataloaders', 'install the nougat-ocr python package with pip using setup.py and all core dependencies', 'install the nougat-ocr package with api extras for fastapi and uvicorn server support', 'install the nougat-ocr package with dataset extras for pytesseract and pdfminer dependencies', 'run the nougat console script entry point from predict:main to convert PDFs to LaTeX', 'run the nougat model evaluation on a dataset and compute edit distance, BLEU, and METEOR scores', 'test the NougatModel inference on image tensors and compare predictions against ground truth labels', 'run the test function with a pretrained checkpoint and dataset to generate predictions and metrics', 'compute metrics using multiprocessing Pool to evaluate predictions against ground truth in parallel', 'save evaluation results including predictions, ground truths, and accuracy scores to a JSON file', 'train a Nougat model using a config file with --config and optional --exp_version flags', 'save a PyTorch checkpoint to a specified path using CustomCheckpointIO save_checkpoint method', 'load a checkpoint from a file or directory path using CustomCheckpointIO load_checkpoint method', 'log the L2 gradient norm of a model after backward pass using GradNormCallback', 'save a training configuration as a YAML file to the experiment output directory']
```

Usage

```
{'train_nougat_model': 'train a Nougat model using a config file with --config and optional --exp_version flags', 'save_checkpoint_custom': 'save a PyTorch checkpoint to a specified path using CustomCheckpointIO save_checkpoint method', 'load_checkpoint_custom': 'load a checkpoint from a file or directory path using CustomCheckpointIO load_checkpoint method', 'log_gradient_norm': 'log the L2 gradient norm of a model after backward pass using GradNormCallback', 'save_config_yaml': 'save a training configuration as a YAML file to the experiment output directory'}
```

