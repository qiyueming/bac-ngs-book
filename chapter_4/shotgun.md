## Shotgun 宏基因组测序

16s rRNA 数据有偏向性：

- Degenerate primers Degenerate primers
- PCR Amplification
- Databases
- Does not capture viruses and eukaryotes

主要用于菌群分析。


用途：需要深度测序的数据，样本一般分为：宿主来源，如人或动物等；环境来源，如土壤或水体等。数据分析时，前者一定要考去除宿主缘DNA，后者要高度深度测序对后期拼接有较大帮助。

#### Methods Protocol

1. DNA isolation
2. Library preparation
3. Sequencing
4. Data QC: FastQC, FastX_toolkit
5. Reads assembly: IDBA-UD, Mira, Velvet/MetaVelvet
6. Partipation: FCP，Phymm/PhymmBL, AMPHORA2, NBC, MEGAN, MG-RAST, CAMERA, IMG/M
7. Analysis: MetaPhAln, PhyloSift/pplacer


#### Reference

1. [Illumina Method](http://applications.illumina.com/applications/microbiology/microbial-sequencing-methods/shotgun-metagenomic-sequencing.html)
2. [Shotgun Metagenomic Sequencing and Analysis](http://hmpdacc.org/doc/d1.s2.t2%20-%20Makedonka%20Mitreva%20-%20WGS%20at%20WashU.pdf)