# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/composer/observation/observable/base.py

Prompts

```
['create a Generic observable from a callable that returns observations given a physics object', 'create a MujocoFeature observable to expose a named MuJoCo mjData field as an observation', 'create a MujocoCamera observable to render RGB or depth images from a named MuJoCo camera', 'configure an Observable by setting update_interval, buffer_size, delay, aggregator, or corruptor attributes', 'use a predefined aggregator like min, max, mean, median, or sum to reduce buffered observations', 'test the Observable base class update_interval, buffer_size, delay, and enabled properties', 'test the Generic observable wrapping a callable with a custom update_interval', 'test the MujocoFeature observable to extract qpos or geom_xpos from physics data', 'test the MujocoCamera observable to render camera images from a MuJoCo physics environment', 'test applying a corruptor function to modify observable values before returning them', 'create an MJCFFeature observable to expose a named attribute of an MJCF element as an observation', 'create an MJCFCamera observable to render RGB, depth, or segmentation images from an MJCF camera element', 'slice an MJCFFeature observable using __getitem__ to select specific array indices of the bound attribute', 'configure MJCFCamera render options like depth, segmentation, scene_option, and render_flag_overrides for custom visualization', 'inspect the array_spec property of MJCFCamera to get the BoundedArray spec with shape, dtype, and value bounds', 'create an MJCFFeature observable with an index list to select specific rows from an xmat array', 'slice an MJCFFeature observable using bracket notation to select a subset of array elements', 'create an MJCFCamera observable with segmentation enabled to render per-geom integer labels instead of RGB pixels']
```

Usage

```
{'create_generic_observable': 'create a Generic observable from a callable that returns observations given a physics object', 'create_mujoco_feature_observable': 'create a MujocoFeature observable to expose a named MuJoCo mjData field as an observation', 'create_mujoco_camera_observable': 'create a MujocoCamera observable to render RGB or depth images from a named MuJoCo camera', 'configure_observable': 'configure an Observable by setting update_interval, buffer_size, delay, aggregator, or corruptor attributes', 'use_aggregators': 'use a predefined aggregator like min, max, mean, median, or sum to reduce buffered observations'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/observable/base_test.py

Prompts

```
['create a Generic observable from a callable that returns observations given a physics object', 'create a MujocoFeature observable to expose a named MuJoCo mjData field as an observation', 'create a MujocoCamera observable to render RGB or depth images from a named MuJoCo camera', 'configure an Observable by setting update_interval, buffer_size, delay, aggregator, or corruptor attributes', 'use a predefined aggregator like min, max, mean, median, or sum to reduce buffered observations', 'test the Observable base class update_interval, buffer_size, delay, and enabled properties', 'test the Generic observable wrapping a callable with a custom update_interval', 'test the MujocoFeature observable to extract qpos or geom_xpos from physics data', 'test the MujocoCamera observable to render camera images from a MuJoCo physics environment', 'test applying a corruptor function to modify observable values before returning them', 'create an MJCFFeature observable to expose a named attribute of an MJCF element as an observation', 'create an MJCFCamera observable to render RGB, depth, or segmentation images from an MJCF camera element', 'slice an MJCFFeature observable using __getitem__ to select specific array indices of the bound attribute', 'configure MJCFCamera render options like depth, segmentation, scene_option, and render_flag_overrides for custom visualization', 'inspect the array_spec property of MJCFCamera to get the BoundedArray spec with shape, dtype, and value bounds', 'create an MJCFFeature observable with an index list to select specific rows from an xmat array', 'slice an MJCFFeature observable using bracket notation to select a subset of array elements', 'create an MJCFCamera observable with segmentation enabled to render per-geom integer labels instead of RGB pixels']
```

Usage

```
{'test_Observable_base_properties': 'test the Observable base class update_interval, buffer_size, delay, and enabled properties', 'test_Generic_observable': 'test the Generic observable wrapping a callable with a custom update_interval', 'test_MujocoFeature_observable': 'test the MujocoFeature observable to extract qpos or geom_xpos from physics data', 'test_MujocoCamera_observable': 'test the MujocoCamera observable to render camera images from a MuJoCo physics environment', 'test_corruptor_on_observable': 'test applying a corruptor function to modify observable values before returning them'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/observable/mjcf.py

Prompts

```
['create a Generic observable from a callable that returns observations given a physics object', 'create a MujocoFeature observable to expose a named MuJoCo mjData field as an observation', 'create a MujocoCamera observable to render RGB or depth images from a named MuJoCo camera', 'configure an Observable by setting update_interval, buffer_size, delay, aggregator, or corruptor attributes', 'use a predefined aggregator like min, max, mean, median, or sum to reduce buffered observations', 'test the Observable base class update_interval, buffer_size, delay, and enabled properties', 'test the Generic observable wrapping a callable with a custom update_interval', 'test the MujocoFeature observable to extract qpos or geom_xpos from physics data', 'test the MujocoCamera observable to render camera images from a MuJoCo physics environment', 'test applying a corruptor function to modify observable values before returning them', 'create an MJCFFeature observable to expose a named attribute of an MJCF element as an observation', 'create an MJCFCamera observable to render RGB, depth, or segmentation images from an MJCF camera element', 'slice an MJCFFeature observable using __getitem__ to select specific array indices of the bound attribute', 'configure MJCFCamera render options like depth, segmentation, scene_option, and render_flag_overrides for custom visualization', 'inspect the array_spec property of MJCFCamera to get the BoundedArray spec with shape, dtype, and value bounds', 'create an MJCFFeature observable with an index list to select specific rows from an xmat array', 'slice an MJCFFeature observable using bracket notation to select a subset of array elements', 'create an MJCFCamera observable with segmentation enabled to render per-geom integer labels instead of RGB pixels']
```

Usage

```
{'create_MJCFFeature_observable': 'create an MJCFFeature observable to expose a named attribute of an MJCF element as an observation', 'create_MJCFCamera_observable': 'create an MJCFCamera observable to render RGB, depth, or segmentation images from an MJCF camera element', 'slice_MJCFFeature_with_getitem': 'slice an MJCFFeature observable using __getitem__ to select specific array indices of the bound attribute', 'configure_MJCFCamera_render_options': 'configure MJCFCamera render options like depth, segmentation, scene_option, and render_flag_overrides for custom visualization', 'inspect_MJCFCamera_array_spec': 'inspect the array_spec property of MJCFCamera to get the BoundedArray spec with shape, dtype, and value bounds'}
```

## File: google-deepmind_dmcontrol/dm_control/composer/observation/observable/mjcf_test.py

Prompts

```
['create a Generic observable from a callable that returns observations given a physics object', 'create a MujocoFeature observable to expose a named MuJoCo mjData field as an observation', 'create a MujocoCamera observable to render RGB or depth images from a named MuJoCo camera', 'configure an Observable by setting update_interval, buffer_size, delay, aggregator, or corruptor attributes', 'use a predefined aggregator like min, max, mean, median, or sum to reduce buffered observations', 'test the Observable base class update_interval, buffer_size, delay, and enabled properties', 'test the Generic observable wrapping a callable with a custom update_interval', 'test the MujocoFeature observable to extract qpos or geom_xpos from physics data', 'test the MujocoCamera observable to render camera images from a MuJoCo physics environment', 'test applying a corruptor function to modify observable values before returning them', 'create an MJCFFeature observable to expose a named attribute of an MJCF element as an observation', 'create an MJCFCamera observable to render RGB, depth, or segmentation images from an MJCF camera element', 'slice an MJCFFeature observable using __getitem__ to select specific array indices of the bound attribute', 'configure MJCFCamera render options like depth, segmentation, scene_option, and render_flag_overrides for custom visualization', 'inspect the array_spec property of MJCFCamera to get the BoundedArray spec with shape, dtype, and value bounds', 'create an MJCFFeature observable with an index list to select specific rows from an xmat array', 'slice an MJCFFeature observable using bracket notation to select a subset of array elements', 'create an MJCFCamera observable with segmentation enabled to render per-geom integer labels instead of RGB pixels']
```

Usage

```
{'create_MJCFFeature_observable': 'create an MJCFFeature observable to extract qpos or xpos data from an MJCF joint or geom element', 'create_MJCFFeature_with_index': 'create an MJCFFeature observable with an index list to select specific rows from an xmat array', 'slice_MJCFFeature_observable': 'slice an MJCFFeature observable using bracket notation to select a subset of array elements', 'create_MJCFCamera_observable': 'create an MJCFCamera observable to render RGB images from a named MJCF camera element at a given resolution', 'create_MJCFCamera_segmentation': 'create an MJCFCamera observable with segmentation enabled to render per-geom integer labels instead of RGB pixels'}
```

