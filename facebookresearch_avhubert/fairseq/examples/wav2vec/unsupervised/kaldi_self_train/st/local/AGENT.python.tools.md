# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/unsupervised/kaldi_self_train/st/local/prepare_data_from_w2v.py

Prompts

```
['run a python script to convert wav2vec features to Kaldi ark and scp format from a numpy feature file', 'run a python script to convert wav2vec features and labels to Kaldi format with utterance to speaker mappings', 'run a python script to generate utt2spk and spk2utt files from wav2vec feature data for Kaldi', 'run a python script to write compressed Kaldi ark files from wav2vec numpy features using copy-feats', 'run a python script to extract labels from wav2vec data and write them as Kaldi text files', 'run the unsupervised metric selection tool with reference and hypothesis transcript files', 'compute word error rate between reference and hypothesis transcripts using edit distance', 'compute language model perplexity for hypothesis transcripts using a kenlm scoring function', 'load a transcript file into a uid-to-transcript dictionary mapping utterance IDs to text', 'load a phoneme lexicon file into a word-to-phonemes dictionary mapping']
```

Usage

```
{'prepare_w2v_features_to_kaldi': 'run a python script to convert wav2vec features to Kaldi ark and scp format from a numpy feature file', 'prepare_w2v_with_labels': 'run a python script to convert wav2vec features and labels to Kaldi format with utterance to speaker mappings', 'prepare_w2v_utt2spk': 'run a python script to generate utt2spk and spk2utt files from wav2vec feature data for Kaldi', 'prepare_w2v_compressed_ark': 'run a python script to write compressed Kaldi ark files from wav2vec numpy features using copy-feats', 'prepare_w2v_text_from_labels': 'run a python script to extract labels from wav2vec data and write them as Kaldi text files'}
```

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/unsupervised/kaldi_self_train/st/local/unsup_select.py

Prompts

```
['run a python script to convert wav2vec features to Kaldi ark and scp format from a numpy feature file', 'run a python script to convert wav2vec features and labels to Kaldi format with utterance to speaker mappings', 'run a python script to generate utt2spk and spk2utt files from wav2vec feature data for Kaldi', 'run a python script to write compressed Kaldi ark files from wav2vec numpy features using copy-feats', 'run a python script to extract labels from wav2vec data and write them as Kaldi text files', 'run the unsupervised metric selection tool with reference and hypothesis transcript files', 'compute word error rate between reference and hypothesis transcripts using edit distance', 'compute language model perplexity for hypothesis transcripts using a kenlm scoring function', 'load a transcript file into a uid-to-transcript dictionary mapping utterance IDs to text', 'load a phoneme lexicon file into a word-to-phonemes dictionary mapping']
```

Usage

```
{'run_unsup_select_cli': 'run the unsupervised metric selection tool with reference and hypothesis transcript files', 'compute_wer_function': 'compute word error rate between reference and hypothesis transcripts using edit distance', 'compute_lm_ppl_function': 'compute language model perplexity for hypothesis transcripts using a kenlm scoring function', 'load_tra_function': 'load a transcript file into a uid-to-transcript dictionary mapping utterance IDs to text', 'load_lex_function': 'load a phoneme lexicon file into a word-to-phonemes dictionary mapping'}
```

