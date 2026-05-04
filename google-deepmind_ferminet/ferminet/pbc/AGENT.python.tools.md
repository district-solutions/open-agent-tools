# Agent Python Tools

- repo: google-deepmind/ferminet
- repo_uri: https://github.com/google-deepmind/ferminet

## File: google-deepmind_ferminet/ferminet/pbc/envelopes.py

Prompts

```
['build a multiwave envelope for periodic boundary conditions using reciprocal lattice kpoints', 'create reciprocal lattice vectors from a lattice matrix and electron spin configuration', 'test the make_multiwave_envelope function with a set of kpoints and atom-electron coordinates', 'test the make_kpoints function with a lattice matrix and spin tuple', 'review the envelope init function that initializes sigma coefficients for Fourier series terms', 'build a periodic boundary condition feature layer for fermionic neural networks using make_pbc_feature_layer', 'compute the periodic norm of vectors in fractional coordinates using periodic_norm with a lattice metric tensor', 'create a PBC feature layer with a custom lattice matrix and dimension via make_pbc_feature_layer', 'create a PBC feature layer excluding electron-atom distance features by setting include_r_ae to False', 'create a PBC feature layer with log-rescaled electron-atom distances for numerical stability', 'build a python module to create an Ewald-summed Coulomb potential function for a periodic lattice', 'create a function that evaluates the local energy of a FermiNet wavefunction under periodic boundary conditions', 'test the make_ewald_potential function with a cubic lattice and verify convergence of the Ewald sum', 'refactor the local_energy function to support excited states in periodic boundary conditions', 'review the Ewald summation implementation for real and reciprocal space potential calculations']
```

Usage

```
{'build_multiwave_envelope': 'build a multiwave envelope for periodic boundary conditions using reciprocal lattice kpoints', 'create_kpoints': 'create reciprocal lattice vectors from a lattice matrix and electron spin configuration', 'test_make_multiwave_envelope': 'test the make_multiwave_envelope function with a set of kpoints and atom-electron coordinates', 'test_make_kpoints': 'test the make_kpoints function with a lattice matrix and spin tuple', 'review_envelope_init': 'review the envelope init function that initializes sigma coefficients for Fourier series terms'}
```

## File: google-deepmind_ferminet/ferminet/pbc/feature_layer.py

Prompts

```
['build a multiwave envelope for periodic boundary conditions using reciprocal lattice kpoints', 'create reciprocal lattice vectors from a lattice matrix and electron spin configuration', 'test the make_multiwave_envelope function with a set of kpoints and atom-electron coordinates', 'test the make_kpoints function with a lattice matrix and spin tuple', 'review the envelope init function that initializes sigma coefficients for Fourier series terms', 'build a periodic boundary condition feature layer for fermionic neural networks using make_pbc_feature_layer', 'compute the periodic norm of vectors in fractional coordinates using periodic_norm with a lattice metric tensor', 'create a PBC feature layer with a custom lattice matrix and dimension via make_pbc_feature_layer', 'create a PBC feature layer excluding electron-atom distance features by setting include_r_ae to False', 'create a PBC feature layer with log-rescaled electron-atom distances for numerical stability', 'build a python module to create an Ewald-summed Coulomb potential function for a periodic lattice', 'create a function that evaluates the local energy of a FermiNet wavefunction under periodic boundary conditions', 'test the make_ewald_potential function with a cubic lattice and verify convergence of the Ewald sum', 'refactor the local_energy function to support excited states in periodic boundary conditions', 'review the Ewald summation implementation for real and reciprocal space potential calculations']
```

Usage

```
{'build_pbc_feature_layer': 'build a periodic boundary condition feature layer for fermionic neural networks using make_pbc_feature_layer', 'compute_periodic_norm': 'compute the periodic norm of vectors in fractional coordinates using periodic_norm with a lattice metric tensor', 'create_feature_layer_with_lattice': 'create a PBC feature layer with a custom lattice matrix and dimension via make_pbc_feature_layer', 'create_feature_layer_without_r_ae': 'create a PBC feature layer excluding electron-atom distance features by setting include_r_ae to False', 'create_rescaled_feature_layer': 'create a PBC feature layer with log-rescaled electron-atom distances for numerical stability'}
```

## File: google-deepmind_ferminet/ferminet/pbc/hamiltonian.py

Prompts

```
['build a multiwave envelope for periodic boundary conditions using reciprocal lattice kpoints', 'create reciprocal lattice vectors from a lattice matrix and electron spin configuration', 'test the make_multiwave_envelope function with a set of kpoints and atom-electron coordinates', 'test the make_kpoints function with a lattice matrix and spin tuple', 'review the envelope init function that initializes sigma coefficients for Fourier series terms', 'build a periodic boundary condition feature layer for fermionic neural networks using make_pbc_feature_layer', 'compute the periodic norm of vectors in fractional coordinates using periodic_norm with a lattice metric tensor', 'create a PBC feature layer with a custom lattice matrix and dimension via make_pbc_feature_layer', 'create a PBC feature layer excluding electron-atom distance features by setting include_r_ae to False', 'create a PBC feature layer with log-rescaled electron-atom distances for numerical stability', 'build a python module to create an Ewald-summed Coulomb potential function for a periodic lattice', 'create a function that evaluates the local energy of a FermiNet wavefunction under periodic boundary conditions', 'test the make_ewald_potential function with a cubic lattice and verify convergence of the Ewald sum', 'refactor the local_energy function to support excited states in periodic boundary conditions', 'review the Ewald summation implementation for real and reciprocal space potential calculations']
```

Usage

```
{'build_ewald_potential': 'build a python module to create an Ewald-summed Coulomb potential function for a periodic lattice', 'create_local_energy_pbc': 'create a function that evaluates the local energy of a FermiNet wavefunction under periodic boundary conditions', 'test_make_ewald_potential': 'test the make_ewald_potential function with a cubic lattice and verify convergence of the Ewald sum', 'refactor_local_energy': 'refactor the local_energy function to support excited states in periodic boundary conditions', 'review_ewald_summation': 'review the Ewald summation implementation for real and reciprocal space potential calculations'}
```

