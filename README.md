# Awesome-360

Awesome works and resources relevant to 360 saliency prediction and visual quality assessment. Insipred by [awesome-360-vision](https://github.com/hsientzucheng/awesome-360-vision)

## Content
1. 360 saliency prediction
2. 360 visual quality assessment
3. ...

## 360 saliency prediction

### ⭕ Image

#### `Scanpath/HM/EM prediction`

* __SaltiNet: _Scan-path prediction_ on 360 degree images using saliency volumes__  
Marc Assens, Kevin McGuinness, Xavier Giro-i-Nieto, Noel E. O'Connor  
_IEEE International Conference on Computer Vision Workshops (__ICCVW__)_, 2017.
[[pdf]](https://arxiv.org/pdf/1707.03123.pdf)  [[code]](https://github.com/massens/saliency-360salient-2017) 

* __The prediction of _head and eye movement_ for 360 degree images__  
Zhu, Yucheng, Guangtao Zhai, and Xiongkuo Min  
_Signal Processing: Image Communication (__SPIC__)_, 2018.
[[pdf]](https://www.researchgate.net/profile/Yucheng-Zhu/publication/325290936_The_prediction_of_head_and_eye_movement_for_360_degree_images/links/5c63dc9ba6fdccb608be664f/The-prediction-of-head-and-eye-movement-for-360-degree-images.pdf) 

* __PathGAN: visual _Scanpath Prediction_ with Generative Adversarial Networks__  
Marc Assens, Xavier Giro-i-Nieto, Kevin McGuinness, and Noel E. O’Connor  
_European Conference on Computer Vision (__ECCV__)_, 2018.
[[pdf]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Assens_PathGAN_Visual_Scanpath_Prediction_with_Generative_Adversarial_Networks_ECCVW_2018_paper.pdf) [[code]](https://github.com/imatge-upc/pathgan)

#### `Salient regions prediction`

* __SalGAN360: Visual _saliency prediction_ on 360 degree images with generative adversarial networks__  
Fang-Yi Chao, Lu Zhang, Wassim Hamidouche, and Olivier Deforges  
_IEEE International Conference on Multimedia & Expo Workshops (__ICMEW__)_, 2018.
[[pdf]](http://openhevc.insa-rennes.fr/wp-content/uploads/2018/07/camera-ready_icme2018template.pdf) [[code]](https://github.com/FannyChao/SalGAN360)

* __SalNet360: _Saliency maps_ for omnidirectional images with CNN__  
Rafael Monroy, Sebastian Lutz, Tejo Chalasani, and Aljosa Smolic  
_Signal Processing: Image Communication (__SPIC__)_, 2018.
[[pdf]](https://arxiv.org/pdf/1709.06505.pdf) [[code]](https://github.com/V-Sense/salnet360)

* __A novel superpixel-based _saliency detection_ model for 360-degree images__  
Fang, Yuming, Xiaoqiang Zhang, and Nevrez Imamoglu  
_Signal Processing: Image Communication (__SPIC__)_, 2018.
[[pdf]](http://sim.jxufe.cn/JDMKL/pdf/A%20novel%20superpixel-based%20saliency%20detection%20model%20for%20360-degree%20images.pdf?WebShieldDRSessionVerify=Fse08zSUzY98q7ecbMBh) [[code]](http://sim.jxufe.cn/JDMKL/code/360-image-saliency-code.zip)

* __SalGCN: _Saliency Prediction_ for 360-Degree Images Based on Spherical Graph Convolutional Networks__  
Haoran Lv, Qin Yang, Chenglin Li, Wenrui Dai, Junni Zou, Hongkai Xiong  
_ACM International Conference on Multimedia (__ACMM__)_, 2020.
[[pdf]](https://dl.acm.org/doi/10.1145/3394171.3413733)

#### `Dataset/Tools`

* __A dataset of head and eye movements for 360 degree images__  
Yashas Rai, Jesús Gutiérrez, and Patrick Le Callet 
_ACM Multimedia Systems Conference (__ACMMSys__)_, 2017.
[[pdf]](https://www.researchgate.net/profile/Yashas_Rai/publication/317393759_A_Dataset_of_Head_and_Eye_Movements_for_360_Degree_Images/links/5e7a56c892851cdfca2f4ba2/A-Dataset-of-Head-and-Eye-Movements-for-360-Degree-Images.pdf) [[project]](https://salient360.ls2n.fr/datasets/training-dataset/)

****

### ⭕ Video

#### `Scanpath/HM/EM prediction + FOV Piloting`

* __Pano2vid: _Automatic cinematography_ for watching 360° videos__  
Yu-Chuan Su, Dinesh Jayaraman, and Kristen Grauman  
_Asian Conference on Computer Vision (__ACCV__)_, 2016.
[[pdf]](http://vision.cs.utexas.edu/projects/Pano2Vid/accv2016-0327su.pdf) [[code]](https://github.com/sammy-su/Pano2Vid)

* __Making 360∘ Video Watchable in 2D: Learning _Videography_ for Click Free Viewing__  
Yu-Chuan Su, Kristen Grauman  
_IEEE Conference on Computer Vision and Pattern Recognition (__CVPR__)_, 2017.
[[pdf]](https://arxiv.org/pdf/1703.00495.pdf) [[code]](https://github.com/sammy-su/Pano2Vid)

* __Deep 360 Pilot: Learning a Deep Agent for _Piloting_ through 360° Sports Video__  
Hou-Ning Hu, Yen-Chen Lin, Ming-Yu Liu, Hsien-Tzu Cheng, Yung-Ju Chang, Min Sun  
_IEEE Conference on Computer Vision and Pattern Recognition (__CVPR__)_, 2017.
[[pdf]](https://arxiv.org/pdf/1705.01759.pdf) [[code]](https://github.com/eborboihuc/Deep360Pilot-CVPR17)

* __Your attention is unique: Detecting 360-degree video saliency in head-mounted display for _head movement prediction___  
Nguyen, Anh, Zhisheng Yan, and Klara Nahrstedt  
_ACM international conference on Multimedia (__ACMM__)_, 2018.
[[pdf]](https://zyan.gsucreate.org/papers/panosalnet_mm18.pdf) [[code]](https://github.com/phananh1010/PanoSalNet)

* __Predicting _head movement_ in panoramic video: A deep reinforcement learning approach__  
Mai Xu, Yuhang Song, Jianyi Wang, Minglang Qiao, Liangyu Huo, and Zulin Wang  
_IEEE Transactions on Pattern Analysis and Machine Intelligence (__TPAMI__)_, 2019.
[[pdf]](https://arxiv.org/pdf/1710.10755.pdf) [[code]](https://github.com/YuhangSong/DHP)

#### `Salient regions prediction`

* __Cube padding for weakly-supervised _saliency prediction_ in 360° videos__  
Hsien-Tzu Cheng, Chun-Hung Chao, Jin-Dong Dong, Hao-Kai Wen, Tyng-Luh Liu, Min Sun  
_IEEE Conference on Computer Vision and Pattern Recognition (__CVPR__)_, 2018.
[[pdf]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Cheng_Cube_Padding_for_CVPR_2018_paper.pdf) [[code]](https://github.com/hsientzucheng/CP-360-Weakly-Supervised-Saliency)

* __V-BMS360: A video extention to the BMS360 image _saliency_ model__  
Lebreton, Pierre, Stephan Fremerey, and Alexander Raake  
_IEEE International Conference on Multimedia & Expo Workshops (__ICMEW__)_, 2018.
[[pdf]](https://ieeexplore.ieee.org/abstract/document/8551523) [[code]](https://github.com/Telecommunication-Telemedia-Assessment/V-BMS360)

* ___Saliency detection_ in 360° videos__  
Ziheng Zhang, Yanyu Xu, Jingyi Yu  
_European Conference on Computer Vision (__ECCV__)_, 2018.
[[pdf]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Ziheng_Zhang_Saliency_Detection_in_ECCV_2018_paper.pdf) [[code]](https://github.com/xuyanyu-shh/Saliency-detection-in-360-video)

* __Viewport-dependent Saliency Prediction in 360° Video__  
Minglang Qiao, Mai Xu, Zulin Wang, Ali Borji  
_IEEE Transactions on Multimedia (__TMM__)_, 2020.
[[pdf]](https://ieeexplore.ieee.org/abstract/document/9072511)

#### `Dataset/Tools`

* __A dataset of head and eye movements for 360° videos__  
Erwan David, Jesus Gutierrez, Antoine Coutrot, Matthieu Perreira da Silva, and Patrick Le Callet  
_ACM Multimedia Systems Conference (__ACMMSys__)_, 2018. 
[[pdf]](https://hal.archives-ouvertes.fr/hal-01994923/document) [[project]](https://www.interdigital.com/data_sets/salient-360-dataset)

* __A saliency dataset for 360-degree videos__  
Anh Nguyen and Zhisheng Yan  
_ACM Multimedia Systems Conference (__ACMMSys__)_, 2019.
[[pdf]](https://zyan.gsucreate.org/papers/360saliency_mmsys19.pdf) [[project]](https://github.com/phananh1010/PanoSaliency)













