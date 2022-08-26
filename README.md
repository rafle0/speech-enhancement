# Speech-Enhancement Tutorial
This repository is tutorial of "DCCRN-Deep Complex Convolution Recurrent Network for Phase-Aware Speech Enhancement".   
You can implement jupyter notebook files on Sagemaker Studio Lab environment.  


## Files
```text
training.ipynb : training process
inference.ipynb : inference for 4 wav files
model.py : original model file of dccrn
smallmodel.py : causal version of dccrn 
```

## Data Licences

All datasets are obtained from https://github.com/microsoft/DNS-Challenge/tree/interspeech2020/master 

The datasets used in this project are licensed as follows:

1. Clean speech: 
* https://librivox.org/; License: https://librivox.org/pages/public-domain/
* PTDB-TUG: Pitch Tracking Database from Graz University of Technology https://www.spsc.tugraz.at/databases-and-tools/ptdb-tug-pitch-tracking-database-from-graz-university-of-technology.html; License: http://opendatacommons.org/licenses/odbl/1.0/ 
* Edinburgh 56 speaker dataset: https://datashare.is.ed.ac.uk/handle/10283/2791; License: https://datashare.is.ed.ac.uk/bitstream/handle/10283/2791/license_text?sequence=11&isAllowed=y 
2. Noise:
* Audioset: https://research.google.com/audioset/index.html; License: https://creativecommons.org/licenses/by/4.0/
* Freesound: https://freesound.org/ Only files with CC0 licenses were selected; License: https://creativecommons.org/publicdomain/zero/1.0/
* Demand: https://zenodo.org/record/1227121#.XRKKxYhKiUk; License: https://creativecommons.org/licenses/by-sa/3.0/deed.en_CA

## Citation:
For the datasets and the DNS challenge:<br />  

```BibTex
@article{reddy2020interspeech,
  title={The INTERSPEECH 2020 Deep Noise Suppression Challenge: Datasets, Subjective Testing Framework, and Challenge Results},
  author={Reddy, Chandan KA and Gopal, Vishak and Cutler, Ross and Beyrami, Ebrahim and Cheng, Roger and Dubey, Harishchandra and Matusevych, Sergiy and Aichner, Robert and Aazami, Ashkan and Braun, Sebastian and others},
  journal={arXiv preprint arXiv:2005.13981},
  year={2020}
}
```
