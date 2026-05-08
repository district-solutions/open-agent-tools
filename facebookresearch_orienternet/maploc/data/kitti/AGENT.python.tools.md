# Agent Python Tools

- repo: facebookresearch/orienternet
- repo_uri: https://github.com/facebookresearch/orienternet

## File: facebookresearch_orienternet/maploc/data/kitti/dataset.py

Prompts

```
['create a KittiDataModule instance with a config dict and optional TileManager for KITTI map localization data', 'run the KittiDataModule setup method to parse train val and test splits from KITTI data files', 'parse a KITTI split file or list of date drive paths into image names and GPS shifts', 'extract camera pose translation and roll pitch yaw Euler angles from a KITTI GPS file', 'build a sequence-aware PyTorch DataLoader that groups KITTI images by date drive and chunks them', 'download KITTI raw data sequences and calibration files from AWS S3 to a local data directory', 'generate map tiles from an OSM file using GPS data and save them to an output path', 'run the prepare script with --data_dir and --generate_tiles flags to download data and generate OSM tiles', 'review the prepare_osm function that parses GPS files, projects coordinates, and creates tile maps', 'refactor the download function to support resuming partial KITTI dataset downloads', 'parse a KITTI GPS file to extract lat/lon coordinates and rotation matrix from yaw, pitch, roll', 'parse a KITTI split file to extract sequence names and optional 3D shift vectors', 'parse a KITTI calibration file into a dictionary of rotation, translation, and projection matrices', 'get camera intrinsics and GPS-to-camera extrinsics from a KITTI calibration directory for a given camera index', 'review the KITTI split files list containing test1, test2, and train file names']
```

Usage

```
{'create_KittiDataModule': 'create a KittiDataModule instance with a config dict and optional TileManager for KITTI map localization data', 'setup_KittiDataModule_splits': 'run the KittiDataModule setup method to parse train val and test splits from KITTI data files', 'parse_split_KittiDataModule': 'parse a KITTI split file or list of date drive paths into image names and GPS shifts', 'get_frame_data_KittiDataModule': 'extract camera pose translation and roll pitch yaw Euler angles from a KITTI GPS file', 'create_sequence_dataloader_KittiDataModule': 'build a sequence-aware PyTorch DataLoader that groups KITTI images by date drive and chunks them'}
```

## File: facebookresearch_orienternet/maploc/data/kitti/prepare.py

Prompts

```
['create a KittiDataModule instance with a config dict and optional TileManager for KITTI map localization data', 'run the KittiDataModule setup method to parse train val and test splits from KITTI data files', 'parse a KITTI split file or list of date drive paths into image names and GPS shifts', 'extract camera pose translation and roll pitch yaw Euler angles from a KITTI GPS file', 'build a sequence-aware PyTorch DataLoader that groups KITTI images by date drive and chunks them', 'download KITTI raw data sequences and calibration files from AWS S3 to a local data directory', 'generate map tiles from an OSM file using GPS data and save them to an output path', 'run the prepare script with --data_dir and --generate_tiles flags to download data and generate OSM tiles', 'review the prepare_osm function that parses GPS files, projects coordinates, and creates tile maps', 'refactor the download function to support resuming partial KITTI dataset downloads', 'parse a KITTI GPS file to extract lat/lon coordinates and rotation matrix from yaw, pitch, roll', 'parse a KITTI split file to extract sequence names and optional 3D shift vectors', 'parse a KITTI calibration file into a dictionary of rotation, translation, and projection matrices', 'get camera intrinsics and GPS-to-camera extrinsics from a KITTI calibration directory for a given camera index', 'review the KITTI split files list containing test1, test2, and train file names']
```

Usage

```
{'download_kitti_data': 'download KITTI raw data sequences and calibration files from AWS S3 to a local data directory', 'prepare_osm_tiles': 'generate map tiles from an OSM file using GPS data and save them to an output path', 'run_prepare_cli': 'run the prepare script with --data_dir and --generate_tiles flags to download data and generate OSM tiles', 'review_prepare_osm': 'review the prepare_osm function that parses GPS files, projects coordinates, and creates tile maps', 'refactor_download': 'refactor the download function to support resuming partial KITTI dataset downloads'}
```

## File: facebookresearch_orienternet/maploc/data/kitti/utils.py

Prompts

```
['create a KittiDataModule instance with a config dict and optional TileManager for KITTI map localization data', 'run the KittiDataModule setup method to parse train val and test splits from KITTI data files', 'parse a KITTI split file or list of date drive paths into image names and GPS shifts', 'extract camera pose translation and roll pitch yaw Euler angles from a KITTI GPS file', 'build a sequence-aware PyTorch DataLoader that groups KITTI images by date drive and chunks them', 'download KITTI raw data sequences and calibration files from AWS S3 to a local data directory', 'generate map tiles from an OSM file using GPS data and save them to an output path', 'run the prepare script with --data_dir and --generate_tiles flags to download data and generate OSM tiles', 'review the prepare_osm function that parses GPS files, projects coordinates, and creates tile maps', 'refactor the download function to support resuming partial KITTI dataset downloads', 'parse a KITTI GPS file to extract lat/lon coordinates and rotation matrix from yaw, pitch, roll', 'parse a KITTI split file to extract sequence names and optional 3D shift vectors', 'parse a KITTI calibration file into a dictionary of rotation, translation, and projection matrices', 'get camera intrinsics and GPS-to-camera extrinsics from a KITTI calibration directory for a given camera index', 'review the KITTI split files list containing test1, test2, and train file names']
```

Usage

```
{'parse_gps_file': 'parse a KITTI GPS file to extract lat/lon coordinates and rotation matrix from yaw, pitch, roll', 'parse_split_file': 'parse a KITTI split file to extract sequence names and optional 3D shift vectors', 'parse_calibration_file': 'parse a KITTI calibration file into a dictionary of rotation, translation, and projection matrices', 'get_camera_calibration': 'get camera intrinsics and GPS-to-camera extrinsics from a KITTI calibration directory for a given camera index', 'review_split_files': 'review the KITTI split files list containing test1, test2, and train file names'}
```

