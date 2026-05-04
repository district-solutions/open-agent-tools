# Agent Python Tools

- repo: facebookresearch/generic-grouping
- repo_uri: https://github.com/facebookresearch/generic-grouping

## File: facebookresearch_generic-grouping/mmdet/version.py

Prompts

```
["parse a version string like '2.8.0' or '1.0.0rc3' into a tuple of integers and release candidate markers", 'check the mmdet version string by importing __version__ from the mmdet version module', 'get the short version alias which references the same value as __version__ in mmdet', 'inspect the precomputed version_info tuple parsed from the mmdet __version__ string at module load time', "parse a release candidate version string such as '1.2.0rc5' using parse_version_info to extract the rc component"]
```

Usage

```
{'parse_version_info': "parse a version string like '2.8.0' or '1.0.0rc3' into a tuple of integers and release candidate markers", 'check_mmseg_version': 'check the mmdet version string by importing __version__ from the mmdet version module', 'get_short_version': 'get the short version alias which references the same value as __version__ in mmdet', 'inspect_version_info_tuple': 'inspect the precomputed version_info tuple parsed from the mmdet __version__ string at module load time', 'parse_rc_version': "parse a release candidate version string such as '1.2.0rc5' using parse_version_info to extract the rc component"}
```

