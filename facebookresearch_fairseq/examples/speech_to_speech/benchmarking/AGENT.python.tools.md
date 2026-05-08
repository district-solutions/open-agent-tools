# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/speech_to_speech/benchmarking/core.py

Prompts

```
['benchmark the average inference runtime of a fairseq model across a dataset using timeit', 'count the average floating point operations per sample using the PYPAPI hardware performance counter library', 'measure the average peak memory consumption in MiB across a dataset using memory_profiler', 'gather run time, memory, and flop metrics for a fairseq model in a single call', 'run a speech-to-units-to-waveform pipeline that chains a speech-to-unit model with a vocoder', 'generate a random dataset with variable sequence lengths for speech-to-speech benchmarking', 'load raw audio waveforms from a w2v TSV file into torch tensors', 'load a fairseq dataset by task name and subset using command-line args', 'get a subset of the shortest audio samples sorted by source length', 'run the CLI to load, sample, and save random short and long dataset subsets as NPY files', 'run a speech-to-speech model benchmark to measure run time, memory, and FLOPs on a dataset', 'run a speech-to-universal-translation model benchmark using a YAML config and dataset path', 'run a 2 or 3 stage cascaded speech-to-speech translation benchmark with stage-specific configs', 'dump speech waveforms from a benchmarked model to a directory with a custom file prefix', 'create an argparse parser with speech generation args for S2S, TTS, S2UT, MT, and S2T model types']
```

Usage

```
{'benchmark_run_time': 'benchmark the average inference runtime of a fairseq model across a dataset using timeit', 'count_flops': 'count the average floating point operations per sample using the PYPAPI hardware performance counter library', 'max_memory': 'measure the average peak memory consumption in MiB across a dataset using memory_profiler', 'gather_all_metrics': 'gather run time, memory, and flop metrics for a fairseq model in a single call', 'S2UT': 'run a speech-to-units-to-waveform pipeline that chains a speech-to-unit model with a vocoder'}
```

## File: facebookresearch_fairseq/examples/speech_to_speech/benchmarking/data_utils.py

Prompts

```
['benchmark the average inference runtime of a fairseq model across a dataset using timeit', 'count the average floating point operations per sample using the PYPAPI hardware performance counter library', 'measure the average peak memory consumption in MiB across a dataset using memory_profiler', 'gather run time, memory, and flop metrics for a fairseq model in a single call', 'run a speech-to-units-to-waveform pipeline that chains a speech-to-unit model with a vocoder', 'generate a random dataset with variable sequence lengths for speech-to-speech benchmarking', 'load raw audio waveforms from a w2v TSV file into torch tensors', 'load a fairseq dataset by task name and subset using command-line args', 'get a subset of the shortest audio samples sorted by source length', 'run the CLI to load, sample, and save random short and long dataset subsets as NPY files', 'run a speech-to-speech model benchmark to measure run time, memory, and FLOPs on a dataset', 'run a speech-to-universal-translation model benchmark using a YAML config and dataset path', 'run a 2 or 3 stage cascaded speech-to-speech translation benchmark with stage-specific configs', 'dump speech waveforms from a benchmarked model to a directory with a custom file prefix', 'create an argparse parser with speech generation args for S2S, TTS, S2UT, MT, and S2T model types']
```

Usage

```
{'generate_random_dataset': 'generate a random dataset with variable sequence lengths for speech-to-speech benchmarking', 'load_dataset_raw_to_waveforms': 'load raw audio waveforms from a w2v TSV file into torch tensors', 'load_dataset_task': 'load a fairseq dataset by task name and subset using command-line args', 'get_short_data_subset': 'get a subset of the shortest audio samples sorted by source length', 'cli_main': 'run the CLI to load, sample, and save random short and long dataset subsets as NPY files'}
```

## File: facebookresearch_fairseq/examples/speech_to_speech/benchmarking/get_metrics.py

Prompts

```
['benchmark the average inference runtime of a fairseq model across a dataset using timeit', 'count the average floating point operations per sample using the PYPAPI hardware performance counter library', 'measure the average peak memory consumption in MiB across a dataset using memory_profiler', 'gather run time, memory, and flop metrics for a fairseq model in a single call', 'run a speech-to-units-to-waveform pipeline that chains a speech-to-unit model with a vocoder', 'generate a random dataset with variable sequence lengths for speech-to-speech benchmarking', 'load raw audio waveforms from a w2v TSV file into torch tensors', 'load a fairseq dataset by task name and subset using command-line args', 'get a subset of the shortest audio samples sorted by source length', 'run the CLI to load, sample, and save random short and long dataset subsets as NPY files', 'run a speech-to-speech model benchmark to measure run time, memory, and FLOPs on a dataset', 'run a speech-to-universal-translation model benchmark using a YAML config and dataset path', 'run a 2 or 3 stage cascaded speech-to-speech translation benchmark with stage-specific configs', 'dump speech waveforms from a benchmarked model to a directory with a custom file prefix', 'create an argparse parser with speech generation args for S2S, TTS, S2UT, MT, and S2T model types']
```

Usage

```
{'run_speech_benchmark': 'run a speech-to-speech model benchmark to measure run time, memory, and FLOPs on a dataset', 'run_s2ut_benchmark': 'run a speech-to-universal-translation model benchmark using a YAML config and dataset path', 'run_cascaded_s2st_benchmark': 'run a 2 or 3 stage cascaded speech-to-speech translation benchmark with stage-specific configs', 'dump_speech_waveforms': 'dump speech waveforms from a benchmarked model to a directory with a custom file prefix', 'create_benchmark_parser': 'create an argparse parser with speech generation args for S2S, TTS, S2UT, MT, and S2T model types'}
```

