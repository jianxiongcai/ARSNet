# ARSNet
This is an archived course project on CS272 Computer Vision II. 
The report is publicly available at [Report/egpaper_final.pdf](https://github.com/ernestcai/ARSNet/blob/master/Report/egpaper_final.pdf)

# Files
- Meeting Log
- Final Report

# weights
- All weights is saved on AI cluster (under ~/weights)
- Named in VERSION_SUBID_BACKBONE
### Version
| Version | Multi-RPN | sharing features | 1*1 conv + sharing feature | Hard-negative Mining | Backbone | Note                                |
|---------|-----------|------------------|----------------------------|----------------------|----------|-------------------------------------|
| 1       |           |                  |                            |                      | VGG16    | Original Implementation from Github |
| 2       |           |                  |                            | Yes                  | VGG16    |                                     |
| 3       | Yes       |                  |                            |                      | VGG16    |                                     |
| 4       | Yes       |                  |                            | Yes                  | VGG16    |                                     |
| 5       | Yes       | Yes              |                            |                      | VGG16    |                                     |
| 6       | Yes       |                  | Yes                        |                      |          |                                     |
### SUBID
Just to avoid name conflict for different weights
### BACKBONE
- VGG16-031 => pretrain_models/vgg16_caffe_0_3_1.pth
- VGG16 => pretrain_models/vgg16_caffe.pth


# Contribution Guide
- Don't put huge files like model weights here...
