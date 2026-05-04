# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/scripts/gen_repre.py

Prompts

```
['generate a raw feature-based object representation from template images using a DINOv2 extractor', 'generate a complete object representation with PCA reduction, k-means clustering, and TF-IDF template descriptors', 'batch generate object representations for all object IDs in a specified BOP dataset', 'configure feature extraction, PCA, clustering, and template descriptor options for object representation generation', 'run the object representation generation pipeline from command-line arguments or a JSON config file', 'run the script to synthesize RGB, depth, and mask templates for 3D object models from a BOP dataset', 'create a GenTemplatesOpts named tuple to configure viewpoint sampling, mesh preprocessing, rendering, and cropping parameters', 'generate camera viewpoints using fibonacci sphere sampling across multiple radius shells for comprehensive object coverage', 'render an object model from a given viewpoint using the PyRender rasterizer with color, depth, and mask outputs', 'crop rendered template images to the object bounding box and warp them to a virtual camera viewport', 'run 6D object pose inference on BOP test images using DINOv2 features and PnP', 'run the infer function with InferOpts to estimate object poses from images', 'create an InferOpts NamedTuple to configure cropping, feature extraction, and PnP parameters', 'review the infer function that establishes 2D-3D correspondences and solves coarse poses via PnP', 'summarize the InferOpts configuration options for feature matching, RANSAC, and visualization settings']
```

Usage

```
{'generate_raw_repre': 'generate a raw feature-based object representation from template images using a DINOv2 extractor', 'generate_repre': 'generate a complete object representation with PCA reduction, k-means clustering, and TF-IDF template descriptors', 'generate_repre_from_list': 'batch generate object representations for all object IDs in a specified BOP dataset', 'GenRepreOpts': 'configure feature extraction, PCA, clustering, and template descriptor options for object representation generation', 'main': 'run the object representation generation pipeline from command-line arguments or a JSON config file'}
```

## File: facebookresearch_foundpose/scripts/gen_templates.py

Prompts

```
['generate a raw feature-based object representation from template images using a DINOv2 extractor', 'generate a complete object representation with PCA reduction, k-means clustering, and TF-IDF template descriptors', 'batch generate object representations for all object IDs in a specified BOP dataset', 'configure feature extraction, PCA, clustering, and template descriptor options for object representation generation', 'run the object representation generation pipeline from command-line arguments or a JSON config file', 'run the script to synthesize RGB, depth, and mask templates for 3D object models from a BOP dataset', 'create a GenTemplatesOpts named tuple to configure viewpoint sampling, mesh preprocessing, rendering, and cropping parameters', 'generate camera viewpoints using fibonacci sphere sampling across multiple radius shells for comprehensive object coverage', 'render an object model from a given viewpoint using the PyRender rasterizer with color, depth, and mask outputs', 'crop rendered template images to the object bounding box and warp them to a virtual camera viewport', 'run 6D object pose inference on BOP test images using DINOv2 features and PnP', 'run the infer function with InferOpts to estimate object poses from images', 'create an InferOpts NamedTuple to configure cropping, feature extraction, and PnP parameters', 'review the infer function that establishes 2D-3D correspondences and solves coarse poses via PnP', 'summarize the InferOpts configuration options for feature matching, RANSAC, and visualization settings']
```

Usage

```
{'synthesize_object_templates': 'run the script to synthesize RGB, depth, and mask templates for 3D object models from a BOP dataset', 'configure_template_generation_options': 'create a GenTemplatesOpts named tuple to configure viewpoint sampling, mesh preprocessing, rendering, and cropping parameters', 'sample_viewpoints_on_viewsphere': 'generate camera viewpoints using fibonacci sphere sampling across multiple radius shells for comprehensive object coverage', 'render_object_with_pyrender': 'render an object model from a given viewpoint using the PyRender rasterizer with color, depth, and mask outputs', 'crop_and_warp_template_images': 'crop rendered template images to the object bounding box and warp them to a virtual camera viewport'}
```

## File: facebookresearch_foundpose/scripts/infer.py

Prompts

```
['generate a raw feature-based object representation from template images using a DINOv2 extractor', 'generate a complete object representation with PCA reduction, k-means clustering, and TF-IDF template descriptors', 'batch generate object representations for all object IDs in a specified BOP dataset', 'configure feature extraction, PCA, clustering, and template descriptor options for object representation generation', 'run the object representation generation pipeline from command-line arguments or a JSON config file', 'run the script to synthesize RGB, depth, and mask templates for 3D object models from a BOP dataset', 'create a GenTemplatesOpts named tuple to configure viewpoint sampling, mesh preprocessing, rendering, and cropping parameters', 'generate camera viewpoints using fibonacci sphere sampling across multiple radius shells for comprehensive object coverage', 'render an object model from a given viewpoint using the PyRender rasterizer with color, depth, and mask outputs', 'crop rendered template images to the object bounding box and warp them to a virtual camera viewport', 'run 6D object pose inference on BOP test images using DINOv2 features and PnP', 'run the infer function with InferOpts to estimate object poses from images', 'create an InferOpts NamedTuple to configure cropping, feature extraction, and PnP parameters', 'review the infer function that establishes 2D-3D correspondences and solves coarse poses via PnP', 'summarize the InferOpts configuration options for feature matching, RANSAC, and visualization settings']
```

Usage

```
{'run_pose_inference': 'run 6D object pose inference on BOP test images using DINOv2 features and PnP', 'run_infer_with_opts': 'run the infer function with InferOpts to estimate object poses from images', 'create_InferOpts': 'create an InferOpts NamedTuple to configure cropping, feature extraction, and PnP parameters', 'review_infer_function': 'review the infer function that establishes 2D-3D correspondences and solves coarse poses via PnP', 'summarize_InferOpts': 'summarize the InferOpts configuration options for feature matching, RANSAC, and visualization settings'}
```

