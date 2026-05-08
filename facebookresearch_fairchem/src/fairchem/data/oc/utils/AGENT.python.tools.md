# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/data/oc/utils/flag_anomaly.py

Prompts

```
['create a DetectTrajAnomaly instance with initial and final ASE atoms objects and atom tags', 'test if the adsorbate connectivity changed between initial and final relaxation structures', 'test if the surface underwent reconstruction by comparing bond connectivity with a tolerance cushion', 'test if the adsorbate has fully desorbed from the surface slab atoms', 'test if any adsorbate atom is interacting with a frozen bulk atom in the slab', 'create a PlaneBoundTriclinicGeometry from an ASE cell with periodic boundary condition shift', 'create a BoxGeometry from center and length or corner coordinates for orthorhombic cells', 'calculate the shortest distance between a plane and external points using normal vector', 'generate a packmol input structure string to pack solvent molecules inside a geometry', 'extract all box properties from any two of center, length, lo_corner, or hi_corner', 'write VASP input files for an ASE Atoms structure to a specified output directory', 'calculate the k-point mesh for a surface calculation based on the unit cell size', 'clean up ASE Atoms and VASP flags by enforcing the right-hand rule and setting k-points', 'run a VASP relaxation calculation on an ASE Atoms object with custom VASP flags', 'set up VASP pseudopotential paths and setups for an ASE Atoms structure']
```

Usage

```
{'create_DetectTrajAnomaly': 'create a DetectTrajAnomaly instance with initial and final ASE atoms objects and atom tags', 'test_is_adsorbate_dissociated': 'test if the adsorbate connectivity changed between initial and final relaxation structures', 'test_has_surface_changed': 'test if the surface underwent reconstruction by comparing bond connectivity with a tolerance cushion', 'test_is_adsorbate_desorbed': 'test if the adsorbate has fully desorbed from the surface slab atoms', 'test_is_adsorbate_intercalated': 'test if any adsorbate atom is interacting with a frozen bulk atom in the slab'}
```

## File: facebookresearch_fairchem/src/fairchem/data/oc/utils/geometry.py

Prompts

```
['create a DetectTrajAnomaly instance with initial and final ASE atoms objects and atom tags', 'test if the adsorbate connectivity changed between initial and final relaxation structures', 'test if the surface underwent reconstruction by comparing bond connectivity with a tolerance cushion', 'test if the adsorbate has fully desorbed from the surface slab atoms', 'test if any adsorbate atom is interacting with a frozen bulk atom in the slab', 'create a PlaneBoundTriclinicGeometry from an ASE cell with periodic boundary condition shift', 'create a BoxGeometry from center and length or corner coordinates for orthorhombic cells', 'calculate the shortest distance between a plane and external points using normal vector', 'generate a packmol input structure string to pack solvent molecules inside a geometry', 'extract all box properties from any two of center, length, lo_corner, or hi_corner', 'write VASP input files for an ASE Atoms structure to a specified output directory', 'calculate the k-point mesh for a surface calculation based on the unit cell size', 'clean up ASE Atoms and VASP flags by enforcing the right-hand rule and setting k-points', 'run a VASP relaxation calculation on an ASE Atoms object with custom VASP flags', 'set up VASP pseudopotential paths and setups for an ASE Atoms structure']
```

Usage

```
{'create_plane_bound_triclinic_geometry': 'create a PlaneBoundTriclinicGeometry from an ASE cell with periodic boundary condition shift', 'create_box_geometry': 'create a BoxGeometry from center and length or corner coordinates for orthorhombic cells', 'calculate_distance_point_plane': 'calculate the shortest distance between a plane and external points using normal vector', 'generate_packmol_structure_inside': 'generate a packmol input structure string to pack solvent molecules inside a geometry', 'extract_box_properties': 'extract all box properties from any two of center, length, lo_corner, or hi_corner'}
```

## File: facebookresearch_fairchem/src/fairchem/data/oc/utils/vasp.py

Prompts

```
['create a DetectTrajAnomaly instance with initial and final ASE atoms objects and atom tags', 'test if the adsorbate connectivity changed between initial and final relaxation structures', 'test if the surface underwent reconstruction by comparing bond connectivity with a tolerance cushion', 'test if the adsorbate has fully desorbed from the surface slab atoms', 'test if any adsorbate atom is interacting with a frozen bulk atom in the slab', 'create a PlaneBoundTriclinicGeometry from an ASE cell with periodic boundary condition shift', 'create a BoxGeometry from center and length or corner coordinates for orthorhombic cells', 'calculate the shortest distance between a plane and external points using normal vector', 'generate a packmol input structure string to pack solvent molecules inside a geometry', 'extract all box properties from any two of center, length, lo_corner, or hi_corner', 'write VASP input files for an ASE Atoms structure to a specified output directory', 'calculate the k-point mesh for a surface calculation based on the unit cell size', 'clean up ASE Atoms and VASP flags by enforcing the right-hand rule and setting k-points', 'run a VASP relaxation calculation on an ASE Atoms object with custom VASP flags', 'set up VASP pseudopotential paths and setups for an ASE Atoms structure']
```

Usage

```
{'write_vasp_input_files': 'write VASP input files for an ASE Atoms structure to a specified output directory', 'calculate_surface_k_points': 'calculate the k-point mesh for a surface calculation based on the unit cell size', 'clean_up_inputs': 'clean up ASE Atoms and VASP flags by enforcing the right-hand rule and setting k-points', 'run_vasp_relaxation': 'run a VASP relaxation calculation on an ASE Atoms object with custom VASP flags', 'setup_vasp_pseudopotentials': 'set up VASP pseudopotential paths and setups for an ASE Atoms structure'}
```

