# Agent Python Tools

- repo: facebookresearch/digit360
- repo_uri: https://github.com/facebookresearch/digit360

## File: facebookresearch_digit360/digit360/interface/usb/usb.py

Prompts

```
['enumerate all connected DIGIT360 USB devices and return a sorted list of Digit360Descriptor objects with serial, tty, audio, and ICS info', 'find and return a specific DIGIT360 device descriptor from a list by its USB serial number string', 'map a hand configuration dictionary to a list of matched DIGIT360 device descriptors by serial number', 'validate that a Digit360Descriptor has all fields populated and none are empty strings', 'discover tty, sound, and video4linux subsystem devices under a USB device and populate a Digit360Descriptor']
```

Usage

```
{'get_digit360_devices': 'enumerate all connected DIGIT360 USB devices and return a sorted list of Digit360Descriptor objects with serial, tty, audio, and ICS info', 'get_digit360_by_serial': 'find and return a specific DIGIT360 device descriptor from a list by its USB serial number string', 'get_digit360_by_hand': 'map a hand configuration dictionary to a list of matched DIGIT360 device descriptors by serial number', 'is_digit360_desc_valid': 'validate that a Digit360Descriptor has all fields populated and none are empty strings', 'find_subsystems': 'discover tty, sound, and video4linux subsystem devices under a USB device and populate a Digit360Descriptor'}
```

