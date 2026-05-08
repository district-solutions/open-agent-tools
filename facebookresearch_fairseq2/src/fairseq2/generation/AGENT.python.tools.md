# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/generation/generator.py

Prompts

```
['implement a subclass of SequenceGenerator that generates sequences from prompt tensors using a CausalLM model', 'implement a subclass of Seq2SeqGenerator that translates source sequences to target sequences using a Seq2SeqModel', 'use SequenceGeneratorOutput to access hypotheses and generation counters after calling a sequence generator', 'create a StepHook callable that inspects generated sequences and step scores after each generation step', 'handle SequenceGenerationError exceptions that occur when the model produces NaN probabilities during generation', 'create a TextTranslator to translate source text to a target language using a Seq2SeqGenerator', 'batch translate a list of source texts using TextTranslator and get translated outputs', 'create a TextCompleter to complete text prompts using a SequenceGenerator and tokenizer', 'batch complete a list of text prompts using TextCompleter and get completed outputs', 'convert a source sequence tensor to text using SequenceToTextConverter with a generator']
```

Usage

```
{'implement_SequenceGenerator_subclass': 'implement a subclass of SequenceGenerator that generates sequences from prompt tensors using a CausalLM model', 'implement_Seq2SeqGenerator_subclass': 'implement a subclass of Seq2SeqGenerator that translates source sequences to target sequences using a Seq2SeqModel', 'use_SequenceGeneratorOutput': 'use SequenceGeneratorOutput to access hypotheses and generation counters after calling a sequence generator', 'create_StepHook': 'create a StepHook callable that inspects generated sequences and step scores after each generation step', 'handle_SequenceGenerationError': 'handle SequenceGenerationError exceptions that occur when the model produces NaN probabilities during generation'}
```

## File: facebookresearch_fairseq2/src/fairseq2/generation/text.py

Prompts

```
['implement a subclass of SequenceGenerator that generates sequences from prompt tensors using a CausalLM model', 'implement a subclass of Seq2SeqGenerator that translates source sequences to target sequences using a Seq2SeqModel', 'use SequenceGeneratorOutput to access hypotheses and generation counters after calling a sequence generator', 'create a StepHook callable that inspects generated sequences and step scores after each generation step', 'handle SequenceGenerationError exceptions that occur when the model produces NaN probabilities during generation', 'create a TextTranslator to translate source text to a target language using a Seq2SeqGenerator', 'batch translate a list of source texts using TextTranslator and get translated outputs', 'create a TextCompleter to complete text prompts using a SequenceGenerator and tokenizer', 'batch complete a list of text prompts using TextCompleter and get completed outputs', 'convert a source sequence tensor to text using SequenceToTextConverter with a generator']
```

Usage

```
{'create_text_translator': 'create a TextTranslator to translate source text to a target language using a Seq2SeqGenerator', 'batch_translate_texts': 'batch translate a list of source texts using TextTranslator and get translated outputs', 'create_text_completer': 'create a TextCompleter to complete text prompts using a SequenceGenerator and tokenizer', 'batch_complete_prompts': 'batch complete a list of text prompts using TextCompleter and get completed outputs', 'convert_sequence_to_text': 'convert a source sequence tensor to text using SequenceToTextConverter with a generator'}
```

