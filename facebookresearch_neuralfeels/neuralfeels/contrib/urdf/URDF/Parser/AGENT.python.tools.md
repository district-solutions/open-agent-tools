# Agent Python Tools

- repo: facebookresearch/neuralfeels
- repo_uri: https://github.com/facebookresearch/neuralfeels

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/URDF/Parser/Joint.py

Prompts

```
['create a Joint instance with a name, type, child name, and parent name', 'set the origin xyz coordinates of a Joint using setOriginXyz with a 3D vector', 'set the origin roll pitch yaw of a Joint using setOriginRpy with a 3D vector', 'set the rotation axis of a Joint using setAxis with a 3D direction vector', 'set the lower and upper limit values of a Joint using setLimitLower and setLimitUpper', 'create a Link object with a given link name for URDF parsing', "add a Visual object to a Link's visuals list with an optional name", 'set the mesh scale of the most recently added visual on a Link', 'set the xyz origin position of the most recently added visual on a Link', 'set the mesh filename for the most recently added visual on a Link', 'create a URDFParser instance and call parse to extract links and joints from a URDF XML file', 'call parseLinks on a URDFParser to parse all link elements with visuals, geometry, and materials', 'call parseJoints on a URDFParser to parse all joint elements with origin, axis, and limit attributes', 'call parseThreeNumber to split a space-separated string of three numbers into a numpy array', 'review the URDFParser class and its parseLinks and parseJoints methods for URDF XML parsing']
```

Usage

```
{'create_joint_instance': 'create a Joint instance with a name, type, child name, and parent name', 'set_joint_origin_xyz': 'set the origin xyz coordinates of a Joint using setOriginXyz with a 3D vector', 'set_joint_origin_rpy': 'set the origin roll pitch yaw of a Joint using setOriginRpy with a 3D vector', 'set_joint_axis': 'set the rotation axis of a Joint using setAxis with a 3D direction vector', 'set_joint_limits': 'set the lower and upper limit values of a Joint using setLimitLower and setLimitUpper'}
```

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/URDF/Parser/Link.py

Prompts

```
['create a Joint instance with a name, type, child name, and parent name', 'set the origin xyz coordinates of a Joint using setOriginXyz with a 3D vector', 'set the origin roll pitch yaw of a Joint using setOriginRpy with a 3D vector', 'set the rotation axis of a Joint using setAxis with a 3D direction vector', 'set the lower and upper limit values of a Joint using setLimitLower and setLimitUpper', 'create a Link object with a given link name for URDF parsing', "add a Visual object to a Link's visuals list with an optional name", 'set the mesh scale of the most recently added visual on a Link', 'set the xyz origin position of the most recently added visual on a Link', 'set the mesh filename for the most recently added visual on a Link', 'create a URDFParser instance and call parse to extract links and joints from a URDF XML file', 'call parseLinks on a URDFParser to parse all link elements with visuals, geometry, and materials', 'call parseJoints on a URDFParser to parse all joint elements with origin, axis, and limit attributes', 'call parseThreeNumber to split a space-separated string of three numbers into a numpy array', 'review the URDFParser class and its parseLinks and parseJoints methods for URDF XML parsing']
```

Usage

```
{'create_Link': 'create a Link object with a given link name for URDF parsing', 'addVisual_to_Link': "add a Visual object to a Link's visuals list with an optional name", 'setVisualMeshScale': 'set the mesh scale of the most recently added visual on a Link', 'setVisualOriginXyz': 'set the xyz origin position of the most recently added visual on a Link', 'setVisualGeometryMeshFilename': 'set the mesh filename for the most recently added visual on a Link'}
```

## File: facebookresearch_neuralfeels/neuralfeels/contrib/urdf/URDF/Parser/URDFParser.py

Prompts

```
['create a Joint instance with a name, type, child name, and parent name', 'set the origin xyz coordinates of a Joint using setOriginXyz with a 3D vector', 'set the origin roll pitch yaw of a Joint using setOriginRpy with a 3D vector', 'set the rotation axis of a Joint using setAxis with a 3D direction vector', 'set the lower and upper limit values of a Joint using setLimitLower and setLimitUpper', 'create a Link object with a given link name for URDF parsing', "add a Visual object to a Link's visuals list with an optional name", 'set the mesh scale of the most recently added visual on a Link', 'set the xyz origin position of the most recently added visual on a Link', 'set the mesh filename for the most recently added visual on a Link', 'create a URDFParser instance and call parse to extract links and joints from a URDF XML file', 'call parseLinks on a URDFParser to parse all link elements with visuals, geometry, and materials', 'call parseJoints on a URDFParser to parse all joint elements with origin, axis, and limit attributes', 'call parseThreeNumber to split a space-separated string of three numbers into a numpy array', 'review the URDFParser class and its parseLinks and parseJoints methods for URDF XML parsing']
```

Usage

```
{'parse_urdf_file': 'create a URDFParser instance and call parse to extract links and joints from a URDF XML file', 'parse_links': 'call parseLinks on a URDFParser to parse all link elements with visuals, geometry, and materials', 'parse_joints': 'call parseJoints on a URDFParser to parse all joint elements with origin, axis, and limit attributes', 'parse_three_number': 'call parseThreeNumber to split a space-separated string of three numbers into a numpy array', 'review_urdfparser_class': 'review the URDFParser class and its parseLinks and parseJoints methods for URDF XML parsing'}
```

