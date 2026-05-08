# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/MMPT/mmpt/models/fairseqmmmodel.py

Prompts

```
["build a FairseqMMModel by wrapping a model built by the task's mmtask", 'create a forward pass through the wrapped mmmodel by forwarding all args and kwargs', 'upgrade the FairseqMMModel state dict by removing unused keys and adding new parameters', 'register the mmmodel architecture with fairseq using the mmarch dummy architecture function', 'review the FairseqMMModel class and its wrapper pattern for task-built models', 'build a pretrained MMPTModel with config, checkpoint, tokenizer, and aligner for end-to-end multimodal inference', 'run the MMPTModel forward pass with video frames and captions to compute pooled video and text embeddings', 'create a forward pass for MMFusionMFMMLM to perform masked frame modeling and masked language modeling on video-text pairs', 'build a shared encoder forward pass that pools video and text embeddings using the same mm_encoder backbone', 'run the MMFusionActionLocalization forward pass to compute logits between video sequences and pooled text embeddings', 'generate text captions from video features using the MMFusionNLG model with bos and eos token ids', 'run a forward pass through MMFusionNLG with caption tokens, video features, and masks to get logits', 'generate text sequences from video embeddings using MMBertForNLG with beam search or greedy decoding', 'run a forward pass through MMBertForNLG with input ids and video embeds to compute prediction scores', 'prepare and trim attention masks and token type ids for MMBertForNLG generation steps', 'build a multimodal BERT model that fuses text and video tokens with isolated attention masks', 'build a multimodal BERT model for token classification with a 779-class COIN classifier head', 'build a multimodal BERT model with shared MFM-MLM prediction head for masked frame and masked language modeling', 'build a multimodal BERT model with MTM head that predicts video logits on vocabulary and non-masked frames', 'review the MMBertModel class that extends BertModel with video token embeddings and multi-layer attention mask support']
```

Usage

```
{'build_FairseqMMModel': "build a FairseqMMModel by wrapping a model built by the task's mmtask", 'create_FairseqMMModel_forward': 'create a forward pass through the wrapped mmmodel by forwarding all args and kwargs', 'upgrade_FairseqMMModel_state_dict': 'upgrade the FairseqMMModel state dict by removing unused keys and adding new parameters', 'register_mmmodel_architecture': 'register the mmmodel architecture with fairseq using the mmarch dummy architecture function', 'review_FairseqMMModel': 'review the FairseqMMModel class and its wrapper pattern for task-built models'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/models/mmfusion.py

Prompts

```
["build a FairseqMMModel by wrapping a model built by the task's mmtask", 'create a forward pass through the wrapped mmmodel by forwarding all args and kwargs', 'upgrade the FairseqMMModel state dict by removing unused keys and adding new parameters', 'register the mmmodel architecture with fairseq using the mmarch dummy architecture function', 'review the FairseqMMModel class and its wrapper pattern for task-built models', 'build a pretrained MMPTModel with config, checkpoint, tokenizer, and aligner for end-to-end multimodal inference', 'run the MMPTModel forward pass with video frames and captions to compute pooled video and text embeddings', 'create a forward pass for MMFusionMFMMLM to perform masked frame modeling and masked language modeling on video-text pairs', 'build a shared encoder forward pass that pools video and text embeddings using the same mm_encoder backbone', 'run the MMFusionActionLocalization forward pass to compute logits between video sequences and pooled text embeddings', 'generate text captions from video features using the MMFusionNLG model with bos and eos token ids', 'run a forward pass through MMFusionNLG with caption tokens, video features, and masks to get logits', 'generate text sequences from video embeddings using MMBertForNLG with beam search or greedy decoding', 'run a forward pass through MMBertForNLG with input ids and video embeds to compute prediction scores', 'prepare and trim attention masks and token type ids for MMBertForNLG generation steps', 'build a multimodal BERT model that fuses text and video tokens with isolated attention masks', 'build a multimodal BERT model for token classification with a 779-class COIN classifier head', 'build a multimodal BERT model with shared MFM-MLM prediction head for masked frame and masked language modeling', 'build a multimodal BERT model with MTM head that predicts video logits on vocabulary and non-masked frames', 'review the MMBertModel class that extends BertModel with video token embeddings and multi-layer attention mask support']
```

Usage

```
{'build_MMPTModel_from_pretrained': 'build a pretrained MMPTModel with config, checkpoint, tokenizer, and aligner for end-to-end multimodal inference', 'run_MMPTModel_forward': 'run the MMPTModel forward pass with video frames and captions to compute pooled video and text embeddings', 'create_MMFusionMFMMLM_forward': 'create a forward pass for MMFusionMFMMLM to perform masked frame modeling and masked language modeling on video-text pairs', 'build_MMFusionShare_forward': 'build a shared encoder forward pass that pools video and text embeddings using the same mm_encoder backbone', 'run_MMFusionActionLocalization_forward': 'run the MMFusionActionLocalization forward pass to compute logits between video sequences and pooled text embeddings'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/models/mmfusionnlg.py

Prompts

```
["build a FairseqMMModel by wrapping a model built by the task's mmtask", 'create a forward pass through the wrapped mmmodel by forwarding all args and kwargs', 'upgrade the FairseqMMModel state dict by removing unused keys and adding new parameters', 'register the mmmodel architecture with fairseq using the mmarch dummy architecture function', 'review the FairseqMMModel class and its wrapper pattern for task-built models', 'build a pretrained MMPTModel with config, checkpoint, tokenizer, and aligner for end-to-end multimodal inference', 'run the MMPTModel forward pass with video frames and captions to compute pooled video and text embeddings', 'create a forward pass for MMFusionMFMMLM to perform masked frame modeling and masked language modeling on video-text pairs', 'build a shared encoder forward pass that pools video and text embeddings using the same mm_encoder backbone', 'run the MMFusionActionLocalization forward pass to compute logits between video sequences and pooled text embeddings', 'generate text captions from video features using the MMFusionNLG model with bos and eos token ids', 'run a forward pass through MMFusionNLG with caption tokens, video features, and masks to get logits', 'generate text sequences from video embeddings using MMBertForNLG with beam search or greedy decoding', 'run a forward pass through MMBertForNLG with input ids and video embeds to compute prediction scores', 'prepare and trim attention masks and token type ids for MMBertForNLG generation steps', 'build a multimodal BERT model that fuses text and video tokens with isolated attention masks', 'build a multimodal BERT model for token classification with a 779-class COIN classifier head', 'build a multimodal BERT model with shared MFM-MLM prediction head for masked frame and masked language modeling', 'build a multimodal BERT model with MTM head that predicts video logits on vocabulary and non-masked frames', 'review the MMBertModel class that extends BertModel with video token embeddings and multi-layer attention mask support']
```

Usage

```
{'generate_MMFusionNLG': 'generate text captions from video features using the MMFusionNLG model with bos and eos token ids', 'forward_MMFusionNLG': 'run a forward pass through MMFusionNLG with caption tokens, video features, and masks to get logits', 'generate_MMBertForNLG': 'generate text sequences from video embeddings using MMBertForNLG with beam search or greedy decoding', 'forward_MMBertForNLG': 'run a forward pass through MMBertForNLG with input ids and video embeds to compute prediction scores', 'prepare_inputs_for_generation_MMBertForNLG': 'prepare and trim attention masks and token type ids for MMBertForNLG generation steps'}
```

## File: facebookresearch_fairseq/examples/MMPT/mmpt/models/transformermodel.py

Prompts

```
["build a FairseqMMModel by wrapping a model built by the task's mmtask", 'create a forward pass through the wrapped mmmodel by forwarding all args and kwargs', 'upgrade the FairseqMMModel state dict by removing unused keys and adding new parameters', 'register the mmmodel architecture with fairseq using the mmarch dummy architecture function', 'review the FairseqMMModel class and its wrapper pattern for task-built models', 'build a pretrained MMPTModel with config, checkpoint, tokenizer, and aligner for end-to-end multimodal inference', 'run the MMPTModel forward pass with video frames and captions to compute pooled video and text embeddings', 'create a forward pass for MMFusionMFMMLM to perform masked frame modeling and masked language modeling on video-text pairs', 'build a shared encoder forward pass that pools video and text embeddings using the same mm_encoder backbone', 'run the MMFusionActionLocalization forward pass to compute logits between video sequences and pooled text embeddings', 'generate text captions from video features using the MMFusionNLG model with bos and eos token ids', 'run a forward pass through MMFusionNLG with caption tokens, video features, and masks to get logits', 'generate text sequences from video embeddings using MMBertForNLG with beam search or greedy decoding', 'run a forward pass through MMBertForNLG with input ids and video embeds to compute prediction scores', 'prepare and trim attention masks and token type ids for MMBertForNLG generation steps', 'build a multimodal BERT model that fuses text and video tokens with isolated attention masks', 'build a multimodal BERT model for token classification with a 779-class COIN classifier head', 'build a multimodal BERT model with shared MFM-MLM prediction head for masked frame and masked language modeling', 'build a multimodal BERT model with MTM head that predicts video logits on vocabulary and non-masked frames', 'review the MMBertModel class that extends BertModel with video token embeddings and multi-layer attention mask support']
```

Usage

```
{'build_MMBertForJoint': 'build a multimodal BERT model that fuses text and video tokens with isolated attention masks', 'build_MMBertForTokenClassification': 'build a multimodal BERT model for token classification with a 779-class COIN classifier head', 'build_MMBertForMFMMLM': 'build a multimodal BERT model with shared MFM-MLM prediction head for masked frame and masked language modeling', 'build_MMBertForMTM': 'build a multimodal BERT model with MTM head that predicts video logits on vocabulary and non-masked frames', 'review_MMBertModel': 'review the MMBertModel class that extends BertModel with video token embeddings and multi-layer attention mask support'}
```

