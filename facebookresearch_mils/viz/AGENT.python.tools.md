# Agent Python Tools

- repo: facebookresearch/mils
- repo_uri: https://github.com/facebookresearch/mils

## File: facebookresearch_mils/viz/image_gen_output_viz.py

Prompts

```
['run the flask app on port 5010 to display image comparison in a browser', 'run process_csv to load a CSV and rearrange baseline and ours image columns', 'run rearrange_images on a DataFrame row to swap baseline and ours image paths', 'review the display_images Flask route that renders the HTML template with image data', 'refactor the html_template Jinja2 string to customize the image comparison table layout', 'run the home route to gather images and log lines from 200 numbered folders', 'run the static files route to serve PNG images from numbered subfolders', 'review the home function that collects images at indices 0, 3, 7, 11, 15, 19 from each folder', 'refactor the main_folder variable to accept a configurable path for the image database directory', 'run the Flask image caption visualization server on port 5006 with debug mode enabled', 'extract captions from log.txt files in a folder tree with optional ablation step selection', 'extract captions from a captions.json file in a given folder and return as a list of dicts', 'view a COCO image by ID alongside ground truth, MeaCap, and model-generated captions', 'serve COCO val2014 image files from the configured images directory via Flask route', 'render the index page that displays COCO images with ground truth, MeaCap, and custom captions', 'load MeaCap model output captions from a JSON file and map them to COCO image IDs']
```

Usage

```
{'run_flask_server': 'run the flask app on port 5010 to display image comparison in a browser', 'run_process_csv': 'run process_csv to load a CSV and rearrange baseline and ours image columns', 'run_rearrange_images': 'run rearrange_images on a DataFrame row to swap baseline and ours image paths', 'review_display_images': 'review the display_images Flask route that renders the HTML template with image data', 'refactor_html_template': 'refactor the html_template Jinja2 string to customize the image comparison table layout'}
```

## File: facebookresearch_mils/viz/image_gen_step_by_step.py

Prompts

```
['run the flask app on port 5010 to display image comparison in a browser', 'run process_csv to load a CSV and rearrange baseline and ours image columns', 'run rearrange_images on a DataFrame row to swap baseline and ours image paths', 'review the display_images Flask route that renders the HTML template with image data', 'refactor the html_template Jinja2 string to customize the image comparison table layout', 'run the home route to gather images and log lines from 200 numbered folders', 'run the static files route to serve PNG images from numbered subfolders', 'review the home function that collects images at indices 0, 3, 7, 11, 15, 19 from each folder', 'refactor the main_folder variable to accept a configurable path for the image database directory', 'run the Flask image caption visualization server on port 5006 with debug mode enabled', 'extract captions from log.txt files in a folder tree with optional ablation step selection', 'extract captions from a captions.json file in a given folder and return as a list of dicts', 'view a COCO image by ID alongside ground truth, MeaCap, and model-generated captions', 'serve COCO val2014 image files from the configured images directory via Flask route', 'render the index page that displays COCO images with ground truth, MeaCap, and custom captions', 'load MeaCap model output captions from a JSON file and map them to COCO image IDs']
```

Usage

```
{'run_flask_server': 'run the flask server on port 5001 to visualize image generation progress step by step', 'run_home_route': 'run the home route to gather images and log lines from 200 numbered folders', 'run_static_files_route': 'run the static files route to serve PNG images from numbered subfolders', 'review_home_function': 'review the home function that collects images at indices 0, 3, 7, 11, 15, 19 from each folder', 'refactor_main_folder_path': 'refactor the main_folder variable to accept a configurable path for the image database directory'}
```

## File: facebookresearch_mils/viz/imagec_viz.py

Prompts

```
['run the flask app on port 5010 to display image comparison in a browser', 'run process_csv to load a CSV and rearrange baseline and ours image columns', 'run rearrange_images on a DataFrame row to swap baseline and ours image paths', 'review the display_images Flask route that renders the HTML template with image data', 'refactor the html_template Jinja2 string to customize the image comparison table layout', 'run the home route to gather images and log lines from 200 numbered folders', 'run the static files route to serve PNG images from numbered subfolders', 'review the home function that collects images at indices 0, 3, 7, 11, 15, 19 from each folder', 'refactor the main_folder variable to accept a configurable path for the image database directory', 'run the Flask image caption visualization server on port 5006 with debug mode enabled', 'extract captions from log.txt files in a folder tree with optional ablation step selection', 'extract captions from a captions.json file in a given folder and return as a list of dicts', 'view a COCO image by ID alongside ground truth, MeaCap, and model-generated captions', 'serve COCO val2014 image files from the configured images directory via Flask route', 'render the index page that displays COCO images with ground truth, MeaCap, and custom captions', 'load MeaCap model output captions from a JSON file and map them to COCO image IDs']
```

Usage

```
{'run_flask_viz_server': 'run the Flask image caption visualization server on port 5006 with debug mode enabled', 'extract_captions_from_logs': 'extract captions from log.txt files in a folder tree with optional ablation step selection', 'extract_captions_from_results': 'extract captions from a captions.json file in a given folder and return as a list of dicts', 'show_image_with_captions': 'view a COCO image by ID alongside ground truth, MeaCap, and model-generated captions', 'serve_coco_images': 'serve COCO val2014 image files from the configured images directory via Flask route'}
```

## File: facebookresearch_mils/viz/imagec_viz_v2.py

Prompts

```
['run the flask app on port 5010 to display image comparison in a browser', 'run process_csv to load a CSV and rearrange baseline and ours image columns', 'run rearrange_images on a DataFrame row to swap baseline and ours image paths', 'review the display_images Flask route that renders the HTML template with image data', 'refactor the html_template Jinja2 string to customize the image comparison table layout', 'run the home route to gather images and log lines from 200 numbered folders', 'run the static files route to serve PNG images from numbered subfolders', 'review the home function that collects images at indices 0, 3, 7, 11, 15, 19 from each folder', 'refactor the main_folder variable to accept a configurable path for the image database directory', 'run the Flask image caption visualization server on port 5006 with debug mode enabled', 'extract captions from log.txt files in a folder tree with optional ablation step selection', 'extract captions from a captions.json file in a given folder and return as a list of dicts', 'view a COCO image by ID alongside ground truth, MeaCap, and model-generated captions', 'serve COCO val2014 image files from the configured images directory via Flask route', 'render the index page that displays COCO images with ground truth, MeaCap, and custom captions', 'load MeaCap model output captions from a JSON file and map them to COCO image IDs']
```

Usage

```
{'run_flask_viz_server': 'run the flask visualization server on port 5012 to compare image captions side by side', 'extract_captions_from_logs': 'extract captions from log.txt files in subdirectories by walking a folder path and choosing a line index', 'render_caption_comparison_page': 'render the index page that displays COCO images with ground truth, MeaCap, and custom captions', 'serve_coco_images': 'serve COCO val2014 image files from the configured images directory via the flask route', 'load_meacap_captions': 'load MeaCap model output captions from a JSON file and map them to COCO image IDs'}
```

