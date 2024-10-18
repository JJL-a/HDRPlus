# HDRPlus
A Large Scale Image and Video Dataset for Forensic Analysis
A official public dataset for paper "ForensiCam-215K: A Large Scale Image and Video Dataset for Forensic Analysis" (submitted to IEEE ICASSP 2025)
## Background
Source camera identification aims to establish the correlation between images and source devices, which is an important branch of research in the field of multimedia forensics. Source camera identification based on sensor pattern noise is currently recognized as the most reliable technology scheme, which assumes that the pixel position between the device fingerprint and the image is synchronized. In recent years, the rapid development of computational imaging technology has subverted the smartphone imaging method and changed the digital image acquisition process. Among the most significant of these developments is high dynamic range (HDR) imaging. HDR photography, widely available in modern smartphones, achieves a broader range of luminance by combining multiple images with varying exposure levels. As a result, this process causes the device fingerprint to lose its spatial alignment with the image content, presenting a novel challenge to the field of source camera identification. Consequently, research in HDR image forensics has become an urgent necessity. Despite the growing demand for studies in this area, existing datasets for HDR image source camera identification are relatively small in scale, which could introduce potential biases in the data and limits the generalizability of findings. Based on this, this paper present a large-scale dataset for HDR image forensics, named HDRPlus. This dataset consists of 14578 images captured by 28 modern smartphones from four major brands. The devices used compose of 10 single-camera smartphones and 18 multi-camera smartphones. For each device, between 165 and 598 images were taken in both default and HDR modes, covering a variety of indoor and outdoor scenes. The newly created HDRPlus dataset is then used to evaluate the effectiveness of existing source camera identification methods based on sensor pattern noise. Experimental results reveal that the performance of these forensics methods degrades significantly when applied to images captured by multi-camera devices or in HDR mode. Moreover, the results indicate considerable variation in performance across devices from different manufacturers and for images with diverse content. This highlights the complexity of the problem and underscores the need for further research and development in this area. Ultimately, the HDRPlus dataset will provide good data support for future work in the field of digital image source camera identification, especially in addressing the challenges posed by HDR imaging and the increasing prevalence of multi-camera smartphones. 
<p align='center'>  
  <img src='https://github.com/dswdsw21072/ForensiCam-215K/blob/main/dataset.png' width='870'/>
</p>
<p align='center'> 

## Examples of some scenes in the ForensiCam-215K dataset

<p align='center'>  
  <img src='https://github.com/dswdsw21072/ForensiCam-215K/blob/main/scene.png' width='870'/>
</p>
<p align='center'> 
  
## Folder structure of the ForensiCam-215K dataset

<p align='center'>  
  <img src='https://github.com/dswdsw21072/ForensiCam-215K/blob/main/datastructure.png' width='650'/>
</p>
<p align='center'> 

## Download 
- https://pan.baidu.com/s/1s9BQJTpg8FZWY6444kxUJA
- Extraction code: dsw6
  
## Conclusions

we present a new image and video dataset comprising 215,901 media content created by 130 modern smartphones. The images were acquired in 6 different shooting modes: Default, Night, HDR, HIGH-RES,AI and Filter, respectively. Three types of smartphone cameras equipped with main lens, wide-angle lens, and telephoto lens are used for each shooting mode, except for HIGH-RES. The videos were captured using default settings. All media contents were taken under tightly controlled conditions. The organization and file naming of this dataset were carefully designed to facilitate data retrieval and processing by researchers, meeting the requirements for various of forensic methods. This dataset could serve as a common benchmark for current and future multimedia forensics.
