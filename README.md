# Nanopore-Sequencing
Cas9/12a Madiated Target Enrichment for Nanopore Sequencing

# The aim of the project 
The aim of the project is to develop library preparation and sequencing methods compatible with third generation sequencing technologies which can be used to determine the number of repeats that cause neurodevelopmental diseases and the higher resolution of structural variants.

# Theoretical Approach and Method
All experiments will be carried out on DNA from cell lines to be purchased from the Coriell Institute. Different patient cells with lar Autosomal Dominant Spinoserebellar Ataxia (ODSCA), Fragile-X, Huntington Disease will be used because of high genetic heterogeneity. The loci known to be affected in the respective disease will be separated intact as much as possible from the remainder of the genome. For this, recently developed CRISPR / Cas9 mediated chromosomal enrichment approaches will be adopted (Gabrieli et al. 2017, 2018; Bennett-Baker et al. 2017). The important advantages of this approach are that CRISPR / Cas9 endonuclease system can be directed to the desired genomic target (s) easily and cheaply, to target more than one genomic locus in the same reaction, and to have such a high specificity. In the few studies reported in the literature to date, methods that require long-lasting and special equipment (eg, Pulse-field gel electrophoresis), and the target DNA was amplified with PCR or MDA (Gabrieli et al. 2018), or non-optimal steps in defining repetitive and complex structural variants, such as DNA sequencing by enrichment with CRISPR / Cas9 (Bennett-Baker et al. 2017). With the CRISPR / Cas9-mediated method to be developed in the proposed project, a much faster and more practical method will be developed, and it will be respond to clinical needs by targeting more than one locus in the same reaction.

# Protocol
Please find the attached protocol described in Cas9-Enrichment and Library Prep Protocol.doc

# Run Parameters
C:\Program Files\OxfordNanopore\ont-guppy\bin>guppy_basecaller -i c:\ebru\fast5_skip -s c:\ebru\output_skip --flowcell FLO-MIN106 --kit SQK-LSK109 --barcode_kits EXP-NBD104 -x "cuda:0" -r
ONT Guppy basecalling software version 6.3.8+d9e0f648d, minimap2 version 2.22-r1101
config file:        C:\Program Files\OxfordNanopore\ont-guppy\data\dna_r9.4.1_450bps_hac.cfg
model file:         C:\Program Files\OxfordNanopore\ont-guppy\data\template_r9.4.1_450bps_hac.jsn
input path:         c:\ebru\fast5_skip
save path:          c:\ebru\output_skip
chunk size:         2000
chunks per runner:  256
minimum qscore:     9
records per file:   4000
num basecallers:    4
gpu device:         cuda:0
kernel path:
runners per device: 4

#Use of this software is permitted solely under the terms of the end user license agreement (EULA).By running, copying or accessing this software, you are demonstrating your acceptance of the EULA.
The EULA may be found in C:\Program Files\OxfordNanopore\ont-guppy\bin

# Run OutPut
You can find fesults for the target enrichment protocol for HTT gene in [Cas9-HTT folder](https://drive.google.com/drive/folders/1WAF_SkkpwK5PV3zeDSfY44Ax-qylGZfM?usp=drive_link). sgRNA designs can be found HTT sgRNA Designs.ods


