# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/spectrogram_diffusion/continuous_encoder.py

Prompts

```
['create a SpectrogramContEncoder instance with T5-based hyperparameters for spectrogram diffusion encoding', 'run the forward pass of SpectrogramContEncoder on encoder inputs with an attention mask', 'build a T5Config to configure the number of heads, d_kv, and feed-forward projection for the encoder', 'review the terminal relative positional encoding logic that rolls positions by sequence length', 'test the get_extended_attention_mask method inherited from ModuleUtilsMixin for attention mask expansion', 'build a python module that uses MidiProcessor to convert a MIDI file into tokenized input sequences', 'create a Codec to encode and decode MIDI events like pitch, velocity, and program into integer indices', 'run note_sequence_to_onsets_and_offsets_and_programs to extract onset times and note events from a NoteSequence', 'test the Tokenizer encode method to convert token IDs into padded sequences with EOS and PAD tokens', 'refactor the run_length_encode_shifts_fn to combine consecutive shift events and remove redundant state change tokens', 'create a SpectrogramNotesEncoder instance with vocab size, model dimensions, and T5 block layers', 'run a forward pass through the SpectrogramNotesEncoder with input tokens and attention mask', 'build a token embedding layer using nn.Embedding with the specified vocab size and model dimension', 'review the frozen position encoding embedding layer that adds positional information to token embeddings', 'test the stacked T5Block encoder layers that process token embeddings with attention masks', 'run the SpectrogramDiffusionPipeline to generate audio from MIDI input tokens using from_pretrained', 'build a SpectrogramDiffusionPipeline instance with notes_encoder, continuous_encoder, decoder, scheduler, and melgan components', 'test the scale_features method to linearly scale features to the network output range', 'test the scale_to_features method to invert scale network outputs back to features range', 'review the encode and decode methods that process input tokens through notes and continuous encoders']
```

Usage

```
{'create_SpectrogramContEncoder': 'create a SpectrogramContEncoder instance with T5-based hyperparameters for spectrogram diffusion encoding', 'run_forward_SpectrogramContEncoder': 'run the forward pass of SpectrogramContEncoder on encoder inputs with an attention mask', 'build_T5Config_encoder': 'build a T5Config to configure the number of heads, d_kv, and feed-forward projection for the encoder', 'review_positional_encoding': 'review the terminal relative positional encoding logic that rolls positions by sequence length', 'test_get_extended_attention_mask': 'test the get_extended_attention_mask method inherited from ModuleUtilsMixin for attention mask expansion'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/spectrogram_diffusion/midi_utils.py

Prompts

```
['create a SpectrogramContEncoder instance with T5-based hyperparameters for spectrogram diffusion encoding', 'run the forward pass of SpectrogramContEncoder on encoder inputs with an attention mask', 'build a T5Config to configure the number of heads, d_kv, and feed-forward projection for the encoder', 'review the terminal relative positional encoding logic that rolls positions by sequence length', 'test the get_extended_attention_mask method inherited from ModuleUtilsMixin for attention mask expansion', 'build a python module that uses MidiProcessor to convert a MIDI file into tokenized input sequences', 'create a Codec to encode and decode MIDI events like pitch, velocity, and program into integer indices', 'run note_sequence_to_onsets_and_offsets_and_programs to extract onset times and note events from a NoteSequence', 'test the Tokenizer encode method to convert token IDs into padded sequences with EOS and PAD tokens', 'refactor the run_length_encode_shifts_fn to combine consecutive shift events and remove redundant state change tokens', 'create a SpectrogramNotesEncoder instance with vocab size, model dimensions, and T5 block layers', 'run a forward pass through the SpectrogramNotesEncoder with input tokens and attention mask', 'build a token embedding layer using nn.Embedding with the specified vocab size and model dimension', 'review the frozen position encoding embedding layer that adds positional information to token embeddings', 'test the stacked T5Block encoder layers that process token embeddings with attention masks', 'run the SpectrogramDiffusionPipeline to generate audio from MIDI input tokens using from_pretrained', 'build a SpectrogramDiffusionPipeline instance with notes_encoder, continuous_encoder, decoder, scheduler, and melgan components', 'test the scale_features method to linearly scale features to the network output range', 'test the scale_to_features method to invert scale network outputs back to features range', 'review the encode and decode methods that process input tokens through notes and continuous encoders']
```

Usage

```
{'build_MidiProcessor': 'build a python module that uses MidiProcessor to convert a MIDI file into tokenized input sequences', 'create_Codec_encode_decode': 'create a Codec to encode and decode MIDI events like pitch, velocity, and program into integer indices', 'run_note_sequence_to_onsets': 'run note_sequence_to_onsets_and_offsets_and_programs to extract onset times and note events from a NoteSequence', 'test_Tokenizer_encode': 'test the Tokenizer encode method to convert token IDs into padded sequences with EOS and PAD tokens', 'refactor_run_length_encode_shifts': 'refactor the run_length_encode_shifts_fn to combine consecutive shift events and remove redundant state change tokens'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/spectrogram_diffusion/notes_encoder.py

Prompts

```
['create a SpectrogramContEncoder instance with T5-based hyperparameters for spectrogram diffusion encoding', 'run the forward pass of SpectrogramContEncoder on encoder inputs with an attention mask', 'build a T5Config to configure the number of heads, d_kv, and feed-forward projection for the encoder', 'review the terminal relative positional encoding logic that rolls positions by sequence length', 'test the get_extended_attention_mask method inherited from ModuleUtilsMixin for attention mask expansion', 'build a python module that uses MidiProcessor to convert a MIDI file into tokenized input sequences', 'create a Codec to encode and decode MIDI events like pitch, velocity, and program into integer indices', 'run note_sequence_to_onsets_and_offsets_and_programs to extract onset times and note events from a NoteSequence', 'test the Tokenizer encode method to convert token IDs into padded sequences with EOS and PAD tokens', 'refactor the run_length_encode_shifts_fn to combine consecutive shift events and remove redundant state change tokens', 'create a SpectrogramNotesEncoder instance with vocab size, model dimensions, and T5 block layers', 'run a forward pass through the SpectrogramNotesEncoder with input tokens and attention mask', 'build a token embedding layer using nn.Embedding with the specified vocab size and model dimension', 'review the frozen position encoding embedding layer that adds positional information to token embeddings', 'test the stacked T5Block encoder layers that process token embeddings with attention masks', 'run the SpectrogramDiffusionPipeline to generate audio from MIDI input tokens using from_pretrained', 'build a SpectrogramDiffusionPipeline instance with notes_encoder, continuous_encoder, decoder, scheduler, and melgan components', 'test the scale_features method to linearly scale features to the network output range', 'test the scale_to_features method to invert scale network outputs back to features range', 'review the encode and decode methods that process input tokens through notes and continuous encoders']
```

Usage

```
{'create_SpectrogramNotesEncoder': 'create a SpectrogramNotesEncoder instance with vocab size, model dimensions, and T5 block layers', 'run_forward_pass': 'run a forward pass through the SpectrogramNotesEncoder with input tokens and attention mask', 'build_token_embedder': 'build a token embedding layer using nn.Embedding with the specified vocab size and model dimension', 'review_position_encoding': 'review the frozen position encoding embedding layer that adds positional information to token embeddings', 'test_T5Block_encoders': 'test the stacked T5Block encoder layers that process token embeddings with attention masks'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/deprecated/spectrogram_diffusion/pipeline_spectrogram_diffusion.py

Prompts

```
['create a SpectrogramContEncoder instance with T5-based hyperparameters for spectrogram diffusion encoding', 'run the forward pass of SpectrogramContEncoder on encoder inputs with an attention mask', 'build a T5Config to configure the number of heads, d_kv, and feed-forward projection for the encoder', 'review the terminal relative positional encoding logic that rolls positions by sequence length', 'test the get_extended_attention_mask method inherited from ModuleUtilsMixin for attention mask expansion', 'build a python module that uses MidiProcessor to convert a MIDI file into tokenized input sequences', 'create a Codec to encode and decode MIDI events like pitch, velocity, and program into integer indices', 'run note_sequence_to_onsets_and_offsets_and_programs to extract onset times and note events from a NoteSequence', 'test the Tokenizer encode method to convert token IDs into padded sequences with EOS and PAD tokens', 'refactor the run_length_encode_shifts_fn to combine consecutive shift events and remove redundant state change tokens', 'create a SpectrogramNotesEncoder instance with vocab size, model dimensions, and T5 block layers', 'run a forward pass through the SpectrogramNotesEncoder with input tokens and attention mask', 'build a token embedding layer using nn.Embedding with the specified vocab size and model dimension', 'review the frozen position encoding embedding layer that adds positional information to token embeddings', 'test the stacked T5Block encoder layers that process token embeddings with attention masks', 'run the SpectrogramDiffusionPipeline to generate audio from MIDI input tokens using from_pretrained', 'build a SpectrogramDiffusionPipeline instance with notes_encoder, continuous_encoder, decoder, scheduler, and melgan components', 'test the scale_features method to linearly scale features to the network output range', 'test the scale_to_features method to invert scale network outputs back to features range', 'review the encode and decode methods that process input tokens through notes and continuous encoders']
```

Usage

```
{'run_spectrogram_diffusion_pipeline': 'run the SpectrogramDiffusionPipeline to generate audio from MIDI input tokens using from_pretrained', 'build_spectrogram_diffusion_pipeline': 'build a SpectrogramDiffusionPipeline instance with notes_encoder, continuous_encoder, decoder, scheduler, and melgan components', 'test_scale_features': 'test the scale_features method to linearly scale features to the network output range', 'test_scale_to_features': 'test the scale_to_features method to invert scale network outputs back to features range', 'review_encode_decode': 'review the encode and decode methods that process input tokens through notes and continuous encoders'}
```

