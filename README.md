# Retinal-OCT-state-of-art
Recopilation of most revelant papers of the retinal image analysis via OCT 

PUBLIC DATASETS:

[www.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm](www.duke.edu/~sf59/Chiu_BOE_2014_dataset.htm)

[https://sites.google.com/site/hosseinrabbanikhorasgani/datasets-1](https://sites.google.com/site/hosseinrabbanikhorasgani/datasets-1)


PUBLIC CODE:

Retina blood vessel segmentation with a convolution neural network (U-net)

https://github.com/orobix/retina-unet
https://arxiv.org/pdf/1505.04597.pdf




# Relation between OCT layers and Visual Acuity

## Outer Retinal Layers as Predictors of Vision Loss
(2015)
https://www.reviewofophthalmology.com/article/outer-retinal-layers-as-predictors-of-vision-loss

 "Correlations between anatomy on OCT and visual function have been investigated in a number of retinal diseases:"

"It is widely believed that damage or disruption of the photoreceptors can be visualized on OCT as loss of integrity of the ELM, EZ and IZ bands.13,14
Attenuation, discontinuity or disruption of these bands have been reported as likely hallmarks of photoreceptor dysfunction or damage in a variety of retinal diseases.6,14,16 These changes are better assessed in the absence of features that could weaken the signal intensity of the outer retinal layers, such as retinal edema, hemorrhage or media opacity."


"The hypothesis that the photoreceptor outer segment layer is the first one to be affected in degenerative conditions, followed by damage of photoreceptor cell bodies occurring later in the process, is supported by histopathological evidence of decrease in outer segment length after retinal detachment in eyes with RD,19 and shortening of cone outer segments and death of neighboring cones following rod cell death in eyes with retinitis pigmentosa.20"

"On the other hand, photoreceptor restoration as observed after macular surgery seems to occur in the opposite order. The ELM zone has been reported as the first structure to recover after macular hole closure, and its recovery has been considered a sign of intact photoreceptor cell bodies and Müller cells (See Figure 2)"


"Measurement of ORL Thickness

Quantitative thickness analysis of the outer retinal layers has also been performed. The Outer Retinal Layer Thickness (ORLT)37,47 can be measured between the inner edges of the outer plexiform layer and inner boundary of the RPE. In conditions where the outer plexiform layer cannot be delineated, as in some retinal dystrophies, ORLT can be represented by the value obtained from Retinal Thickness minus the Inner Retinal Layer Thickness."


# Anatomical correlates to the bands seen in the outer retina by optical coherence tomography: literature review and model.

  > 400 Cites (2013)
  
## Imaging of macular diseases with optical coherence tomography.
  > 1500 Cites (1995)
    Puliafito CA1, Hee MR, Lin CP, Reichel E, Schuman JS, Duker JS, Izatt JA, Swanson EA, Fujimoto JG.


## Patterns of diabetic macular edema with optical coherence tomography.

  > 600 Cites (1999)
    Otani T1, Kishi S, Maruyama Y.
  
    PURPOSE:
    We report cross-sectional images of diabetic macular edema and correlation between tomographic features and visual acuity with best correction by means of optical coherence tomography.

## Disorganization of the Retinal Inner Layers as a Predictor of Visual Acuity in Eyes With Center-Involved Diabetic Macular Edema
  > 60 cites (2014)

## Optical coherence tomographic patterns of diabetic macular edema.
  > 200 Cites (2006)
  Kim BY1, Smith SD, Kaiser PK.

  PURPOSE:
  To describe various morphologic patterns of diabetic macular edema (DME) demonstrated by optical coherence tomography (OCT) and correlate them with visual acuity.


  "In addition, OCT produces cross-sectional images of the retina that have been found to correlate well with retinal histology as demonstrated by light microscopy. 12"

## A comparison of retinal morphology viewed by optical coherence tomography and by light microscopy.
  > 280 Cites (1997)

## SCORE Study report 1: Baseline associations between central retinal thickness and visual acuity in patients with retinal vein occlusion.**
  > 100 cites (2009)
    Scott IU, VanVeldhuisen PC, Oden NL, et al. Ophthalmology 2009;116:504-12.

    Objetive: "Investigate relation between OCT-measured center point thickness  and best-corrected visual acuity in eyes with macular edema associated with retinal vein occlusion"

    Conclusions: "The correlation between OCT-measured center point thickness and visual acuity letter score is modest. OCT-measured center point thickness represents a useful tool for the detection and monitoring of macular edema in retinal vein occlusion, but it cannot reliably substitute for visual acuity measurements."



## 2016
http://iovs.arvojournals.org/article.aspx?articleid=2594252


## OCT-Leakage Mapping A New Automated Method of OCT Data Analysis to Identify and Locate Abnormal Fluid in Retinal Edema**
Dec 2017


## Kernel regression based segmentation of optical coherence tomography images with diabetic macular edema**
2015 *Chiu et al*


## Retinal cone and rod photoreceptor cells exhibit differential susceptibility to light–induced damage**
- (2012) > 25 cites 
Relation between photoreceptor deathcells and visual loss, observed on OCT images.



# Retinal analysis with OCT: state-of-the-art 

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


## State-of-the-art

- (2015) > 20 cites
**State-of-the-art in retinal optical coherence tomography image analysis.** *Baghaie A1, Yu Z1, D'Souza RM1.*
Quant Imaging Med Surg. 2015 Aug;5(4):603-17. doi:[10.3978/j.issn.2223-4292.2015.07.02.](10.3978/j.issn.2223-4292.2015.07.02.)