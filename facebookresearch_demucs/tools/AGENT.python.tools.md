# Agent Python Tools

- repo: facebookresearch/demucs
- repo_uri: https://github.com/facebookresearch/demucs

## File: facebookresearch_demucs/tools/automix.py

Prompts

```
['run the automix script to create realistic mixes with stems from different songs aligned by BPM and pitch', 'build a new track by mixing stems from different songs with tempo and pitch alignment', 'analyse a track to extract BPM, beat onsets, and chroma distribution from the bass line', 'align the first beats of multiple audio stems using a gaussian grid matching approach', 'find the optimal pitch shift in semitones between two chroma distributions by comparing rolled histograms', 'run the bench.py script with an experiment signature to benchmark GPU memory and timing', 'use the bench context manager to measure GPU memory usage and elapsed time for CUDA operations', 'benchmark a Demucs model forward and backward pass on GPU and report memory and time', 'benchmark a Demucs model forward-only pass on GPU and report memory and time', 'benchmark CPU inference of a Demucs model on a 40 second audio clip using apply_model', 'run the convert CLI to transform demucs experiment signatures from dev to release format', 'convert a demucs experiment signature by transforming its argv and mapping to a new signature', 'transform a demucs argv list by removing deprecated options and replacing model names', 'compare the output of an old demucs model against a converted model using a delta metric', 'dump converted demucs models to serialized .th files with checksums in an output directory']
```

Usage

```
{'run_automix_main': 'run the automix script to create realistic mixes with stems from different songs aligned by BPM and pitch', 'build_track_from_catalog': 'build a new track by mixing stems from different songs with tempo and pitch alignment', 'analyse_track_bpm_pitch': 'analyse a track to extract BPM, beat onsets, and chroma distribution from the bass line', 'align_stems_beat_onsets': 'align the first beats of multiple audio stems using a gaussian grid matching approach', 'find_best_pitch_shift': 'find the optimal pitch shift in semitones between two chroma distributions by comparing rolled histograms'}
```

## File: facebookresearch_demucs/tools/bench.py

Prompts

```
['run the automix script to create realistic mixes with stems from different songs aligned by BPM and pitch', 'build a new track by mixing stems from different songs with tempo and pitch alignment', 'analyse a track to extract BPM, beat onsets, and chroma distribution from the bass line', 'align the first beats of multiple audio stems using a gaussian grid matching approach', 'find the optimal pitch shift in semitones between two chroma distributions by comparing rolled histograms', 'run the bench.py script with an experiment signature to benchmark GPU memory and timing', 'use the bench context manager to measure GPU memory usage and elapsed time for CUDA operations', 'benchmark a Demucs model forward and backward pass on GPU and report memory and time', 'benchmark a Demucs model forward-only pass on GPU and report memory and time', 'benchmark CPU inference of a Demucs model on a 40 second audio clip using apply_model', 'run the convert CLI to transform demucs experiment signatures from dev to release format', 'convert a demucs experiment signature by transforming its argv and mapping to a new signature', 'transform a demucs argv list by removing deprecated options and replacing model names', 'compare the output of an old demucs model against a converted model using a delta metric', 'dump converted demucs models to serialized .th files with checksums in an output directory']
```

Usage

```
{'run_bench_script': 'run the bench.py script with an experiment signature to benchmark GPU memory and timing', 'use_bench_context_manager': 'use the bench context manager to measure GPU memory usage and elapsed time for CUDA operations', 'benchmark_forward_backward': 'benchmark a Demucs model forward and backward pass on GPU and report memory and time', 'benchmark_forward_only': 'benchmark a Demucs model forward-only pass on GPU and report memory and time', 'benchmark_cpu_inference': 'benchmark CPU inference of a Demucs model on a 40 second audio clip using apply_model'}
```

## File: facebookresearch_demucs/tools/convert.py

Prompts

```
['run the automix script to create realistic mixes with stems from different songs aligned by BPM and pitch', 'build a new track by mixing stems from different songs with tempo and pitch alignment', 'analyse a track to extract BPM, beat onsets, and chroma distribution from the bass line', 'align the first beats of multiple audio stems using a gaussian grid matching approach', 'find the optimal pitch shift in semitones between two chroma distributions by comparing rolled histograms', 'run the bench.py script with an experiment signature to benchmark GPU memory and timing', 'use the bench context manager to measure GPU memory usage and elapsed time for CUDA operations', 'benchmark a Demucs model forward and backward pass on GPU and report memory and time', 'benchmark a Demucs model forward-only pass on GPU and report memory and time', 'benchmark CPU inference of a Demucs model on a 40 second audio clip using apply_model', 'run the convert CLI to transform demucs experiment signatures from dev to release format', 'convert a demucs experiment signature by transforming its argv and mapping to a new signature', 'transform a demucs argv list by removing deprecated options and replacing model names', 'compare the output of an old demucs model against a converted model using a delta metric', 'dump converted demucs models to serialized .th files with checksums in an output directory']
```

Usage

```
{'run_convert_sigs': 'run the convert CLI to transform demucs experiment signatures from dev to release format', 'convert_experiment_signature': 'convert a demucs experiment signature by transforming its argv and mapping to a new signature', 'transform_argv_list': 'transform a demucs argv list by removing deprecated options and replacing model names', 'compare_model_outputs': 'compare the output of an old demucs model against a converted model using a delta metric', 'dump_converted_models': 'dump converted demucs models to serialized .th files with checksums in an output directory'}
```

