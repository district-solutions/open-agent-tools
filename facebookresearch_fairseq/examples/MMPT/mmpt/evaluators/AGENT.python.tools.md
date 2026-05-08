# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/MMPT/mmpt/evaluators/evaluator.py

Prompts

```
['create an Evaluator instance with a config object specifying metric and predictor class names', 'run the Evaluator callable to load merged prediction files and compute metrics from numpy outputs', 'run the evaluate method to predict on a model and compute metrics from the dataloader', 'review the Evaluator constructor to understand how metric and predictor classes are dynamically loaded from config', 'summarize the Evaluator class that performs offline and online evaluation on downstream tasks using configurable metrics and predictors', 'compute retrieval metrics R1, R5, R10, and median rank from a similarity matrix using RetrievalMetric', 'compute DiDeMo moment localization metrics rank1, rank5, and mean IoU from predicted video segments', 'compute NLG evaluation metrics including BLEU, METEOR, ROUGE, and CIDEr from NLGEval using NLGMetric', 'compute action recognition accuracy and recall splits from video embeddings and labels using ActionRecognitionMetric', 'compute per-task and average recall for cross-task predictions using CrossTaskMetric', 'run NLGPredictor to generate text predictions from an MMFusion model using a HuggingFace tokenizer', 'run RetrievalPredictor to compute pooled video and text embeddings for cross-modal retrieval scoring', 'run QAPredictor to predict video question answers by computing pooled video-text similarity scores', 'run CrossTaskPredictor to compute averaged sliding-window logits for video moment prediction tasks', 'run COINZSPredictor for zero-shot video sequence labeling using label hidden state similarity thresholds']
```

Usage

```
{'create_Evaluator': 'create an Evaluator instance with a config object specifying metric and predictor class names', 'run_Evaluator_call': 'run the Evaluator callable to load merged prediction files and compute metrics from numpy outputs', 'run_Evaluator_evaluate': 'run the evaluate method to predict on a model and compute metrics from the dataloader', 'review_Evaluator_init': 'review the Evaluator constructor to understand how metric and predictor classes are dynamically loaded from config', 'summarize_Evaluator': 'summarize the Evaluator class that performs offline and online evaluation on downstream tasks using configurable metrics and predictors'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/evaluators/metric.py

Prompts

```
['create an Evaluator instance with a config object specifying metric and predictor class names', 'run the Evaluator callable to load merged prediction files and compute metrics from numpy outputs', 'run the evaluate method to predict on a model and compute metrics from the dataloader', 'review the Evaluator constructor to understand how metric and predictor classes are dynamically loaded from config', 'summarize the Evaluator class that performs offline and online evaluation on downstream tasks using configurable metrics and predictors', 'compute retrieval metrics R1, R5, R10, and median rank from a similarity matrix using RetrievalMetric', 'compute DiDeMo moment localization metrics rank1, rank5, and mean IoU from predicted video segments', 'compute NLG evaluation metrics including BLEU, METEOR, ROUGE, and CIDEr from NLGEval using NLGMetric', 'compute action recognition accuracy and recall splits from video embeddings and labels using ActionRecognitionMetric', 'compute per-task and average recall for cross-task predictions using CrossTaskMetric', 'run NLGPredictor to generate text predictions from an MMFusion model using a HuggingFace tokenizer', 'run RetrievalPredictor to compute pooled video and text embeddings for cross-modal retrieval scoring', 'run QAPredictor to predict video question answers by computing pooled video-text similarity scores', 'run CrossTaskPredictor to compute averaged sliding-window logits for video moment prediction tasks', 'run COINZSPredictor for zero-shot video sequence labeling using label hidden state similarity thresholds']
```

Usage

```
{'compute_retrieval_metrics': 'compute retrieval metrics R1, R5, R10, and median rank from a similarity matrix using RetrievalMetric', 'compute_didemo_metrics': 'compute DiDeMo moment localization metrics rank1, rank5, and mean IoU from predicted video segments', 'compute_nlg_metrics': 'compute NLG evaluation metrics including BLEU, METEOR, ROUGE, and CIDEr from NLGEval using NLGMetric', 'compute_action_recognition_metrics': 'compute action recognition accuracy and recall splits from video embeddings and labels using ActionRecognitionMetric', 'compute_cross_task_recall': 'compute per-task and average recall for cross-task predictions using CrossTaskMetric'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/evaluators/predictor.py

Prompts

```
['create an Evaluator instance with a config object specifying metric and predictor class names', 'run the Evaluator callable to load merged prediction files and compute metrics from numpy outputs', 'run the evaluate method to predict on a model and compute metrics from the dataloader', 'review the Evaluator constructor to understand how metric and predictor classes are dynamically loaded from config', 'summarize the Evaluator class that performs offline and online evaluation on downstream tasks using configurable metrics and predictors', 'compute retrieval metrics R1, R5, R10, and median rank from a similarity matrix using RetrievalMetric', 'compute DiDeMo moment localization metrics rank1, rank5, and mean IoU from predicted video segments', 'compute NLG evaluation metrics including BLEU, METEOR, ROUGE, and CIDEr from NLGEval using NLGMetric', 'compute action recognition accuracy and recall splits from video embeddings and labels using ActionRecognitionMetric', 'compute per-task and average recall for cross-task predictions using CrossTaskMetric', 'run NLGPredictor to generate text predictions from an MMFusion model using a HuggingFace tokenizer', 'run RetrievalPredictor to compute pooled video and text embeddings for cross-modal retrieval scoring', 'run QAPredictor to predict video question answers by computing pooled video-text similarity scores', 'run CrossTaskPredictor to compute averaged sliding-window logits for video moment prediction tasks', 'run COINZSPredictor for zero-shot video sequence labeling using label hidden state similarity thresholds']
```

Usage

```
{'run_NLGPredictor': 'run NLGPredictor to generate text predictions from an MMFusion model using a HuggingFace tokenizer', 'run_RetrievalPredictor': 'run RetrievalPredictor to compute pooled video and text embeddings for cross-modal retrieval scoring', 'run_QAPredictor': 'run QAPredictor to predict video question answers by computing pooled video-text similarity scores', 'run_CrossTaskPredictor': 'run CrossTaskPredictor to compute averaged sliding-window logits for video moment prediction tasks', 'run_COINZSPredictor': 'run COINZSPredictor for zero-shot video sequence labeling using label hidden state similarity thresholds'}
```

