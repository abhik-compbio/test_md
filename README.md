# test_md

## Generate topology

Use `pdb2gmx` to generate the topology, processed structure, and hydrogen atoms for the protein system.

```bash
gmx pdb2gmx -f 5AWL.pdb -o protein_processed.gro -water tip3p
```

### Input
- `5AWL.pdb` : Protein structure file

### Output
- `protein_processed.gro` : Processed protein structure
- `topol.top` : Topology file
- `posre.itp` : Position restraint file
