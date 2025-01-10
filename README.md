# Segment Grouping of Influenza A

This directory creates a JSON that contains the mapping of Influenza A genbank assemblies to segment accessions.

It can be used to create a mapping for any taxon by replacing the taxon-id and running:

```
micromamba create -f environment.yaml
micromamba activate grouping
snakemake
```

As of 10.01.2024 there are 102'477 assemblies which encompass a total of 809'682 sequences, the majority of assemblies contain all segments, the distribution is as follows:
`{8: 101123, 5: 51, 6: 20, 7: 39, 3: 3, 4: 10, 1: 1}`