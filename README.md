# Exclusively Dark (ExDark) Image Dataset

Updated on June 1, 2019 (added codes for low-light image enhancement using Gaussian Process)

Released on May 29, 2018

## Description

* In order to facilitate a new object detection and image enhancement research, we introduce the Exclusively Dark (ExDark) dataset [(CVIU 2019)](http://cs-chan.com/doc/cviu.pdf). The Exclusively Dark (ExDARK) dataset is a collection of 7,363 low-light images from very low-light environments to twilight (i.e 10 different conditions) with 12 object classes (as to PASCAL VOC) annotated on both image class level and local object bounding boxes. 

![demo](Exdark.gif)

* Now available, codes for low-light image enhancement using Gaussian Process for features retrieval. [(SPIC 2019)](http://cs-chan.com/doc/SPIC2019.pdf)

<img src="llgp_enhance/2015_00003.gif" height="150" > <img src="llgp_enhance/2015_02446.gif" height="150" > <img src="llgp_enhance/2015_06400.gif" height="150" >

## Citation
If you find this dataset and/or work useful for your research, please cite
```
@article{loh2019getting,
  title={Getting to know low-light images with the Exclusively Dark dataset},
  author={Loh, Yuen Peng and Chan, Chee Seng},
  journal={Computer Vision and Image Understanding},
  volume={178},
  pages={30--42},
  year={2019},
  publisher={Elsevier}
}

@article{loh2019low,
  title={Low-light image enhancement using Gaussian Process for features retrieval},
  author={Loh, Yuen Peng and Liang, Xuefeng and Chan, Chee Seng},
  journal={Signal Processing: Image Communication},
  volume={74},
  pages={175--190},
  year={2019},
  publisher={Elsevier}
}
```

## Feedback
Suggestions and opinions of this dataset (both positive and negative) are greatly welcomed. Please contact the authors by sending an email to
`lexloh2009 at hotmail.com`or `cs.chan at um.edu.my`.

## License
The project is open sourced under BSD-3 license (see the ``` LICENSE ``` file). Codes can be used freely only for academic purpose.
