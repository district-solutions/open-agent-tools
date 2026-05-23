# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/ingest/enrichment/socratic/socratic.py

Prompts

```
['run the zeroshot_classifier function on an image to get top-10 class predictions from multiple classifiers', 'build a CLIP-based zero-shot classifier from a list of text labels and a prompt template', 'generate an image captioning prompt from classifier outputs including image type, people count, and objects', 'load the CLIP ViT-L/14 model and all precomputed zero-shot classifier weights into a model dictionary', 'sort candidate captions by their similarity scores against an image feature vector using CLIP']
```

Usage

```
{'run_zeroshot_classifier': 'run the zeroshot_classifier function on an image to get top-10 class predictions from multiple classifiers', 'build_simple_classifier': 'build a CLIP-based zero-shot classifier from a list of text labels and a prompt template', 'generate_prompt': 'generate an image captioning prompt from classifier outputs including image type, people count, and objects', 'load_models': 'load the CLIP ViT-L/14 model and all precomputed zero-shot classifier weights into a model dictionary', 'sorting_texts': 'sort candidate captions by their similarity scores against an image feature vector using CLIP'}
```

