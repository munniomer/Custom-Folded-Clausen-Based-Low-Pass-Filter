<p align="center">
  <img width="700" src="Observations/allX.png">
</p>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/digantamisra98/Custom-Folded-Clausen-Based-Low-Pass-Filter/master)
[![DOI](https://zenodo.org/badge/192178248.svg)](https://zenodo.org/badge/latestdoi/192178248)
[![Donate](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

# Custom Folded Clausen Based LowPass Filter

## Abstract

Filter Design is an important procedure of Image Processing to present new digital filters which can challenge the current state of the art filters with improved performance and results. This paper is a comprehensive, intuitive and novel approach of designing Custom Folded Clausen based low pass filters inspired from the architecture of a standard Gaussian Gabor Filter which can be applied on images for noise removal, smoothening or blurring the image, low-level abstract detection of spatial orientated edges and low-level segmentation; and can be modified to improve performance or modulate its use. 

## Filter Parameters:

|Filter Psuedo Name| Type of Clausen Function| Mean Value for Folded Normal Kernel (𝝁)| Standard Deviation Value for Folded Normal Kernel (𝝈)|
|---|---|---|---|
|Filter Y|1<sup>st</sup> Order Standard Clausen Function|0 |1| 
|Filter X| 2ND ORDER SL-TYPE CLAUSEN FUNCTION|0 | 1|
|Filter XI| 2ND ORDER SL-TYPE CLAUSEN FUNCTION|1 |1 |
|Filter XII| 2ND ORDER SL-TYPE CLAUSEN FUNCTION|0.5 |1.5 |
|Filter XIII| 2ND ORDER SL-TYPE CLAUSEN FUNCTION|0.5|2 |
|Filter XIV |2ND ORDER SL-TYPE CLAUSEN FUNCTION |2 |1 |
|Filter XV |2ND ORDER SL-TYPE CLAUSEN FUNCTION |0 | 0.5 |

## Results

<div style="text-align:center"><img src ="Observations/Filtered Image.png"  width="500"/></div>
<div style="text-align:center"><img src ="Observations/zoom.png"  width="400"/></div>

## Cite this work:

```
@misc{Clausen Folded Low-Pass Filters,
  author = {Diganta Misra},
  title = {Custom Folded Clausen based Low Pass Filters},
  year = {2019},
  url = {https://github.com/digantamisra98/Custom-Folded-Clausen-Based-Low-Pass-Filter},
}
```
