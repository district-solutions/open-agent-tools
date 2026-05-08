# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/examples/Gen1/python_samples/mps_semidense_point_visibility/PointsAndObservationsManager.py

Prompts

```
['create a PointsAndObservationsManager from an MpsDataProvider to load and index semi-dense point cloud data', 'get the visible 2D UV observations and point UIDs for a given SLAM camera timestamp and serial', 'get the projected RGB camera UV observations and point UIDs from SLAM-visible point unique IDs', 'build an index mapping timestamp and camera serial pairs to observation slice ranges for fast retrieval', 'review the PointsAndObservationsManager class and its methods for semi-dense point cloud manipulation and observation retrieval', 'create a TracksManager instance to manage MPS point visibility tracks across camera channels', 'update tracks for a camera label with new UV coordinates and remove stale observations', 'get or create the track dictionary for a given camera label string', 'add a new point to a track dictionary and trim history to max track length', 'remove track entries that are no longer visible from the currently visible point UIDs set', 'run the MPS semi-dense point visibility demo with Rerun visualization for VRS data', 'display 2D observations, tracklets, and 3D visible points onto Rerun image views', 'create a PointsAndObservationsManager from an MpsDataProvider to retrieve visible points per camera and timestamp', 'run OnlineRgbCameraHelper to retrieve RGB camera calibration and corrected pose from MPS and VRS data providers', 'review OnlineRgbCameraHelper to understand how it falls back from online to static camera calibration', 'summarize OnlineRgbCameraHelper which returns a tuple of CameraCalibration and SE3 pose for a given device time', 'test OnlineRgbCameraHelper with mock VrsDataProvider and MpsDataProvider to verify calibration fallback logic', 'refactor OnlineRgbCameraHelper to handle None corrected RGB pose gracefully instead of calling exit']
```

Usage

```
{'create_manager_from_mps': 'create a PointsAndObservationsManager from an MpsDataProvider to load and index semi-dense point cloud data', 'get_slam_observations': 'get the visible 2D UV observations and point UIDs for a given SLAM camera timestamp and serial', 'get_rgb_observations': 'get the projected RGB camera UV observations and point UIDs from SLAM-visible point unique IDs', 'index_observations': 'build an index mapping timestamp and camera serial pairs to observation slice ranges for fast retrieval', 'review_manager_class': 'review the PointsAndObservationsManager class and its methods for semi-dense point cloud manipulation and observation retrieval'}
```

## File: facebookresearch_projectariatools/examples/Gen1/python_samples/mps_semidense_point_visibility/TracksManager.py

Prompts

```
['create a PointsAndObservationsManager from an MpsDataProvider to load and index semi-dense point cloud data', 'get the visible 2D UV observations and point UIDs for a given SLAM camera timestamp and serial', 'get the projected RGB camera UV observations and point UIDs from SLAM-visible point unique IDs', 'build an index mapping timestamp and camera serial pairs to observation slice ranges for fast retrieval', 'review the PointsAndObservationsManager class and its methods for semi-dense point cloud manipulation and observation retrieval', 'create a TracksManager instance to manage MPS point visibility tracks across camera channels', 'update tracks for a camera label with new UV coordinates and remove stale observations', 'get or create the track dictionary for a given camera label string', 'add a new point to a track dictionary and trim history to max track length', 'remove track entries that are no longer visible from the currently visible point UIDs set', 'run the MPS semi-dense point visibility demo with Rerun visualization for VRS data', 'display 2D observations, tracklets, and 3D visible points onto Rerun image views', 'create a PointsAndObservationsManager from an MpsDataProvider to retrieve visible points per camera and timestamp', 'run OnlineRgbCameraHelper to retrieve RGB camera calibration and corrected pose from MPS and VRS data providers', 'review OnlineRgbCameraHelper to understand how it falls back from online to static camera calibration', 'summarize OnlineRgbCameraHelper which returns a tuple of CameraCalibration and SE3 pose for a given device time', 'test OnlineRgbCameraHelper with mock VrsDataProvider and MpsDataProvider to verify calibration fallback logic', 'refactor OnlineRgbCameraHelper to handle None corrected RGB pose gracefully instead of calling exit']
```

Usage

```
{'create_tracks_manager': 'create a TracksManager instance to manage MPS point visibility tracks across camera channels', 'update_tracks_and_remove_old_observations': 'update tracks for a camera label with new UV coordinates and remove stale observations', 'get_track_for_camera_label': 'get or create the track dictionary for a given camera label string', 'add_point_to_track': 'add a new point to a track dictionary and trim history to max track length', 'remove_non_visible_observations': 'remove track entries that are no longer visible from the currently visible point UIDs set'}
```

## File: facebookresearch_projectariatools/examples/Gen1/python_samples/mps_semidense_point_visibility/mps_semidense_point_visibility_demo.py

Prompts

```
['create a PointsAndObservationsManager from an MpsDataProvider to load and index semi-dense point cloud data', 'get the visible 2D UV observations and point UIDs for a given SLAM camera timestamp and serial', 'get the projected RGB camera UV observations and point UIDs from SLAM-visible point unique IDs', 'build an index mapping timestamp and camera serial pairs to observation slice ranges for fast retrieval', 'review the PointsAndObservationsManager class and its methods for semi-dense point cloud manipulation and observation retrieval', 'create a TracksManager instance to manage MPS point visibility tracks across camera channels', 'update tracks for a camera label with new UV coordinates and remove stale observations', 'get or create the track dictionary for a given camera label string', 'add a new point to a track dictionary and trim history to max track length', 'remove track entries that are no longer visible from the currently visible point UIDs set', 'run the MPS semi-dense point visibility demo with Rerun visualization for VRS data', 'display 2D observations, tracklets, and 3D visible points onto Rerun image views', 'create a PointsAndObservationsManager from an MpsDataProvider to retrieve visible points per camera and timestamp', 'run OnlineRgbCameraHelper to retrieve RGB camera calibration and corrected pose from MPS and VRS data providers', 'review OnlineRgbCameraHelper to understand how it falls back from online to static camera calibration', 'summarize OnlineRgbCameraHelper which returns a tuple of CameraCalibration and SE3 pose for a given device time', 'test OnlineRgbCameraHelper with mock VrsDataProvider and MpsDataProvider to verify calibration fallback logic', 'refactor OnlineRgbCameraHelper to handle None corrected RGB pose gracefully instead of calling exit']
```

Usage

```
{'run_mps_semidense_demo': 'run the MPS semi-dense point visibility demo with Rerun visualization for VRS data', 'display_tracks_and_points': 'display 2D observations, tracklets, and 3D visible points onto Rerun image views', 'create_points_and_observations_manager': 'create a PointsAndObservationsManager from an MpsDataProvider to retrieve visible points per camera and timestamp', 'create_tracks_manager': 'create a TracksManager to update and store visible point tracks across frames with a max track length', 'get_rgb_observations': 'get RGB camera observations by reprojecting SLAM-visible 3D points using online camera calibration and device pose'}
```

## File: facebookresearch_projectariatools/examples/Gen1/python_samples/mps_semidense_point_visibility/utils.py

Prompts

```
['create a PointsAndObservationsManager from an MpsDataProvider to load and index semi-dense point cloud data', 'get the visible 2D UV observations and point UIDs for a given SLAM camera timestamp and serial', 'get the projected RGB camera UV observations and point UIDs from SLAM-visible point unique IDs', 'build an index mapping timestamp and camera serial pairs to observation slice ranges for fast retrieval', 'review the PointsAndObservationsManager class and its methods for semi-dense point cloud manipulation and observation retrieval', 'create a TracksManager instance to manage MPS point visibility tracks across camera channels', 'update tracks for a camera label with new UV coordinates and remove stale observations', 'get or create the track dictionary for a given camera label string', 'add a new point to a track dictionary and trim history to max track length', 'remove track entries that are no longer visible from the currently visible point UIDs set', 'run the MPS semi-dense point visibility demo with Rerun visualization for VRS data', 'display 2D observations, tracklets, and 3D visible points onto Rerun image views', 'create a PointsAndObservationsManager from an MpsDataProvider to retrieve visible points per camera and timestamp', 'run OnlineRgbCameraHelper to retrieve RGB camera calibration and corrected pose from MPS and VRS data providers', 'review OnlineRgbCameraHelper to understand how it falls back from online to static camera calibration', 'summarize OnlineRgbCameraHelper which returns a tuple of CameraCalibration and SE3 pose for a given device time', 'test OnlineRgbCameraHelper with mock VrsDataProvider and MpsDataProvider to verify calibration fallback logic', 'refactor OnlineRgbCameraHelper to handle None corrected RGB pose gracefully instead of calling exit']
```

Usage

```
{'run_OnlineRgbCameraHelper': 'run OnlineRgbCameraHelper to retrieve RGB camera calibration and corrected pose from MPS and VRS data providers', 'review_OnlineRgbCameraHelper': 'review OnlineRgbCameraHelper to understand how it falls back from online to static camera calibration', 'summarize_OnlineRgbCameraHelper': 'summarize OnlineRgbCameraHelper which returns a tuple of CameraCalibration and SE3 pose for a given device time', 'test_OnlineRgbCameraHelper': 'test OnlineRgbCameraHelper with mock VrsDataProvider and MpsDataProvider to verify calibration fallback logic', 'refactor_OnlineRgbCameraHelper': 'refactor OnlineRgbCameraHelper to handle None corrected RGB pose gracefully instead of calling exit'}
```

