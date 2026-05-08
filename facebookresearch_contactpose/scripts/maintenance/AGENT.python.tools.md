# Agent Python Tools

- repo: facebookresearch/contactpose
- repo_uri: https://github.com/facebookresearch/contactpose

## File: facebookresearch_contactpose/scripts/maintenance/get_urls.py

Prompts

```
['run the script with --p_id to generate Dropbox shared links for all video objects of a participant', 'create a public Dropbox shared link for a video path using the get_url function', 'update the data/urls.json file with new Dropbox shared URLs for video color objects', 'refactor the get_url function to use requests directly instead of writing to a temporary JSON file', 'review the data_template settings for Dropbox API sharing visibility and access configuration', 'move Kinect camera video files from a participant folder into a new color subfolder on Dropbox', 'create a new folder on Dropbox at the specified path using files_create_folder', 'check if a video file exists on Dropbox using files_get_metadata before moving it', 'move a video file from one Dropbox path to another using files_move', 'run the maintenance script to batch move participant videos into organized color subfolders on Dropbox', 'run produce to download images and encode contact pose videos for a participant number', 'run produce with cleanup flag to retry failed video production tasks from status.json', 'run produce_worker to download images for a task tuple and encode them into video files', 'run produce with parallel mode to process multiple participant-intent-object combinations concurrently using a process pool', 'run produce with explicit tasks list to produce videos for specific participant-intent-object combinations', 'run the remove function to delete zip files and color.mp4 videos for a participant session directory', 'run the remove function to delete all zip files from object subdirectories in a participant session', 'run the remove function to delete color.mp4 files from kinect2_left, kinect2_right, and kinect2_middle camera directories', 'run the remove function to delete all files at the root level of a participant session directory', 'run the script from the command line with a participant number argument to clean up session data']
```

Usage

```
{'run_get_url_for_participant': 'run the script with --p_id to generate Dropbox shared links for all video objects of a participant', 'create_dropbox_shared_link': 'create a public Dropbox shared link for a video path using the get_url function', 'update_urls_json': 'update the data/urls.json file with new Dropbox shared URLs for video color objects', 'refactor_get_url': 'refactor the get_url function to use requests directly instead of writing to a temporary JSON file', 'review_data_template': 'review the data_template settings for Dropbox API sharing visibility and access configuration'}
```

## File: facebookresearch_contactpose/scripts/maintenance/move_videos_dropbox.py

Prompts

```
['run the script with --p_id to generate Dropbox shared links for all video objects of a participant', 'create a public Dropbox shared link for a video path using the get_url function', 'update the data/urls.json file with new Dropbox shared URLs for video color objects', 'refactor the get_url function to use requests directly instead of writing to a temporary JSON file', 'review the data_template settings for Dropbox API sharing visibility and access configuration', 'move Kinect camera video files from a participant folder into a new color subfolder on Dropbox', 'create a new folder on Dropbox at the specified path using files_create_folder', 'check if a video file exists on Dropbox using files_get_metadata before moving it', 'move a video file from one Dropbox path to another using files_move', 'run the maintenance script to batch move participant videos into organized color subfolders on Dropbox', 'run produce to download images and encode contact pose videos for a participant number', 'run produce with cleanup flag to retry failed video production tasks from status.json', 'run produce_worker to download images for a task tuple and encode them into video files', 'run produce with parallel mode to process multiple participant-intent-object combinations concurrently using a process pool', 'run produce with explicit tasks list to produce videos for specific participant-intent-object combinations', 'run the remove function to delete zip files and color.mp4 videos for a participant session directory', 'run the remove function to delete all zip files from object subdirectories in a participant session', 'run the remove function to delete color.mp4 files from kinect2_left, kinect2_right, and kinect2_middle camera directories', 'run the remove function to delete all files at the root level of a participant session directory', 'run the script from the command line with a participant number argument to clean up session data']
```

Usage

```
{'move_dropbox_videos': 'move Kinect camera video files from a participant folder into a new color subfolder on Dropbox', 'create_dropbox_folder': 'create a new folder on Dropbox at the specified path using files_create_folder', 'check_dropbox_file_exists': 'check if a video file exists on Dropbox using files_get_metadata before moving it', 'move_dropbox_file': 'move a video file from one Dropbox path to another using files_move', 'run_video_migration': 'run the maintenance script to batch move participant videos into organized color subfolders on Dropbox'}
```

## File: facebookresearch_contactpose/scripts/maintenance/produce_videos.py

Prompts

```
['run the script with --p_id to generate Dropbox shared links for all video objects of a participant', 'create a public Dropbox shared link for a video path using the get_url function', 'update the data/urls.json file with new Dropbox shared URLs for video color objects', 'refactor the get_url function to use requests directly instead of writing to a temporary JSON file', 'review the data_template settings for Dropbox API sharing visibility and access configuration', 'move Kinect camera video files from a participant folder into a new color subfolder on Dropbox', 'create a new folder on Dropbox at the specified path using files_create_folder', 'check if a video file exists on Dropbox using files_get_metadata before moving it', 'move a video file from one Dropbox path to another using files_move', 'run the maintenance script to batch move participant videos into organized color subfolders on Dropbox', 'run produce to download images and encode contact pose videos for a participant number', 'run produce with cleanup flag to retry failed video production tasks from status.json', 'run produce_worker to download images for a task tuple and encode them into video files', 'run produce with parallel mode to process multiple participant-intent-object combinations concurrently using a process pool', 'run produce with explicit tasks list to produce videos for specific participant-intent-object combinations', 'run the remove function to delete zip files and color.mp4 videos for a participant session directory', 'run the remove function to delete all zip files from object subdirectories in a participant session', 'run the remove function to delete color.mp4 files from kinect2_left, kinect2_right, and kinect2_middle camera directories', 'run the remove function to delete all files at the root level of a participant session directory', 'run the script from the command line with a participant number argument to clean up session data']
```

Usage

```
{'produce_contactpose_videos': 'run produce to download images and encode contact pose videos for a participant number', 'produce_cleanup_failed_tasks': 'run produce with cleanup flag to retry failed video production tasks from status.json', 'produce_worker_download_and_encode': 'run produce_worker to download images for a task tuple and encode them into video files', 'produce_parallel_video_pipeline': 'run produce with parallel mode to process multiple participant-intent-object combinations concurrently using a process pool', 'produce_specific_tasks': 'run produce with explicit tasks list to produce videos for specific participant-intent-object combinations'}
```

## File: facebookresearch_contactpose/scripts/maintenance/remove_videos.py

Prompts

```
['run the script with --p_id to generate Dropbox shared links for all video objects of a participant', 'create a public Dropbox shared link for a video path using the get_url function', 'update the data/urls.json file with new Dropbox shared URLs for video color objects', 'refactor the get_url function to use requests directly instead of writing to a temporary JSON file', 'review the data_template settings for Dropbox API sharing visibility and access configuration', 'move Kinect camera video files from a participant folder into a new color subfolder on Dropbox', 'create a new folder on Dropbox at the specified path using files_create_folder', 'check if a video file exists on Dropbox using files_get_metadata before moving it', 'move a video file from one Dropbox path to another using files_move', 'run the maintenance script to batch move participant videos into organized color subfolders on Dropbox', 'run produce to download images and encode contact pose videos for a participant number', 'run produce with cleanup flag to retry failed video production tasks from status.json', 'run produce_worker to download images for a task tuple and encode them into video files', 'run produce with parallel mode to process multiple participant-intent-object combinations concurrently using a process pool', 'run produce with explicit tasks list to produce videos for specific participant-intent-object combinations', 'run the remove function to delete zip files and color.mp4 videos for a participant session directory', 'run the remove function to delete all zip files from object subdirectories in a participant session', 'run the remove function to delete color.mp4 files from kinect2_left, kinect2_right, and kinect2_middle camera directories', 'run the remove function to delete all files at the root level of a participant session directory', 'run the script from the command line with a participant number argument to clean up session data']
```

Usage

```
{'remove_zip_and_video_files': 'run the remove function to delete zip files and color.mp4 videos for a participant session directory', 'remove_zip_files_from_object_dirs': 'run the remove function to delete all zip files from object subdirectories in a participant session', 'remove_kinect_color_videos': 'run the remove function to delete color.mp4 files from kinect2_left, kinect2_right, and kinect2_middle camera directories', 'remove_session_root_files': 'run the remove function to delete all files at the root level of a participant session directory', 'run_remove_cli': 'run the script from the command line with a participant number argument to clean up session data'}
```

