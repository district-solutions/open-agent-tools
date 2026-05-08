# Agent Python Tools

- repo: facebookresearch/fairmotion
- repo_uri: https://github.com/facebookresearch/fairmotion

## File: facebookresearch_fairmotion/fairmotion/core/motion.py

Prompts

```
['create a Joint object with a name, dof, and parent joint to build a skeleton hierarchy', 'build a Skeleton by adding Joint objects with parent-child relationships using add_joint', 'create a Pose object from a numpy matrix of 4x4 transformation matrices using Pose.from_matrix', 'interpolate between two Pose objects with an alpha weight using Pose.interpolate for smooth transitions', 'create a Motion sequence from a numpy array of transformation matrices using Motion.from_matrix', 'compute similarity between end-effectors and root for two poses using weighted position and velocity differences', 'compute joint angle difference between two poses with optional root correction and angular velocity comparison', 'compare end-effector positions and velocities of two poses relative to their facing frames', 'measure the joint angle difference between two poses using rotation matrix axis-angle conversion', 'evaluate pose similarity with custom joint weights and optional root correction along the up axis', 'compute angular and linear velocity for all joints between two Pose objects using Velocity.compute', 'get the angular velocity of a specific joint in local or global frame using Velocity.get_angular', 'get the linear velocity of a specific joint in local or global frame using Velocity.get_linear', 'interpolate between two Velocity objects at a given alpha ratio using Velocity.interpolate', 'create a MotionWithVelocity from a Motion object and compute joint velocities using from_motion']
```

Usage

```
{'create_joint_hierarchy': 'create a Joint object with a name, dof, and parent joint to build a skeleton hierarchy', 'build_skeleton_from_joints': 'build a Skeleton by adding Joint objects with parent-child relationships using add_joint', 'create_pose_from_matrix': 'create a Pose object from a numpy matrix of 4x4 transformation matrices using Pose.from_matrix', 'interpolate_two_poses': 'interpolate between two Pose objects with an alpha weight using Pose.interpolate for smooth transitions', 'create_motion_from_matrix': 'create a Motion sequence from a numpy array of transformation matrices using Motion.from_matrix'}
```

## File: facebookresearch_fairmotion/fairmotion/core/similarity.py

Prompts

```
['create a Joint object with a name, dof, and parent joint to build a skeleton hierarchy', 'build a Skeleton by adding Joint objects with parent-child relationships using add_joint', 'create a Pose object from a numpy matrix of 4x4 transformation matrices using Pose.from_matrix', 'interpolate between two Pose objects with an alpha weight using Pose.interpolate for smooth transitions', 'create a Motion sequence from a numpy array of transformation matrices using Motion.from_matrix', 'compute similarity between end-effectors and root for two poses using weighted position and velocity differences', 'compute joint angle difference between two poses with optional root correction and angular velocity comparison', 'compare end-effector positions and velocities of two poses relative to their facing frames', 'measure the joint angle difference between two poses using rotation matrix axis-angle conversion', 'evaluate pose similarity with custom joint weights and optional root correction along the up axis', 'compute angular and linear velocity for all joints between two Pose objects using Velocity.compute', 'get the angular velocity of a specific joint in local or global frame using Velocity.get_angular', 'get the linear velocity of a specific joint in local or global frame using Velocity.get_linear', 'interpolate between two Velocity objects at a given alpha ratio using Velocity.interpolate', 'create a MotionWithVelocity from a Motion object and compute joint velocities using from_motion']
```

Usage

```
{'compute_root_ee_similarity': 'compute similarity between end-effectors and root for two poses using weighted position and velocity differences', 'compute_pose_similarity': 'compute joint angle difference between two poses with optional root correction and angular velocity comparison', 'compare_pose_end_effectors': 'compare end-effector positions and velocities of two poses relative to their facing frames', 'measure_joint_angle_difference': 'measure the joint angle difference between two poses using rotation matrix axis-angle conversion', 'evaluate_pose_similarity_with_weights': 'evaluate pose similarity with custom joint weights and optional root correction along the up axis'}
```

## File: facebookresearch_fairmotion/fairmotion/core/velocity.py

Prompts

```
['create a Joint object with a name, dof, and parent joint to build a skeleton hierarchy', 'build a Skeleton by adding Joint objects with parent-child relationships using add_joint', 'create a Pose object from a numpy matrix of 4x4 transformation matrices using Pose.from_matrix', 'interpolate between two Pose objects with an alpha weight using Pose.interpolate for smooth transitions', 'create a Motion sequence from a numpy array of transformation matrices using Motion.from_matrix', 'compute similarity between end-effectors and root for two poses using weighted position and velocity differences', 'compute joint angle difference between two poses with optional root correction and angular velocity comparison', 'compare end-effector positions and velocities of two poses relative to their facing frames', 'measure the joint angle difference between two poses using rotation matrix axis-angle conversion', 'evaluate pose similarity with custom joint weights and optional root correction along the up axis', 'compute angular and linear velocity for all joints between two Pose objects using Velocity.compute', 'get the angular velocity of a specific joint in local or global frame using Velocity.get_angular', 'get the linear velocity of a specific joint in local or global frame using Velocity.get_linear', 'interpolate between two Velocity objects at a given alpha ratio using Velocity.interpolate', 'create a MotionWithVelocity from a Motion object and compute joint velocities using from_motion']
```

Usage

```
{'compute_velocity_between_poses': 'compute angular and linear velocity for all joints between two Pose objects using Velocity.compute', 'get_angular_velocity': 'get the angular velocity of a specific joint in local or global frame using Velocity.get_angular', 'get_linear_velocity': 'get the linear velocity of a specific joint in local or global frame using Velocity.get_linear', 'interpolate_velocity': 'interpolate between two Velocity objects at a given alpha ratio using Velocity.interpolate', 'create_motion_with_velocity': 'create a MotionWithVelocity from a Motion object and compute joint velocities using from_motion'}
```

