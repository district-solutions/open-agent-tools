# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/demo/backend/server/app.py

Prompts

```
['run the Flask app on host 0.0.0.0 port 5000 to serve the SAM2 inference API', 'call the propagate_in_video endpoint to stream mask predictions frame by frame for a video session', 'serve gallery video files from the configured GALLERY_PATH directory via HTTP GET requests', 'serve poster image files from the configured POSTERS_PATH directory via HTTP GET requests', 'serve user uploaded video files from the configured UPLOADS_PATH directory via HTTP GET requests']
```

Usage

```
{'run_flask_server': 'run the Flask app on host 0.0.0.0 port 5000 to serve the SAM2 inference API', 'propagate_in_video': 'call the propagate_in_video endpoint to stream mask predictions frame by frame for a video session', 'serve_gallery_videos': 'serve gallery video files from the configured GALLERY_PATH directory via HTTP GET requests', 'serve_poster_images': 'serve poster image files from the configured POSTERS_PATH directory via HTTP GET requests', 'serve_uploaded_videos': 'serve user uploaded video files from the configured UPLOADS_PATH directory via HTTP GET requests'}
```

