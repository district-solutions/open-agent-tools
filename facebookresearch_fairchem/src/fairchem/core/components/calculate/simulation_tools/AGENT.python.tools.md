# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/components/calculate/simulation_tools/thermostats.py

Prompts

```
['build a NoseHooverNVT thermostat with a target temperature and damping time for NVT MD simulations', 'build a Bussi stochastic velocity rescaling thermostat with a target temperature and coupling time', 'build a Langevin thermostat with a target temperature and friction coefficient for stochastic MD dynamics', 'build a BerendsenNPT thermostat with temperature, pressure, and coupling times for constant pressure MD simulations', 'save and restore the internal state of a Bussi or Langevin thermostat for checkpointing MD runs', 'create a TrajectoryFrame from an ASE Atoms object with step number and simulation time', 'convert a TrajectoryFrame dataclass instance to a dictionary for Parquet serialization', 'append a TrajectoryFrame to a ParquetTrajectoryWriter buffer with automatic flush on interval', 'flush buffered trajectory frames to disk as a new Parquet row group with zstd compression', 'use ParquetTrajectoryWriter as a context manager to write MD trajectory data and auto close']
```

Usage

```
{'build_nose_hoover_nvt_thermostat': 'build a NoseHooverNVT thermostat with a target temperature and damping time for NVT MD simulations', 'build_bussi_thermostat': 'build a Bussi stochastic velocity rescaling thermostat with a target temperature and coupling time', 'build_langevin_thermostat': 'build a Langevin thermostat with a target temperature and friction coefficient for stochastic MD dynamics', 'build_berendsen_npt_thermostat': 'build a BerendsenNPT thermostat with temperature, pressure, and coupling times for constant pressure MD simulations', 'save_restore_thermostat_state': 'save and restore the internal state of a Bussi or Langevin thermostat for checkpointing MD runs'}
```

## File: facebookresearch_fairchem/src/fairchem/core/components/calculate/simulation_tools/trajectory.py

Prompts

```
['build a NoseHooverNVT thermostat with a target temperature and damping time for NVT MD simulations', 'build a Bussi stochastic velocity rescaling thermostat with a target temperature and coupling time', 'build a Langevin thermostat with a target temperature and friction coefficient for stochastic MD dynamics', 'build a BerendsenNPT thermostat with temperature, pressure, and coupling times for constant pressure MD simulations', 'save and restore the internal state of a Bussi or Langevin thermostat for checkpointing MD runs', 'create a TrajectoryFrame from an ASE Atoms object with step number and simulation time', 'convert a TrajectoryFrame dataclass instance to a dictionary for Parquet serialization', 'append a TrajectoryFrame to a ParquetTrajectoryWriter buffer with automatic flush on interval', 'flush buffered trajectory frames to disk as a new Parquet row group with zstd compression', 'use ParquetTrajectoryWriter as a context manager to write MD trajectory data and auto close']
```

Usage

```
{'create_TrajectoryFrame_from_atoms': 'create a TrajectoryFrame from an ASE Atoms object with step number and simulation time', 'convert_TrajectoryFrame_to_dict': 'convert a TrajectoryFrame dataclass instance to a dictionary for Parquet serialization', 'append_frame_to_parquet_writer': 'append a TrajectoryFrame to a ParquetTrajectoryWriter buffer with automatic flush on interval', 'flush_parquet_trajectory_buffer': 'flush buffered trajectory frames to disk as a new Parquet row group with zstd compression', 'use_parquet_writer_context_manager': 'use ParquetTrajectoryWriter as a context manager to write MD trajectory data and auto close'}
```

