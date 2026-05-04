# Agent Python Tools

- repo: google-deepmind/flowsforatomicsolids
- repo_uri: https://github.com/google-deepmind/flows_for_atomic_solids

## File: google-deepmind_flowsforatomicsolids/systems/energies.py

Prompts

```
['create a subclass of PotentialEnergy that implements the abstract energy method for custom particle systems', 'compute the forces exerted on each particle using PotentialEnergy.forces with particle coordinates and box length', 'compute the excess virial pressure for particle coordinates using PotentialEnergy.pressure with periodic boundary conditions', 'create a subclass of PairwisePotentialEnergy that implements _unclipped_pairwise_potential for a custom pairwise interaction model', 'compute pairwise forces between all particle pairs using PairwisePotentialEnergy.pairwise_forces with PBC coordinates', 'compute the monatomic water potential energy for a batch of particle coordinates using the mW model', 'compute the two-body pairwise interaction energy between particles using the mW potential with a smooth cutoff', 'compute the three-body angular interaction energy between particle triplets using the mW model with tetrahedral preference', 'compute forces on each particle by taking the negative gradient of the monatomic water energy with respect to coordinates', 'compute the excess virial pressure for a batch of particle coordinates using the monatomic water potential energy']
```

Usage

```
{'create_PotentialEnergy_subclass': 'create a subclass of PotentialEnergy that implements the abstract energy method for custom particle systems', 'compute_forces_PotentialEnergy': 'compute the forces exerted on each particle using PotentialEnergy.forces with particle coordinates and box length', 'compute_pressure_PotentialEnergy': 'compute the excess virial pressure for particle coordinates using PotentialEnergy.pressure with periodic boundary conditions', 'create_PairwisePotentialEnergy_subclass': 'create a subclass of PairwisePotentialEnergy that implements _unclipped_pairwise_potential for a custom pairwise interaction model', 'compute_pairwise_forces_PairwisePotentialEnergy': 'compute pairwise forces between all particle pairs using PairwisePotentialEnergy.pairwise_forces with PBC coordinates'}
```

## File: google-deepmind_flowsforatomicsolids/systems/monatomic_water.py

Prompts

```
['create a subclass of PotentialEnergy that implements the abstract energy method for custom particle systems', 'compute the forces exerted on each particle using PotentialEnergy.forces with particle coordinates and box length', 'compute the excess virial pressure for particle coordinates using PotentialEnergy.pressure with periodic boundary conditions', 'create a subclass of PairwisePotentialEnergy that implements _unclipped_pairwise_potential for a custom pairwise interaction model', 'compute pairwise forces between all particle pairs using PairwisePotentialEnergy.pairwise_forces with PBC coordinates', 'compute the monatomic water potential energy for a batch of particle coordinates using the mW model', 'compute the two-body pairwise interaction energy between particles using the mW potential with a smooth cutoff', 'compute the three-body angular interaction energy between particle triplets using the mW model with tetrahedral preference', 'compute forces on each particle by taking the negative gradient of the monatomic water energy with respect to coordinates', 'compute the excess virial pressure for a batch of particle coordinates using the monatomic water potential energy']
```

Usage

```
{'compute_monatomic_water_energy': 'compute the monatomic water potential energy for a batch of particle coordinates using the mW model', 'compute_two_body_energy': 'compute the two-body pairwise interaction energy between particles using the mW potential with a smooth cutoff', 'compute_three_body_energy': 'compute the three-body angular interaction energy between particle triplets using the mW model with tetrahedral preference', 'compute_forces_from_energy': 'compute forces on each particle by taking the negative gradient of the monatomic water energy with respect to coordinates', 'compute_pressure_from_energy': 'compute the excess virial pressure for a batch of particle coordinates using the monatomic water potential energy'}
```

