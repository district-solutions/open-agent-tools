# Agent Python Tools

- repo: google-deepmind/ferminet
- repo_uri: https://github.com/google-deepmind/ferminet

## File: google-deepmind_ferminet/ferminet/pbc/tests/features_test.py

Prompts

```
['test the PBC feature layer output shape matches init dimensions for electron features', 'test the PBC feature layer produces identical features after displacing an electron by a lattice vector', 'test make_pbc_feature_layer with configurable include_r_ae parameter for homogeneous electron gas', 'test networks.construct_input_features to build electron-electron and atom-electron distance features from coordinates', 'test the feature layer apply method with ae, ee, r_ae, and r_ee inputs', 'test that local energy is invariant when displacing an electron by a lattice vector under PBC', 'run the PbcHamiltonianTest test class to verify periodic boundary condition Hamiltonian behavior', 'build a FermiNet network using make_fermi_net with a multiwave envelope and PBC feature layer', 'create a local energy function closure via hamiltonian.local_energy with charges, nspins, and lattice parameters', 'review the test_periodicity method to understand how PBC energy invariance is validated with displaced electron coordinates']
```

Usage

```
{'test_pbc_feature_layer_shape': 'test the PBC feature layer output shape matches init dimensions for electron features', 'test_pbc_feature_layer_periodicity': 'test the PBC feature layer produces identical features after displacing an electron by a lattice vector', 'test_make_pbc_feature_layer': 'test make_pbc_feature_layer with configurable include_r_ae parameter for homogeneous electron gas', 'test_construct_input_features': 'test networks.construct_input_features to build electron-electron and atom-electron distance features from coordinates', 'test_feature_layer_apply': 'test the feature layer apply method with ae, ee, r_ae, and r_ee inputs'}
```

## File: google-deepmind_ferminet/ferminet/pbc/tests/hamiltonian_test.py

Prompts

```
['test the PBC feature layer output shape matches init dimensions for electron features', 'test the PBC feature layer produces identical features after displacing an electron by a lattice vector', 'test make_pbc_feature_layer with configurable include_r_ae parameter for homogeneous electron gas', 'test networks.construct_input_features to build electron-electron and atom-electron distance features from coordinates', 'test the feature layer apply method with ae, ee, r_ae, and r_ee inputs', 'test that local energy is invariant when displacing an electron by a lattice vector under PBC', 'run the PbcHamiltonianTest test class to verify periodic boundary condition Hamiltonian behavior', 'build a FermiNet network using make_fermi_net with a multiwave envelope and PBC feature layer', 'create a local energy function closure via hamiltonian.local_energy with charges, nspins, and lattice parameters', 'review the test_periodicity method to understand how PBC energy invariance is validated with displaced electron coordinates']
```

Usage

```
{'test_local_energy_periodicity': 'test that local energy is invariant when displacing an electron by a lattice vector under PBC', 'run_PbcHamiltonianTest': 'run the PbcHamiltonianTest test class to verify periodic boundary condition Hamiltonian behavior', 'build_fermi_net_with_pbc': 'build a FermiNet network using make_fermi_net with a multiwave envelope and PBC feature layer', 'create_local_energy_closure': 'create a local energy function closure via hamiltonian.local_energy with charges, nspins, and lattice parameters', 'review_PbcHamiltonianTest_test_periodicity': 'review the test_periodicity method to understand how PBC energy invariance is validated with displaced electron coordinates'}
```

