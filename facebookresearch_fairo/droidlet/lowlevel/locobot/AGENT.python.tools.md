# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/locobot_mover.py

Prompts

```
['create a LoCoBotMover instance with an IP address and habitat or locobot backend', 'move the Locobot to relative x,y,yaw positions using move_relative with blocking mode', 'move the Locobot to absolute canonical world coordinates using move_absolute', 'point the Locobot camera at an object position using look_at with yaw and pitch degrees', 'fetch RGB, depth, and point cloud data from the Locobot camera using get_rgb_depth', 'create a Pos object with x, y, z coordinates for 3D spatial positioning', 'convert a Pos object to a numpy array using pos_to_np for vector math', 'check if a plaintext username matches a SHA256 hashed username with salt', 'find which object a player is looking at from a list of candidates by position and gaze', 'compute the capped line of sight intersection point for an agent and player struct']
```

Usage

```
{'create_locobot_mover': 'create a LoCoBotMover instance with an IP address and habitat or locobot backend', 'move_relative_locobot': 'move the Locobot to relative x,y,yaw positions using move_relative with blocking mode', 'move_absolute_locobot': 'move the Locobot to absolute canonical world coordinates using move_absolute', 'look_at_object': 'point the Locobot camera at an object position using look_at with yaw and pitch degrees', 'get_rgb_depth': 'fetch RGB, depth, and point cloud data from the Locobot camera using get_rgb_depth'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/locobot/locobot_util.py

Prompts

```
['create a LoCoBotMover instance with an IP address and habitat or locobot backend', 'move the Locobot to relative x,y,yaw positions using move_relative with blocking mode', 'move the Locobot to absolute canonical world coordinates using move_absolute', 'point the Locobot camera at an object position using look_at with yaw and pitch degrees', 'fetch RGB, depth, and point cloud data from the Locobot camera using get_rgb_depth', 'create a Pos object with x, y, z coordinates for 3D spatial positioning', 'convert a Pos object to a numpy array using pos_to_np for vector math', 'check if a plaintext username matches a SHA256 hashed username with salt', 'find which object a player is looking at from a list of candidates by position and gaze', 'compute the capped line of sight intersection point for an agent and player struct']
```

Usage

```
{'create_Pos_class': 'create a Pos object with x, y, z coordinates for 3D spatial positioning', 'convert_pos_to_numpy': 'convert a Pos object to a numpy array using pos_to_np for vector math', 'check_username_hash': 'check if a plaintext username matches a SHA256 hashed username with salt', 'find_object_looked_at': 'find which object a player is looking at from a list of candidates by position and gaze', 'compute_capped_line_of_sight': 'compute the capped line of sight intersection point for an agent and player struct'}
```

