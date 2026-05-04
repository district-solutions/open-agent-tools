# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/examples/003-python-speech-to-text/stt/actions.py

Prompts

```
['run the speech to text action that transcribes audio chunks into text output', 'stream transcription text output from an STT model server with stop command detection', 'check if a text string is a stop or exit command for halting transcription', 'create an action registry with the speech to text action schema and handler', 'review the run_speech_to_text async function that feeds audio chunks to the STT model server', 'create a singleton STTModelServer instance using STTModelServer.instance() for speech-to-text transcription', 'feed a numpy audio chunk to the STTModelServer recorder for real-time transcription', 'wait for and retrieve a transcription piece from the STTModelServer with an optional callback', 'use STTModelServer as a context manager to auto-shutdown the recorder on exit', 'initialize an AudioToTextRecorder with medium model and custom silence duration settings', 'register custom serializers and deserializers for boolean, bytearray, and text types with the actionengine serializer registry', 'convert a python boolean value to a single byte for binary serialization', 'deserialize a single byte back into a python boolean value', 'encode a python string to utf-8 bytes for binary serialization', 'decode utf-8 bytes back into a python string']
```

Usage

```
{'run_speech_to_text_action': 'run the speech to text action that transcribes audio chunks into text output', 'stream_text_output': 'stream transcription text output from an STT model server with stop command detection', 'has_stop_command': 'check if a text string is a stop or exit command for halting transcription', 'make_action_registry': 'create an action registry with the speech to text action schema and handler', 'review_run_speech_to_text': 'review the run_speech_to_text async function that feeds audio chunks to the STT model server'}
```

## File: google-deepmind_actionengine/examples/003-python-speech-to-text/stt/model_server.py

Prompts

```
['run the speech to text action that transcribes audio chunks into text output', 'stream transcription text output from an STT model server with stop command detection', 'check if a text string is a stop or exit command for halting transcription', 'create an action registry with the speech to text action schema and handler', 'review the run_speech_to_text async function that feeds audio chunks to the STT model server', 'create a singleton STTModelServer instance using STTModelServer.instance() for speech-to-text transcription', 'feed a numpy audio chunk to the STTModelServer recorder for real-time transcription', 'wait for and retrieve a transcription piece from the STTModelServer with an optional callback', 'use STTModelServer as a context manager to auto-shutdown the recorder on exit', 'initialize an AudioToTextRecorder with medium model and custom silence duration settings', 'register custom serializers and deserializers for boolean, bytearray, and text types with the actionengine serializer registry', 'convert a python boolean value to a single byte for binary serialization', 'deserialize a single byte back into a python boolean value', 'encode a python string to utf-8 bytes for binary serialization', 'decode utf-8 bytes back into a python string']
```

Usage

```
{'create_stt_singleton': 'create a singleton STTModelServer instance using STTModelServer.instance() for speech-to-text transcription', 'feed_audio_chunk': 'feed a numpy audio chunk to the STTModelServer recorder for real-time transcription', 'wait_for_transcription': 'wait for and retrieve a transcription piece from the STTModelServer with an optional callback', 'use_stt_context_manager': 'use STTModelServer as a context manager to auto-shutdown the recorder on exit', 'initialize_stt_recorder': 'initialize an AudioToTextRecorder with medium model and custom silence duration settings'}
```

## File: google-deepmind_actionengine/examples/003-python-speech-to-text/stt/serialisation.py

Prompts

```
['run the speech to text action that transcribes audio chunks into text output', 'stream transcription text output from an STT model server with stop command detection', 'check if a text string is a stop or exit command for halting transcription', 'create an action registry with the speech to text action schema and handler', 'review the run_speech_to_text async function that feeds audio chunks to the STT model server', 'create a singleton STTModelServer instance using STTModelServer.instance() for speech-to-text transcription', 'feed a numpy audio chunk to the STTModelServer recorder for real-time transcription', 'wait for and retrieve a transcription piece from the STTModelServer with an optional callback', 'use STTModelServer as a context manager to auto-shutdown the recorder on exit', 'initialize an AudioToTextRecorder with medium model and custom silence duration settings', 'register custom serializers and deserializers for boolean, bytearray, and text types with the actionengine serializer registry', 'convert a python boolean value to a single byte for binary serialization', 'deserialize a single byte back into a python boolean value', 'encode a python string to utf-8 bytes for binary serialization', 'decode utf-8 bytes back into a python string']
```

Usage

```
{'register_stt_serialisers': 'register custom serializers and deserializers for boolean, bytearray, and text types with the actionengine serializer registry', 'bool_to_bytes': 'convert a python boolean value to a single byte for binary serialization', 'bytes_to_bool': 'deserialize a single byte back into a python boolean value', 'str_to_bytes': 'encode a python string to utf-8 bytes for binary serialization', 'bytes_to_str': 'decode utf-8 bytes back into a python string'}
```

