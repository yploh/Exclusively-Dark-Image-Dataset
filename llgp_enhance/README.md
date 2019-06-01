# Low-light Image Enhancement using Gaussian Process for Features Retrieval

Released on June 1, 2019

## Description

This is the implementation of our SPIC2019 work titled: [Low-light Image Enhancement using Gaussian Process for Features Retrieval](http://cs-chan.com/doc/SPIC2019.pdf)

![demo](2015_00003.gif)
![demo](2015_02446.gif)
![demo](2015_06400.gif)

## Citation

If you find this code useful for your research, please cite:
```
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

## Dependency

The codes are implemented in MATLAB using prior versions of the [MatConvNet](http://www.vlfeat.org/matconvnet/) and the [Gaussian Process for Machine Learning](http://www.gaussianprocess.org/gpml/code/matlab/doc/index.html) toolboxes.

## Installation and Running

1. Extract GPR_v1.1.zip

2. Extract matconvnet-1.0-beta20.tar.gz
   - run vl_compilenn
   - run vl_setupnn
   * for problems installing the toolbox, please refer to [MatConvNet](http://www.vlfeat.org/matconvnet/)

3. Run demo.m

## Feedback
Suggestions and opinions of this work (both positive and negative) are greatly welcomed. Please contact the authors by sending an email to
`lexloh2009 at hotmail.com`or `cs.chan at um.edu.my`.

## License and
The project is open sourced under BSD-3 license (see the ``` LICENSE ``` file). Codes can be used freely only for academic purposes.
