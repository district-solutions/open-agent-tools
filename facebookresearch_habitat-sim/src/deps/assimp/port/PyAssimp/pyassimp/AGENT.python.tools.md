# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/pyassimp/core.py

Prompts

```
['load a 3D model file into a scene object using pyassimp.load with optional postprocessing flags', 'export a scene object to a 3D model file using pyassimp.export with a specified file type', 'export a scene object to a memory blob using pyassimp.export_blob with a specified file type', 'decompose a 4x4 transformation matrix into scaling, rotation quaternion, and position vectors using pyassimp.decompose_matrix', 'release the memory allocated for a loaded scene object using pyassimp.release to prevent memory leaks', 'summarize the FORMATS list which contains 3D model file format extensions supported by PyAssimp', 'review the available_formats function that returns the list of supported 3D model format extensions', 'test the available_formats function to verify it returns the expected list of format strings', 'build a python cli module that prints all supported 3D model formats from the FORMATS list', 'create a python cli module that calls available_formats and outputs each format on a new line', 'apply a 4x4 transformation matrix to a 3D vector using the transform function', 'compute the inverse of a 4x4 matrix using the _inv helper function', 'compute the axis-aligned bounding box of an assimp scene by traversing all nodes and meshes', 'discover and load the assimp shared library from system paths and return bound C functions', 'convert a VECTOR3D object into a plain Python tuple of x, y, z coordinates']
```

Usage

```
{'load_3d_model': 'load a 3D model file into a scene object using pyassimp.load with optional postprocessing flags', 'export_scene_to_file': 'export a scene object to a 3D model file using pyassimp.export with a specified file type', 'export_scene_to_blob': 'export a scene object to a memory blob using pyassimp.export_blob with a specified file type', 'decompose_transformation_matrix': 'decompose a 4x4 transformation matrix into scaling, rotation quaternion, and position vectors using pyassimp.decompose_matrix', 'release_scene_memory': 'release the memory allocated for a loaded scene object using pyassimp.release to prevent memory leaks'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/pyassimp/formats.py

Prompts

```
['load a 3D model file into a scene object using pyassimp.load with optional postprocessing flags', 'export a scene object to a 3D model file using pyassimp.export with a specified file type', 'export a scene object to a memory blob using pyassimp.export_blob with a specified file type', 'decompose a 4x4 transformation matrix into scaling, rotation quaternion, and position vectors using pyassimp.decompose_matrix', 'release the memory allocated for a loaded scene object using pyassimp.release to prevent memory leaks', 'summarize the FORMATS list which contains 3D model file format extensions supported by PyAssimp', 'review the available_formats function that returns the list of supported 3D model format extensions', 'test the available_formats function to verify it returns the expected list of format strings', 'build a python cli module that prints all supported 3D model formats from the FORMATS list', 'create a python cli module that calls available_formats and outputs each format on a new line', 'apply a 4x4 transformation matrix to a 3D vector using the transform function', 'compute the inverse of a 4x4 matrix using the _inv helper function', 'compute the axis-aligned bounding box of an assimp scene by traversing all nodes and meshes', 'discover and load the assimp shared library from system paths and return bound C functions', 'convert a VECTOR3D object into a plain Python tuple of x, y, z coordinates']
```

Usage

```
{'summarize_FORMATS': 'summarize the FORMATS list which contains 3D model file format extensions supported by PyAssimp', 'review_available_formats': 'review the available_formats function that returns the list of supported 3D model format extensions', 'test_available_formats': 'test the available_formats function to verify it returns the expected list of format strings', 'build_FORMATS_cli': 'build a python cli module that prints all supported 3D model formats from the FORMATS list', 'create_available_formats_cli': 'create a python cli module that calls available_formats and outputs each format on a new line'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/port/PyAssimp/pyassimp/helper.py

Prompts

```
['load a 3D model file into a scene object using pyassimp.load with optional postprocessing flags', 'export a scene object to a 3D model file using pyassimp.export with a specified file type', 'export a scene object to a memory blob using pyassimp.export_blob with a specified file type', 'decompose a 4x4 transformation matrix into scaling, rotation quaternion, and position vectors using pyassimp.decompose_matrix', 'release the memory allocated for a loaded scene object using pyassimp.release to prevent memory leaks', 'summarize the FORMATS list which contains 3D model file format extensions supported by PyAssimp', 'review the available_formats function that returns the list of supported 3D model format extensions', 'test the available_formats function to verify it returns the expected list of format strings', 'build a python cli module that prints all supported 3D model formats from the FORMATS list', 'create a python cli module that calls available_formats and outputs each format on a new line', 'apply a 4x4 transformation matrix to a 3D vector using the transform function', 'compute the inverse of a 4x4 matrix using the _inv helper function', 'compute the axis-aligned bounding box of an assimp scene by traversing all nodes and meshes', 'discover and load the assimp shared library from system paths and return bound C functions', 'convert a VECTOR3D object into a plain Python tuple of x, y, z coordinates']
```

Usage

```
{'transform_vector3_with_matrix': 'apply a 4x4 transformation matrix to a 3D vector using the transform function', 'invert_4x4_matrix': 'compute the inverse of a 4x4 matrix using the _inv helper function', 'get_scene_bounding_box': 'compute the axis-aligned bounding box of an assimp scene by traversing all nodes and meshes', 'search_assimp_library': 'discover and load the assimp shared library from system paths and return bound C functions', 'convert_vector3d_to_tuple': 'convert a VECTOR3D object into a plain Python tuple of x, y, z coordinates'}
```

