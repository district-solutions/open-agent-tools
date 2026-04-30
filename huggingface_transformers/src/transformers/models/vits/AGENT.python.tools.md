# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vits/configuration_vits.py

Prompts

```
['create a VitsConfig instance with default hyperparameters for the facebook/mms-tts-eng model', 'create a VitsConfig instance configured for a multi-speaker VITS text-to-speech model', 'create a VitsConfig instance with custom upsample_rates and upsample_kernel_sizes for the HiFi-GAN upsampling network', 'create a VitsConfig instance with stochastic duration prediction enabled and custom noise_scale for speech variation', 'review the VitsConfig.validate_architecture method that validates upsample_kernel_sizes and upsample_rates lengths match', 'convert a VITS checkpoint from fairseq or MMS-TTS format to a Hugging Face VitsModel checkpoint', 'convert a Facebook MMS-TTS checkpoint for a specific language to Hugging Face VitsModel format', 'convert a VITS checkpoint using a custom vocab.txt file and output to a specified folder', 'convert a VITS checkpoint specifying the number of speakers and sampling rate', 'convert a VITS checkpoint and push the resulting model and tokenizer to a Hugging Face hub repo', 'run the VITS model to synthesize speech from text input and speaker embeddings', 'create a VITS text encoder that transforms input token IDs into latent prior distributions', 'build a Hi-Fi GAN decoder that converts spectrograms into speech waveforms', 'test the stochastic duration predictor that models speech timing with normalizing flows', 'review the residual coupling block that transforms latent variables in the flow model', 'create a VitsTokenizer instance from a JSON vocab file with phonemization and normalization enabled', 'test the VitsTokenizer.normalize_text method to lowercase text while preserving special tokens', 'review the VitsTokenizer.prepare_for_tokenization method that normalizes, romanizes, and phonemizes input text', 'summarize the VitsTokenizer._tokenize method that splits text into character tokens with blank token insertion', 'build a call to VitsTokenizer.save_vocabulary to write the encoder vocab as sorted JSON to a directory']
```

Usage

```
{'create_vitsconfig_default': 'create a VitsConfig instance with default hyperparameters for the facebook/mms-tts-eng model', 'create_vitsconfig_multispeaker': 'create a VitsConfig instance configured for a multi-speaker VITS text-to-speech model', 'create_vitsconfig_custom_upsample': 'create a VitsConfig instance with custom upsample_rates and upsample_kernel_sizes for the HiFi-GAN upsampling network', 'create_vitsconfig_stochastic_duration': 'create a VitsConfig instance with stochastic duration prediction enabled and custom noise_scale for speech variation', 'review_vitsconfig_validate_architecture': 'review the VitsConfig.validate_architecture method that validates upsample_kernel_sizes and upsample_rates lengths match'}
```

## File: huggingface_transformers/src/transformers/models/vits/convert_original_checkpoint.py

Prompts

```
['create a VitsConfig instance with default hyperparameters for the facebook/mms-tts-eng model', 'create a VitsConfig instance configured for a multi-speaker VITS text-to-speech model', 'create a VitsConfig instance with custom upsample_rates and upsample_kernel_sizes for the HiFi-GAN upsampling network', 'create a VitsConfig instance with stochastic duration prediction enabled and custom noise_scale for speech variation', 'review the VitsConfig.validate_architecture method that validates upsample_kernel_sizes and upsample_rates lengths match', 'convert a VITS checkpoint from fairseq or MMS-TTS format to a Hugging Face VitsModel checkpoint', 'convert a Facebook MMS-TTS checkpoint for a specific language to Hugging Face VitsModel format', 'convert a VITS checkpoint using a custom vocab.txt file and output to a specified folder', 'convert a VITS checkpoint specifying the number of speakers and sampling rate', 'convert a VITS checkpoint and push the resulting model and tokenizer to a Hugging Face hub repo', 'run the VITS model to synthesize speech from text input and speaker embeddings', 'create a VITS text encoder that transforms input token IDs into latent prior distributions', 'build a Hi-Fi GAN decoder that converts spectrograms into speech waveforms', 'test the stochastic duration predictor that models speech timing with normalizing flows', 'review the residual coupling block that transforms latent variables in the flow model', 'create a VitsTokenizer instance from a JSON vocab file with phonemization and normalization enabled', 'test the VitsTokenizer.normalize_text method to lowercase text while preserving special tokens', 'review the VitsTokenizer.prepare_for_tokenization method that normalizes, romanizes, and phonemizes input text', 'summarize the VitsTokenizer._tokenize method that splits text into character tokens with blank token insertion', 'build a call to VitsTokenizer.save_vocabulary to write the encoder vocab as sorted JSON to a directory']
```

Usage

```
{'convert_checkpoint': 'convert a VITS checkpoint from fairseq or MMS-TTS format to a Hugging Face VitsModel checkpoint', 'convert_mms_tts_checkpoint': 'convert a Facebook MMS-TTS checkpoint for a specific language to Hugging Face VitsModel format', 'convert_checkpoint_with_custom_vocab': 'convert a VITS checkpoint using a custom vocab.txt file and output to a specified folder', 'convert_checkpoint_with_speakers': 'convert a VITS checkpoint specifying the number of speakers and sampling rate', 'convert_checkpoint_push_to_hub': 'convert a VITS checkpoint and push the resulting model and tokenizer to a Hugging Face hub repo'}
```

## File: huggingface_transformers/src/transformers/models/vits/modeling_vits.py

Prompts

```
['create a VitsConfig instance with default hyperparameters for the facebook/mms-tts-eng model', 'create a VitsConfig instance configured for a multi-speaker VITS text-to-speech model', 'create a VitsConfig instance with custom upsample_rates and upsample_kernel_sizes for the HiFi-GAN upsampling network', 'create a VitsConfig instance with stochastic duration prediction enabled and custom noise_scale for speech variation', 'review the VitsConfig.validate_architecture method that validates upsample_kernel_sizes and upsample_rates lengths match', 'convert a VITS checkpoint from fairseq or MMS-TTS format to a Hugging Face VitsModel checkpoint', 'convert a Facebook MMS-TTS checkpoint for a specific language to Hugging Face VitsModel format', 'convert a VITS checkpoint using a custom vocab.txt file and output to a specified folder', 'convert a VITS checkpoint specifying the number of speakers and sampling rate', 'convert a VITS checkpoint and push the resulting model and tokenizer to a Hugging Face hub repo', 'run the VITS model to synthesize speech from text input and speaker embeddings', 'create a VITS text encoder that transforms input token IDs into latent prior distributions', 'build a Hi-Fi GAN decoder that converts spectrograms into speech waveforms', 'test the stochastic duration predictor that models speech timing with normalizing flows', 'review the residual coupling block that transforms latent variables in the flow model', 'create a VitsTokenizer instance from a JSON vocab file with phonemization and normalization enabled', 'test the VitsTokenizer.normalize_text method to lowercase text while preserving special tokens', 'review the VitsTokenizer.prepare_for_tokenization method that normalizes, romanizes, and phonemizes input text', 'summarize the VitsTokenizer._tokenize method that splits text into character tokens with blank token insertion', 'build a call to VitsTokenizer.save_vocabulary to write the encoder vocab as sorted JSON to a directory']
```

Usage

```
{'run_vits_text_to_speech': 'run the VITS model to synthesize speech from text input and speaker embeddings', 'create_vits_text_encoder': 'create a VITS text encoder that transforms input token IDs into latent prior distributions', 'build_vits_hifi_gan_decoder': 'build a Hi-Fi GAN decoder that converts spectrograms into speech waveforms', 'test_vits_stochastic_duration_predictor': 'test the stochastic duration predictor that models speech timing with normalizing flows', 'review_vits_residual_coupling_block': 'review the residual coupling block that transforms latent variables in the flow model'}
```

## File: huggingface_transformers/src/transformers/models/vits/tokenization_vits.py

Prompts

```
['create a VitsConfig instance with default hyperparameters for the facebook/mms-tts-eng model', 'create a VitsConfig instance configured for a multi-speaker VITS text-to-speech model', 'create a VitsConfig instance with custom upsample_rates and upsample_kernel_sizes for the HiFi-GAN upsampling network', 'create a VitsConfig instance with stochastic duration prediction enabled and custom noise_scale for speech variation', 'review the VitsConfig.validate_architecture method that validates upsample_kernel_sizes and upsample_rates lengths match', 'convert a VITS checkpoint from fairseq or MMS-TTS format to a Hugging Face VitsModel checkpoint', 'convert a Facebook MMS-TTS checkpoint for a specific language to Hugging Face VitsModel format', 'convert a VITS checkpoint using a custom vocab.txt file and output to a specified folder', 'convert a VITS checkpoint specifying the number of speakers and sampling rate', 'convert a VITS checkpoint and push the resulting model and tokenizer to a Hugging Face hub repo', 'run the VITS model to synthesize speech from text input and speaker embeddings', 'create a VITS text encoder that transforms input token IDs into latent prior distributions', 'build a Hi-Fi GAN decoder that converts spectrograms into speech waveforms', 'test the stochastic duration predictor that models speech timing with normalizing flows', 'review the residual coupling block that transforms latent variables in the flow model', 'create a VitsTokenizer instance from a JSON vocab file with phonemization and normalization enabled', 'test the VitsTokenizer.normalize_text method to lowercase text while preserving special tokens', 'review the VitsTokenizer.prepare_for_tokenization method that normalizes, romanizes, and phonemizes input text', 'summarize the VitsTokenizer._tokenize method that splits text into character tokens with blank token insertion', 'build a call to VitsTokenizer.save_vocabulary to write the encoder vocab as sorted JSON to a directory']
```

Usage

```
{'create_vits_tokenizer': 'create a VitsTokenizer instance from a JSON vocab file with phonemization and normalization enabled', 'test_normalize_text': 'test the VitsTokenizer.normalize_text method to lowercase text while preserving special tokens', 'review_prepare_for_tokenization': 'review the VitsTokenizer.prepare_for_tokenization method that normalizes, romanizes, and phonemizes input text', 'summarize__tokenize': 'summarize the VitsTokenizer._tokenize method that splits text into character tokens with blank token insertion', 'build_save_vocabulary': 'build a call to VitsTokenizer.save_vocabulary to write the encoder vocab as sorted JSON to a directory'}
```

