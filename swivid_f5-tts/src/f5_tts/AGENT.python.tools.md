# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/f5_tts/api.py

Prompts

```
['create an F5TTS instance with a specified model name, checkpoint file, and target device', 'run inference to generate speech from a reference audio file and target text with configurable seed', 'test the transcribe method to extract text from a reference audio file with optional language', 'export generated WAV audio to a file with optional silence removal', 'export a spectrogram visualization to a PNG image file', 'run the F5-TTS socket server on host 0.0.0.0 port 9998 with reference audio and text', 'create a TTSStreamingProcessor with model checkpoint, vocab, reference audio, and reference text', 'build a TTS streaming pipeline that generates audio chunks and writes them to output.wav', 'test the AudioFileWriterThread that queues and writes audio chunks to a WAV file', 'review the start_server function that binds a TCP socket and handles client connections']
```

Usage

```
{'create_F5TTS_instance': 'create an F5TTS instance with a specified model name, checkpoint file, and target device', 'run_infer_generate_speech': 'run inference to generate speech from a reference audio file and target text with configurable seed', 'test_transcribe_extract_text': 'test the transcribe method to extract text from a reference audio file with optional language', 'export_wav_save_audio': 'export generated WAV audio to a file with optional silence removal', 'export_spectrogram_save_image': 'export a spectrogram visualization to a PNG image file'}
```

## File: swivid_f5-tts/src/f5_tts/socket_server.py

Prompts

```
['create an F5TTS instance with a specified model name, checkpoint file, and target device', 'run inference to generate speech from a reference audio file and target text with configurable seed', 'test the transcribe method to extract text from a reference audio file with optional language', 'export generated WAV audio to a file with optional silence removal', 'export a spectrogram visualization to a PNG image file', 'run the F5-TTS socket server on host 0.0.0.0 port 9998 with reference audio and text', 'create a TTSStreamingProcessor with model checkpoint, vocab, reference audio, and reference text', 'build a TTS streaming pipeline that generates audio chunks and writes them to output.wav', 'test the AudioFileWriterThread that queues and writes audio chunks to a WAV file', 'review the start_server function that binds a TCP socket and handles client connections']
```

Usage

```
{'run_socket_server_tts': 'run the F5-TTS socket server on host 0.0.0.0 port 9998 with reference audio and text', 'create_tts_streaming_processor': 'create a TTSStreamingProcessor with model checkpoint, vocab, reference audio, and reference text', 'build_tts_streaming_output': 'build a TTS streaming pipeline that generates audio chunks and writes them to output.wav', 'test_audio_file_writer_thread': 'test the AudioFileWriterThread that queues and writes audio chunks to a WAV file', 'review_start_server': 'review the start_server function that binds a TCP socket and handles client connections'}
```

