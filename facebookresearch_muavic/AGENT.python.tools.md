# Agent Python Tools

- repo: facebookresearch/muavic
- repo_uri: https://github.com/facebookresearch/muavic

## File: facebookresearch_muavic/get_data.py

Prompts

```
['run the get_data script with --root-path and --src-lang to download and prepare the MuAViC dataset for a specific language', 'run prepare_mtedx to download mTEDx data, preprocess audio and video files, and prepare AVSR and AVST manifests for non-English languages', 'run prepare_lrs3 to segment pretrain videos, process LRS3 videos, and prepare AVSR and AVST manifests for English language data', 'review the main function that creates directories, dispatches to prepare_mtedx or prepare_lrs3 based on language, and cleans up temporary directories', 'review the argparse setup that accepts --root-path, --src-lang with 9 language choices, and --num-workers for parallel processing', 'create a manifest DataFrame from LRS3 pretrain transcription text files with word-level timing intervals', 'segment LRS3 pretrain videos and text files into shorter clips based on silence thresholds', 'process LRS3 videos to extract audio WAV files and crop face-aligned video clips for each split', 'prepare audio-visual speech recognition manifest TSV and transcription files for English LRS3 data', 'prepare audio-visual speech translation manifests by merging TED2020 human translations with pseudo translations', 'download mTEDx dataset from OpenSLR for a given source and target language pair', 'download TED talk videos from YouTube for a specific language across train, valid, and test splits', 'segment and normalize mTEDx audio files to 16kHz mono WAV format for a given language', 'segment and normalize mTEDx video files into cropped mouth ROI clips at 25 FPS for a given language', 'create audio-visual speech recognition manifest TSV files mapping segmented audio and video paths for a language', 'crop mouth patches from video frames using face landmark metadata and mean face alignment', 'split a video file into individual frames at a specified fps using ffmpeg', 'download a video from YouTube given its video ID and save as mp4', 'normalize text by removing punctuation, parenthetical expressions, and converting to lowercase', 'read a TSV audio-video manifest file and return a pandas DataFrame with frame counts']
```

Usage

```
{'run_get_data_for_language': 'run the get_data script with --root-path and --src-lang to download and prepare the MuAViC dataset for a specific language', 'run_prepare_mtedx': 'run prepare_mtedx to download mTEDx data, preprocess audio and video files, and prepare AVSR and AVST manifests for non-English languages', 'run_prepare_lrs3': 'run prepare_lrs3 to segment pretrain videos, process LRS3 videos, and prepare AVSR and AVST manifests for English language data', 'review_main_function': 'review the main function that creates directories, dispatches to prepare_mtedx or prepare_lrs3 based on language, and cleans up temporary directories', 'review_argparse_setup': 'review the argparse setup that accepts --root-path, --src-lang with 9 language choices, and --num-workers for parallel processing'}
```

## File: facebookresearch_muavic/lrs3_utils.py

Prompts

```
['run the get_data script with --root-path and --src-lang to download and prepare the MuAViC dataset for a specific language', 'run prepare_mtedx to download mTEDx data, preprocess audio and video files, and prepare AVSR and AVST manifests for non-English languages', 'run prepare_lrs3 to segment pretrain videos, process LRS3 videos, and prepare AVSR and AVST manifests for English language data', 'review the main function that creates directories, dispatches to prepare_mtedx or prepare_lrs3 based on language, and cleans up temporary directories', 'review the argparse setup that accepts --root-path, --src-lang with 9 language choices, and --num-workers for parallel processing', 'create a manifest DataFrame from LRS3 pretrain transcription text files with word-level timing intervals', 'segment LRS3 pretrain videos and text files into shorter clips based on silence thresholds', 'process LRS3 videos to extract audio WAV files and crop face-aligned video clips for each split', 'prepare audio-visual speech recognition manifest TSV and transcription files for English LRS3 data', 'prepare audio-visual speech translation manifests by merging TED2020 human translations with pseudo translations', 'download mTEDx dataset from OpenSLR for a given source and target language pair', 'download TED talk videos from YouTube for a specific language across train, valid, and test splits', 'segment and normalize mTEDx audio files to 16kHz mono WAV format for a given language', 'segment and normalize mTEDx video files into cropped mouth ROI clips at 25 FPS for a given language', 'create audio-visual speech recognition manifest TSV files mapping segmented audio and video paths for a language', 'crop mouth patches from video frames using face landmark metadata and mean face alignment', 'split a video file into individual frames at a specified fps using ffmpeg', 'download a video from YouTube given its video ID and save as mp4', 'normalize text by removing punctuation, parenthetical expressions, and converting to lowercase', 'read a TSV audio-video manifest file and return a pandas DataFrame with frame counts']
```

Usage

```
{'create_manifest_for_pretrain': 'create a manifest DataFrame from LRS3 pretrain transcription text files with word-level timing intervals', 'segment_pretrain_videos_and_text': 'segment LRS3 pretrain videos and text files into shorter clips based on silence thresholds', 'process_lrs3_videos': 'process LRS3 videos to extract audio WAV files and crop face-aligned video clips for each split', 'prepare_lrs3_avsr_manifests': 'prepare audio-visual speech recognition manifest TSV and transcription files for English LRS3 data', 'prepare_lrs3_avst_manifests': 'prepare audio-visual speech translation manifests by merging TED2020 human translations with pseudo translations'}
```

## File: facebookresearch_muavic/mtedx_utils.py

Prompts

```
['run the get_data script with --root-path and --src-lang to download and prepare the MuAViC dataset for a specific language', 'run prepare_mtedx to download mTEDx data, preprocess audio and video files, and prepare AVSR and AVST manifests for non-English languages', 'run prepare_lrs3 to segment pretrain videos, process LRS3 videos, and prepare AVSR and AVST manifests for English language data', 'review the main function that creates directories, dispatches to prepare_mtedx or prepare_lrs3 based on language, and cleans up temporary directories', 'review the argparse setup that accepts --root-path, --src-lang with 9 language choices, and --num-workers for parallel processing', 'create a manifest DataFrame from LRS3 pretrain transcription text files with word-level timing intervals', 'segment LRS3 pretrain videos and text files into shorter clips based on silence thresholds', 'process LRS3 videos to extract audio WAV files and crop face-aligned video clips for each split', 'prepare audio-visual speech recognition manifest TSV and transcription files for English LRS3 data', 'prepare audio-visual speech translation manifests by merging TED2020 human translations with pseudo translations', 'download mTEDx dataset from OpenSLR for a given source and target language pair', 'download TED talk videos from YouTube for a specific language across train, valid, and test splits', 'segment and normalize mTEDx audio files to 16kHz mono WAV format for a given language', 'segment and normalize mTEDx video files into cropped mouth ROI clips at 25 FPS for a given language', 'create audio-visual speech recognition manifest TSV files mapping segmented audio and video paths for a language', 'crop mouth patches from video frames using face landmark metadata and mean face alignment', 'split a video file into individual frames at a specified fps using ffmpeg', 'download a video from YouTube given its video ID and save as mp4', 'normalize text by removing punctuation, parenthetical expressions, and converting to lowercase', 'read a TSV audio-video manifest file and return a pandas DataFrame with frame counts']
```

Usage

```
{'download_mtedx_data': 'download mTEDx dataset from OpenSLR for a given source and target language pair', 'download_mtedx_lang_videos': 'download TED talk videos from YouTube for a specific language across train, valid, and test splits', 'preprocess_mtedx_audio': 'segment and normalize mTEDx audio files to 16kHz mono WAV format for a given language', 'preprocess_mtedx_video': 'segment and normalize mTEDx video files into cropped mouth ROI clips at 25 FPS for a given language', 'prepare_mtedx_avsr_manifests': 'create audio-visual speech recognition manifest TSV files mapping segmented audio and video paths for a language'}
```

## File: facebookresearch_muavic/utils.py

Prompts

```
['run the get_data script with --root-path and --src-lang to download and prepare the MuAViC dataset for a specific language', 'run prepare_mtedx to download mTEDx data, preprocess audio and video files, and prepare AVSR and AVST manifests for non-English languages', 'run prepare_lrs3 to segment pretrain videos, process LRS3 videos, and prepare AVSR and AVST manifests for English language data', 'review the main function that creates directories, dispatches to prepare_mtedx or prepare_lrs3 based on language, and cleans up temporary directories', 'review the argparse setup that accepts --root-path, --src-lang with 9 language choices, and --num-workers for parallel processing', 'create a manifest DataFrame from LRS3 pretrain transcription text files with word-level timing intervals', 'segment LRS3 pretrain videos and text files into shorter clips based on silence thresholds', 'process LRS3 videos to extract audio WAV files and crop face-aligned video clips for each split', 'prepare audio-visual speech recognition manifest TSV and transcription files for English LRS3 data', 'prepare audio-visual speech translation manifests by merging TED2020 human translations with pseudo translations', 'download mTEDx dataset from OpenSLR for a given source and target language pair', 'download TED talk videos from YouTube for a specific language across train, valid, and test splits', 'segment and normalize mTEDx audio files to 16kHz mono WAV format for a given language', 'segment and normalize mTEDx video files into cropped mouth ROI clips at 25 FPS for a given language', 'create audio-visual speech recognition manifest TSV files mapping segmented audio and video paths for a language', 'crop mouth patches from video frames using face landmark metadata and mean face alignment', 'split a video file into individual frames at a specified fps using ffmpeg', 'download a video from YouTube given its video ID and save as mp4', 'normalize text by removing punctuation, parenthetical expressions, and converting to lowercase', 'read a TSV audio-video manifest file and return a pandas DataFrame with frame counts']
```

Usage

```
{'crop_patch_mouth': 'crop mouth patches from video frames using face landmark metadata and mean face alignment', 'split_video_to_frames': 'split a video file into individual frames at a specified fps using ffmpeg', 'download_video_from_youtube': 'download a video from YouTube given its video ID and save as mp4', 'normalize_text': 'normalize text by removing punctuation, parenthetical expressions, and converting to lowercase', 'read_av_manifest': 'read a TSV audio-video manifest file and return a pandas DataFrame with frame counts'}
```

