## DeepPerVar

By leveraging paired whole genome sequencing data and epigenetic functional assays in a population cohort, a  DeepPerVar is a multi-modal deep learning framework to predict genome-wide quantitative epigenetic signals and evaluate the functional consequence of noncoding variants on an individual level by quantifying their allelic difference on the prediction. By applying DeepPerVar to the ROSMAP cohort studying Alzheimer’s disease (AD), the web server can accurately predict genome-wide H3K9ac signals and DNA methylation ratio given DNA genomic sequence under reference and alternative alleles, and use the allelic difference as the score to evaluate the functional consequence of genetic variants associated with Alzheimer’s disease in a personal genome.

<center>

<div align=center><img width="800" height="500" src="https://raw.githubusercontent.com/alfredyewang/DeepPerVar/main/src/DeepPerVar.jpeg"/></div>
</center>  


## DeepPerVar

We implement a webserver to predict genome-wide H3K9ac signals and DNA methylation ratio and the mutation effect on these two epigenetics signals. The webserver can be accessed from [link].(http://35.202.146.70/). <br />
<br />

## Requirements and Installation

DeepPerVar is implemented by Python3.

- Python 3.8
- samtools 1.15.1
- hdf5 == 1.10.4
- numpy >= 1.18.5
- pytorch ==1.7.1

Download [Reference Genome (hg19)]() [DeepPerVar Models] (https://drive.google.com/file/d/1Q_EzL_R4MLHSPYXKIqGUeXkDNx1yJ4WB/view?usp=sharing)

```
unzip Base.zip
```

Download DeepPerVar:
```
git clone https://github.com/alfredyewang/DeepPerVar
```
Install requirements
```
pip3 install -r requirements --user
