# HG002_Data_Freeze_v1.0

## Human Pangenome Reference Consortium
### HG002 Data Freeze (v1.0)

## Introduction
The Human Reference Pangenome Consortium is hosting a collection of HG002 (NA24385) data to serve as an initial training data set, which will guide the development of new assembly production and evaluation strategies. 

Information about our consortium can be found at https://humanpangenome.org/ and on Twitter @HumanPangenome.
 
The following data are available from the HG002 (NA24385) human cell line:
 
 - PacBio HiFi:  High-coverage with recent chemistries (v2.0 Chem Insert sizes 15kb and 20kb, and access to earlier chemistry with Insert sizes 19 kb and 24kb)
 - PacBio CLR:  Continuous Long Reads (30 kb size selection), >60X fold coverage from 2 SMRT Cells, 1 SMRT Cell is 30X fold coverage (v1.0 Chem). 
 - Oxford Nanopore (Unsheared PromethION data):  Totaling 658x coverage of unsheared sequencing (28 PromethION Flow cells).  With a total of ~51x 100kb+ reads.
 - Oxford Nanopore (Ultra-long RAD004 GridION data):  Totaling ##x coverage of unsheared sequencing (## GridION Flow cells).  With a total of ~15x 100kb+ reads.
 - Hi-C:  Sequencing libraries represent two distinct protocols/optimized methods (labeled HiC.1 and HiC.2, from two anonymized companies) to reach "smooth-coverage" with access to high coverage Nova-Seq (250bp PE).
 - Strand-seq data (provided by Jan Korbel’s laboratory).
 - 10X Genomics:  25X for NA24385 as well as >20X coverage for the parents (NA24149 and NA24143) as well as NA12878 using Illumina Instrumentation.  Data generated by 10X Genomics for the Genome in a Bottle (GIAB) Consortium
 - BioNano Maps with mean read length of 195 kb  (112X coverage) for the Genome in a Bottle (GIAB) Consortium
 - Illumina:  Whole genome data, 300x PCR-free Illumina 150bp + 40x PCR-free 250bp, from GIAB
 
All HG002 data (and links to parental data) are posted at the following Amazon s3 ‘humanpangenomics’ link:  https://s3-us-west-2.amazonaws.com/human-pangenomics/HG002/hpp_HG002_NA24385_son_v1/parents/links_HG003_NA24149_father.txt 
 
In addition, we will host links to the following parental data: PacBio (HiFi and CLR), Nanopore-PromethION unsheared, BioNano maps, 10XG, and Illumina data (300x PCR-free and 6kb mate-pair sequencing) for both Father (HG003, NA24149) and Mother (HG004,   	NA24143).
https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG002/hpp_HG002_NA24385_son_v1/parents/
 
Please contact  Karen Miga (khmiga@soe.ucsc.edu) if you need any additional information or assistance.
Data reuse and license
All data is released to the public domain (CC0) and we encourage its reuse. We would appreciate it if you would acknowledge the Human Pangenome Reference Consortium when assemblies are posted or if you use the data sets generated by the consortium.
Citation:
 
## Sequencing Data
 
The annotated table of sequence data can be downloaded [here](https://docs.google.com/spreadsheets/d/1eUXfyTqWVy9O3bYYyZdiEoWhnztUJXIf7u8X3UE-ryg/edit?usp=sharing).

## PacBio HiFi:
 
HiFi data: We have a total of 7 Cells worth of HG002 data with recent chemistries:
 
1. 3 Cells from a 15 kb library
2. 2 Cells from a 19 kb library
3. 2 Cells from a 20 kb library
4. 2 Cells from a 25 kb library
 
Datasets 1 and 3 are with the official 2.0 chemistry (to be launched in Oct 2019), 2 & 4 are with a slightly earlier version but still very good datasets. If you want to test higher depth of coverage you should be able to combine datasets 2-4 if you like (or all of them for that matter).
 
Insert size 15kb: 3 cells; coverage: 22x
Insert size 19-24kb: 4 cells, coverage: 24x
 
## PacBio CLR: 
 
HG002/NA24385 Ashkenazi son, CLR (30 kb size selection), ~30-fold coverage (1 SMRT Cell)
 
WUSTL
SMRT cell 'A01':
Polymerase read bases 140,829,614,688
Polymerase reads 5,606,947
Polymerase read N50 42,922
Subread Length (mean) 21,871
Subread N50 37,116
Insert length (mean) 22,072
Insert N50 37,703
Unique Molecular Yield: 123,059,829,616
 
SMRT cell 'C01':
Polymerase read     	bases 159,869,879,629
Polymerase reads 6,678,991
Polymerase read N50 23,936
Subread Length (mean) 20,549
Subread N50 34,601
Insert length (mean) 20,962
Insert N50 35,428
Unique Molecular Yield: 138,808,414,978

## Oxford Nanopore: 
 
## GIAB UL data

GIAB UL dataset (HG002_giab_ULfastqs_guppy3.2.4.fastq.gz) was generated using RAD004 sequencing chemistry on a GridION. 

NOTE: If you have previously downloaded this file (before January 9, 2020) please note that some of the reads in that file were later flagged to be removed. The list of read id's to be excluded is in the HG002_giab_UL_old_fastqs_mislabeled-sample_read-ids.txt.gz file.

## Nanopore PromethION data

The UCSC data (HG002_ucsc_Jan_2019_Guppy_3.4.fastq.gz) were generated using the Shasta publication protocol (3 LSK109-based sequencing libraries per PromethION flow cell with 3 flow cells per individual), with observed N50s (average) ~42 kb and 6x coverage per individual in 100kb+ reads.

The additional UCSC data (HG002_ucsc_Dec_2019_Guppy_3.2.fastq.gz) were generated in efforts to boost coverage in 100kb+ reads using the same Shasta publication protocol. 

The HG002_ucsc_Oct_2018_Guppy_3.0.fastq.gz dataset was generated at UCSC in 2018 as part of optimization using unsheared DNA and LSK109 sequencing chemistry.

The HG002_ONT_PAD64459_Guppy_3.2.fastq.gz was generated and donated by ONT using unsheared DNA and LSK109 chemistry.

 
## 10X Genomics: 
 
All data provided here (along w/ additional tools to visualize the data) are also available  at:  http://software.10xgenomics.com/giab2015
 
Samples Provided
Included in this data release are raw data and results from 4 different samples:
1. NA24385 (Ashkenazim trio son)
2. NA24149 (Ashkenazim trio father)
3. NA24143 (Ashkenazim trio mother)
 
II. Sample Preparation and Sequencing
All DNA was freshly extracted from cells obtained from Coriell, using a modified version of the Qiagen MagAttract protocol (as described in the GemCode User Guide Rev B).
 
10X GemCode libraries were prepared according to the standard GemCode protocol (as described in the GemCode User Guide Rev B). Briefly, 1.2ng of input molecules were partitioned using a microfluidic chip into > 200,000 molecular reactors to extend DNA fragments and introduce a 14bp partition-specific barcode, creating Linked-Reads.
 
Libraries were sequenced on a HiSeq2500 (using either High Output v4 or Rapid Run v1 chemistry) to the following short-read depths:
NA24385: 25X
NA24149: 22X
NA24143: 24X
 
Details on the GemCode technology can be found at:
http://10xgenomics.com
 
IV. Files and File Formats:
BAM (and index): Contains aligned and position-sorted reads along with associated barcodes.
 
Detailed documentation on formats for the above files can be found at:
http://software.10xgenomics.com
 
## BioNano DLS: 
 
all.bnx is the raw data after image processing and filtering for molecules >150kb
EXP_REFINEFINAL1.cmap is the de novo assembly consensus genome map set
 
## Illumina:
 
 - 300x PCR-free Illumina 150bp + 40x PCR-free 250bp   GIAB    	ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG002_NA24385_son/NIST_Illumina_2x250bps/
 - 6kb mate-pair         	GIAB    	ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG002_NA24385_son/NIST_Stanford_Illumina_6kb_matepair/
 
 
## HiC:

### HiC_1 
##### Files
 - HG002.HiC_1_S1_R1_001.fastq.gz
 - HG002.HiC_1_S1_R2_001.fastq.gz
 - HG002.HiC_1_S2_R1_001.fastq.gz
 - HG002.HiC_1_S2_R2_001.fastq.gz
 - HG002.HiC_1_S3_R1_001.fastq.gz
 - HG002.HiC_1_S3_R2_001.fastq.gz
 
##### Details
These three sequencing libraries are triplicates made from one sample
of 100,000 cells of the HG002 sample.
They are proximity ligation libraries generated using a procedure
that includes a linker sequence. Each library was generated using
 
The DNA fragmentation and proximity-ligation does not use restriction
enzymes. Thus, the mapping and analysis procedures may not to be
modified.
 
##### Alignment
The raw fastq data should be aligned using bwa mem with the -5SP
option. This effectively excludes the linker sequence from the bam
output alignments.
For example:
bwa mem -5SP index_path/hg38.fa Sample_R1.fastq Sample_R2.fastq
 
#### Linker sequence
The proximity-ligation procedure uses an adapter with a 3' overhang as
template for the proximity ligation. The adapter sequence is as follow:
 
5' GGTTCGTCCATCGATC 3'
3' CCAAGCAGGTAG 5'
 
The resulting bridge after proximity ligation will be (Ns being genomic DNA)
 
5' NNNNGGTTCGTCCATCGATCCCAAGCAGGTAGNNNN 3'
3' NNNNCCAAGCAGGTAGCTAGGGTTCGTCCATCNNNN 5'
 
### HiC_2
##### Files - 2x150bp Sequencing
HG002.HiC_2_R1.fastq.gz
HG002.HiC_2_R2.fastq.gz


##### Files - 2x250bp Sequencing*
HG002.HiC_2_NovaSeq_S2_L001_R1_001.fastq.gz
HG002.HiC_2_NovaSeq_S2_L001_R2_001.fastq.gz

*As of Jan 22 2020, only one dataset is available. Additional datasets will be made available within 1 week of the initial data freeze, in order to increase the total sequence depth of HiC_2 libraries to be equivalent with HiC_1 libraries.*


##### Details
These two sequencing libraries are generated from biological replicates (i.e. two independent cultures) HG002 lymphoblast cells obtained from Coriell (https://www.coriell.org/0/Sections/Search/Sample_Detail.aspx?Ref=GM24385&Product=CC). So the 2x150bp Sequencing library is prepared from Biological Replicate 1, while the 2x250bp library is prepared from Biological Replicate 2.

They are HiC libraries generated using a procedure that deploys an specialized combination of restriction enzymes (RE), where the RE cut site distributions are optimized to produce uniform genomic coverage. The specific RE cut site motifs are: ^GATC, G^ANTC, C^TNAG, T^TAA. The â€œ^â€ is the cut site on the + DNA strand, and the â€™Nâ€™ can be any of the 4 genomic bases. Because of this, there are 10 possible RE cut sites.


##### Alignment
We align the HiC data using bwa mem with the -SP5M option.

For example:
bwa mem -SP5M index_path/hg38.fa Sample_R1.fastq Sample_R2.fastq

A full mapping and data analysis pipeline for certain applications, such as identifying SNVs from HiC data, can be made available upon request.


##### Other Analysis Considerations - Normalization
The RE cut site distributions are optimized to produce uniform genomic coverage. For certain applications such as genome scaffolding, several open source tools (e.g. SALSA2) conduct data normalization based on RE cut site locations. We advise analyses groups to perform their analyses with normalization based on known information about RE cut sites locations AND without assuming a priori knowledge about RE cut site locations. For applications such as polishing, knowledge of RE cut site locations could help reducing errors (especially at chimeric junctions) to improve polishing accuracy. 

 
## Parents:
 
### HG003, Father

 | Data description | Contributor | Link |
 | ---------------- | ----------- | ---- |
 | Nanopore-PromethION | UCSC | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/UCSC_Ultralong_OxfordNanopore_Promethion/ |
 | PacBio CLR | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/10Xgenomics_ChromiumGenome/NA24149.fastqs/ |
 | 10XG | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/10Xgenomics_ChromiumGenome/NA24149.fastqs/ |
 | Bionano DLS | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/BioNano/ |
 | 300x PCR-free Illumina 150bp + 40x PCR-free 250bp | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/NIST_Illumina_2x250bps/ |
 | 6kb mate-pair | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/NIST_Stanford_Illumina_6kb_matepair/ |
 
### HG004, Mother
 
 | Data description | Contributor | Link |
 | ---------------- | ----------- | ---- |
 | Nanopore-PromethION | UCSC | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/UCSC_Ultralong_OxfordNanopore_Promethion/ |
 | PacBio CLR | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/PacBio_MtSinai_NIST/ |
 | 10XG | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/10Xgenomics_ChromiumGenome/ |
 | Bionano DLS | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/BioNano/ |
 | 300x PCR-free Illumina 150bp + 40x PCR-free 250bp | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/NIST_Illumina_2x250bps/ | 
 | 6kb mate-pair | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/NIST_Stanford_Illumina_6kb_matepair/ |


