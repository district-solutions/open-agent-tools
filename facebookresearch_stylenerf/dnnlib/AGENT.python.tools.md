# Agent Python Tools

- repo: facebookresearch/stylenerf
- repo_uri: https://github.com/facebookresearch/stylenerf

## File: facebookresearch_stylenerf/dnnlib/camera.py

Prompts

```
['build a python module to compute camera rays from camera matrices and pixel coordinates', 'create a function that generates random or deterministic camera poses on a sphere given angular ranges', 'create a function that transforms pixel positions with depth values to 3D world coordinates', 'create a function that converts 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt', 'create a function that samples importance points from bins weighted by a probability distribution', 'compute the Kaiser window attenuation factor given number of taps, half-bandwidth, and sample rate', 'calculate the Kaiser window beta parameter based on taps, half-bandwidth, and sample rate', 'generate a sinc function tensor from input values with epsilon for numerical stability', 'build a Kaiser window tensor for filter design given taps, half-bandwidth, and sample rate', 'create a lowpass filter kernel using Kaiser windowing with specified cutoff and sample rate', 'build a python module to apply Fourier or Gaussian positional encoding to input coordinates', 'create a python module to generate initial camera rays with sample points and z values', 'test the sample_camera_positions function to generate random camera locations on a sphere', 'refactor the volume rendering integration function to support custom alpha clamping modes', 'extract a 3D mesh from a NeRF model using marching cubes on the sigma field', 'create an EasyDict that allows attribute-style access to dictionary keys and values', 'create a Logger to redirect stdout and stderr to a file with optional flushing', 'call a Python function by its fully-qualified name string with positional and keyword arguments', 'construct an instance of a Python class given its fully-qualified name and constructor arguments', 'download a URL to a cached file and return a binary file object or filename']
```

Usage

```
{'build_camera_rays': 'build a python module to compute camera rays from camera matrices and pixel coordinates', 'create_camera_pose': 'create a function that generates random or deterministic camera poses on a sphere given angular ranges', 'transform_pixels_to_world': 'create a function that transforms pixel positions with depth values to 3D world coordinates', 'convert_rotation_6d_to_matrix': 'create a function that converts 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt', 'sample_pdf_bins': 'create a function that samples importance points from bins weighted by a probability distribution'}
```

## File: facebookresearch_stylenerf/dnnlib/filters.py

Prompts

```
['build a python module to compute camera rays from camera matrices and pixel coordinates', 'create a function that generates random or deterministic camera poses on a sphere given angular ranges', 'create a function that transforms pixel positions with depth values to 3D world coordinates', 'create a function that converts 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt', 'create a function that samples importance points from bins weighted by a probability distribution', 'compute the Kaiser window attenuation factor given number of taps, half-bandwidth, and sample rate', 'calculate the Kaiser window beta parameter based on taps, half-bandwidth, and sample rate', 'generate a sinc function tensor from input values with epsilon for numerical stability', 'build a Kaiser window tensor for filter design given taps, half-bandwidth, and sample rate', 'create a lowpass filter kernel using Kaiser windowing with specified cutoff and sample rate', 'build a python module to apply Fourier or Gaussian positional encoding to input coordinates', 'create a python module to generate initial camera rays with sample points and z values', 'test the sample_camera_positions function to generate random camera locations on a sphere', 'refactor the volume rendering integration function to support custom alpha clamping modes', 'extract a 3D mesh from a NeRF model using marching cubes on the sigma field', 'create an EasyDict that allows attribute-style access to dictionary keys and values', 'create a Logger to redirect stdout and stderr to a file with optional flushing', 'call a Python function by its fully-qualified name string with positional and keyword arguments', 'construct an instance of a Python class given its fully-qualified name and constructor arguments', 'download a URL to a cached file and return a binary file object or filename']
```

Usage

```
{'compute_kaiser_attenuation': 'compute the Kaiser window attenuation factor given number of taps, half-bandwidth, and sample rate', 'calculate_kaiser_beta': 'calculate the Kaiser window beta parameter based on taps, half-bandwidth, and sample rate', 'generate_sinc_function': 'generate a sinc function tensor from input values with epsilon for numerical stability', 'build_kaiser_window': 'build a Kaiser window tensor for filter design given taps, half-bandwidth, and sample rate', 'create_lowpass_filter': 'create a lowpass filter kernel using Kaiser windowing with specified cutoff and sample rate'}
```

## File: facebookresearch_stylenerf/dnnlib/geometry.py

Prompts

```
['build a python module to compute camera rays from camera matrices and pixel coordinates', 'create a function that generates random or deterministic camera poses on a sphere given angular ranges', 'create a function that transforms pixel positions with depth values to 3D world coordinates', 'create a function that converts 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt', 'create a function that samples importance points from bins weighted by a probability distribution', 'compute the Kaiser window attenuation factor given number of taps, half-bandwidth, and sample rate', 'calculate the Kaiser window beta parameter based on taps, half-bandwidth, and sample rate', 'generate a sinc function tensor from input values with epsilon for numerical stability', 'build a Kaiser window tensor for filter design given taps, half-bandwidth, and sample rate', 'create a lowpass filter kernel using Kaiser windowing with specified cutoff and sample rate', 'build a python module to apply Fourier or Gaussian positional encoding to input coordinates', 'create a python module to generate initial camera rays with sample points and z values', 'test the sample_camera_positions function to generate random camera locations on a sphere', 'refactor the volume rendering integration function to support custom alpha clamping modes', 'extract a 3D mesh from a NeRF model using marching cubes on the sigma field', 'create an EasyDict that allows attribute-style access to dictionary keys and values', 'create a Logger to redirect stdout and stderr to a file with optional flushing', 'call a Python function by its fully-qualified name string with positional and keyword arguments', 'construct an instance of a Python class given its fully-qualified name and constructor arguments', 'download a URL to a cached file and return a binary file object or filename']
```

Usage

```
{'build_positional_encoding': 'build a python module to apply Fourier or Gaussian positional encoding to input coordinates', 'create_camera_rays': 'create a python module to generate initial camera rays with sample points and z values', 'test_sample_camera_positions': 'test the sample_camera_positions function to generate random camera locations on a sphere', 'refactor_integration': 'refactor the volume rendering integration function to support custom alpha clamping modes', 'extract_geometry_mesh': 'extract a 3D mesh from a NeRF model using marching cubes on the sigma field'}
```

## File: facebookresearch_stylenerf/dnnlib/util.py

Prompts

```
['build a python module to compute camera rays from camera matrices and pixel coordinates', 'create a function that generates random or deterministic camera poses on a sphere given angular ranges', 'create a function that transforms pixel positions with depth values to 3D world coordinates', 'create a function that converts 6D rotation representations to 3x3 rotation matrices using Gram-Schmidt', 'create a function that samples importance points from bins weighted by a probability distribution', 'compute the Kaiser window attenuation factor given number of taps, half-bandwidth, and sample rate', 'calculate the Kaiser window beta parameter based on taps, half-bandwidth, and sample rate', 'generate a sinc function tensor from input values with epsilon for numerical stability', 'build a Kaiser window tensor for filter design given taps, half-bandwidth, and sample rate', 'create a lowpass filter kernel using Kaiser windowing with specified cutoff and sample rate', 'build a python module to apply Fourier or Gaussian positional encoding to input coordinates', 'create a python module to generate initial camera rays with sample points and z values', 'test the sample_camera_positions function to generate random camera locations on a sphere', 'refactor the volume rendering integration function to support custom alpha clamping modes', 'extract a 3D mesh from a NeRF model using marching cubes on the sigma field', 'create an EasyDict that allows attribute-style access to dictionary keys and values', 'create a Logger to redirect stdout and stderr to a file with optional flushing', 'call a Python function by its fully-qualified name string with positional and keyword arguments', 'construct an instance of a Python class given its fully-qualified name and constructor arguments', 'download a URL to a cached file and return a binary file object or filename']
```

Usage

```
{'create_EasyDict': 'create an EasyDict that allows attribute-style access to dictionary keys and values', 'create_Logger': 'create a Logger to redirect stdout and stderr to a file with optional flushing', 'call_func_by_name': 'call a Python function by its fully-qualified name string with positional and keyword arguments', 'construct_class_by_name': 'construct an instance of a Python class given its fully-qualified name and constructor arguments', 'open_url': 'download a URL to a cached file and return a binary file object or filename'}
```

