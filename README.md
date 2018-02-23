# Retinal-OCT-state-of-art
Recopilation of most revelant papers of the retinal image analysis via OCT 

PUBLIC DATASETS:

[www.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm](www.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm)

[https://sites.google.com/site/hosseinrabbanikhorasgani/datasets-1](https://sites.google.com/site/hosseinrabbanikhorasgani/datasets-1)

**Kernel regression based segmentation of optical coherence tomography images with diabetic macular edema**
2015 *Chiu et al*




- (2015) > 20 cites
**State-of-the-art in retinal optical coherence tomography image analysis.** *Baghaie A1, Yu Z1, D'Souza RM1.*
Quant Imaging Med Surg. 2015 Aug;5(4):603-17. doi:[10.3978/j.issn.2223-4292.2015.07.02.](10.3978/j.issn.2223-4292.2015.07.02.)



Main steps:

## Noise reduction:
  
  - (1990) > 13.000 cites
    Scale-space and edge detection using anisotropic diffusion  
  
  - (1980)
    Digital image enhancement and noise filtering by use of local statistic							 
	
  - (1982)
    A model for radar images and its application to adaptive digital filtering of multiplicative noise 
	
  - (1985)
    Adaptive noise smoothing filter for images with signal-dependent noise							 

## Segmentation:

### [Automatic segmentation of seven retinal layers in SDOCT images congruent with expert manual segmentation](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3408910/)
*Chiu et al.*
(2010) > 300 cites

Segmentation of retinal layers in Spectral Domain Optical Coherence Tomography images using graph theory and dynamic programming.

#### Code implementation:
Simplified version [Matlab](https://es.mathworks.com/matlabcentral/fileexchange/43518-graph-based-segmentation-of-retinal-layers-in-oct-images)

Full version [Matlab](https://github.com/pangyuteng/caserel)

### [Retinal layer segmentation of macular OCT images using boundary classification](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3704094/)
*A. Lang et al*
2013 ~= 100 Cites

A random forest classifier to segment eight retinal layers in macular cube images acquired by OCT.


### [Segmentation of Intra-Retinal Layers from Optical Coherence Tomography Images using an Active Contour Approach](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5601784)
*A Yazdanpanah et al*
2011 > 100 cites

A semiautomated segmentation algorithm to detect intra-retinal layers in OCT images acquired from rodent models of retinal degeneration.



### [ReLayNet: Retinal Layer and Fluid Segmentation of Macular Optical Coherence Tomography using Fully Convolutional Networks](https://arxiv.org/abs/1704.02161)
*A. G. Roy et al*
2017 

Arxiv

A Deep learning architecture for end-to-end segmentation of retinal layers and fluid masses in eye OCT scans.


## Image Registration
