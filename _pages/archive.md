---
layout: archive
title: ""
permalink: /archive/
author_profile: true
header:
  show: false
---
This section contains selected projects and simulations from my undergraduate years and earlier, archived for completeness.

# Projects
* **Patchwise Localization of Neovascularization in Fundus Images Using Transfer Learning**
  - *Self-initiated, Undergraduate Research Internship Project* [<a href = 'https://drive.google.com/file/d/1pdMF5yO26JVyZqFDgYLNlMHHPxDd7Doq/view?usp=sharing'>Report</a>] 
  - **Advisor**: 
    + <a href = 'https://scholar.google.com/citations?user=481sMoEAAAAJ'>Shashika Munasingha</a> (Doctoral Candidate), Auckland Bioengineering Institute, New Zealand
<p align="center"><img src="../images/dr.png" width="800"/></p>

  -- *If the image is not clear, click <a href = '../images/dr.png'>here</a>.*
<p>&nbsp;</p>

* **Feature-Fused Parallel Deep Learning Model for Generalized Synthetic Image Detection [IEEE VIPCUP 2022]**
  - *Research Competition* [<a href = 'https://drive.google.com/file/d/1TGP0_vnvKNLODO7k_Oht_m7RB2WecerR/view?usp=sharing'>Report</a>] 
  - Our method was placed in the **Top 5** solutions
  - **Advisor(s)**: 
    + <a href = 'https://scholar.google.com/citations?user=qe5byo4AAAAJ&hl=en'>Dr. Chamira Edussooriya</a> (Senior Lecturer), University of Moratuwa, Sri Lanka
    + <a href = 'https://scholar.google.com.au/citations?user=Ctp3igcAAAAJ&hl=en'>Jathushan Rajasegaran</a> (PhD Student), BAIR, University of California, Berkeley, USA
<p align="center"><img src="../images/vipcup.png" width="800"/></p>
<p>&nbsp;</p>

* **Parasitic Egg Detection and Classification in Microscopic Images**
  - *Research Competition* [<a href = 'https://www.researchgate.net/publication/368642404_Rethinking_Object_Detection_in_terms_of_Classification_and_Localization_through_Parallel_Deep_Learning_Models'>Preliminary Report for ICIP 2022 Grand Challenge</a>] 
  - **Advisor**: 
    + <a href = 'https://scholar.google.com.sg/citations?user=9ebsWAoAAAAJ&hl=en'>Dr Rukshani Liyanaarachchi</a> (Senior Lecturer), University of Moratuwa, Sri Lanka
<p align="center"><img src="../images/icip.png" width="800"/></p>

* **CAMSAT: Paediatric Anaesthesia Monitoring System**
  - *Self-initiated Undergraduate Research* [<a href = 'https://drive.google.com/file/d/1jPVycFGds_hssIDrzRhg9aXx7OQUle6b/view?usp=sharing'>Report</a>] 
  - Won the **1st runners-up** award at the SPARK Challenge 2021/22 - Climate Change-oriented Innovation Competition, Organized by the University of Moratuwa, Sri Lanka
<p align="center"><img src="../images/block.png" width="600"/></p>
<p>&nbsp;</p>

* **Analysis of a Vibrotactile P300 Brain-Computer Interface Dataset from a Patient with Locked-in Syndrome**
  - *Virtual Hackathon, Spring School, G.tec Medical Engineering GmbH (2022)* [<a href = 'https://drive.google.com/file/d/1nFQiUXplHLS2WWsWD4tghbT-OT4DS-on/view?usp=sharing'>Presentation</a>][<a href = 'https://github.com/Sam54000/vibro-tactile-P300-lockedIn-patient'>Github</a>] 
  - **Collaborator**: 
    + <a href = 'https://scholar.google.com/citations?user=HCm1_UkAAAAJ&hl=fr'>Samuel Louviot</a> (PhD Student),  University of Lorraine, France
<p align="center"><img src="../images/gtec.png" width="800"/></p>

# Simulations
## Digital Filters for Biosignal Processing
Implemented the following digital filters on MATLAB and filtered biomedical signals, specifically noisy ECG signals. 
* Smoothing Filters
  - Moving average filters
  - Savitzky-Golay filters
* Ensemble Averaging
* FIR Derivative Filters
* FIR Filters based on Windows
  - Rectangular window
  - Hanning window
  - Hamming window
  - Blackman window
  - Kaiser window
* IIR Filters
  - Butterworth LPF
<p align="center"><img src="../images/ecg_filt_1.png" width="800"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1GRp5eKdRQ7RfSJI6jinCFlwDzy3G_77w/view?usp=sharing'>Report</a>

## Optimum and Adaptive Filters for Biosignal Processing
Conventional FIR and IIR filters are designed based on limited information on temporal and spectral characteristics of the signal. Moreover, one might say that they are ad-hoc filters as trial-and-error method is sometimes used to determine the filter specifications. 

On the other hand, optimum filters such as the Wiener filter could be employed for a given time series by considering the statistical characteristics of the signal and noise, under the following assumptions.
* Signal and noise processes are independent
* Signal and noise are stationary
* Desired signal is known
* Noise characteristics are known

When the signal and noise are non-stationary, we would have to apply filters that are optimal as well as adaptive. Some examples for such filters are, 
* Least Mean Square (LMS) method
* Recursive Least Squares (RLS) method
<p align="center"><img src="../images/ecg_filt_2.png" width="800"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1o5V144nOX08O-X7uEo6TzVeLjodfKjWH/view?usp=sharing'>Report</a>

## Continuous and Discrete Wavelet Transforms
Implemented continuous and discrete wavelet transforms using built-in MATLAB functions and applied them for denoising and compression of different signals. 

In the context of continuous wavelet transforms (CWT), there are many wavelet families such as Shannon, Mexican hat, Morlet, etc. However, the drawbacks of CWT include highly redundant computations which leads to the requirement of additional computational power and time consumption. Avoiding this, in discrete wavelet transform (DWT), the scaling and translation are performed in a discrete manner.
<p align="center"><img src="../images/ecg_filt_3.png" width="800"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1ibvX1KQhU91rrmV9r5tyR29LXqCfo0OY/view?usp=sharing'>Report</a>


## Branched Cylinders: Dendritic Tree Approximations
Explored some of the time independent electrical properties of single branched cables. Branched cables are an important means of modelling the passive electrical properties of axonal and dendritic trees. For convenience, trees exhibiting only one order of branching were considered. Nevertheless, the principles could be easily extended to higher order trees.
<p align="center"><img src="../images/dendritic.png" width="450"/><img src="../images/ss.png" width="400"/></p>
In the above diagram, V<sub>1</sub>,V<sub>21</sub> and V<sub>22</sub> are the membrane potentials of the respective branches. d<sub>1</sub>, d<sub>21</sub> and d<sub>22</sub> are the diameters of the parent and daughter branches respectively and X is axial distance.

By solving the differential equations with the given nodal and boundary conditions, steady-state voltage profile in each branch could be determined. 

For more details: <a href = 'https://drive.google.com/file/d/1jjmqrKMkHgaRf0pqWFG-mMN3Vr79IYv7/view?usp=sharing'>Report</a>

## Properties of the Hodgkin-Huxley equations
Many of the properties of the propagating action potential are similar to the membrane action potential. The features; <b>threshold, refractoriness</b> (absolute and relative), <b>repetitive activity, temperature dependence</b> that are observed physiologically, were simulated using the Hodgkin-Huxley equations.
<p align="center"><img src="../images/hh.png" width="450"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1UFPYGIXockZTfHUblWP9migdCa2Y3OCP/view?usp=sharing'>Report</a>

## Mathematical Modelling of Compartmental Systems
Many compartmental systems can be represented by a series of first-order differential equations.
* Bolies Glucose/ Insulin Model
* Riggs Model for Iodine Metabolism
<p align="center"><img src="../images/cs.png" width="450"/><img src="../images/gi.png" width="400"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1D8cFy-ad_XFkPkeByfzMhiE7XNZY3Tkx/view?usp=sharing'>Report</a>

## Image Downsampling Processor
Designed and simulated/implemented a processor that could down-sample an input image using Vivado Design Suite. The input image was transmitted to the processor where the image was down-sampled and once finished, the results were sent back for display purposes.
<p align="center"><img src="../images/downsample_proc.png" width="800"/></p>
<p align="center"><img src="../images/image_cameraman.jpg" width="350"/>      <img src="../images/cameraman_downsampled.jpg" width="175"/></p>
<p align="center">Original and Downsampled Image</p>

For more details: <a href = 'https://drive.google.com/file/d/17boW2Lucrl8q1lLBczsg5-FsFSRw2sct/view?usp=sharing'>Report</a>


## Object Counting on a Moving Conveyor Belt
Hexagonal nuts on a moving conveyor belt were detected and localized from a video stream using a conventional image processing pipeline including;
* Otsu Thresholding
* Morphological Closing
* Connected Component Analysis
* Contour Analysis
<p align="center"><img src="../images/com_vision.png" width="1050"/></p>

For more details: <a href = 'https://drive.google.com/file/d/1A49N0SqSG2mHoBpuD9Ckj3xq1O-_QkWk/view?usp=sharing'>Report</a>