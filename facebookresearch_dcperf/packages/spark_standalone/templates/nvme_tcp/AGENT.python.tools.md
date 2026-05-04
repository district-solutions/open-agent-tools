# Agent Python Tools

- repo: facebookresearch/dcperf
- repo_uri: https://github.com/facebookresearch/dcperf

## File: facebookresearch_dcperf/packages/spark_standalone/templates/nvme_tcp/setup_nvmet.py

Prompts

```
['run the exporter setup command to configure NVMe-oF target subsystems and export devices over TCP', 'run the importer connect command to discover and connect to remote NVMe-oF target devices over TCP', 'run the importer mount command to create a RAID0 mdadm array and mount it as an XFS filesystem', 'run the importer clear command to unmount, stop mdadm, and disconnect all imported NVMe devices', 'build and install the nvme-cli tool from source by cloning, checking out, and compiling the repository', 'run a shell command as a subprocess and capture its stdout output as a string', 'execute a shell command string via os.system with optional logging and dry-run support', 'read and parse /etc/os-release into a dictionary of key-value pairs', 'check if the current OS distribution matches a given distro ID or ID_LIKE entry', 'create a named logger with a custom format string and log level using dictConfig']
```

Usage

```
{'setup_nvmet_exporter': 'run the exporter setup command to configure NVMe-oF target subsystems and export devices over TCP', 'setup_nvmet_importer_connect': 'run the importer connect command to discover and connect to remote NVMe-oF target devices over TCP', 'setup_nvmet_importer_mount': 'run the importer mount command to create a RAID0 mdadm array and mount it as an XFS filesystem', 'setup_nvmet_importer_clear': 'run the importer clear command to unmount, stop mdadm, and disconnect all imported NVMe devices', 'build_nvme_cli': 'build and install the nvme-cli tool from source by cloning, checking out, and compiling the repository'}
```

## File: facebookresearch_dcperf/packages/spark_standalone/templates/nvme_tcp/utils.py

Prompts

```
['run the exporter setup command to configure NVMe-oF target subsystems and export devices over TCP', 'run the importer connect command to discover and connect to remote NVMe-oF target devices over TCP', 'run the importer mount command to create a RAID0 mdadm array and mount it as an XFS filesystem', 'run the importer clear command to unmount, stop mdadm, and disconnect all imported NVMe devices', 'build and install the nvme-cli tool from source by cloning, checking out, and compiling the repository', 'run a shell command as a subprocess and capture its stdout output as a string', 'execute a shell command string via os.system with optional logging and dry-run support', 'read and parse /etc/os-release into a dictionary of key-value pairs', 'check if the current OS distribution matches a given distro ID or ID_LIKE entry', 'create a named logger with a custom format string and log level using dictConfig']
```

Usage

```
{'run_cmd': 'run a shell command as a subprocess and capture its stdout output as a string', 'exec_cmd': 'execute a shell command string via os.system with optional logging and dry-run support', 'get_os_release': 'read and parse /etc/os-release into a dictionary of key-value pairs', 'is_distro_like': 'check if the current OS distribution matches a given distro ID or ID_LIKE entry', 'setup_logger': 'create a named logger with a custom format string and log level using dictConfig'}
```

