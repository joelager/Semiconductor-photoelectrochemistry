# Semiconductor-photoelectrochemistry
Calculations associated with semiconductor photocathodes and photoanodes

## Reichman model, 1980
The Jupyter notebook `Reichman PEC model` adapts analyses in 
>Reichman, J., The current voltage Characteristics of semiconductor-electrolyte junction photovoltaic cells  [*Appl. Phys. Lett.* **1980**, 36, 574-577](http://aip.scitation.org/doi/10.1063/1.91551).  

See also:
>Gärtner, W. W. Depletion-Layer Photoeffects in Semiconductors. [*Phys. Rev.* **1959**, 116, 84–87](https://link.aps.org/doi/10.1103/PhysRev.116.84).

The comparison of this approach to a full Poisson drift-diffusion solution done in AFORS-HET is discussed in the following book chapeter  
>Ager, J. W. Chapter 6. Approaches for Stable and Efficient Photoelectrodes. In Integrated Solar Fuel Generators; Sharp, I. D., Atwater, H. A., Lewerenz, H.-J. L., Eds.; [Royal Society of Chemistry, **2018**; pp 183–213](http://ebook.rsc.org/?DOI=10.1039/9781788010313-00183).

Reichman extends the approach of Gärtner but has space charge layer (SCR) recombination, and both electron and hole currents. The example given in the paper is an n-type semiconductor but the approach could be used equally as well for the p-type case. 

Also included are input files which will allow simulations to be done with the AFORS-HET solar cell simulator. 

## Peter model, 1984
The Jupyter notebook `Peter PEC model Part I` adapts analyses in  
> Peter, L. M.; Li, J.; Peat, R. Surface Recombination at Semiconductor Electrodes Part I. Transient and Steady-State Photocurrents. [J. Electroanal. Chem. Interfacial Electrochem. 1984, 165, 29–40](https://linkinghub.elsevier.com/retrieve/pii/S0022072884800844)

In contrast to approach of Reichman (see other notebook), recombination in the space charge region is not considered. Instead, recombination at a surface state is added to the model.

