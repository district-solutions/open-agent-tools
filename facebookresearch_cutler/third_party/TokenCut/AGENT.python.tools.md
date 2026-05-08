# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/third_party/TokenCut/datasets.py

Prompts

```
['create an ImageDataset from a single image file path with optional resize dimensions', 'create a Dataset dataloader for VOC07, VOC12, or COCO20k with optional hard image removal', 'extract ground truth bounding boxes and class IDs from COCO targets with iscrowd filtering', 'extract ground truth bounding boxes and class names from VOC targets with optional hard removal', 'compute IoU, GIoU, DIoU, or CIoU between two bounding boxes in x1y1x2y2 or xywh format', 'run TokenCut zero-shot object discovery on a single image using a ViT model and normalized cuts', 'run TokenCut object discovery on VOC07, VOC12, or COCO20k datasets and evaluate corloc accuracy', 'extract key, query, or value features from the last attention layer of a ViT model and save as numpy arrays', 'run the DINO-seg baseline method on images using a specified attention head for segmentation', 'visualize TokenCut predicted bounding boxes and eigenvector heatmaps on input images', 'get a pretrained ViT small model with patch size 16 using DINO weights', 'get a pretrained ViT base model with patch size 8 using DINO weights', 'get a pretrained MoCo ViT small or base model with frozen parameters', 'get a pretrained MAE ViT base model with encoder weights only', 'get a pretrained ResNet50 model with DINO weights and frozen parameters', 'run the ncut function to apply Normalized Cut on image patch features and extract object bounding boxes', 'run the detect_box function to extract a bounding box from a bipartition mask using connected components', 'refactor the ncut function to support a custom tau threshold for graph construction edge weights', 'review the ncut function eigenvector computation and bipartition logic for object discovery', 'summarize the detect_box function connected component labeling and bounding box rescaling to image coordinates', 'save an image array to a specified folder using PIL Image.fromarray', 'draw a predicted bounding box on an image and save the result', 'draw predicted and ground truth bounding boxes on an image for comparison', 'visualize and save the second smallest eigenvector as a heat map image', 'review the visualize_predictions_gt function to fix the len(gt>1) bug']
```

Usage

```
{'create_ImageDataset': 'create an ImageDataset from a single image file path with optional resize dimensions', 'create_Dataset': 'create a Dataset dataloader for VOC07, VOC12, or COCO20k with optional hard image removal', 'extract_gt_COCO': 'extract ground truth bounding boxes and class IDs from COCO targets with iscrowd filtering', 'extract_gt_VOC': 'extract ground truth bounding boxes and class names from VOC targets with optional hard removal', 'compute_bbox_iou': 'compute IoU, GIoU, DIoU, or CIoU between two bounding boxes in x1y1x2y2 or xywh format'}
```

## File: facebookresearch_cutler/third_party/TokenCut/main_tokencut.py

Prompts

```
['create an ImageDataset from a single image file path with optional resize dimensions', 'create a Dataset dataloader for VOC07, VOC12, or COCO20k with optional hard image removal', 'extract ground truth bounding boxes and class IDs from COCO targets with iscrowd filtering', 'extract ground truth bounding boxes and class names from VOC targets with optional hard removal', 'compute IoU, GIoU, DIoU, or CIoU between two bounding boxes in x1y1x2y2 or xywh format', 'run TokenCut zero-shot object discovery on a single image using a ViT model and normalized cuts', 'run TokenCut object discovery on VOC07, VOC12, or COCO20k datasets and evaluate corloc accuracy', 'extract key, query, or value features from the last attention layer of a ViT model and save as numpy arrays', 'run the DINO-seg baseline method on images using a specified attention head for segmentation', 'visualize TokenCut predicted bounding boxes and eigenvector heatmaps on input images', 'get a pretrained ViT small model with patch size 16 using DINO weights', 'get a pretrained ViT base model with patch size 8 using DINO weights', 'get a pretrained MoCo ViT small or base model with frozen parameters', 'get a pretrained MAE ViT base model with encoder weights only', 'get a pretrained ResNet50 model with DINO weights and frozen parameters', 'run the ncut function to apply Normalized Cut on image patch features and extract object bounding boxes', 'run the detect_box function to extract a bounding box from a bipartition mask using connected components', 'refactor the ncut function to support a custom tau threshold for graph construction edge weights', 'review the ncut function eigenvector computation and bipartition logic for object discovery', 'summarize the detect_box function connected component labeling and bounding box rescaling to image coordinates', 'save an image array to a specified folder using PIL Image.fromarray', 'draw a predicted bounding box on an image and save the result', 'draw predicted and ground truth bounding boxes on an image for comparison', 'visualize and save the second smallest eigenvector as a heat map image', 'review the visualize_predictions_gt function to fix the len(gt>1) bug']
```

Usage

```
{'run_tokencut_object_discovery': 'run TokenCut zero-shot object discovery on a single image using a ViT model and normalized cuts', 'run_tokencut_on_dataset': 'run TokenCut object discovery on VOC07, VOC12, or COCO20k datasets and evaluate corloc accuracy', 'extract_vit_features': 'extract key, query, or value features from the last attention layer of a ViT model and save as numpy arrays', 'run_dinoseg_baseline': 'run the DINO-seg baseline method on images using a specified attention head for segmentation', 'visualize_tokencut_predictions': 'visualize TokenCut predicted bounding boxes and eigenvector heatmaps on input images'}
```

## File: facebookresearch_cutler/third_party/TokenCut/networks.py

Prompts

```
['create an ImageDataset from a single image file path with optional resize dimensions', 'create a Dataset dataloader for VOC07, VOC12, or COCO20k with optional hard image removal', 'extract ground truth bounding boxes and class IDs from COCO targets with iscrowd filtering', 'extract ground truth bounding boxes and class names from VOC targets with optional hard removal', 'compute IoU, GIoU, DIoU, or CIoU between two bounding boxes in x1y1x2y2 or xywh format', 'run TokenCut zero-shot object discovery on a single image using a ViT model and normalized cuts', 'run TokenCut object discovery on VOC07, VOC12, or COCO20k datasets and evaluate corloc accuracy', 'extract key, query, or value features from the last attention layer of a ViT model and save as numpy arrays', 'run the DINO-seg baseline method on images using a specified attention head for segmentation', 'visualize TokenCut predicted bounding boxes and eigenvector heatmaps on input images', 'get a pretrained ViT small model with patch size 16 using DINO weights', 'get a pretrained ViT base model with patch size 8 using DINO weights', 'get a pretrained MoCo ViT small or base model with frozen parameters', 'get a pretrained MAE ViT base model with encoder weights only', 'get a pretrained ResNet50 model with DINO weights and frozen parameters', 'run the ncut function to apply Normalized Cut on image patch features and extract object bounding boxes', 'run the detect_box function to extract a bounding box from a bipartition mask using connected components', 'refactor the ncut function to support a custom tau threshold for graph construction edge weights', 'review the ncut function eigenvector computation and bipartition logic for object discovery', 'summarize the detect_box function connected component labeling and bounding box rescaling to image coordinates', 'save an image array to a specified folder using PIL Image.fromarray', 'draw a predicted bounding box on an image and save the result', 'draw predicted and ground truth bounding boxes on an image for comparison', 'visualize and save the second smallest eigenvector as a heat map image', 'review the visualize_predictions_gt function to fix the len(gt>1) bug']
```

Usage

```
{'get_model_vit_small': 'get a pretrained ViT small model with patch size 16 using DINO weights', 'get_model_vit_base': 'get a pretrained ViT base model with patch size 8 using DINO weights', 'get_model_moco': 'get a pretrained MoCo ViT small or base model with frozen parameters', 'get_model_mae': 'get a pretrained MAE ViT base model with encoder weights only', 'get_model_resnet50': 'get a pretrained ResNet50 model with DINO weights and frozen parameters'}
```

## File: facebookresearch_cutler/third_party/TokenCut/object_discovery.py

Prompts

```
['create an ImageDataset from a single image file path with optional resize dimensions', 'create a Dataset dataloader for VOC07, VOC12, or COCO20k with optional hard image removal', 'extract ground truth bounding boxes and class IDs from COCO targets with iscrowd filtering', 'extract ground truth bounding boxes and class names from VOC targets with optional hard removal', 'compute IoU, GIoU, DIoU, or CIoU between two bounding boxes in x1y1x2y2 or xywh format', 'run TokenCut zero-shot object discovery on a single image using a ViT model and normalized cuts', 'run TokenCut object discovery on VOC07, VOC12, or COCO20k datasets and evaluate corloc accuracy', 'extract key, query, or value features from the last attention layer of a ViT model and save as numpy arrays', 'run the DINO-seg baseline method on images using a specified attention head for segmentation', 'visualize TokenCut predicted bounding boxes and eigenvector heatmaps on input images', 'get a pretrained ViT small model with patch size 16 using DINO weights', 'get a pretrained ViT base model with patch size 8 using DINO weights', 'get a pretrained MoCo ViT small or base model with frozen parameters', 'get a pretrained MAE ViT base model with encoder weights only', 'get a pretrained ResNet50 model with DINO weights and frozen parameters', 'run the ncut function to apply Normalized Cut on image patch features and extract object bounding boxes', 'run the detect_box function to extract a bounding box from a bipartition mask using connected components', 'refactor the ncut function to support a custom tau threshold for graph construction edge weights', 'review the ncut function eigenvector computation and bipartition logic for object discovery', 'summarize the detect_box function connected component labeling and bounding box rescaling to image coordinates', 'save an image array to a specified folder using PIL Image.fromarray', 'draw a predicted bounding box on an image and save the result', 'draw predicted and ground truth bounding boxes on an image for comparison', 'visualize and save the second smallest eigenvector as a heat map image', 'review the visualize_predictions_gt function to fix the len(gt>1) bug']
```

Usage

```
{'run_ncut_normalized_cut': 'run the ncut function to apply Normalized Cut on image patch features and extract object bounding boxes', 'run_detect_box_bounding_box': 'run the detect_box function to extract a bounding box from a bipartition mask using connected components', 'refactor_ncut_threshold': 'refactor the ncut function to support a custom tau threshold for graph construction edge weights', 'review_ncut_eigenvector_bipartition': 'review the ncut function eigenvector computation and bipartition logic for object discovery', 'summarize_detect_box_connected_components': 'summarize the detect_box function connected component labeling and bounding box rescaling to image coordinates'}
```

## File: facebookresearch_cutler/third_party/TokenCut/visualizations.py

Prompts

```
['create an ImageDataset from a single image file path with optional resize dimensions', 'create a Dataset dataloader for VOC07, VOC12, or COCO20k with optional hard image removal', 'extract ground truth bounding boxes and class IDs from COCO targets with iscrowd filtering', 'extract ground truth bounding boxes and class names from VOC targets with optional hard removal', 'compute IoU, GIoU, DIoU, or CIoU between two bounding boxes in x1y1x2y2 or xywh format', 'run TokenCut zero-shot object discovery on a single image using a ViT model and normalized cuts', 'run TokenCut object discovery on VOC07, VOC12, or COCO20k datasets and evaluate corloc accuracy', 'extract key, query, or value features from the last attention layer of a ViT model and save as numpy arrays', 'run the DINO-seg baseline method on images using a specified attention head for segmentation', 'visualize TokenCut predicted bounding boxes and eigenvector heatmaps on input images', 'get a pretrained ViT small model with patch size 16 using DINO weights', 'get a pretrained ViT base model with patch size 8 using DINO weights', 'get a pretrained MoCo ViT small or base model with frozen parameters', 'get a pretrained MAE ViT base model with encoder weights only', 'get a pretrained ResNet50 model with DINO weights and frozen parameters', 'run the ncut function to apply Normalized Cut on image patch features and extract object bounding boxes', 'run the detect_box function to extract a bounding box from a bipartition mask using connected components', 'refactor the ncut function to support a custom tau threshold for graph construction edge weights', 'review the ncut function eigenvector computation and bipartition logic for object discovery', 'summarize the detect_box function connected component labeling and bounding box rescaling to image coordinates', 'save an image array to a specified folder using PIL Image.fromarray', 'draw a predicted bounding box on an image and save the result', 'draw predicted and ground truth bounding boxes on an image for comparison', 'visualize and save the second smallest eigenvector as a heat map image', 'review the visualize_predictions_gt function to fix the len(gt>1) bug']
```

Usage

```
{'visualize_img': 'save an image array to a specified folder using PIL Image.fromarray', 'visualize_predictions': 'draw a predicted bounding box on an image and save the result', 'visualize_predictions_gt': 'draw predicted and ground truth bounding boxes on an image for comparison', 'visualize_eigvec': 'visualize and save the second smallest eigenvector as a heat map image', 'review_visualize_predictions_gt': 'review the visualize_predictions_gt function to fix the len(gt>1) bug'}
```

