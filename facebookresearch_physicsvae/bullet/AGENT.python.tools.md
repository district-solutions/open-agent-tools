# Agent Python Tools

- repo: facebookresearch/physicsvae
- repo_uri: https://github.com/facebookresearch/physicsvae

## File: facebookresearch_physicsvae/bullet/bullet_render.py

Prompts

```
['render a pybullet physics model with links, joints, and joint geometry using OpenGL', 'render a pybullet visual shape like sphere, box, capsule, cylinder, or mesh geometry', 'render all links of a pybullet model with optional color filtering and wireframe overlay', 'render contact point arrows for a pybullet model showing collision forces and normals', 'render a dictionary of OBJ mesh materials with OpenGL lighting and vertex arrays', "set the position, orientation, linear and angular velocities of a PyBullet body's base link", "get the position, orientation, linear and angular velocities of a PyBullet body's base link", 'get positions, orientations, linear and angular velocities for specified link indices of a PyBullet body', 'get joint torques applied during the previous simulation step for specified joint indices', 'compute PD control forces for target joint positions and velocities with configurable gain and force limits']
```

Usage

```
{'render_model_pybullet': 'render a pybullet physics model with links, joints, and joint geometry using OpenGL', 'render_geom_visual_shape': 'render a pybullet visual shape like sphere, box, capsule, cylinder, or mesh geometry', 'render_links_pybullet_model': 'render all links of a pybullet model with optional color filtering and wireframe overlay', 'render_contacts_pybullet': 'render contact point arrows for a pybullet model showing collision forces and normals', 'render_meshes_obj': 'render a dictionary of OBJ mesh materials with OpenGL lighting and vertex arrays'}
```

## File: facebookresearch_physicsvae/bullet/bullet_utils.py

Prompts

```
['render a pybullet physics model with links, joints, and joint geometry using OpenGL', 'render a pybullet visual shape like sphere, box, capsule, cylinder, or mesh geometry', 'render all links of a pybullet model with optional color filtering and wireframe overlay', 'render contact point arrows for a pybullet model showing collision forces and normals', 'render a dictionary of OBJ mesh materials with OpenGL lighting and vertex arrays', "set the position, orientation, linear and angular velocities of a PyBullet body's base link", "get the position, orientation, linear and angular velocities of a PyBullet body's base link", 'get positions, orientations, linear and angular velocities for specified link indices of a PyBullet body', 'get joint torques applied during the previous simulation step for specified joint indices', 'compute PD control forces for target joint positions and velocities with configurable gain and force limits']
```

Usage

```
{'set_base_pQvw': "set the position, orientation, linear and angular velocities of a PyBullet body's base link", 'get_base_pQvw': "get the position, orientation, linear and angular velocities of a PyBullet body's base link", 'get_link_pQvw': 'get positions, orientations, linear and angular velocities for specified link indices of a PyBullet body', 'get_joint_torques': 'get joint torques applied during the previous simulation step for specified joint indices', 'compute_PD_forces': 'compute PD control forces for target joint positions and velocities with configurable gain and force limits'}
```

