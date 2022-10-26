# BENG183

# Acknowledgements: 
This homework and included tutorials is based on https://github.com/Irenexzwen. Big thanks to her! Check out her website http://wenxingzhao.com/

## Homework notes:
1) [Working environment 
setup](https://github.com/Irenexzwen/BIOE183/blob/master/Tutorial1_Preparation.md)
2) [Raw Data QC and 
Cleaning](https://github.com/Irenexzwen/BIOE183/blob/master/Tutorial2_RawData.md)
3) **Needs changing** [Mapping and 
quantification](https://github.com/Irenexzwen/BIOE183/blob/master/Tutorial3_Mapping_and_qualification.md)
4) [Differential 
analysis](https://github.com/Irenexzwen/BIOE183/blob/master/Tutorial4_DE.md)

## Raw Sample files:


Download the fastq files of the following samples below.

### Sample for the homework
We will use RNAseq data from [FlyAtlas2 
database](http://flyatlas.gla.ac.uk/FlyAtlas2/index.html), which collects 
hundreds of RNAseq data of drosophila melanogaster. You can search by 
gene, category or tissue. Here we downloaded 4 samples (female_head x 2, 
female_midgut x 2).

- Female Head
[[female_head1_R1_raw]](https://drive.google.com/file/d/1T6QDIcvY5qC_E488IjPZEkhvlukgXQbe/view?usp=sharing),[[female_head1_R2_raw]](https://drive.google.com/file/d/1RV6YPV9_KAUr9h-rEdOVRJHPuCV5ozT_/view?usp=sharing)

- Female Midgut
[[female_midgut1_R1_raw]](https://drive.google.com/file/d/124XZXIhu8Rm8CsvNYx87LVVgDl6UWOt3/view?usp=sharing),[[female_midgut1_R2_raw]](https://drive.google.com/file/d/11rBcLQ-HrYlV3oGgRklkD8-yAX3cCLqY/view?usp=sharing)



## Clean Data 

Follow tutorail 2 to clean reads in fastq files.

## Reference genome.fa / transcriptome.fa / gtf
We usually download the reference data from 
[ensemble](https://uswest.ensembl.org/info/data/ftp/index.html). You 
search "drosophila" and choose DNA / cDNA / gtf, then you use a `wget` to 
download.
- drosophila genome: 
ftp://ftp.ensembl.org/pub/release-97/fasta/drosophila_melanogaster/dna/Drosophila_melanogaster.BDGP6.22.dna.toplevel.fa.gz

- drosophila transcriptome: 
ftp://ftp.ensembl.org/pub/release-97/fasta/drosophila_melanogaster/cdna/Drosophila_melanogaster.BDGP6.22.cdna.all.fa.gz

- drosophila gtf: 
ftp://ftp.ensembl.org/pub/release-97/gtf/drosophila_melanogaster/Drosophila_melanogaster.BDGP6.22.97.chr.gtf.gz

## Index files
Pre-computed index files: [download 
here](https://drive.google.com/open?id=1CT-iZ2PzPwWa44KxhjYsv4pD5GnnJStg)

## FeatureCounts Count table

Follow tutorial 3 to produce feature counts table.

You can download feature counts for all samples [here](https://drive.google.com/file/d/1E_QnRJ_b98H_hINhukBXdqxd0Q2Qcqu4/view?usp=sharing)

## Resources:
#### Tutorials:
[1] Weill Cornell Medical Colledge: 
http://chagall.med.cornell.edu/RNASEQcourse/

#### Software manuals:
- [Bioconda](https://www.youtube.com/watch?v=lGa9PCSH5IU) starting from 
3:30. 
- [fastQC manual](https://dnacore.missouri.edu/PDF/FastQC_Manual.pdf)
- [fastp manual](https://github.com/OpenGene/fastp)