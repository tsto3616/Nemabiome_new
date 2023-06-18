# Nemabiome_new

Bioifnormatically pooling ASVs through 16 pooling methods. First 3 PCRs were performed and we pooled those PCRs through laboratory means and bioinformatic means. Pooling methods described below:

P1= PCR1
P2= PCR2
P3= PCR3
P4= PCR1 and PCR2 pooled in the lab, after amplication before sequencing
P5= PCR1 and PCR3 pooled in the lab, after amplication before sequencing
P6= PCR2 and PCR3 pooled in the lab, after amplication before sequencing
P7= PCR1, PCR2 and PCR3 pooled in the lab, after amplication before sequencing
P8= PCR1, PCR2 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, no further editing
P9= PCR1, PCR2 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, reads removed for that ASV in that sample if only one PCR replicate detected the ASV
P10= PCR1, PCR2 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, reads removed for that ASV in that sample if only two PCR replicates detected the ASV
P11= PCR1 and PCR2 pooled bioinformatically by adding together the ASV reads after sequencing, no further editing
P12= PCR1 and PCR2 pooled bioinformatically by adding together the ASV reads after sequencing, reads removed for that ASV in that sample if the ASV is not detected in both replicates
P13= PCR1 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, no further editing
P14= PCR1 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, reads removed for that ASV in that sample if the ASV is not detected in both replicates
P15= PCR2 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, no further editing
P16= PCR2 and PCR3 pooled bioinformatically by adding together the ASV reads after sequencing, reads removed for that ASV in that sample if the ASV is not detected in both replicates

All the R files to create the bioinformatic pooling was done in the R file in this branch
