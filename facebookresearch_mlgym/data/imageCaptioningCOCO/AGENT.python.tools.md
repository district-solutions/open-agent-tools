# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/imageCaptioningCOCO/baseline.py

Prompts

```
['run the image captioning model training on the COCO dataset with ResNet50 encoder and LSTM decoder', 'build a vocabulary from a list of sentences using a frequency threshold filter', 'create a PyTorch Dataset class that loads COCO images and captions from a parquet file', 'test the ResNet50-based EncoderCNN model that extracts image features for caption generation', 'review the DecoderRNN sample method that generates captions using greedy search on image features', 'run the evaluate module to compute the mean BLEU score from a submission CSV file', 'run the load_submission function to read a submission CSV file into a pandas DataFrame', 'test the main function by passing a submission file path via the --submission_file argument', 'review the load_submission function that uses pandas to read CSV submission files', 'refactor the main function to support additional scoring metrics beyond BLEU']
```

Usage

```
{'run_image_captioning_training': 'run the image captioning model training on the COCO dataset with ResNet50 encoder and LSTM decoder', 'build_vocabulary_from_sentences': 'build a vocabulary from a list of sentences using a frequency threshold filter', 'create_coco_dataset': 'create a PyTorch Dataset class that loads COCO images and captions from a parquet file', 'test_encoder_cnn': 'test the ResNet50-based EncoderCNN model that extracts image features for caption generation', 'review_decoder_rnn_sample': 'review the DecoderRNN sample method that generates captions using greedy search on image features'}
```

## File: facebookresearch_mlgym/data/imageCaptioningCOCO/evaluate.py

Prompts

```
['run the image captioning model training on the COCO dataset with ResNet50 encoder and LSTM decoder', 'build a vocabulary from a list of sentences using a frequency threshold filter', 'create a PyTorch Dataset class that loads COCO images and captions from a parquet file', 'test the ResNet50-based EncoderCNN model that extracts image features for caption generation', 'review the DecoderRNN sample method that generates captions using greedy search on image features', 'run the evaluate module to compute the mean BLEU score from a submission CSV file', 'run the load_submission function to read a submission CSV file into a pandas DataFrame', 'test the main function by passing a submission file path via the --submission_file argument', 'review the load_submission function that uses pandas to read CSV submission files', 'refactor the main function to support additional scoring metrics beyond BLEU']
```

Usage

```
{'run_evaluate_bleu_scores': 'run the evaluate module to compute the mean BLEU score from a submission CSV file', 'run_load_submission': 'run the load_submission function to read a submission CSV file into a pandas DataFrame', 'test_main': 'test the main function by passing a submission file path via the --submission_file argument', 'review_load_submission': 'review the load_submission function that uses pandas to read CSV submission files', 'refactor_main': 'refactor the main function to support additional scoring metrics beyond BLEU'}
```

