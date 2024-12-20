# Quasi-repeater  
Detection of repeating and quasi-repeating earthquakes.  

## Workflow  
![Zhou & Ghosh, (2024)](./doc/Quasi-repeater_workflow.jpg)  

- **Usage** 
```bash
python 1_cc_link.py
python 2_init_clustering.py
python 3_relink_clustering.py
```  

## Installation  
Setup proper Python environment by installing [Anaconda](https://www.anaconda.com/products/individual#Downloads), [Obspy](https://github.com/obspy/obspy/wiki/Installation-via-Anaconda), and [PyTorch](https://pytorch.org/) sequentially.  

## References
**Zhou, Y.**<sup>`*`</sup> and A. Ghosh (2024, under review). Abundant Quasi-Repeating Earthquakes Occurring Within Repeater Sequences on the Erkenek-Pütürge Fault (SE Turkey). *Geophysical Research Letters*  

**Zhou, Y.**<sup>`*`</sup>, C. Ren, A. Ghosh, H. Meng, L. Fang<sup>`*`</sup>, H. Yue, et al. (2022). Seismological Characterization of the 2021 Yangbi Foreshock-Mainshock Sequence, Yunnan, China: More than a Triggered Cascade. *Journal of Geophysical Research: Solid Earth*; 127(8). doi: [10.1029/2022JB024534](https://doi.org/10.1029/2022JB024534)  
