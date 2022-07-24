# MTVital - Efficient Deep Learning-based Estimation of the Vital Signs on Smartphones

Official repository of "[Efficient Deep Learning-based Estimation of the Vital Signs on Smartphones](https://arxiv.org/abs/2204.08989)".

This repository contains the code and the proposed dataset (MTHS)

## Checklist
- [x] MTHS dataset
- [x] Finger Videos (New!)
- [x] Code
- [ ] Webpage 

## Code

* Codes are included in the `code` folder. Please refer to its `Readme.md` for more detailed information. 
## Dataset - MTHS: 
* This folder contains our dataset
* Each subject has two `.npy` files: mean RGB signals as `signal_x.npy` and ground truth labels as `label_x.npy`, where `x` is the patient id.
* `signal_x.npy` contains the mean signals ordered as R, G, and then B sampled at 30Hz.
* `label_x.npy` contains the ground truth data ordered as HR(bpm) - SpO2(%) Sampled at 1Hz.

### New! - Fingertip videos
Due to some requests we now provide the raw fingertip videos. 

Download it from here: [MTHS-FingerVideos](https://drive.google.com/file/d/1zXCAonTwdtOHBJ97OGn_KsfiKLQ191Lo/view?usp=sharing). 

## License
This project's code is released under the MIT license.
Note that the dataset is released under the [CC BY-NC-ND license](https://creativecommons.org/licenses/by-nc-nd/4.0/). 



## Citation
If you use our dataset or find this repository helpful, please consider citing:

```
@misc{2204.08989,
Author = {Taha Samavati and Mahdi Farvardin},
Title = {Efficient Deep Learning-based Estimation of the Vital Signs on Smartphones},
Year = {2022},
Eprint = {arXiv:2204.08989},
}
```

## Contact emails
* tahasamavati12@gmail.com
* m_farvardin@comp.iust.ac.ir
