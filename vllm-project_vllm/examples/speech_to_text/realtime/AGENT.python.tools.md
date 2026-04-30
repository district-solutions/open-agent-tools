# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/speech_to_text/realtime/openai_realtime_client.py

Prompts

```
['run the realtime transcription client against a vLLM server with an audio file', 'transcribe an audio file by streaming PCM16 chunks over a WebSocket connection to vLLM', 'convert an audio file to base64-encoded PCM16 at 16kHz mono using load_audio', 'review the realtime_transcribe async function that handles WebSocket session and streaming transcription', 'refactor the audio_to_pcm16_base64 function to support additional audio formats or sample rates', 'run the realtime speech transcription Gradio client connected to a vLLM server via WebSocket', 'start the transcription service by launching a WebSocket connection in a background thread', 'stop the transcription service and return the accumulated transcription text', 'process incoming audio by converting to mono, normalizing, resampling to 16kHz, and queueing PCM16 base64 chunks', 'handle WebSocket audio streaming by sending audio chunks and receiving transcription delta updates concurrently']
```

Usage

```
{'run_realtime_transcription': 'run the realtime transcription client against a vLLM server with an audio file', 'transcribe_audio_websocket': 'transcribe an audio file by streaming PCM16 chunks over a WebSocket connection to vLLM', 'convert_audio_to_pcm16_base64': 'convert an audio file to base64-encoded PCM16 at 16kHz mono using load_audio', 'review_realtime_transcribe': 'review the realtime_transcribe async function that handles WebSocket session and streaming transcription', 'refactor_audio_to_pcm16_base64': 'refactor the audio_to_pcm16_base64 function to support additional audio formats or sample rates'}
```

## File: vllm-project_vllm/examples/speech_to_text/realtime/openai_realtime_microphone_client.py

Prompts

```
['run the realtime transcription client against a vLLM server with an audio file', 'transcribe an audio file by streaming PCM16 chunks over a WebSocket connection to vLLM', 'convert an audio file to base64-encoded PCM16 at 16kHz mono using load_audio', 'review the realtime_transcribe async function that handles WebSocket session and streaming transcription', 'refactor the audio_to_pcm16_base64 function to support additional audio formats or sample rates', 'run the realtime speech transcription Gradio client connected to a vLLM server via WebSocket', 'start the transcription service by launching a WebSocket connection in a background thread', 'stop the transcription service and return the accumulated transcription text', 'process incoming audio by converting to mono, normalizing, resampling to 16kHz, and queueing PCM16 base64 chunks', 'handle WebSocket audio streaming by sending audio chunks and receiving transcription delta updates concurrently']
```

Usage

```
{'run_realtime_transcription_client': 'run the realtime speech transcription Gradio client connected to a vLLM server via WebSocket', 'start_recording_transcription': 'start the transcription service by launching a WebSocket connection in a background thread', 'stop_recording_transcription': 'stop the transcription service and return the accumulated transcription text', 'process_audio_chunk': 'process incoming audio by converting to mono, normalizing, resampling to 16kHz, and queueing PCM16 base64 chunks', 'websocket_handler_audio_streaming': 'handle WebSocket audio streaming by sending audio chunks and receiving transcription delta updates concurrently'}
```

