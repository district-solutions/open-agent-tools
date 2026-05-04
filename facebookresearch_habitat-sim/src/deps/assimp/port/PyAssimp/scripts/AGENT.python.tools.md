# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/scripts/3d_viewer_py3.py

Prompts

```
['run a PyASSIMP 3D viewer to load and display a 3D model file with interactive camera controls', 'create a PyAssimp3DViewer instance with a model path and custom window width and height', 'load a 3D model file using pyassimp with post-processing presets for maximum quality rendering', 'cycle through available cameras in the 3D viewer scene including the default and embedded cameras', 'render a 3D mesh using basic, flat, silhouette, or Gooch shading shaders with configurable lighting', 'render a 3D model file with postprocessing preset for maximum realtime quality', 'load a 3D model and prepare OpenGL vertex, normal, and triangle buffers for each mesh', 'scale and center a 3D scene to fit the entire geometry within the OpenGL viewport', 'run the quicktest script to load all 3D model files and verify pyassimp works', 'test the run_tests function that walks directories and loads 3D models using sample.main', 'review the extensions list of valid 3D model file formats supported by pyassimp', 'refactor the basepaths list to add additional test model directories for pyassimp', 'summarize how AssimpError exceptions are caught and counted as controlled errors during model loading', 'run sample.py with a 3D model file to print scene meshes materials and textures', 'run recur_node on a scene root node to recursively print the node hierarchy tree', 'run main with a filename to load a 3D model via pyassimp and print full scene statistics', 'review the main function to understand how pyassimp loads and inspects 3D model scenes', 'summarize the recur_node function that recursively prints a scene node tree with indentation', 'create a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'convert a quaternion [x, y, z, w] into a 4x4 homogeneous rotation matrix', 'create a 4x4 rotation matrix from Euler angles with a specified axis sequence like sxyz', 'decompose a 4x4 transformation matrix into scale, shear, Euler angles, translation, and perspective components', 'compute the optimal transformation matrix to superimpose one set of 3D vectors onto another']
```

Usage

```
{'run_3d_viewer': 'run a PyASSIMP 3D viewer to load and display a 3D model file with interactive camera controls', 'create_viewer_instance': 'create a PyAssimp3DViewer instance with a model path and custom window width and height', 'load_3d_model': 'load a 3D model file using pyassimp with post-processing presets for maximum quality rendering', 'cycle_cameras': 'cycle through available cameras in the 3D viewer scene including the default and embedded cameras', 'render_mesh_with_shaders': 'render a 3D mesh using basic, flat, silhouette, or Gooch shading shaders with configurable lighting'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/scripts/fixed_pipeline_3d_viewer.py

Prompts

```
['run a PyASSIMP 3D viewer to load and display a 3D model file with interactive camera controls', 'create a PyAssimp3DViewer instance with a model path and custom window width and height', 'load a 3D model file using pyassimp with post-processing presets for maximum quality rendering', 'cycle through available cameras in the 3D viewer scene including the default and embedded cameras', 'render a 3D mesh using basic, flat, silhouette, or Gooch shading shaders with configurable lighting', 'render a 3D model file with postprocessing preset for maximum realtime quality', 'load a 3D model and prepare OpenGL vertex, normal, and triangle buffers for each mesh', 'scale and center a 3D scene to fit the entire geometry within the OpenGL viewport', 'run the quicktest script to load all 3D model files and verify pyassimp works', 'test the run_tests function that walks directories and loads 3D models using sample.main', 'review the extensions list of valid 3D model file formats supported by pyassimp', 'refactor the basepaths list to add additional test model directories for pyassimp', 'summarize how AssimpError exceptions are caught and counted as controlled errors during model loading', 'run sample.py with a 3D model file to print scene meshes materials and textures', 'run recur_node on a scene root node to recursively print the node hierarchy tree', 'run main with a filename to load a 3D model via pyassimp and print full scene statistics', 'review the main function to understand how pyassimp loads and inspects 3D model scenes', 'summarize the recur_node function that recursively prints a scene node tree with indentation', 'create a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'convert a quaternion [x, y, z, w] into a 4x4 homogeneous rotation matrix', 'create a 4x4 rotation matrix from Euler angles with a specified axis sequence like sxyz', 'decompose a 4x4 transformation matrix into scale, shear, Euler angles, translation, and perspective components', 'compute the optimal transformation matrix to superimpose one set of 3D vectors onto another']
```

Usage

```
{'run_3d_viewer': 'run the GLRenderer to load and display a 3D model file using OpenGL fixed-function pipeline', 'render_model_with_postprocess': 'render a 3D model file with postprocessing preset for maximum realtime quality', 'load_model_with_buffers': 'load a 3D model and prepare OpenGL vertex, normal, and triangle buffers for each mesh', 'cycle_cameras': 'cycle through embedded cameras in a 3D scene by pressing the c key during rendering', 'fit_scene_to_viewport': 'scale and center a 3D scene to fit the entire geometry within the OpenGL viewport'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/scripts/quicktest.py

Prompts

```
['run a PyASSIMP 3D viewer to load and display a 3D model file with interactive camera controls', 'create a PyAssimp3DViewer instance with a model path and custom window width and height', 'load a 3D model file using pyassimp with post-processing presets for maximum quality rendering', 'cycle through available cameras in the 3D viewer scene including the default and embedded cameras', 'render a 3D mesh using basic, flat, silhouette, or Gooch shading shaders with configurable lighting', 'render a 3D model file with postprocessing preset for maximum realtime quality', 'load a 3D model and prepare OpenGL vertex, normal, and triangle buffers for each mesh', 'scale and center a 3D scene to fit the entire geometry within the OpenGL viewport', 'run the quicktest script to load all 3D model files and verify pyassimp works', 'test the run_tests function that walks directories and loads 3D models using sample.main', 'review the extensions list of valid 3D model file formats supported by pyassimp', 'refactor the basepaths list to add additional test model directories for pyassimp', 'summarize how AssimpError exceptions are caught and counted as controlled errors during model loading', 'run sample.py with a 3D model file to print scene meshes materials and textures', 'run recur_node on a scene root node to recursively print the node hierarchy tree', 'run main with a filename to load a 3D model via pyassimp and print full scene statistics', 'review the main function to understand how pyassimp loads and inspects 3D model scenes', 'summarize the recur_node function that recursively prints a scene node tree with indentation', 'create a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'convert a quaternion [x, y, z, w] into a 4x4 homogeneous rotation matrix', 'create a 4x4 rotation matrix from Euler angles with a specified axis sequence like sxyz', 'decompose a 4x4 transformation matrix into scale, shear, Euler angles, translation, and perspective components', 'compute the optimal transformation matrix to superimpose one set of 3D vectors onto another']
```

Usage

```
{'run_tests_quicktest': 'run the quicktest script to load all 3D model files and verify pyassimp works', 'test_run_tests_function': 'test the run_tests function that walks directories and loads 3D models using sample.main', 'review_extensions_list': 'review the extensions list of valid 3D model file formats supported by pyassimp', 'refactor_basepaths': 'refactor the basepaths list to add additional test model directories for pyassimp', 'summarize_assimperror_handling': 'summarize how AssimpError exceptions are caught and counted as controlled errors during model loading'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/scripts/sample.py

Prompts

```
['run a PyASSIMP 3D viewer to load and display a 3D model file with interactive camera controls', 'create a PyAssimp3DViewer instance with a model path and custom window width and height', 'load a 3D model file using pyassimp with post-processing presets for maximum quality rendering', 'cycle through available cameras in the 3D viewer scene including the default and embedded cameras', 'render a 3D mesh using basic, flat, silhouette, or Gooch shading shaders with configurable lighting', 'render a 3D model file with postprocessing preset for maximum realtime quality', 'load a 3D model and prepare OpenGL vertex, normal, and triangle buffers for each mesh', 'scale and center a 3D scene to fit the entire geometry within the OpenGL viewport', 'run the quicktest script to load all 3D model files and verify pyassimp works', 'test the run_tests function that walks directories and loads 3D models using sample.main', 'review the extensions list of valid 3D model file formats supported by pyassimp', 'refactor the basepaths list to add additional test model directories for pyassimp', 'summarize how AssimpError exceptions are caught and counted as controlled errors during model loading', 'run sample.py with a 3D model file to print scene meshes materials and textures', 'run recur_node on a scene root node to recursively print the node hierarchy tree', 'run main with a filename to load a 3D model via pyassimp and print full scene statistics', 'review the main function to understand how pyassimp loads and inspects 3D model scenes', 'summarize the recur_node function that recursively prints a scene node tree with indentation', 'create a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'convert a quaternion [x, y, z, w] into a 4x4 homogeneous rotation matrix', 'create a 4x4 rotation matrix from Euler angles with a specified axis sequence like sxyz', 'decompose a 4x4 transformation matrix into scale, shear, Euler angles, translation, and perspective components', 'compute the optimal transformation matrix to superimpose one set of 3D vectors onto another']
```

Usage

```
{'run_sample_3d_model_inspection': 'run sample.py with a 3D model file to print scene meshes materials and textures', 'run_recur_node_traversal': 'run recur_node on a scene root node to recursively print the node hierarchy tree', 'run_main_load_and_inspect': 'run main with a filename to load a 3D model via pyassimp and print full scene statistics', 'review_main_scene_inspection': 'review the main function to understand how pyassimp loads and inspects 3D model scenes', 'summarize_recur_node': 'summarize the recur_node function that recursively prints a scene node tree with indentation'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/scripts/transformations.py

Prompts

```
['run a PyASSIMP 3D viewer to load and display a 3D model file with interactive camera controls', 'create a PyAssimp3DViewer instance with a model path and custom window width and height', 'load a 3D model file using pyassimp with post-processing presets for maximum quality rendering', 'cycle through available cameras in the 3D viewer scene including the default and embedded cameras', 'render a 3D mesh using basic, flat, silhouette, or Gooch shading shaders with configurable lighting', 'render a 3D model file with postprocessing preset for maximum realtime quality', 'load a 3D model and prepare OpenGL vertex, normal, and triangle buffers for each mesh', 'scale and center a 3D scene to fit the entire geometry within the OpenGL viewport', 'run the quicktest script to load all 3D model files and verify pyassimp works', 'test the run_tests function that walks directories and loads 3D models using sample.main', 'review the extensions list of valid 3D model file formats supported by pyassimp', 'refactor the basepaths list to add additional test model directories for pyassimp', 'summarize how AssimpError exceptions are caught and counted as controlled errors during model loading', 'run sample.py with a 3D model file to print scene meshes materials and textures', 'run recur_node on a scene root node to recursively print the node hierarchy tree', 'run main with a filename to load a 3D model via pyassimp and print full scene statistics', 'review the main function to understand how pyassimp loads and inspects 3D model scenes', 'summarize the recur_node function that recursively prints a scene node tree with indentation', 'create a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'convert a quaternion [x, y, z, w] into a 4x4 homogeneous rotation matrix', 'create a 4x4 rotation matrix from Euler angles with a specified axis sequence like sxyz', 'decompose a 4x4 transformation matrix into scale, shear, Euler angles, translation, and perspective components', 'compute the optimal transformation matrix to superimpose one set of 3D vectors onto another']
```

Usage

```
{'create_rotation_matrix': 'create a 4x4 rotation matrix from an angle, direction vector, and optional pivot point', 'convert_quaternion_to_matrix': 'convert a quaternion [x, y, z, w] into a 4x4 homogeneous rotation matrix', 'convert_euler_to_matrix': 'create a 4x4 rotation matrix from Euler angles with a specified axis sequence like sxyz', 'decompose_transformation_matrix': 'decompose a 4x4 transformation matrix into scale, shear, Euler angles, translation, and perspective components', 'compute_superimposition_matrix': 'compute the optimal transformation matrix to superimpose one set of 3D vectors onto another'}
```

