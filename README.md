# Assemblytics: a web analytics tool for the detection of variants from an assembly 

Modified version of assemblytics, including faster computation of N50, and removal of the interchromosomal/inversion variant filters.
The R scripts are removed, and the maximum variant length is set to entire chromosome, minimum variant size is set to 100

To run Assemblytics on the command-line, simply make all scripts executable (chmod +x script_name)

Then run as:

```
python Assemblytics delta_file output_prefix unique_anchor_length

```

The delta file  may be produced using nucmer:

```
nucmer Reference.fa  Query.fa -p prefix
```

# Cite
Please cite http://www.ncbi.nlm.nih.gov/pubmed/27318204
