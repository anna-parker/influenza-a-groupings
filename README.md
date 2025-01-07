# Segment Grouping of Influenza A

This directory creates a JSON that contains the mapping of Influenza A genbank assemblies to segment accessions.

It can be used to create a mapping for any taxon by replacing the taxon-id and running:

```
micromamba create -f environment.yaml
micromamba activate grouping
snakemake
```
