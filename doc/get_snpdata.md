# NAME

**get_snpdata**

# USAGE

**get_snpdata**(vcf.file="file.vcf.gz", meta.file="file.txt", output.dir="/path/to/output/dir", gaf=NULL, gff=NULL)

# DESCRIPTION

**get_snpdata** is a function that create the SNPdata object required for this package.

# OPTIONS
```
vcf.file: the input vcf file (required)
meta.file: the metadata file (required)
output.dir: the path to the folder where the output files will be stored (optional)
gaf: the gene ontology annotation file (optional). this could be downloaded from the PlasmoDB website
gff: the gene annotation file (optional). this could be downloaded from the PlasmoDB website

# RETURN
a SNPdata object with the following elements:
```
     1.  meta: the metadata table
     2.  details: the genomic coordinates of the SNPs
     3.  GT: the matrix of genotypes
     4.  vcf: the vcf file from which the object was generated
     5.  index: an integer
```
