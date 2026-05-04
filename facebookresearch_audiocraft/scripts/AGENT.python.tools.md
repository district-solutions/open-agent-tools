# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/scripts/mos.py

Prompts

```
['run a Flask app for Mean Opinion Score surveys using flask run or gunicorn on port 4567', 'create a new MOS survey study by submitting XP or grid names via the index route', 'run a survey page to rate audio model samples on a 1 to 5 scale with blind mode support', 'view aggregated MOS results with mean ratings and confidence intervals for a survey signature', 'login a user to the MOS survey app via the login route and store session data', 'run the resample_dataset script to resample audio files in a dataset to a target sample rate', 'run the resample_dataset script via SLURM to parallelize audio resampling across multiple nodes', 'run the resample_dataset script in debug mode to locally process a single shard of audio files', 'review the process_dataset function that reads audio files, converts sample rate and channels, and writes output', 'review the read_txt_files function that reads a text file list of audio file paths and filters non-audio extensions']
```

Usage

```
{'run_flask_mos_server': 'run a Flask app for Mean Opinion Score surveys using flask run or gunicorn on port 4567', 'create_survey_study': 'create a new MOS survey study by submitting XP or grid names via the index route', 'run_survey_rating': 'run a survey page to rate audio model samples on a 1 to 5 scale with blind mode support', 'view_survey_results': 'view aggregated MOS results with mean ratings and confidence intervals for a survey signature', 'login_user_session': 'login a user to the MOS survey app via the login route and store session data'}
```

## File: facebookresearch_audiocraft/scripts/resample_dataset.py

Prompts

```
['run a Flask app for Mean Opinion Score surveys using flask run or gunicorn on port 4567', 'create a new MOS survey study by submitting XP or grid names via the index route', 'run a survey page to rate audio model samples on a 1 to 5 scale with blind mode support', 'view aggregated MOS results with mean ratings and confidence intervals for a survey signature', 'login a user to the MOS survey app via the login route and store session data', 'run the resample_dataset script to resample audio files in a dataset to a target sample rate', 'run the resample_dataset script via SLURM to parallelize audio resampling across multiple nodes', 'run the resample_dataset script in debug mode to locally process a single shard of audio files', 'review the process_dataset function that reads audio files, converts sample rate and channels, and writes output', 'review the read_txt_files function that reads a text file list of audio file paths and filters non-audio extensions']
```

Usage

```
{'run_resample_dataset': 'run the resample_dataset script to resample audio files in a dataset to a target sample rate', 'run_resample_dataset_slurm': 'run the resample_dataset script via SLURM to parallelize audio resampling across multiple nodes', 'run_resample_dataset_debug': 'run the resample_dataset script in debug mode to locally process a single shard of audio files', 'review_process_dataset': 'review the process_dataset function that reads audio files, converts sample rate and channels, and writes output', 'review_read_txt_files': 'review the read_txt_files function that reads a text file list of audio file paths and filters non-audio extensions'}
```

