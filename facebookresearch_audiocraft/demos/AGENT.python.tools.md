# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/demos/jasco_app.py

Prompts

```
['run the JASCO Gradio UI for text-to-music generation with chord and drum conditioning', 'run the JASCO demo with custom server port, auth, and share options via argparse', 'load a pretrained JASCO model by version such as jasco-chords-drums-400M or 1B', 'generate music from text descriptions, chords, melody matrix, and drum prompts using _do_predictions', 'parse a chord progression string like (C, 0.0), (D, 2.0) into a list of tuples', 'run the MAGNeT Gradio UI for text-to-music generation with configurable model and decoding parameters', 'run the MAGNeT Gradio app with username and password authentication on a custom port', 'load a pretrained MAGNeT model by version name such as facebook/magnet-small-10secs', 'generate audio from text prompts using the loaded MAGNeT model with temperature and top-p settings', 'batch predict audio outputs from multiple text descriptions using the magnet-small-10secs model', 'run the MusicGen Gradio UI app with optional auth and server port flags', 'run the batched MusicGen Gradio UI for HuggingFace Spaces with queue support', 'load a pretrained MusicGen model by version name such as musicgen-stereo-melody', 'generate music from text descriptions and optional melody audio using MusicGen', 'generate music using MultiBand Diffusion decoder for improved audio quality', 'run the MusicGen-Style Gradio UI app with optional auth, port, and share flags', 'run music generation from text and optional melody using the predict_full function', 'run batch audio predictions with text descriptions and melody conditioning via _do_predictions', 'load the MultiBandDiffusion model for enhanced audio decoding using load_diffusion']
```

Usage

```
{'run_jasco_gradio_ui': 'run the JASCO Gradio UI for text-to-music generation with chord and drum conditioning', 'run_jasco_with_args': 'run the JASCO demo with custom server port, auth, and share options via argparse', 'load_jasco_model': 'load a pretrained JASCO model by version such as jasco-chords-drums-400M or 1B', 'generate_music_with_predictions': 'generate music from text descriptions, chords, melody matrix, and drum prompts using _do_predictions', 'parse_chords_string': 'parse a chord progression string like (C, 0.0), (D, 2.0) into a list of tuples'}
```

## File: facebookresearch_audiocraft/demos/magnet_app.py

Prompts

```
['run the JASCO Gradio UI for text-to-music generation with chord and drum conditioning', 'run the JASCO demo with custom server port, auth, and share options via argparse', 'load a pretrained JASCO model by version such as jasco-chords-drums-400M or 1B', 'generate music from text descriptions, chords, melody matrix, and drum prompts using _do_predictions', 'parse a chord progression string like (C, 0.0), (D, 2.0) into a list of tuples', 'run the MAGNeT Gradio UI for text-to-music generation with configurable model and decoding parameters', 'run the MAGNeT Gradio app with username and password authentication on a custom port', 'load a pretrained MAGNeT model by version name such as facebook/magnet-small-10secs', 'generate audio from text prompts using the loaded MAGNeT model with temperature and top-p settings', 'batch predict audio outputs from multiple text descriptions using the magnet-small-10secs model', 'run the MusicGen Gradio UI app with optional auth and server port flags', 'run the batched MusicGen Gradio UI for HuggingFace Spaces with queue support', 'load a pretrained MusicGen model by version name such as musicgen-stereo-melody', 'generate music from text descriptions and optional melody audio using MusicGen', 'generate music using MultiBand Diffusion decoder for improved audio quality', 'run the MusicGen-Style Gradio UI app with optional auth, port, and share flags', 'run music generation from text and optional melody using the predict_full function', 'run batch audio predictions with text descriptions and melody conditioning via _do_predictions', 'load the MultiBandDiffusion model for enhanced audio decoding using load_diffusion']
```

Usage

```
{'run_magnet_gradio_app': 'run the MAGNeT Gradio UI for text-to-music generation with configurable model and decoding parameters', 'run_magnet_app_with_auth': 'run the MAGNeT Gradio app with username and password authentication on a custom port', 'load_model': 'load a pretrained MAGNeT model by version name such as facebook/magnet-small-10secs', 'do_predictions': 'generate audio from text prompts using the loaded MAGNeT model with temperature and top-p settings', 'predict_batched': 'batch predict audio outputs from multiple text descriptions using the magnet-small-10secs model'}
```

## File: facebookresearch_audiocraft/demos/musicgen_app.py

Prompts

```
['run the JASCO Gradio UI for text-to-music generation with chord and drum conditioning', 'run the JASCO demo with custom server port, auth, and share options via argparse', 'load a pretrained JASCO model by version such as jasco-chords-drums-400M or 1B', 'generate music from text descriptions, chords, melody matrix, and drum prompts using _do_predictions', 'parse a chord progression string like (C, 0.0), (D, 2.0) into a list of tuples', 'run the MAGNeT Gradio UI for text-to-music generation with configurable model and decoding parameters', 'run the MAGNeT Gradio app with username and password authentication on a custom port', 'load a pretrained MAGNeT model by version name such as facebook/magnet-small-10secs', 'generate audio from text prompts using the loaded MAGNeT model with temperature and top-p settings', 'batch predict audio outputs from multiple text descriptions using the magnet-small-10secs model', 'run the MusicGen Gradio UI app with optional auth and server port flags', 'run the batched MusicGen Gradio UI for HuggingFace Spaces with queue support', 'load a pretrained MusicGen model by version name such as musicgen-stereo-melody', 'generate music from text descriptions and optional melody audio using MusicGen', 'generate music using MultiBand Diffusion decoder for improved audio quality', 'run the MusicGen-Style Gradio UI app with optional auth, port, and share flags', 'run music generation from text and optional melody using the predict_full function', 'run batch audio predictions with text descriptions and melody conditioning via _do_predictions', 'load the MultiBandDiffusion model for enhanced audio decoding using load_diffusion']
```

Usage

```
{'run_musicgen_gradio_ui': 'run the MusicGen Gradio UI app with optional auth and server port flags', 'run_musicgen_batched_ui': 'run the batched MusicGen Gradio UI for HuggingFace Spaces with queue support', 'load_musicgen_model': 'load a pretrained MusicGen model by version name such as musicgen-stereo-melody', 'generate_music_with_melody': 'generate music from text descriptions and optional melody audio using MusicGen', 'generate_music_with_diffusion': 'generate music using MultiBand Diffusion decoder for improved audio quality'}
```

## File: facebookresearch_audiocraft/demos/musicgen_style_app.py

Prompts

```
['run the JASCO Gradio UI for text-to-music generation with chord and drum conditioning', 'run the JASCO demo with custom server port, auth, and share options via argparse', 'load a pretrained JASCO model by version such as jasco-chords-drums-400M or 1B', 'generate music from text descriptions, chords, melody matrix, and drum prompts using _do_predictions', 'parse a chord progression string like (C, 0.0), (D, 2.0) into a list of tuples', 'run the MAGNeT Gradio UI for text-to-music generation with configurable model and decoding parameters', 'run the MAGNeT Gradio app with username and password authentication on a custom port', 'load a pretrained MAGNeT model by version name such as facebook/magnet-small-10secs', 'generate audio from text prompts using the loaded MAGNeT model with temperature and top-p settings', 'batch predict audio outputs from multiple text descriptions using the magnet-small-10secs model', 'run the MusicGen Gradio UI app with optional auth and server port flags', 'run the batched MusicGen Gradio UI for HuggingFace Spaces with queue support', 'load a pretrained MusicGen model by version name such as musicgen-stereo-melody', 'generate music from text descriptions and optional melody audio using MusicGen', 'generate music using MultiBand Diffusion decoder for improved audio quality', 'run the MusicGen-Style Gradio UI app with optional auth, port, and share flags', 'run music generation from text and optional melody using the predict_full function', 'run batch audio predictions with text descriptions and melody conditioning via _do_predictions', 'load the MultiBandDiffusion model for enhanced audio decoding using load_diffusion']
```

Usage

```
{'run_musicgen_style_gradio_app': 'run the MusicGen-Style Gradio UI app with optional auth, port, and share flags', 'run_predict_full_music_generation': 'run music generation from text and optional melody using the predict_full function', 'run_do_predictions_batch': 'run batch audio predictions with text descriptions and melody conditioning via _do_predictions', 'load_musicgen_model': 'load a pretrained MusicGen model by version name using load_model', 'load_multiband_diffusion': 'load the MultiBandDiffusion model for enhanced audio decoding using load_diffusion'}
```

