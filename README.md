# HG002_Data_Freeze_v1.0

## Human Pangenome Reference Consortium
### HG002 Data Freeze (v1.0)

## Introduction
The Human Reference Pangenome Consortium has organized a collection of HG002 (NA24385) data to guide the development of new assembly and evaluation strategies for our reference production efforts.

Information about our consortium can be found at https://humanpangenome.org/ and on Twitter @HumanPangenome.
 
The following data are available from the HG002 (NA24385) human cell line:
 
 - **PacBio HiFi**:  SMRTbell libraries were prepared and size-selected with
SageELF to the targeted size (15 kb, 19 kb, 20 kb, or 25 kb), with Sequel II System with Chemistry 2.0, Sequel II System with pre-2.0 Early Access Chemistry, and Sequel System with Chemistry 3.0
 - **PacBio CLR**:  Continuous Long Reads (30 kb size selection), >60X fold coverage from 2 SMRT Cells, 1 SMRT Cell is 30X fold coverage (v1.0 Chem).
 - **Oxford Nanopore (Unsheared PromethION data)**:  Totaling 658x coverage of unsheared sequencing (28 PromethION Flow cells).  With a total of ~51x 100kb+ reads.
 - **Oxford Nanopore (Ultra-long GridION data)**:  Totaling ~52x coverage of unsheared sequencing (106 MinION Flow cells).  With a total of ~15x 100kb+ reads.
 - **Hi-C**:  Sequencing libraries represent two distinct protocols/optimized methods (labeled HiC.1 and HiC.2, from two anonymized companies) to reach "smooth-coverage", with access to high coverage Nova-Seq (250bp PE).
 - **Strand-seq**: Strand-specific libraries were generated in collaboration with Jan Korbel’s laboratory (EMBL, Heidelberg). These data represent 192 barcoded single-cell libraries.
 - **10X Genomics**:  Chromium Genome Platform from 10X Genomics was sequenced to two depths: 51.7x coverage, and a deeper coverage (300Gb, 84.4x coverage) dataset.  Additional data is available from  BioProject: PRJNA527321
 - **BioNano Maps** DLE1 Data collected (Molecules >150 kbp): 317 Gbp Read N50(Molecules >150 kbp): 323 kbp provided by BioNano Genomics and Genome in a Bottle (GIAB) Consortium
 - **Illumina**:  Whole genome data, 300x PCR-free Illumina 150bp + 40x PCR-free 250bp, from GIAB
 
All HG002 data (and links to parental data) are posted at the following Amazon AWS public dataset: [human-pangenomics](https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG002/hpp_HG002_NA24385_son_v1/).


In addition, we will host links to the following parental data: PacBio (HiFi and CLR), Nanopore-PromethION unsheared, BioNano maps, 10XG, and Illumina data (300x PCR-free and 6kb mate-pair sequencing), and HiC for both Father (HG003, NA24149) and Mother (HG004, NA24143). With links provided below: [https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG002/hpp_HG002_NA24385_son_v1/parents/](https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG002/hpp_HG002_NA24385_son_v1/parents/)

Please contact  Karen Miga (khmiga@soe.ucsc.edu) or Miten Jain (miten@soe.ucsc.edu) if you need any additional information or assistance.

# Data reuse and license

All data are released to the public domain (CC0) and we encourage its reuse. We would appreciate it if you would acknowledge the Human Pangenome Reference Consortium when assemblies are posted or if you use the data sets generated by the consortium.

# Citations

_Please credit the use of GIAB datasets:_

Zook, Justin M., et al. "Extensive sequencing of seven human genomes to characterize benchmark reference materials." Scientific data 3.1 (2016): 1-26.

_Please credit the use of UCSC nanopore and HiC (HG003 and HG004) datasets:_

Shafin, Kishwar, et al. "Efficient de novo assembly of eleven human genomes using PromethION sequencing and a novel nanopore toolkit." BioRxiv (2019): 715722.

_Please credit the use of previously published PacBio HiFi  data:_

Wenger, Aaron M., et al. "Accurate circular consensus long-read sequencing improves variant detection and assembly of a human genome." Nature biotechnology 37.10 (2019): 1155-1162.

# Sequencing Data
 
_The annotated table of sequence data can be downloaded [here](https://docs.google.com/spreadsheets/d/1eUXfyTqWVy9O3bYYyZdiEoWhnztUJXIf7u8X3UE-ryg/edit?usp=sharing)._


## PacBio HiFi:
 
README - PacBio HiFi reads of HG002, Ashkenazim Son

Last Updated:  January 24, 2020

DNA samples were extracted from large homogenized growths of B-lymphoblastoid cell lines from the Coriell Institute for Medical Research and sheared to 20 kb with Megaruptor.  SMRTbell libraries were prepared and size-selected with SageELF to the targeted size (15 kb, 19 kb, 20 kb, or 25 kb).  Circular Consensus Sequence was generated in SMRT Link, and reads were filtered to 99% predicted accuracy (QV20).  Sample preparation, library preparation, sequencing,  and CCS analysis were performed at PacBio.

Sequel II System with Chemistry 2.0
 - Size selection - 15 kb or 20 kb selected on SageELF
 - Run time - 30 hrs per SMRT Cell 8M
 - CCS - "Circular Consensus Sequencing" analysis in SMRT Link v8.0
 - SRA - https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA586863
 - 15 kb Library, ~36-fold coverage
   - m64012_190920_173625
   - m64012_190921_234837
   - m64015_190920_185703
   - m64015_190922_010918
 - 20 kb Library, ~16-fold coverage
   - m64011_190830_220126
   - m64011_190901_095311

Sequel II System with pre-2.0 Early Access Chemistry
 - Size selection - 15 kb, 19 kb, or 25 kb selected on SageELF
 - Run time - 30 hrs per SMRT Cell 8M
 - CCS - "Circular Consensus Sequencing" analysis in SMRT Link v8.0 pre-release
 - 15 kb Library
   - m64002_190803_004553
   - m64002_190804_135352
   - m64004_190803_004451
 - 19 kb Library
   - m64011_190714_120746
   - m64011_190728_111204
 - 25 kb Library
   - m64011_190712_225711
   - m64011_190726_220327

Sequel System with Chemistry 3.0
 - Size selection - 15 kb selected on SageELF
 - Run time - 24 hrs per SMRT Cell 1M
 - CCS - "Circular Consensus Sequencing" analysis in SMRT Link v6.0
 - SRA - https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA529679
 - 15kb, ~28-fold coverage
   - m54238_180901_011437
   - m54238_180902_013549
   - m54238_180903_015530
   - m54238_180904_021549
   - m54238_180907_170406
   - m54238_180908_172515
   - m54238_180909_174539
   - m54238_180910_180559
   - m54238_180913_181445
   - m54238_180914_183539
   - m54238_180915_185611
   - m54238_180916_191625
   - m54238_180919_165326
   - m54238_180920_171425
   - m54238_180921_173448
   - m54238_180922_175520
   - m54238_180925_225123
   - m54238_180926_231301
   - m54238_180927_233325
   - m54328_180921_232856
   - m54328_180922_235017
   - m54328_180924_001027
   - m54328_180925_003051
   - m54328_180926_222309
   - m54328_180927_224427
   - m54328_180928_230446
   - m54328_180929_232524
   - m54329_180924_222717
   - m54329_180925_224838
   - m54329_180926_230856
   - m54329_180927_232921
   - m54334_180924_221206
   - m54334_180925_223328
   - m54334_180926_225337
   - m54334_180927_231334
   - m54335_180924_221150
   - m54335_180925_223313
   - m54335_180926_225328
   - m54335_180927_231344


For Research Use Only. Not for use in diagnostic procedures.   © Copyright 2020,
Pacific Biosciences of California, Inc. All rights reserved. The data provided
in these files is subject to change without notice and Pacific Biosciences
assumes no responsibility for any errors or omissions. Certain notices, terms,
conditions and/or use restrictions may pertain to your use of Pacific
Biosciences data, products and/or third party products. Please refer to the
applicable Pacific Biosciences Terms and Conditions of Sale and to the
applicable license terms at https://www.pacb.com/legal-and-trademarks/terms-and-
conditions-of-sale. Pacific Biosciences, the Pacific Biosciences logo, PacBio,
SMRT, SMRTbell, Iso-Seq, and Sequel are trademarks of Pacific Biosciences. All
other trademarks are the sole property of their respective owners.


## PacBio CLR: 
 
README - PacBio CLR reads of HG002, Ashkenazim Son

Last Updated:  January 24, 2020

DNA samples were extracted from large homogenized growths of B-lymphoblastoid
cell lines from the Coriell Institute for Medical Research and sheared to 30 kb
with Megaruptor.  A SMRTbell library was prepared with SMRTbell Express 2.0 and
size-selected with BluePippin to >15 kb.  The library was sequenced on the
Sequel II System with Chemistry 2.0 for 15 hrs per SMRT Cell 8M. Sample preparation,
library preparation and sequencing were performed at PacBio.

    m64070_190824_163708, ~30-fold unique molecular coverage

For Research Use Only. Not for use in diagnostic procedures. Copyright 2020,
Pacific Biosciences of California, Inc. All rights reserved. The data provided
in these files is subject to change without notice and Pacific Biosciences
assumes no responsibility for any errors or omissions. Certain notices, terms,
conditions and/or use restrictions may pertain to your use of Pacific
Biosciences data, products and/or third party products. Please refer to the
applicable Pacific Biosciences Terms and Conditions of Sale and to the
applicable license terms at https://www.pacb.com/legal-and-trademarks/terms-and-
conditions-of-sale. Pacific Biosciences, the Pacific Biosciences logo, PacBio,
SMRT, SMRTbell, Iso-Seq, and Sequel are trademarks of Pacific Biosciences. All
other trademarks are the sole property of their respective owners.


HG002 CLR data provided by the McDonnell Genome Institute at Washington University in St. Louis, Missouri, 

SAMPLE

HG002 extracted DNA from cells using Qiagen MagAttract Kit

METHODS

 - Shearing - 60kb with Megaruptor
 - Library prep - SMRTbell Express Template Prep 2.0
 - Size selection - >40 kb with BluePippin
 - Sequencing - Sequel System II with binding kit (101-842-900) and sequencing kit (101-820-200)
 - SMRT Cells - SMRT Cell 8M Tray 101-389-001
 - Run time - 20 hrs per SMRT Cell

SMRT cell 'A01':

 - Polymerase read bases 140,829,614,688
 - Polymerase reads 5,606,947
 - Polymerase read N50 42,922
 - Subread Length (mean) 21,871
 - Subread N50 37,116
 - Insert length (mean) 22,072
 - Insert N50 37,703
 - Unique Molecular Yield: 123,059,829,616

SMRT cell 'C01':

 - Polymerase read bases 159,869,879,629
 - Polymerase reads 6,678,991
 - Polymerase read N50 23,936
 - Subread Length (mean) 20,549
 - Subread N50 34,601
 - Insert length (mean) 20,962
 - Insert N50 35,428
 - Unique Molecular Yield: 138,808,414,978


## Oxford Nanopore: 
 
### GIAB UL data

GIAB UL dataset (HG002_giab_ULfastqs_guppy3.2.4.fastq.gz) was generated using RAD004 sequencing chemistry on a GridION. 

NOTE: If you have previously downloaded this file (before January 9, 2020) please note that some of the reads in that file were later flagged to be removed. The list of read id's to be excluded is in the HG002_giab_UL_old_fastqs_mislabeled-sample_read-ids.txt.gz file.

### Nanopore PromethION data

The UCSC data (HG002_ucsc_Jan_2019_Guppy_3.4.fastq.gz) were generated using the Shasta publication protocol (3 LSK109-based sequencing libraries per PromethION flow cell with 3 flow cells per individual), with observed N50s (average) ~42 kb and 6x coverage per individual in 100kb+ reads.

The additional UCSC data (HG002_ucsc_Dec_2019_Guppy_3.2.fastq.gz) were generated in efforts to boost coverage in 100kb+ reads using the same Shasta publication protocol. 

The HG002_ucsc_Oct_2018_Guppy_3.0.fastq.gz dataset was generated at UCSC in 2018 as part of optimization using unsheared DNA and LSK109 sequencing chemistry.

The HG002_ONT_PAD64459_Guppy_3.2.fastq.gz was generated and donated by ONT using unsheared DNA and LSK109 chemistry.
 
## 10X Genomics: 
 
(1) GIAB Data for the A/J trio from 10X Genomics, Inc.

The following datasets were produced using the Chromium Genome Platform from 10X Genomics:

A/J trio
 - Son (NA24385): 51.7x coverage (300Gb: 84.4x coverage)
 - Mother (NA24143): 69.1x coverage
 - Father (NA24149): 70.6x coverage


Samples were processed using Long Ranger (version 2.2) against both GRCh37 and GRCh38, as well as assembled with Supernova 2.0.1. 

The son in the A/J trio (NA24385) was sequenced to two depths. The first is the same dataset that went into the Supernova assemblies. The second is a deeper (300Gb, 84.4x coverage) dataset that was also ran through Long Ranger 2.2 against both GRCh37 and GRCH38.

Default Long Ranger file formats are described here:
http://support.10xgenomics.com/genome-exome/software/pipelines/latest/output/overview

And Supernova file formats are described here:

https://support.10xgenomics.com/de-novo-assembly/software/pipelines/latest/output/generating

The three default VCFs (phased_variants, dels and svs) were also reformatted to support structural variant analysis with SURVIVOR. In particular, the SVLEN, SVTYPE and END tags were added. The phased_variants file was filtered to remove SNVs.

All samples were sequenced on the Illumina Xten at 2x150bp. The A/J trio was done using v1 of the 10x library prep protocol.


(2) Additional A/J (Son, NA24385)10XG data from Accession: PRJNA527321. 

Abstract: This study aims to explore the parameter space of 10x Linked-Read data for human diploid assembly and structural variant detection. The submission includes eight 10x Linked-Reads libraries, five for NA12878 and three for NA24385. These libraries with different parameters of Cf, Cr and MuFL.

SRX5532186: 10x data for L5

1 ILLUMINA (HiSeq X Ten) run: 1.1G spots, 321.4G bases, 146.7Gb downloads

Design: 10x Linked-Read sequencing of NA24385 with Cf=208, WmuFL=267.4X

88.6 GB - SRR8739414_1.fastq.gz

101.2 GB - SRR8739414_2.fastq.gz

SRX5532189: 10x data for L4

1 ILLUMINA (HiSeq X Ten) run: 1.2G spots, 373.7G bases, 154.3Gb downloads

Design: 10x Linked-Read sequencing of NA24385 with Cf=1504, WmuFL=246.9X

93.8 GB - SRR8739411_1.fastq.gz
108.8 GB - SRR8739411_2.fastq.gz


## BioNano DLE: 
 
Data generation at BioNano Genomics in collaboration with Genome in a Bottle Consortium
Technology: Bionano optical mapping

Link to raw data: 

https://www.dropbox.com/sh/3u8n31yl6ipc9i3/AAAYndHkUuLzviTy3980CAFZa?dl=0

GM24385 DLE1:
Data collected (Molecules >150 kbp): 317 Gbp 
Read N50(Molecules >150 kbp): 323 kbp

GM24149 DLE1:

Data collected (Molecules >150 kbp): 249 Gbp 

Read N50(Molecules >150 kbp): 383 kbp

GM24143 DLE1:

Data collected (Molecules >150 kbp): 316 Gbp 

Read N50(Molecules >150 kbp): 332 kbp

Software used for assembly: Bionano Solve3.2.1

Link to Solve3.2.1: http://bnxinstall.com/solve/Solve3.2.1_04122018.tar.gz

Parameters used: optArguments_haplotype_DLE1_saphyr_human.xml in Solve 3.2.1
 

## Illumina:

(1) 2x250bp overlapping libraries with nominally 350bp insert size  (NIST, GIAB)
 
Library Preparation:

For each Reference Material, 1 library was prepared using the Illumina TruSeq (LT) DNA PCR-Free Sample Prep Kits (FC-121-3001). 

DNA concentrations were measured using a Qubit 2.0 fluorometer (Life Technologies). Genomic DNA (1.5 ug) was fragmented using a Covaris S2 focused ultrasonicator in micro TUBE AFA Fiber Pre-Slit Snap-Cap 6x16mm micro tubes and the Covaris MicroTUBE holder (covaris part numbers 520045 and 500114, respectively) under the following conditions for a target insert size of 350 base pairs. Size selection was done using a 96-well 0.8 mL plate (Fisher Scientific Part # AB-0859), a magnetic stand-96 (Ambion part # AM10027) and the Illumina sample purification beads according to the 350 bp insert protocol.

Adenylation of 3’™ ends was done in 0.2 mL PCR tubes on an MJ Research PTC-200 thermal cycler. The optional A-Tailing control was not used.  Ligation of indexed paired-end adapters was done in 0.2 mL PCR tubes using the DNA adapter tubes included in the Illumina TruSeq (LT) DNA PCR-Free Sample Prep Kit on an MJ Research PTC-200 thermal cycler. The optional ligation control was not used. The libraries were cleaned up in a 96-well 0.8 mL plate (Fisher Scientific Part # AB-0859) and a magnetic stand-96 (Ambion part # AM10027) using the Illumina sample purification beads. The final libraries were run on an Agilent 2100 Bioanalyzer HS-DNA chip to verify fragment size distribution. Final library concentration was measured via qPCR using the KAPA library quantification kit for Illumina sequencing platforms (KAPA part # KK4835). 

Sequencing:

The TruSeq libraries were run on an Illumina HiSeq 2500 in Rapid mode (v2) with 2x250 paired end reads. Pooled Libraries were initially loaded at a concentration of 10 pM. loading concentration was adjusted accordingly on subsequent runs to balance the libraries as well as possible.

(2) 6kb mate pair libraries (NIST, GIAB)

Library Preparation 
 
Mate Pair libraries were generated using Nextera Mate Pair Sample Preparation Kit (Illumina, Cat# FC-132-1001). Briefly, 4 µg of high molecular weight genomic DNA from the NIST Reference Materials (or from Coriell for the Asian parents) was fragmented to about 7 kb in a 400 mL tagmentation reaction containing 12 µL of Tagment Enzyme at 55âˆžC for 30 minutes. The tagmented DNA fragments were purified with Zymo Genomic DNA Clean & ConcentratorTM Kit (Zymo Research, Cat# D4010).  The gap in the tagmented DNA was filled with a Strand Displacement Polymerase in a 200  µL strand displacement reaction at 20âˆžC for 30 minutes. DNA was then purified with AMPure XP Beads (0.5x vol, Beckman Coulter, Cat# A63880) and size-selected by 0.6% agarose gel electrophoresis in 0.5x TBE buffer. The 6-9 kb fragments were excised from a gel and DNA was recovered using a ZymocleanTM Large Fragment DNA Recovery Kit (Zymo Research, Cat# D4045). Up to 600  µg of DNA was then circulated overnight at 30âˆžC with Circularization Ligase in a 300  µL reaction.
 
After overnight circularization, the uncirculated linear DNA was removed by Exonuclease digestion. Both DNA Ligase and Exonuclease were inactivated by heat treatment and the addition of Stop Ligation Buffer. Circularized DNA was then sheared to smaller sized fragments (300-1000 bp) using Covaris S2 with T6 (6x32 mm) glass tube (Covaris, Part# 520031 and 520042) under these conditions: Intensity of 8, Duty Cycle of 20%, Cycles Per Burst of 200, Time of 40 sec, Temperature of 6-8âˆžC.
 
The sheared DNA fragments that contain the biotinylated junction adapter are mate pair fragments. These fragments were isolated by binding to Dynabeads M-280 Streptavidin Magnetic Beads (Invitrogen, Part# 112-05D) in Bead Bind Buffer.  The unbiotinylated molecules in solution are unwanted genomic fragments that are removed through a series of washes. All downstream reactions were carried out on bead and beads were washed between successive reactions. The sheared DNA was first end-repaired to generate blunt ends followed by an A-Tailing reaction to add a single Ã¬AÃ® nucleotide to the 3Ã­ ends of the blunt fragments. Then the Illumina T-tailed indexing adapters were ligated to the A-tailed fragments.
 
The adapter-ligated fragments were PCR amplified [98âˆžC/1 min, 11 cycles of (98âˆžC/10 sec, 60âˆžC/30 sec, 72âˆžC/30s), 72âˆžC/5 min , 4âˆžC /hold] to generate the final library. The amplified library was purified using AMPure XP Beads (0.67x vol) and eluted in Resuspension Buffer. The size distribution of the library was determined by running a sample on an Agilent Technologies 2100 Bioanalyzer. Library concentration was measured by the Qubit dsDNA HS Assay Kit (Life Technologies, Cat# Q32851).
 
Sequencing
 
Pooled Mate-Pair libraries were sequenced on an Illumina HiSeq 2500 in Rapid mode (v1) with 2x101 bp paired-end reads. The loading concentration was 9.5 pM. This Initial run was for library QC purposes prior to running high throughput.

The Mate-Pair libraries were also sequenced on an Illumina HiSeq 2500 in high output mode (v4) with 2x125 bp paired-end reads. Libraries were sequenced on individual lanes (not pooled). The template loading concentration for each lane was adjusted based on the cluster density from the QC run. Two replicate flowcells were sequenced simultaneously, each with 6 lanes of mate-pair libraries. 

Bioinformatics

To assess duplication rate, coverage, and insert size of the mate-pair libraries, reads were stripped of adapter sequences. Read pairs were removed if the sequence of one or both mates was less than 20 bp after adapter stripping, or if the adapter sequence was at the beginning rather the end of a read (indicating the read inserts were likely to be in inward-facing F/R orientation rather than the expected outward-facing R/F orientation). Reads were then mapped to the hg19 reference genome from ucsc or the GRCh38 reference genome with decoy but no alts using bwa mem (Li 2013) with default settings, and duplicates were marked using samblaster (Faust 2014).
 
The high rate of PCR duplicates (close to 50% in some libraries) resulted in lower than expected sequence coverage (13-17x average across all sequenced genomic positions). A more relevant metric for mate-pair data is the physical coverage, which measures the number of inferred fragments that cover a particular genomic position (including both the sequenced ends as well as the unsequenced genomic region between the ends). Because the empirical insert size average was between 6Ã±7kb per individual, the physical coverage of the genome was quite high (>400x per individual). BAMs were stripped of duplicate reads to reduce file size, but the full data are available in fastq format.
 

## Strand-seq:

Strand-seq data produced, sequenced and processed by Ashley D. Sanders and Jan O. Korbel at the EMBL, Heidelberg on behalf of the Human Pangenome Consortium. 

Strand-specific libaries were generated as described in Sanders et al. Nat Protoc. 2017 and sequenced on a NextSeq Illumina platform. 192 barcoded single-cell libraries were pooled for sequencing of HG002 sample.  

Raw demultiplexed fastq files from the paired-end sequencing run (80bp read length) were uploaded for each single cell library. These data can be found at https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG002/hpp_HG002_NA24385_son_v1/Strand_seq/.
Strand-seq stat

===============

Estimated depth of coverage for 83 selected libraries: 2.01x
% of GRCh38 covered by at least one read in 83 selected libraries: 69.97%

 
## HiC:

Sequencing libraries represent two distinct protocols/optimized methods (labeled HiC.1 and HiC.2, from two anonymized companies) to reach "smooth-coverage", with access to high coverage Nova-Seq (250bp PE).  Attention is required to coverage difference between the two methods in processing and comparisons.

Guidance for  processing are listed below:

### HiC.1

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

### HiC.2

##### Files - 2x150bp Sequencing
 - HG002.HiC_2_R1.fastq.gz
 - HG002.HiC_2_R2.fastq.gz


##### Files - 2x250bp Sequencing*
 - HG002.HiC_2_NovaSeq_S2_L001_R1_001.fastq.gz
 - HG002.HiC_2_NovaSeq_S2_L001_R2_001.fastq.gz

 * As of Jan 22 2020, only one dataset is available. Additional datasets will be made available within 1 week of the initial data freeze, in order to increase the total sequence depth of HiC_2 libraries to be equivalent with HiC_1 libraries.

##### Details
These two sequencing libraries are generated from biological replicates (i.e. two independent cultures) HG002 lymphoblast cells obtained from Coriell (https://www.coriell.org/0/Sections/Search/Sample_Detail.aspx?Ref=GM24385&Product=CC). So the 2x150bp Sequencing library is prepared from Biological Replicate 1, while the 2x250bp library is prepared from Biological Replicate 2.

They are HiC libraries generated using a procedure that deploys an specialized combination of restriction enzymes (RE), where the RE cut site distributions are optimized to produce uniform genomic coverage. The specific RE cut site motifs are: ^GATC, G^ANTC, C^TNAG, T^TAA. The â€œ^â€ is the cut site on the + DNA strand, and the â€™Nâ€™ can be any of the 4 genomic bases. Because of this, there are 10 possible RE cut sites.

##### Alignment
We align the HiC data using bwa mem with the -SP5M option.

For example:
bwa mem -SP5M index_path/hg38.fa Sample_R1.fastq Sample_R2.fastq

A full mapping and data analysis pipeline for certain applications, such as identifying SNVs from HiC data, can be made available upon request.

##### Other Analysis Considerations - Normalization
The RE cut site distributions are optimized to produce uniform genomic coverage. For certain applications such as genome scaffolding, several open source tools (e.g. SALSA2) conduct data normalization based on RE cut site locations. We advise analyses groups to perform their analyses with normalization based on known information about RE cut sites locations AND without assuming a priori knowledge about RE cut site locations. For applications such as polishing, knowledge of RE cut site locations could help reducing errors (especially at chimeric junctions) to improve polishing accuracy. 


## Available Parental Datasets:
 
### Father	HG003	NA24149

 | Data description | Contributor | Link |
 | ---------------- | ----------- | ---- |
 | Nanopore-PromethION | UCSC | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/UCSC_Ultralong_OxfordNanopore_Promethion/ |
 | PacBio CLR | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/PacBio_MtSinai_NIST/ |
 | 10XG | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/data/AshkenazimTrio/HG003_NA24149_father/10Xgenomics_ChromiumGenome/NA24149.fastqs/ |
 | Bionano DLS | GIAB | https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG003/BNG/ |
 | 300x PCR-free Illumina 150bp + 40x PCR-free 250bp | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/NIST_Illumina_2x250bps/ |
 | 6kb mate-pair | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG003_NA24149_father/NIST_Stanford_Illumina_6kb_matepair/ |
 | PacBio HiFi | Google + HudsonAlpha + GIAB | https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG003/PacBio_HiFi/ |
 | HiC | UCSC | https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG003/hic/ | 

### Mother	HG004	NA24143
 
 | Data description | Contributor | Link |
 | ---------------- | ----------- | ---- |
 | Nanopore-PromethION | UCSC | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/UCSC_Ultralong_OxfordNanopore_Promethion/ |
 | PacBio CLR | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/PacBio_MtSinai_NIST/ |
 | 10XG | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/data/AshkenazimTrio/HG004_NA24143_mother/10Xgenomics_ChromiumGenome/NA24143.fastqs/ |
 | Bionano DLS | GIAB | https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG004/BNG/ |
 | 300x PCR-free Illumina 150bp + 40x PCR-free 250bp | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/NIST_Illumina_2x250bps/ | 
 | 6kb mate-pair | GIAB | ftp://ftp-trace.ncbi.nlm.nih.gov/giab/ftp/data/AshkenazimTrio/HG004_NA24143_mother/NIST_Stanford_Illumina_6kb_matepair/ |
 | PacBio HiFi | Google + HudsonAlpha + GIAB | https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG004/PacBio_HiFi/ |
 | HiC | UCSC | https://s3-us-west-2.amazonaws.com/human-pangenomics/index.html?prefix=HG004/hic/ |


