# Agent Python Tools

- repo: facebookresearch/brainmagick
- repo_uri: https://github.com/facebookresearch/brainmagick

## File: facebookresearch_brainmagick/bm/studies/schoffelen2019/mock.py

Prompts

```
['use the data context manager to create a temporary mocked MEG dataset structure for testing', 'call add_fake_sequence_uid to assign randomized sequence UIDs to a log DataFrame based on block IDs', 'use _mocked_recording_paths to return a StudyPaths object for subject sub-A2002 during tests', 'test the data context manager to verify it creates fake MEG fif files and symlinks TextGrid files', 'review the add_fake_sequence_uid function to understand how it maps block IDs to shuffled sequence UIDs', 'create a StudyPaths instance with a subject_uid to access MEG recording paths', 'test the StudyPaths is_valid method to check if raw and metadata files exist', 'get the raw MEG data file path for a subject using the StudyPaths raw property', 'get the metadata file path for a subject using the StudyPaths metadata property', 'get the audio wave file path for a stimulus name using StudyPaths wave_file method', 'read a MEG experiment log file and return a cleaned DataFrame with conditions, words, and phonemes', 'align experiment log timestamps with MEG event triggers using spearman correlation matching', 'parse a Praat TextGrid file into a list of word and phoneme event dictionaries', 'add word_sequence and word_index columns to a log DataFrame for each fixation block', 'map word sequences to unique stimulus UIDs from the stimuli file and add to the log', 'iterate over all Schoffelen2019 MEG recordings filtered by visual or audio modality', 'read a CTF or FIF MEG raw data file using the appropriate MNE reader', 'load and align MEG events with metadata into a cleaned pandas DataFrame', 'filter recording events by a custom query string on the events DataFrame', 'download and extract the Schoffelen2019 study derivatives zip file from the Donders repository', 'test iterating over all Schoffelen2019 recordings and verify subject modality and UID', 'test retrieving events from a Schoffelen2019Recording and compare against cached expected CSV', 'test loading raw MEG data from a Schoffelen2019Recording and verify channel count and timepoints', 'test preprocessing raw MEG data with api.preprocess_mne to resample and filter signals', 'test converting a TextGrid file to a DataFrame using preproc.tgrid_to_dict']
```

Usage

```
{'create_mock_dataset_context': 'use the data context manager to create a temporary mocked MEG dataset structure for testing', 'add_fake_sequence_uid_to_log': 'call add_fake_sequence_uid to assign randomized sequence UIDs to a log DataFrame based on block IDs', 'mock_recording_paths': 'use _mocked_recording_paths to return a StudyPaths object for subject sub-A2002 during tests', 'test_mock_data_context': 'test the data context manager to verify it creates fake MEG fif files and symlinks TextGrid files', 'review_add_fake_sequence_uid': 'review the add_fake_sequence_uid function to understand how it maps block IDs to shuffled sequence UIDs'}
```

## File: facebookresearch_brainmagick/bm/studies/schoffelen2019/paths.py

Prompts

```
['use the data context manager to create a temporary mocked MEG dataset structure for testing', 'call add_fake_sequence_uid to assign randomized sequence UIDs to a log DataFrame based on block IDs', 'use _mocked_recording_paths to return a StudyPaths object for subject sub-A2002 during tests', 'test the data context manager to verify it creates fake MEG fif files and symlinks TextGrid files', 'review the add_fake_sequence_uid function to understand how it maps block IDs to shuffled sequence UIDs', 'create a StudyPaths instance with a subject_uid to access MEG recording paths', 'test the StudyPaths is_valid method to check if raw and metadata files exist', 'get the raw MEG data file path for a subject using the StudyPaths raw property', 'get the metadata file path for a subject using the StudyPaths metadata property', 'get the audio wave file path for a stimulus name using StudyPaths wave_file method', 'read a MEG experiment log file and return a cleaned DataFrame with conditions, words, and phonemes', 'align experiment log timestamps with MEG event triggers using spearman correlation matching', 'parse a Praat TextGrid file into a list of word and phoneme event dictionaries', 'add word_sequence and word_index columns to a log DataFrame for each fixation block', 'map word sequences to unique stimulus UIDs from the stimuli file and add to the log', 'iterate over all Schoffelen2019 MEG recordings filtered by visual or audio modality', 'read a CTF or FIF MEG raw data file using the appropriate MNE reader', 'load and align MEG events with metadata into a cleaned pandas DataFrame', 'filter recording events by a custom query string on the events DataFrame', 'download and extract the Schoffelen2019 study derivatives zip file from the Donders repository', 'test iterating over all Schoffelen2019 recordings and verify subject modality and UID', 'test retrieving events from a Schoffelen2019Recording and compare against cached expected CSV', 'test loading raw MEG data from a Schoffelen2019Recording and verify channel count and timepoints', 'test preprocessing raw MEG data with api.preprocess_mne to resample and filter signals', 'test converting a TextGrid file to a DataFrame using preproc.tgrid_to_dict']
```

Usage

```
{'create_StudyPaths_instance': 'create a StudyPaths instance with a subject_uid to access MEG recording paths', 'test_is_valid': 'test the StudyPaths is_valid method to check if raw and metadata files exist', 'get_raw_path': 'get the raw MEG data file path for a subject using the StudyPaths raw property', 'get_metadata_path': 'get the metadata file path for a subject using the StudyPaths metadata property', 'get_wave_file_path': 'get the audio wave file path for a stimulus name using StudyPaths wave_file method'}
```

## File: facebookresearch_brainmagick/bm/studies/schoffelen2019/preproc.py

Prompts

```
['use the data context manager to create a temporary mocked MEG dataset structure for testing', 'call add_fake_sequence_uid to assign randomized sequence UIDs to a log DataFrame based on block IDs', 'use _mocked_recording_paths to return a StudyPaths object for subject sub-A2002 during tests', 'test the data context manager to verify it creates fake MEG fif files and symlinks TextGrid files', 'review the add_fake_sequence_uid function to understand how it maps block IDs to shuffled sequence UIDs', 'create a StudyPaths instance with a subject_uid to access MEG recording paths', 'test the StudyPaths is_valid method to check if raw and metadata files exist', 'get the raw MEG data file path for a subject using the StudyPaths raw property', 'get the metadata file path for a subject using the StudyPaths metadata property', 'get the audio wave file path for a stimulus name using StudyPaths wave_file method', 'read a MEG experiment log file and return a cleaned DataFrame with conditions, words, and phonemes', 'align experiment log timestamps with MEG event triggers using spearman correlation matching', 'parse a Praat TextGrid file into a list of word and phoneme event dictionaries', 'add word_sequence and word_index columns to a log DataFrame for each fixation block', 'map word sequences to unique stimulus UIDs from the stimuli file and add to the log', 'iterate over all Schoffelen2019 MEG recordings filtered by visual or audio modality', 'read a CTF or FIF MEG raw data file using the appropriate MNE reader', 'load and align MEG events with metadata into a cleaned pandas DataFrame', 'filter recording events by a custom query string on the events DataFrame', 'download and extract the Schoffelen2019 study derivatives zip file from the Donders repository', 'test iterating over all Schoffelen2019 recordings and verify subject modality and UID', 'test retrieving events from a Schoffelen2019Recording and compare against cached expected CSV', 'test loading raw MEG data from a Schoffelen2019Recording and verify channel count and timepoints', 'test preprocessing raw MEG data with api.preprocess_mne to resample and filter signals', 'test converting a TextGrid file to a DataFrame using preproc.tgrid_to_dict']
```

Usage

```
{'read_log': 'read a MEG experiment log file and return a cleaned DataFrame with conditions, words, and phonemes', 'get_log_times': 'align experiment log timestamps with MEG event triggers using spearman correlation matching', 'tgrid_to_dict': 'parse a Praat TextGrid file into a list of word and phoneme event dictionaries', 'add_word_sequence_and_position': 'add word_sequence and word_index columns to a log DataFrame for each fixation block', 'add_sequence_uid': 'map word sequences to unique stimulus UIDs from the stimuli file and add to the log'}
```

## File: facebookresearch_brainmagick/bm/studies/schoffelen2019/schoffelen2019.py

Prompts

```
['use the data context manager to create a temporary mocked MEG dataset structure for testing', 'call add_fake_sequence_uid to assign randomized sequence UIDs to a log DataFrame based on block IDs', 'use _mocked_recording_paths to return a StudyPaths object for subject sub-A2002 during tests', 'test the data context manager to verify it creates fake MEG fif files and symlinks TextGrid files', 'review the add_fake_sequence_uid function to understand how it maps block IDs to shuffled sequence UIDs', 'create a StudyPaths instance with a subject_uid to access MEG recording paths', 'test the StudyPaths is_valid method to check if raw and metadata files exist', 'get the raw MEG data file path for a subject using the StudyPaths raw property', 'get the metadata file path for a subject using the StudyPaths metadata property', 'get the audio wave file path for a stimulus name using StudyPaths wave_file method', 'read a MEG experiment log file and return a cleaned DataFrame with conditions, words, and phonemes', 'align experiment log timestamps with MEG event triggers using spearman correlation matching', 'parse a Praat TextGrid file into a list of word and phoneme event dictionaries', 'add word_sequence and word_index columns to a log DataFrame for each fixation block', 'map word sequences to unique stimulus UIDs from the stimuli file and add to the log', 'iterate over all Schoffelen2019 MEG recordings filtered by visual or audio modality', 'read a CTF or FIF MEG raw data file using the appropriate MNE reader', 'load and align MEG events with metadata into a cleaned pandas DataFrame', 'filter recording events by a custom query string on the events DataFrame', 'download and extract the Schoffelen2019 study derivatives zip file from the Donders repository', 'test iterating over all Schoffelen2019 recordings and verify subject modality and UID', 'test retrieving events from a Schoffelen2019Recording and compare against cached expected CSV', 'test loading raw MEG data from a Schoffelen2019Recording and verify channel count and timepoints', 'test preprocessing raw MEG data with api.preprocess_mne to resample and filter signals', 'test converting a TextGrid file to a DataFrame using preproc.tgrid_to_dict']
```

Usage

```
{'iter_schoffelen_recordings': 'iterate over all Schoffelen2019 MEG recordings filtered by visual or audio modality', 'read_raw_meg': 'read a CTF or FIF MEG raw data file using the appropriate MNE reader', 'load_events_dataframe': 'load and align MEG events with metadata into a cleaned pandas DataFrame', 'filter_events_by_condition': 'filter recording events by a custom query string on the events DataFrame', 'download_schoffelen_derivatives': 'download and extract the Schoffelen2019 study derivatives zip file from the Donders repository'}
```

## File: facebookresearch_brainmagick/bm/studies/schoffelen2019/test_schoffelen2019.py

Prompts

```
['use the data context manager to create a temporary mocked MEG dataset structure for testing', 'call add_fake_sequence_uid to assign randomized sequence UIDs to a log DataFrame based on block IDs', 'use _mocked_recording_paths to return a StudyPaths object for subject sub-A2002 during tests', 'test the data context manager to verify it creates fake MEG fif files and symlinks TextGrid files', 'review the add_fake_sequence_uid function to understand how it maps block IDs to shuffled sequence UIDs', 'create a StudyPaths instance with a subject_uid to access MEG recording paths', 'test the StudyPaths is_valid method to check if raw and metadata files exist', 'get the raw MEG data file path for a subject using the StudyPaths raw property', 'get the metadata file path for a subject using the StudyPaths metadata property', 'get the audio wave file path for a stimulus name using StudyPaths wave_file method', 'read a MEG experiment log file and return a cleaned DataFrame with conditions, words, and phonemes', 'align experiment log timestamps with MEG event triggers using spearman correlation matching', 'parse a Praat TextGrid file into a list of word and phoneme event dictionaries', 'add word_sequence and word_index columns to a log DataFrame for each fixation block', 'map word sequences to unique stimulus UIDs from the stimuli file and add to the log', 'iterate over all Schoffelen2019 MEG recordings filtered by visual or audio modality', 'read a CTF or FIF MEG raw data file using the appropriate MNE reader', 'load and align MEG events with metadata into a cleaned pandas DataFrame', 'filter recording events by a custom query string on the events DataFrame', 'download and extract the Schoffelen2019 study derivatives zip file from the Donders repository', 'test iterating over all Schoffelen2019 recordings and verify subject modality and UID', 'test retrieving events from a Schoffelen2019Recording and compare against cached expected CSV', 'test loading raw MEG data from a Schoffelen2019Recording and verify channel count and timepoints', 'test preprocessing raw MEG data with api.preprocess_mne to resample and filter signals', 'test converting a TextGrid file to a DataFrame using preproc.tgrid_to_dict']
```

Usage

```
{'test_Schoffelen2019Recording_iter': 'test iterating over all Schoffelen2019 recordings and verify subject modality and UID', 'test_Schoffelen2019Recording_events': 'test retrieving events from a Schoffelen2019Recording and compare against cached expected CSV', 'test_Schoffelen2019Recording_raw': 'test loading raw MEG data from a Schoffelen2019Recording and verify channel count and timepoints', 'test_preprocess_mne': 'test preprocessing raw MEG data with api.preprocess_mne to resample and filter signals', 'test_tgrid_to_dict': 'test converting a TextGrid file to a DataFrame using preproc.tgrid_to_dict'}
```

