# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/libdatachannel/examples/streamer/samples/generate_h264.py

Prompts

```
['run the script to convert an input video file into individual H.264 sample files using ffmpeg', 'create an H264ByteStream instance from an H.264 file to parse NAL units into frame samples', 'build a function that extracts the NAL unit type from an H.264 NALU byte sequence', 'refactor the merge_sample method to combine NAL units into a length-prefixed byte stream', 'review the reduce_nalus_to_samples method that groups NAL units into frame samples by keyframe boundaries', 'run the script to convert an input audio file into individual 160-byte Opus sample files', 'run the Ogg parser to read and parse Ogg page segments from an Ogg audio stream file', 'build a tool that uses ffmpeg to encode audio to Opus and split it into individual sample files', 'refactor the generate function to support configurable sample sizes and output formats', 'review the Ogg and Page classes that parse Ogg bitstream pages using KaitaiStruct']
```

Usage

```
{'run_generate_h264_samples': 'run the script to convert an input video file into individual H.264 sample files using ffmpeg', 'create_h264_bytestream_from_file': 'create an H264ByteStream instance from an H.264 file to parse NAL units into frame samples', 'build_h264_nalu_type_detector': 'build a function that extracts the NAL unit type from an H.264 NALU byte sequence', 'refactor_merge_sample_to_length_prefixed': 'refactor the merge_sample method to combine NAL units into a length-prefixed byte stream', 'review_reduce_nalus_to_samples': 'review the reduce_nalus_to_samples method that groups NAL units into frame samples by keyframe boundaries'}
```

## File: google-deepmind_actionengine/third_party/libdatachannel/examples/streamer/samples/generate_opus.py

Prompts

```
['run the script to convert an input video file into individual H.264 sample files using ffmpeg', 'create an H264ByteStream instance from an H.264 file to parse NAL units into frame samples', 'build a function that extracts the NAL unit type from an H.264 NALU byte sequence', 'refactor the merge_sample method to combine NAL units into a length-prefixed byte stream', 'review the reduce_nalus_to_samples method that groups NAL units into frame samples by keyframe boundaries', 'run the script to convert an input audio file into individual 160-byte Opus sample files', 'run the Ogg parser to read and parse Ogg page segments from an Ogg audio stream file', 'build a tool that uses ffmpeg to encode audio to Opus and split it into individual sample files', 'refactor the generate function to support configurable sample sizes and output formats', 'review the Ogg and Page classes that parse Ogg bitstream pages using KaitaiStruct']
```

Usage

```
{'run_generate_opus_samples': 'run the script to convert an input audio file into individual 160-byte Opus sample files', 'run_ogg_parser': 'run the Ogg parser to read and parse Ogg page segments from an Ogg audio stream file', 'build_opus_generator': 'build a tool that uses ffmpeg to encode audio to Opus and split it into individual sample files', 'refactor_generate_function': 'refactor the generate function to support configurable sample sizes and output formats', 'review_ogg_class': 'review the Ogg and Page classes that parse Ogg bitstream pages using KaitaiStruct'}
```

