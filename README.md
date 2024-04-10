# SRCNN
## Implementation of SRCNN (Image super resolution using deep convolutional networks)
This work provides the implementation of SRCNN, a super-resolution model, presented in 2014. I have read through the whole paper and tried to generate the model with reference to some other sources. The model is implemented using pytorch. The quality of generated model is in line with the result of paper. T90 is used as training dataset and Set 5 is used as test dataset.
| `<SRCNN>`  | `<ORIGINAL>`   |
|------------|----------------|
|![image](https://github.com/kimhyeonejun/SRCNN/assets/103301952/b46db0b4-b790-4c23-ba51-2adc09057ba4)|![image](https://github.com/kimhyeonejun/SRCNN/assets/103301952/6d2d15d0-9c70-456c-95f5-5929ccfef377)|
| PSNR: 29.69dB | Original image |

The performance of our model is compared with the performance of model indicated in the paper, as follows.
The comparision takes place with 4-upscaling images. 

| `<Mine>`  | `<Paper>`   |
|------------|----------------|
| PSNR: 30.41dB | PSNR: 30.48dB |

Note that each measurement is done with Y channels in YGB coordinates.
