# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/wav2vec/unsupervised/kaldi_self_train/st/local/prepare_data_from_w2v.py

Prompts

```
['run the script to convert wav2vec features to Kaldi format for a given data split', 'run get_parser to create an argparse parser with w2v_dir, tar_root, split, and label arguments', 'run main to read wav2vec .npy features and write Kaldi .ark and .scp files', 'review the main function that converts wav2vec features to Kaldi format with utt2spk and spk2utt files', 'summarize the script that converts wav2vec numpy features to Kaldi ark scp format', 'run the unsupervised metric tool to score decoded pseudo labels against reference transcripts using WER and LM perplexity', 'load a Kaldi-style transcript file into a dictionary mapping utterance IDs to text', 'load a word-to-phoneme lexicon file into a dictionary mapping words to phoneme lists', 'compute word error rate between reference and hypothesis transcripts with optional phonemization via G2P or lexicon', 'compute language model perplexity over hypothesis transcripts using a KenLM scoring function']
```

Usage

```
{'run_prepare_data_from_w2v': 'run the script to convert wav2vec features to Kaldi format for a given data split', 'run_get_parser': 'run get_parser to create an argparse parser with w2v_dir, tar_root, split, and label arguments', 'run_main': 'run main to read wav2vec .npy features and write Kaldi .ark and .scp files', 'review_main': 'review the main function that converts wav2vec features to Kaldi format with utt2spk and spk2utt files', 'summarize_prepare_data_from_w2v': 'summarize the script that converts wav2vec numpy features to Kaldi ark scp format'}
```

## File: facebookresearch_fairseq/examples/wav2vec/unsupervised/kaldi_self_train/st/local/unsup_select.py

Prompts

```
['run the script to convert wav2vec features to Kaldi format for a given data split', 'run get_parser to create an argparse parser with w2v_dir, tar_root, split, and label arguments', 'run main to read wav2vec .npy features and write Kaldi .ark and .scp files', 'review the main function that converts wav2vec features to Kaldi format with utt2spk and spk2utt files', 'summarize the script that converts wav2vec numpy features to Kaldi ark scp format', 'run the unsupervised metric tool to score decoded pseudo labels against reference transcripts using WER and LM perplexity', 'load a Kaldi-style transcript file into a dictionary mapping utterance IDs to text', 'load a word-to-phoneme lexicon file into a dictionary mapping words to phoneme lists', 'compute word error rate between reference and hypothesis transcripts with optional phonemization via G2P or lexicon', 'compute language model perplexity over hypothesis transcripts using a KenLM scoring function']
```

Usage

```
{'run_unsupervised_selection': 'run the unsupervised metric tool to score decoded pseudo labels against reference transcripts using WER and LM perplexity', 'load_tra_transcripts': 'load a Kaldi-style transcript file into a dictionary mapping utterance IDs to text', 'load_lex_lexicon': 'load a word-to-phoneme lexicon file into a dictionary mapping words to phoneme lists', 'compute_wer': 'compute word error rate between reference and hypothesis transcripts with optional phonemization via G2P or lexicon', 'compute_lm_ppl': 'compute language model perplexity over hypothesis transcripts using a KenLM scoring function'}
```

