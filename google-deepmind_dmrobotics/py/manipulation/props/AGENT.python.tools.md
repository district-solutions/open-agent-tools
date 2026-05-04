# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/manipulation/props/mesh_object.py

Prompts

```
['build a MeshProp from STL mesh files for use in MuJoCo robot manipulation simulations', 'build a MeshProp with a PNG texture file applied to the visual geometry', 'build a MeshProp with separate collision meshes for accurate physics simulation', 'review the MeshProp mass property to verify total mass across all geometry elements', 'summarize the MeshProp textures property to extract PNG texture data from MJCF assets', 'create a MeshProp from an OBJ mesh file with a given name and visual meshes list', 'create a MeshProp from an OBJ mesh file with a custom PNG texture file attached', 'test creating a MeshProp and verify its name and empty textures before compiling', 'test that two MeshProps created with the same texture file share identical texture data', 'compile a MeshProp into a MuJoCo physics model by attaching it to an empty arena', 'create a Singleton metaclass that ensures only one instance of a class exists across the application', 'create a VersionedSequence namedtuple with version and ids fields for tracking prop collection state', 'create a PropSetDict subclass of dict that evaluates callables on every key access to return VersionedSequence', 'test the PropSetDict __getitem__ method to verify it evaluates stored callables and returns VersionedSequence', 'review the PropSetDict _evaluate method to understand how it handles static sequences versus callable functions']
```

Usage

```
{'build_meshprop_from_stl': 'build a MeshProp from STL mesh files for use in MuJoCo robot manipulation simulations', 'build_meshprop_with_texture': 'build a MeshProp with a PNG texture file applied to the visual geometry', 'build_meshprop_with_collision': 'build a MeshProp with separate collision meshes for accurate physics simulation', 'review_meshprop_mass': 'review the MeshProp mass property to verify total mass across all geometry elements', 'summarize_meshprop_textures': 'summarize the MeshProp textures property to extract PNG texture data from MJCF assets'}
```

## File: google-deepmind_dmrobotics/py/manipulation/props/mesh_object_test.py

Prompts

```
['build a MeshProp from STL mesh files for use in MuJoCo robot manipulation simulations', 'build a MeshProp with a PNG texture file applied to the visual geometry', 'build a MeshProp with separate collision meshes for accurate physics simulation', 'review the MeshProp mass property to verify total mass across all geometry elements', 'summarize the MeshProp textures property to extract PNG texture data from MJCF assets', 'create a MeshProp from an OBJ mesh file with a given name and visual meshes list', 'create a MeshProp from an OBJ mesh file with a custom PNG texture file attached', 'test creating a MeshProp and verify its name and empty textures before compiling', 'test that two MeshProps created with the same texture file share identical texture data', 'compile a MeshProp into a MuJoCo physics model by attaching it to an empty arena', 'create a Singleton metaclass that ensures only one instance of a class exists across the application', 'create a VersionedSequence namedtuple with version and ids fields for tracking prop collection state', 'create a PropSetDict subclass of dict that evaluates callables on every key access to return VersionedSequence', 'test the PropSetDict __getitem__ method to verify it evaluates stored callables and returns VersionedSequence', 'review the PropSetDict _evaluate method to understand how it handles static sequences versus callable functions']
```

Usage

```
{'create_meshprop_from_obj': 'create a MeshProp from an OBJ mesh file with a given name and visual meshes list', 'create_meshprop_with_texture': 'create a MeshProp from an OBJ mesh file with a custom PNG texture file attached', 'test_meshprop_creation': 'test creating a MeshProp and verify its name and empty textures before compiling', 'test_meshprop_texture_sharing': 'test that two MeshProps created with the same texture file share identical texture data', 'compile_meshprop_to_physics': 'compile a MeshProp into a MuJoCo physics model by attaching it to an empty arena'}
```

## File: google-deepmind_dmrobotics/py/manipulation/props/object_collection.py

Prompts

```
['build a MeshProp from STL mesh files for use in MuJoCo robot manipulation simulations', 'build a MeshProp with a PNG texture file applied to the visual geometry', 'build a MeshProp with separate collision meshes for accurate physics simulation', 'review the MeshProp mass property to verify total mass across all geometry elements', 'summarize the MeshProp textures property to extract PNG texture data from MJCF assets', 'create a MeshProp from an OBJ mesh file with a given name and visual meshes list', 'create a MeshProp from an OBJ mesh file with a custom PNG texture file attached', 'test creating a MeshProp and verify its name and empty textures before compiling', 'test that two MeshProps created with the same texture file share identical texture data', 'compile a MeshProp into a MuJoCo physics model by attaching it to an empty arena', 'create a Singleton metaclass that ensures only one instance of a class exists across the application', 'create a VersionedSequence namedtuple with version and ids fields for tracking prop collection state', 'create a PropSetDict subclass of dict that evaluates callables on every key access to return VersionedSequence', 'test the PropSetDict __getitem__ method to verify it evaluates stored callables and returns VersionedSequence', 'review the PropSetDict _evaluate method to understand how it handles static sequences versus callable functions']
```

Usage

```
{'create_singleton_metaclass': 'create a Singleton metaclass that ensures only one instance of a class exists across the application', 'create_versioned_sequence_namedtuple': 'create a VersionedSequence namedtuple with version and ids fields for tracking prop collection state', 'create_propsetdict_dynamic_dict': 'create a PropSetDict subclass of dict that evaluates callables on every key access to return VersionedSequence', 'test_propsetdict_getitem': 'test the PropSetDict __getitem__ method to verify it evaluates stored callables and returns VersionedSequence', 'review_propsetdict_evaluate': 'review the PropSetDict _evaluate method to understand how it handles static sequences versus callable functions'}
```

