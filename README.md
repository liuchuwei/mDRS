# mDRS

## Dependence
![](https://img.shields.io/badge/software-version-blue)  
[![](https://img.shields.io/badge/Guppy-v6.5.7-green)](https://community.nanoporetech.com/downloads)
[![](https://img.shields.io/badge/Minimap2-v2.24-green)](https://github.com/lh3/minimap2)
[![](https://img.shields.io/badge/samtools-v1.1.7-green)](https://github.com/samtools/samtools)  
[![](https://img.shields.io/badge/DRUMMER-v1.0-blue)](https://github.com/DepledgeLab/DRUMMER/)
[![](https://img.shields.io/badge/bedtools-v2.29.1-blue)](https://bedtools.readthedocs.io/en/latest/)
[![](https://img.shields.io/badge/ELIGOS-v2.0.1-blue)](https://gitlab.com/piroonj/eligos2)
[![](https://img.shields.io/badge/Epinano-v1.2.0-blue)](https://github.com/novoalab/EpiNano)  
[![](https://img.shields.io/badge/MINES-v0.0-orange)](https://github.com/YeoLab/MINES.git)
[![](https://img.shields.io/badge/Tombo-v1.5.1-orange)](https://github.com/nanoporetech/tombo)
[![](https://img.shields.io/badge/Nanocompore-v1.0.0-orange)](https://github.com/tleonardi/nanocompore_paper_analyses)
[![](https://img.shields.io/badge/Nanom6A-v2.0-orange)](https://github.com/gaoyubang/nanom6A)  
[![](https://img.shields.io/badge/Xpore-v2.0-purple)](https://github.com/GoekeLab/xpore)
[![](https://img.shields.io/badge/m6Anet-v1.0-purple)](https://github.com/GoekeLab/m6anet) 
[![](https://img.shields.io/badge/nanopolish-v0.14.0-purple)](https://github.com/jts/nanopolish)  
[![](https://img.shields.io/badge/Dinopore-v1.0-brown)](https://github.com/darelab2014/Dinopore)
[![](https://img.shields.io/badge/nanoRMS-v1.0-brown)](https://github.com/novoalab/nanoRMS)

## Genome
[![](https://img.shields.io/badge/mm39-orange)](https://hgdownload.soe.ucsc.edu/goldenPath/mm39/bigZips/)
[![](https://img.shields.io/badge/hg38-green)](https://hgdownload.soe.ucsc.edu/goldenPath/hg38/bigZips/)

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#Intallation">Intallation</a>
    </li>
    <li><a href="#Usage">Usage</a></li>
    <li><a href="#References">References</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#Contact">Contact</a></li>
  </ol>
</details>

## Intallation
1.Install environment: check the env directory of yml files
   ```sh
   conda env create -f $environment.yml
   ```
2.prepare tookit: check and modify the tookit.py file.
    
## Usage
1.Basecalling
   ```sh
   python 01.basecalling.py -i $fast5 -o $out
   ```
2.m6A detection
   ```sh
   git clone https://github.com/liuchuwei/PGLCN.git
   ```

## License
Distributed under the GPL-2.0 License License. See LICENSE for more information.

## Contact
liuchw3@mail2.sysu.edu.cn

## Reference


