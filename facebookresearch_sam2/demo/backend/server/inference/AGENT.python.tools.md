# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/demo/backend/server/inference/multipart.py

Prompts

```
['build a multipart response using MultipartResponseBuilder.build with a boundary, headers dict, and body string', 'get the assembled multipart message bytes from a MultipartResponseBuilder instance using get_message', 'build a multipart response with a bytes body by passing bytes directly to MultipartResponseBuilder.build', 'create a MultipartResponseBuilder instance with a boundary string to start assembling a multipart message', 'review the MultipartResponseBuilder class and its build, get_message, append_header, and append_body methods', 'create a SAM 2 video tracking session by initializing the predictor with a video file path', 'add interactive point prompts to a video frame to select and label objects for tracking', 'propagate object tracking masks forward and backward across all frames in a video', 'remove a tracked object by its ID from the current video tracking session state', 'cancel an ongoing video propagation tracking operation for a specific session']
```

Usage

```
{'build_multipart_response': 'build a multipart response using MultipartResponseBuilder.build with a boundary, headers dict, and body string', 'get_multipart_message': 'get the assembled multipart message bytes from a MultipartResponseBuilder instance using get_message', 'build_multipart_with_bytes_body': 'build a multipart response with a bytes body by passing bytes directly to MultipartResponseBuilder.build', 'create_multipart_builder': 'create a MultipartResponseBuilder instance with a boundary string to start assembling a multipart message', 'review_multipart_builder_class': 'review the MultipartResponseBuilder class and its build, get_message, append_header, and append_body methods'}
```

## File: facebookresearch_sam2/demo/backend/server/inference/predictor.py

Prompts

```
['build a multipart response using MultipartResponseBuilder.build with a boundary, headers dict, and body string', 'get the assembled multipart message bytes from a MultipartResponseBuilder instance using get_message', 'build a multipart response with a bytes body by passing bytes directly to MultipartResponseBuilder.build', 'create a MultipartResponseBuilder instance with a boundary string to start assembling a multipart message', 'review the MultipartResponseBuilder class and its build, get_message, append_header, and append_body methods', 'create a SAM 2 video tracking session by initializing the predictor with a video file path', 'add interactive point prompts to a video frame to select and label objects for tracking', 'propagate object tracking masks forward and backward across all frames in a video', 'remove a tracked object by its ID from the current video tracking session state', 'cancel an ongoing video propagation tracking operation for a specific session']
```

Usage

```
{'start_tracking_session': 'create a SAM 2 video tracking session by initializing the predictor with a video file path', 'add_points_to_frame': 'add interactive point prompts to a video frame to select and label objects for tracking', 'propagate_tracking_in_video': 'propagate object tracking masks forward and backward across all frames in a video', 'remove_tracked_object': 'remove a tracked object by its ID from the current video tracking session state', 'cancel_video_propagation': 'cancel an ongoing video propagation tracking operation for a specific session'}
```

