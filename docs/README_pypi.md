
<img src="https://raw.githubusercontent.com/GCA-VH-lab/msa4u/main/docs/img/msa4u_logo.png" width="300"/>


## Description

**MSA4u** is a simple visualisation tool for Multiple Sequence Alignments.

**Programming language:** Python3   
**OS:** MacOS, Linux  
**Python dependencies:** biopython, configs, argparse, reportlab  
**OS-level dependencies:** mafft (v. 7.490 is included in the package)   
**License:** [WTFPL](http://www.wtfpl.net)  
**Version:** 0.4.0 (January 2023)


## Installation

- The most stable release of uorf4u can be installed directly from pypi:

```
python3 -m pip install msa4u
```

- The development version is available at github :

```
git clone https://github.com/GCA-VH-lab/msa4u.git
cd msa4u
python3 -m pip install --upgrade pip
python3 -m pip install wheel
python3 setup.py sdist bdist_wheel
python3 -m pip install -e .
```

**!** If you're a linux user, run `msa4u --linux` post-install command once to update paths in the premade config files that set by default for MacOS users.


## Reference

If you find msa4u useful, please cite [uorf4u paper](https://doi.org/10.1101/2022.10.27.514069). msa4u initially was developed as a sublibrary of uorf4u.     
Artyom. A. Egorov, Gemma C. Atkinson, **uORF4u: a tool for annotation of conserved upstream open reading frames**, *bioRxiv 2022.10.27.514069; doi: [10.1101/2022.10.27.514069](https://doi.org/10.1101/2022.10.27.514069)*


## Contact

Please contact us by e-mail _artem**dot**egorov**AT**med**dot**lu**dot**se_ or use Issues to report any technical problems.  

## Authors

mas4u is developed by Artyom Egorov at [the Atkinson Lab](https://atkinson-lab.com), Department of Experimental Medical Science, Lund University, Sweden. We are open for suggestions to extend and improve msa4u functionality. Please don't hesitate to share your ideas or feature requests.
