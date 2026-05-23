# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/torchkin/torchkin/forward_kinematics.py

Prompts

```
['build a forward kinematics autograd function for a robot using ForwardKinematicsFactory', 'create forward kinematics functions for a robot using get_forward_kinematics_fns', 'test forward kinematics by computing link poses from joint angles', 'compute the spatial jacobian for each link given joint angles', 'compute the body jacobian for each link given joint angles', 'create a Link object with name, id, parent_joint, and child_joints for kinematic chain representation', 'create a FixedJoint with zero degrees of freedom that returns origin as relative pose', 'create a RevoluteJoint with specified rotation axis and compute relative pose from angle input', 'create a PrismaticJoint with specified translation axis and compute relative pose from angle input', 'create a RevoluteJointX, RevoluteJointY, or RevoluteJointZ for rotation around specific coordinate axes', 'build a Robot instance from a URDF XML file using Robot.from_urdf_file', 'create a Robot instance with a custom name, dtype, and device', 'get a list of robot links by name or all links using get_links', 'review the Robot class properties like dof, num_joints, num_links, joints, and links', 'summarize the Robot abstract class and its kinematics tree building methods']
```

Usage

```
{'build_forward_kinematics_factory': 'build a forward kinematics autograd function for a robot using ForwardKinematicsFactory', 'create_fk_functions': 'create forward kinematics functions for a robot using get_forward_kinematics_fns', 'test_forward_kinematics': 'test forward kinematics by computing link poses from joint angles', 'compute_spatial_jacobian': 'compute the spatial jacobian for each link given joint angles', 'compute_body_jacobian': 'compute the body jacobian for each link given joint angles'}
```

## File: facebookresearch_theseus/torchkin/torchkin/joint.py

Prompts

```
['build a forward kinematics autograd function for a robot using ForwardKinematicsFactory', 'create forward kinematics functions for a robot using get_forward_kinematics_fns', 'test forward kinematics by computing link poses from joint angles', 'compute the spatial jacobian for each link given joint angles', 'compute the body jacobian for each link given joint angles', 'create a Link object with name, id, parent_joint, and child_joints for kinematic chain representation', 'create a FixedJoint with zero degrees of freedom that returns origin as relative pose', 'create a RevoluteJoint with specified rotation axis and compute relative pose from angle input', 'create a PrismaticJoint with specified translation axis and compute relative pose from angle input', 'create a RevoluteJointX, RevoluteJointY, or RevoluteJointZ for rotation around specific coordinate axes', 'build a Robot instance from a URDF XML file using Robot.from_urdf_file', 'create a Robot instance with a custom name, dtype, and device', 'get a list of robot links by name or all links using get_links', 'review the Robot class properties like dof, num_joints, num_links, joints, and links', 'summarize the Robot abstract class and its kinematics tree building methods']
```

Usage

```
{'create_Link': 'create a Link object with name, id, parent_joint, and child_joints for kinematic chain representation', 'create_FixedJoint': 'create a FixedJoint with zero degrees of freedom that returns origin as relative pose', 'create_RevoluteJoint': 'create a RevoluteJoint with specified rotation axis and compute relative pose from angle input', 'create_PrismaticJoint': 'create a PrismaticJoint with specified translation axis and compute relative pose from angle input', 'create_RevoluteJointXYZ': 'create a RevoluteJointX, RevoluteJointY, or RevoluteJointZ for rotation around specific coordinate axes'}
```

## File: facebookresearch_theseus/torchkin/torchkin/robot.py

Prompts

```
['build a forward kinematics autograd function for a robot using ForwardKinematicsFactory', 'create forward kinematics functions for a robot using get_forward_kinematics_fns', 'test forward kinematics by computing link poses from joint angles', 'compute the spatial jacobian for each link given joint angles', 'compute the body jacobian for each link given joint angles', 'create a Link object with name, id, parent_joint, and child_joints for kinematic chain representation', 'create a FixedJoint with zero degrees of freedom that returns origin as relative pose', 'create a RevoluteJoint with specified rotation axis and compute relative pose from angle input', 'create a PrismaticJoint with specified translation axis and compute relative pose from angle input', 'create a RevoluteJointX, RevoluteJointY, or RevoluteJointZ for rotation around specific coordinate axes', 'build a Robot instance from a URDF XML file using Robot.from_urdf_file', 'create a Robot instance with a custom name, dtype, and device', 'get a list of robot links by name or all links using get_links', 'review the Robot class properties like dof, num_joints, num_links, joints, and links', 'summarize the Robot abstract class and its kinematics tree building methods']
```

Usage

```
{'build_robot_from_urdf': 'build a Robot instance from a URDF XML file using Robot.from_urdf_file', 'create_robot_instance': 'create a Robot instance with a custom name, dtype, and device', 'get_robot_links': 'get a list of robot links by name or all links using get_links', 'review_robot_properties': 'review the Robot class properties like dof, num_joints, num_links, joints, and links', 'summarize_robot_class': 'summarize the Robot abstract class and its kinematics tree building methods'}
```

