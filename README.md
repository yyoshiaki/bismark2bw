# bismark2bw
conversion bismark file into bigwig file

## Installation

```
conda install -c bioconda ucsc-bedgraphtobigwig
```

```
git clone https://github.com/yyoshiaki/bismark2bw.git
```

chromsizes

```
wget ftp://hgdownload.soe.ucsc.edu/goldenPath/hg38/bigZips/hg38.chrom.sizes
```

## Usage

```
./bismark2bw data/example.sort.bismark.cov data/hg38.chrom.sizes data/out.bw 
```