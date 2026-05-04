# Agent Python Tools

- repo: facebookresearch/glore
- repo_uri: https://github.com/facebookresearch/glore

## File: facebookresearch_glore/dataset/Kinetics/scripts/convert_videos.py

Prompts

```
['run the script to convert MP4 videos to AVI format using ffmpeg with parallel processing', 'run a shell command and return output or skip if the destination file already exists', 'run batch video conversion on a list of videos using an ffmpeg command format string', 'run a scan of subdirectories to collect all MP4 video file paths from a root folder', 'run the main block to convert Kinetics dataset videos from source to destination with optional shuffling', 'run the script to rename Kinetics dataset folders by replacing spaces with underscores', 'run the remove_spaces script to rename train and val folder names using CSV lists', 'create a function that moves a source file or directory to a destination with logging', 'create a function that reads a CSV and renames folders by replacing spaces with underscores', 'test the rename_folder_name function with a CSV file and root folder path']
```

Usage

```
{'run_convert_videos': 'run the script to convert MP4 videos to AVI format using ffmpeg with parallel processing', 'run_exe_cmd': 'run a shell command and return output or skip if the destination file already exists', 'run_convert_video_wapper': 'run batch video conversion on a list of videos using an ffmpeg command format string', 'run_read_video_list': 'run a scan of subdirectories to collect all MP4 video file paths from a root folder', 'run_main': 'run the main block to convert Kinetics dataset videos from source to destination with optional shuffling'}
```

## File: facebookresearch_glore/dataset/Kinetics/scripts/remove_spaces.py

Prompts

```
['run the script to convert MP4 videos to AVI format using ffmpeg with parallel processing', 'run a shell command and return output or skip if the destination file already exists', 'run batch video conversion on a list of videos using an ffmpeg command format string', 'run a scan of subdirectories to collect all MP4 video file paths from a root folder', 'run the main block to convert Kinetics dataset videos from source to destination with optional shuffling', 'run the script to rename Kinetics dataset folders by replacing spaces with underscores', 'run the remove_spaces script to rename train and val folder names using CSV lists', 'create a function that moves a source file or directory to a destination with logging', 'create a function that reads a CSV and renames folders by replacing spaces with underscores', 'test the rename_folder_name function with a CSV file and root folder path']
```

Usage

```
{'run_rename_folder_name': 'run the script to rename Kinetics dataset folders by replacing spaces with underscores', 'run_remove_spaces_script': 'run the remove_spaces script to rename train and val folder names using CSV lists', 'create_move_function': 'create a function that moves a source file or directory to a destination with logging', 'create_rename_folder_name': 'create a function that reads a CSV and renames folders by replacing spaces with underscores', 'test_rename_folder_name': 'test the rename_folder_name function with a CSV file and root folder path'}
```

