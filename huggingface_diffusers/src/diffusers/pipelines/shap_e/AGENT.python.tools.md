# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/src/diffusers/pipelines/shap_e/camera.py

Prompts

```
['create 20 evenly spaced panoramic cameras orbiting a point using create_pan_cameras', 'create a DifferentiableProjectiveCamera dataclass with origin, x, y, z tensors and field of view', 'get normalized camera rays from pixel coordinates using get_camera_rays on a camera instance', 'get all camera rays for every pixel using the camera_rays property on a camera instance', 'resize a DifferentiableProjectiveCamera to new dimensions while preserving aspect ratio using resize_image', 'generate a 3D asset from a text prompt using the ShapEPipeline with NeRF rendering', 'encode a text prompt into CLIP embeddings using the _encode_prompt method with classifier-free guidance', 'prepare random Gaussian latents scaled by the scheduler noise sigma for the prior model', 'render a 3D mesh from generated latents using the ShapE renderer decode_to_mesh method', 'render a 2D image from generated latents using the ShapE renderer decode_to_image method', 'run the ShapEImg2ImgPipeline to generate 3D rendered images from an input PIL image', 'encode an input image into CLIP image embeddings using the image encoder and processor', 'prepare random or provided latents scaled by the scheduler init noise sigma', 'decode latent representations into 3D mesh objects using the ShapE renderer', 'decode latent representations into rendered image frames using the ShapE renderer', 'render rays through a 3D volume using coarse and fine stratified sampling for NeRF rendering', 'decode ShapE latents into a rendered image using the ShapERenderer with coarse and fine ray sampling', 'decode ShapE latents into a textured 3D mesh using marching cubes on the signed distance field', 'integrate density and channel samples along ray timesteps to compute weighted RGB output and transmittance', 'construct a 3D triangle mesh from a signed distance field using the marching cubes algorithm']
```

Usage

```
{'create_pan_cameras': 'create 20 evenly spaced panoramic cameras orbiting a point using create_pan_cameras', 'create_differentiable_projective_camera': 'create a DifferentiableProjectiveCamera dataclass with origin, x, y, z tensors and field of view', 'get_camera_rays': 'get normalized camera rays from pixel coordinates using get_camera_rays on a camera instance', 'get_camera_rays_property': 'get all camera rays for every pixel using the camera_rays property on a camera instance', 'resize_image': 'resize a DifferentiableProjectiveCamera to new dimensions while preserving aspect ratio using resize_image'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/shap_e/pipeline_shap_e.py

Prompts

```
['create 20 evenly spaced panoramic cameras orbiting a point using create_pan_cameras', 'create a DifferentiableProjectiveCamera dataclass with origin, x, y, z tensors and field of view', 'get normalized camera rays from pixel coordinates using get_camera_rays on a camera instance', 'get all camera rays for every pixel using the camera_rays property on a camera instance', 'resize a DifferentiableProjectiveCamera to new dimensions while preserving aspect ratio using resize_image', 'generate a 3D asset from a text prompt using the ShapEPipeline with NeRF rendering', 'encode a text prompt into CLIP embeddings using the _encode_prompt method with classifier-free guidance', 'prepare random Gaussian latents scaled by the scheduler noise sigma for the prior model', 'render a 3D mesh from generated latents using the ShapE renderer decode_to_mesh method', 'render a 2D image from generated latents using the ShapE renderer decode_to_image method', 'run the ShapEImg2ImgPipeline to generate 3D rendered images from an input PIL image', 'encode an input image into CLIP image embeddings using the image encoder and processor', 'prepare random or provided latents scaled by the scheduler init noise sigma', 'decode latent representations into 3D mesh objects using the ShapE renderer', 'decode latent representations into rendered image frames using the ShapE renderer', 'render rays through a 3D volume using coarse and fine stratified sampling for NeRF rendering', 'decode ShapE latents into a rendered image using the ShapERenderer with coarse and fine ray sampling', 'decode ShapE latents into a textured 3D mesh using marching cubes on the signed distance field', 'integrate density and channel samples along ray timesteps to compute weighted RGB output and transmittance', 'construct a 3D triangle mesh from a signed distance field using the marching cubes algorithm']
```

Usage

```
{'generate_3d_from_prompt': 'generate a 3D asset from a text prompt using the ShapEPipeline with NeRF rendering', 'encode_prompt_embeddings': 'encode a text prompt into CLIP embeddings using the _encode_prompt method with classifier-free guidance', 'prepare_latents_for_prior': 'prepare random Gaussian latents scaled by the scheduler noise sigma for the prior model', 'render_mesh_from_latent': 'render a 3D mesh from generated latents using the ShapE renderer decode_to_mesh method', 'render_image_from_latent': 'render a 2D image from generated latents using the ShapE renderer decode_to_image method'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/shap_e/pipeline_shap_e_img2img.py

Prompts

```
['create 20 evenly spaced panoramic cameras orbiting a point using create_pan_cameras', 'create a DifferentiableProjectiveCamera dataclass with origin, x, y, z tensors and field of view', 'get normalized camera rays from pixel coordinates using get_camera_rays on a camera instance', 'get all camera rays for every pixel using the camera_rays property on a camera instance', 'resize a DifferentiableProjectiveCamera to new dimensions while preserving aspect ratio using resize_image', 'generate a 3D asset from a text prompt using the ShapEPipeline with NeRF rendering', 'encode a text prompt into CLIP embeddings using the _encode_prompt method with classifier-free guidance', 'prepare random Gaussian latents scaled by the scheduler noise sigma for the prior model', 'render a 3D mesh from generated latents using the ShapE renderer decode_to_mesh method', 'render a 2D image from generated latents using the ShapE renderer decode_to_image method', 'run the ShapEImg2ImgPipeline to generate 3D rendered images from an input PIL image', 'encode an input image into CLIP image embeddings using the image encoder and processor', 'prepare random or provided latents scaled by the scheduler init noise sigma', 'decode latent representations into 3D mesh objects using the ShapE renderer', 'decode latent representations into rendered image frames using the ShapE renderer', 'render rays through a 3D volume using coarse and fine stratified sampling for NeRF rendering', 'decode ShapE latents into a rendered image using the ShapERenderer with coarse and fine ray sampling', 'decode ShapE latents into a textured 3D mesh using marching cubes on the signed distance field', 'integrate density and channel samples along ray timesteps to compute weighted RGB output and transmittance', 'construct a 3D triangle mesh from a signed distance field using the marching cubes algorithm']
```

Usage

```
{'run_pipeline_img2img': 'run the ShapEImg2ImgPipeline to generate 3D rendered images from an input PIL image', 'encode_image_embeddings': 'encode an input image into CLIP image embeddings using the image encoder and processor', 'prepare_latents': 'prepare random or provided latents scaled by the scheduler init noise sigma', 'decode_to_mesh': 'decode latent representations into 3D mesh objects using the ShapE renderer', 'decode_to_image': 'decode latent representations into rendered image frames using the ShapE renderer'}
```

## File: huggingface_diffusers/src/diffusers/pipelines/shap_e/renderer.py

Prompts

```
['create 20 evenly spaced panoramic cameras orbiting a point using create_pan_cameras', 'create a DifferentiableProjectiveCamera dataclass with origin, x, y, z tensors and field of view', 'get normalized camera rays from pixel coordinates using get_camera_rays on a camera instance', 'get all camera rays for every pixel using the camera_rays property on a camera instance', 'resize a DifferentiableProjectiveCamera to new dimensions while preserving aspect ratio using resize_image', 'generate a 3D asset from a text prompt using the ShapEPipeline with NeRF rendering', 'encode a text prompt into CLIP embeddings using the _encode_prompt method with classifier-free guidance', 'prepare random Gaussian latents scaled by the scheduler noise sigma for the prior model', 'render a 3D mesh from generated latents using the ShapE renderer decode_to_mesh method', 'render a 2D image from generated latents using the ShapE renderer decode_to_image method', 'run the ShapEImg2ImgPipeline to generate 3D rendered images from an input PIL image', 'encode an input image into CLIP image embeddings using the image encoder and processor', 'prepare random or provided latents scaled by the scheduler init noise sigma', 'decode latent representations into 3D mesh objects using the ShapE renderer', 'decode latent representations into rendered image frames using the ShapE renderer', 'render rays through a 3D volume using coarse and fine stratified sampling for NeRF rendering', 'decode ShapE latents into a rendered image using the ShapERenderer with coarse and fine ray sampling', 'decode ShapE latents into a textured 3D mesh using marching cubes on the signed distance field', 'integrate density and channel samples along ray timesteps to compute weighted RGB output and transmittance', 'construct a 3D triangle mesh from a signed distance field using the marching cubes algorithm']
```

Usage

```
{'render_rays_volumetric': 'render rays through a 3D volume using coarse and fine stratified sampling for NeRF rendering', 'decode_latents_to_image': 'decode ShapE latents into a rendered image using the ShapERenderer with coarse and fine ray sampling', 'decode_latents_to_mesh': 'decode ShapE latents into a textured 3D mesh using marching cubes on the signed distance field', 'integrate_volume_samples': 'integrate density and channel samples along ray timesteps to compute weighted RGB output and transmittance', 'march_cubes_sdf_to_mesh': 'construct a 3D triangle mesh from a signed distance field using the marching cubes algorithm'}
```

