# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/criterion.py

Prompts

```
['build a Wav2Vec2AsrCriterion instance with a RecipeModel and optional WerCalculator for ASR training', 'test the Wav2Vec2AsrCriterion call method to compute CTC loss and WER for a Seq2SeqBatch', 'review the prepare_metric_bag method to register ASR metrics on a MetricBag instance', 'summarize the _forward_with_logits method that returns CTC loss, logits, and BatchLayout from a batch', 'refactor the process_metric_values method to handle WER calculator metric value processing', 'add ASR metrics like ctc_loss, num_examples, and padding to a MetricBag for tracking', 'update the CTC loss metric in a MetricBag by normalizing loss and converting to bits', 'update ASR batch metrics including num_examples, num_elements, and padding from a Seq2SeqBatch', 'review the add_asr_metrics function to understand how ASR metrics are registered in a MetricBag', 'summarize the update_ctc_loss function which normalizes loss by batch size and converts to log base 2', 'create a Wav2Vec2AsrRecipe to train an ASR model with CTC loss and pretrained encoder initialization', 'prepare CTC training by sharing encoder parameters from a pretrained wav2vec2 SSL model', 'create a trainer that freezes the encoder for N steps then unfreezes it during ASR training', 'build a Wav2Vec2AsrTrainUnit that processes batches and manages encoder freezing during training', 'evaluate a Wav2Vec2 ASR model using Wav2Vec2AsrEvalUnit with word error rate metric tracking', 'create a WerCalculator instance with a tokenizer and optional reference and hypothesis output streams', 'build a WerCalculator from a RecipeContext that auto-creates transcription output files per DP rank', 'run compute_wer to decode CTC logits via greedy decoding and update WER metrics in a MetricBag', 'test the greedy CTC decoding that performs argmax and unique_consecutive to generate hypothesis sequences', 'review process_metric_values to split WER and UER tensors from the metric values mapping']
```

Usage

```
{'build_Wav2Vec2AsrCriterion': 'build a Wav2Vec2AsrCriterion instance with a RecipeModel and optional WerCalculator for ASR training', 'test_call_method': 'test the Wav2Vec2AsrCriterion call method to compute CTC loss and WER for a Seq2SeqBatch', 'review_prepare_metric_bag': 'review the prepare_metric_bag method to register ASR metrics on a MetricBag instance', 'summarize_forward_with_logits': 'summarize the _forward_with_logits method that returns CTC loss, logits, and BatchLayout from a batch', 'refactor_process_metric_values': 'refactor the process_metric_values method to handle WER calculator metric value processing'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/metrics.py

Prompts

```
['build a Wav2Vec2AsrCriterion instance with a RecipeModel and optional WerCalculator for ASR training', 'test the Wav2Vec2AsrCriterion call method to compute CTC loss and WER for a Seq2SeqBatch', 'review the prepare_metric_bag method to register ASR metrics on a MetricBag instance', 'summarize the _forward_with_logits method that returns CTC loss, logits, and BatchLayout from a batch', 'refactor the process_metric_values method to handle WER calculator metric value processing', 'add ASR metrics like ctc_loss, num_examples, and padding to a MetricBag for tracking', 'update the CTC loss metric in a MetricBag by normalizing loss and converting to bits', 'update ASR batch metrics including num_examples, num_elements, and padding from a Seq2SeqBatch', 'review the add_asr_metrics function to understand how ASR metrics are registered in a MetricBag', 'summarize the update_ctc_loss function which normalizes loss by batch size and converts to log base 2', 'create a Wav2Vec2AsrRecipe to train an ASR model with CTC loss and pretrained encoder initialization', 'prepare CTC training by sharing encoder parameters from a pretrained wav2vec2 SSL model', 'create a trainer that freezes the encoder for N steps then unfreezes it during ASR training', 'build a Wav2Vec2AsrTrainUnit that processes batches and manages encoder freezing during training', 'evaluate a Wav2Vec2 ASR model using Wav2Vec2AsrEvalUnit with word error rate metric tracking', 'create a WerCalculator instance with a tokenizer and optional reference and hypothesis output streams', 'build a WerCalculator from a RecipeContext that auto-creates transcription output files per DP rank', 'run compute_wer to decode CTC logits via greedy decoding and update WER metrics in a MetricBag', 'test the greedy CTC decoding that performs argmax and unique_consecutive to generate hypothesis sequences', 'review process_metric_values to split WER and UER tensors from the metric values mapping']
```

Usage

```
{'add_asr_metrics': 'add ASR metrics like ctc_loss, num_examples, and padding to a MetricBag for tracking', 'update_ctc_loss': 'update the CTC loss metric in a MetricBag by normalizing loss and converting to bits', 'update_asr_batch_metrics': 'update ASR batch metrics including num_examples, num_elements, and padding from a Seq2SeqBatch', 'review_add_asr_metrics': 'review the add_asr_metrics function to understand how ASR metrics are registered in a MetricBag', 'summarize_update_ctc_loss': 'summarize the update_ctc_loss function which normalizes loss by batch size and converts to log base 2'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/recipe.py

Prompts

```
['build a Wav2Vec2AsrCriterion instance with a RecipeModel and optional WerCalculator for ASR training', 'test the Wav2Vec2AsrCriterion call method to compute CTC loss and WER for a Seq2SeqBatch', 'review the prepare_metric_bag method to register ASR metrics on a MetricBag instance', 'summarize the _forward_with_logits method that returns CTC loss, logits, and BatchLayout from a batch', 'refactor the process_metric_values method to handle WER calculator metric value processing', 'add ASR metrics like ctc_loss, num_examples, and padding to a MetricBag for tracking', 'update the CTC loss metric in a MetricBag by normalizing loss and converting to bits', 'update ASR batch metrics including num_examples, num_elements, and padding from a Seq2SeqBatch', 'review the add_asr_metrics function to understand how ASR metrics are registered in a MetricBag', 'summarize the update_ctc_loss function which normalizes loss by batch size and converts to log base 2', 'create a Wav2Vec2AsrRecipe to train an ASR model with CTC loss and pretrained encoder initialization', 'prepare CTC training by sharing encoder parameters from a pretrained wav2vec2 SSL model', 'create a trainer that freezes the encoder for N steps then unfreezes it during ASR training', 'build a Wav2Vec2AsrTrainUnit that processes batches and manages encoder freezing during training', 'evaluate a Wav2Vec2 ASR model using Wav2Vec2AsrEvalUnit with word error rate metric tracking', 'create a WerCalculator instance with a tokenizer and optional reference and hypothesis output streams', 'build a WerCalculator from a RecipeContext that auto-creates transcription output files per DP rank', 'run compute_wer to decode CTC logits via greedy decoding and update WER metrics in a MetricBag', 'test the greedy CTC decoding that performs argmax and unique_consecutive to generate hypothesis sequences', 'review process_metric_values to split WER and UER tensors from the metric values mapping']
```

Usage

```
{'create_wav2vec2_asr_recipe': 'create a Wav2Vec2AsrRecipe to train an ASR model with CTC loss and pretrained encoder initialization', 'prepare_ctc_training_from_encoder': 'prepare CTC training by sharing encoder parameters from a pretrained wav2vec2 SSL model', 'create_trainer_with_freeze_steps': 'create a trainer that freezes the encoder for N steps then unfreezes it during ASR training', 'build_wav2vec2_asr_train_unit': 'build a Wav2Vec2AsrTrainUnit that processes batches and manages encoder freezing during training', 'evaluate_wav2vec2_asr_with_wer': 'evaluate a Wav2Vec2 ASR model using Wav2Vec2AsrEvalUnit with word error rate metric tracking'}
```

## File: facebookresearch_fairseq2/recipes/wav2vec2/asr/wer_calculator.py

Prompts

```
['build a Wav2Vec2AsrCriterion instance with a RecipeModel and optional WerCalculator for ASR training', 'test the Wav2Vec2AsrCriterion call method to compute CTC loss and WER for a Seq2SeqBatch', 'review the prepare_metric_bag method to register ASR metrics on a MetricBag instance', 'summarize the _forward_with_logits method that returns CTC loss, logits, and BatchLayout from a batch', 'refactor the process_metric_values method to handle WER calculator metric value processing', 'add ASR metrics like ctc_loss, num_examples, and padding to a MetricBag for tracking', 'update the CTC loss metric in a MetricBag by normalizing loss and converting to bits', 'update ASR batch metrics including num_examples, num_elements, and padding from a Seq2SeqBatch', 'review the add_asr_metrics function to understand how ASR metrics are registered in a MetricBag', 'summarize the update_ctc_loss function which normalizes loss by batch size and converts to log base 2', 'create a Wav2Vec2AsrRecipe to train an ASR model with CTC loss and pretrained encoder initialization', 'prepare CTC training by sharing encoder parameters from a pretrained wav2vec2 SSL model', 'create a trainer that freezes the encoder for N steps then unfreezes it during ASR training', 'build a Wav2Vec2AsrTrainUnit that processes batches and manages encoder freezing during training', 'evaluate a Wav2Vec2 ASR model using Wav2Vec2AsrEvalUnit with word error rate metric tracking', 'create a WerCalculator instance with a tokenizer and optional reference and hypothesis output streams', 'build a WerCalculator from a RecipeContext that auto-creates transcription output files per DP rank', 'run compute_wer to decode CTC logits via greedy decoding and update WER metrics in a MetricBag', 'test the greedy CTC decoding that performs argmax and unique_consecutive to generate hypothesis sequences', 'review process_metric_values to split WER and UER tensors from the metric values mapping']
```

Usage

```
{'create_WerCalculator': 'create a WerCalculator instance with a tokenizer and optional reference and hypothesis output streams', 'build_WerCalculator_from_context': 'build a WerCalculator from a RecipeContext that auto-creates transcription output files per DP rank', 'run_compute_wer': 'run compute_wer to decode CTC logits via greedy decoding and update WER metrics in a MetricBag', 'test_generate_hypotheses': 'test the greedy CTC decoding that performs argmax and unique_consecutive to generate hypothesis sequences', 'review_process_metric_values': 'review process_metric_values to split WER and UER tensors from the metric values mapping'}
```

