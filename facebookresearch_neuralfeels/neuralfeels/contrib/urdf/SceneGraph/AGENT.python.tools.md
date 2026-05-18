# Agent Python Tools

- repo: facebookresearch/neuralfeels
- repo_uri: https://github.com/facebookresearch/neuralfeels

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/SceneGraph/MeshNode.py

Prompts

```
['create a MeshNode instance to hold and manage 3D triangle mesh data', 'add an open3d triangle mesh object to the MeshNode, combining it with any existing mesh', 'load a mesh from an OBJ file, paint it a uniform color, and add it to the MeshNode', 'get a deep copy of the stored mesh transformed by a world matrix for rendering', 'review the MeshNode class and its mesh management methods for 3D scene graph usage', 'create a SceneGraph from a root URDF link with optional joint angles to build a hierarchical scene', 'update the SceneGraph state by recursively applying joint rotations and translations to all nodes', 'get all Open3D meshes from the SceneGraph after updating transforms for visualization', 'update joint angles on the SceneGraph from a PyTorch tensor to reconfigure the robot pose', 'extract roll-pitch-yaw rotation values for a scene node based on its joint axis and angle', 'create a SceneNode with parent-child relationships and update world matrices for the entire hierarchy', 'add an Open3D mesh to a SceneNode and retrieve the transformed mesh using getMesh', 'translate a SceneNode in 3D space by applying a translation vector to its local transform', 'rotate a SceneNode around an arbitrary axis by a specified angle in radians', 'scale a SceneNode uniformly or non-uniformly by applying a scale factor to its local transform', 'create a Transform instance that initializes identity matrices for translation, rotation, and scale', 'build a call to getMatrix that returns the combined 4x4 transformation matrix', 'test translateMat by applying a translation matrix to the Transform instance', 'refactor rotateMat to apply a rotation matrix to the Transform instance', 'review scaleMat to apply a scaling matrix to the Transform instance']
```

Usage

```
{'create_meshnode': 'create a MeshNode instance to hold and manage 3D triangle mesh data', 'addMesh': 'add an open3d triangle mesh object to the MeshNode, combining it with any existing mesh', 'addMeshFile': 'load a mesh from an OBJ file, paint it a uniform color, and add it to the MeshNode', 'getMesh': 'get a deep copy of the stored mesh transformed by a world matrix for rendering', 'review_MeshNode': 'review the MeshNode class and its mesh management methods for 3D scene graph usage'}
```

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/SceneGraph/SceneGraph.py

Prompts

```
['create a MeshNode instance to hold and manage 3D triangle mesh data', 'add an open3d triangle mesh object to the MeshNode, combining it with any existing mesh', 'load a mesh from an OBJ file, paint it a uniform color, and add it to the MeshNode', 'get a deep copy of the stored mesh transformed by a world matrix for rendering', 'review the MeshNode class and its mesh management methods for 3D scene graph usage', 'create a SceneGraph from a root URDF link with optional joint angles to build a hierarchical scene', 'update the SceneGraph state by recursively applying joint rotations and translations to all nodes', 'get all Open3D meshes from the SceneGraph after updating transforms for visualization', 'update joint angles on the SceneGraph from a PyTorch tensor to reconfigure the robot pose', 'extract roll-pitch-yaw rotation values for a scene node based on its joint axis and angle', 'create a SceneNode with parent-child relationships and update world matrices for the entire hierarchy', 'add an Open3D mesh to a SceneNode and retrieve the transformed mesh using getMesh', 'translate a SceneNode in 3D space by applying a translation vector to its local transform', 'rotate a SceneNode around an arbitrary axis by a specified angle in radians', 'scale a SceneNode uniformly or non-uniformly by applying a scale factor to its local transform', 'create a Transform instance that initializes identity matrices for translation, rotation, and scale', 'build a call to getMatrix that returns the combined 4x4 transformation matrix', 'test translateMat by applying a translation matrix to the Transform instance', 'refactor rotateMat to apply a rotation matrix to the Transform instance', 'review scaleMat to apply a scaling matrix to the Transform instance']
```

Usage

```
{'construct_scene_graph': 'create a SceneGraph from a root URDF link with optional joint angles to build a hierarchical scene', 'update_scene_state': 'update the SceneGraph state by recursively applying joint rotations and translations to all nodes', 'get_meshes': 'get all Open3D meshes from the SceneGraph after updating transforms for visualization', 'update_joint_angles': 'update joint angles on the SceneGraph from a PyTorch tensor to reconfigure the robot pose', 'extract_rpy': 'extract roll-pitch-yaw rotation values for a scene node based on its joint axis and angle'}
```

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/SceneGraph/SceneNode.py

Prompts

```
['create a MeshNode instance to hold and manage 3D triangle mesh data', 'add an open3d triangle mesh object to the MeshNode, combining it with any existing mesh', 'load a mesh from an OBJ file, paint it a uniform color, and add it to the MeshNode', 'get a deep copy of the stored mesh transformed by a world matrix for rendering', 'review the MeshNode class and its mesh management methods for 3D scene graph usage', 'create a SceneGraph from a root URDF link with optional joint angles to build a hierarchical scene', 'update the SceneGraph state by recursively applying joint rotations and translations to all nodes', 'get all Open3D meshes from the SceneGraph after updating transforms for visualization', 'update joint angles on the SceneGraph from a PyTorch tensor to reconfigure the robot pose', 'extract roll-pitch-yaw rotation values for a scene node based on its joint axis and angle', 'create a SceneNode with parent-child relationships and update world matrices for the entire hierarchy', 'add an Open3D mesh to a SceneNode and retrieve the transformed mesh using getMesh', 'translate a SceneNode in 3D space by applying a translation vector to its local transform', 'rotate a SceneNode around an arbitrary axis by a specified angle in radians', 'scale a SceneNode uniformly or non-uniformly by applying a scale factor to its local transform', 'create a Transform instance that initializes identity matrices for translation, rotation, and scale', 'build a call to getMatrix that returns the combined 4x4 transformation matrix', 'test translateMat by applying a translation matrix to the Transform instance', 'refactor rotateMat to apply a rotation matrix to the Transform instance', 'review scaleMat to apply a scaling matrix to the Transform instance']
```

Usage

```
{'create_scene_node_hierarchy': 'create a SceneNode with parent-child relationships and update world matrices for the entire hierarchy', 'add_mesh_to_scene_node': 'add an Open3D mesh to a SceneNode and retrieve the transformed mesh using getMesh', 'translate_scene_node': 'translate a SceneNode in 3D space by applying a translation vector to its local transform', 'rotate_scene_node_by_axis': 'rotate a SceneNode around an arbitrary axis by a specified angle in radians', 'scale_scene_node': 'scale a SceneNode uniformly or non-uniformly by applying a scale factor to its local transform'}
```

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/SceneGraph/Transform.py

Prompts

```
['create a MeshNode instance to hold and manage 3D triangle mesh data', 'add an open3d triangle mesh object to the MeshNode, combining it with any existing mesh', 'load a mesh from an OBJ file, paint it a uniform color, and add it to the MeshNode', 'get a deep copy of the stored mesh transformed by a world matrix for rendering', 'review the MeshNode class and its mesh management methods for 3D scene graph usage', 'create a SceneGraph from a root URDF link with optional joint angles to build a hierarchical scene', 'update the SceneGraph state by recursively applying joint rotations and translations to all nodes', 'get all Open3D meshes from the SceneGraph after updating transforms for visualization', 'update joint angles on the SceneGraph from a PyTorch tensor to reconfigure the robot pose', 'extract roll-pitch-yaw rotation values for a scene node based on its joint axis and angle', 'create a SceneNode with parent-child relationships and update world matrices for the entire hierarchy', 'add an Open3D mesh to a SceneNode and retrieve the transformed mesh using getMesh', 'translate a SceneNode in 3D space by applying a translation vector to its local transform', 'rotate a SceneNode around an arbitrary axis by a specified angle in radians', 'scale a SceneNode uniformly or non-uniformly by applying a scale factor to its local transform', 'create a Transform instance that initializes identity matrices for translation, rotation, and scale', 'build a call to getMatrix that returns the combined 4x4 transformation matrix', 'test translateMat by applying a translation matrix to the Transform instance', 'refactor rotateMat to apply a rotation matrix to the Transform instance', 'review scaleMat to apply a scaling matrix to the Transform instance']
```

Usage

```
{'create_Transform': 'create a Transform instance that initializes identity matrices for translation, rotation, and scale', 'build_getMatrix': 'build a call to getMatrix that returns the combined 4x4 transformation matrix', 'test_translateMat': 'test translateMat by applying a translation matrix to the Transform instance', 'refactor_rotateMat': 'refactor rotateMat to apply a rotation matrix to the Transform instance', 'review_scaleMat': 'review scaleMat to apply a scaling matrix to the Transform instance'}
```

