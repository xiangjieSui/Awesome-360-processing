# Awesome-360-processing

Awesome works and resources relevant to 360 saliency prediction and visual quality assessment. Insipred by [awesome-360-vision](https://github.com/hsientzucheng/awesome-360-vision).

## 🔺 Content
1. 360 saliency prediction
2. 360 visual quality assessment
3. 360 transmission
4. 360 sickness

## 🔺 360 saliency prediction

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

* __SalGCN: _Saliency prediction_ for 360-degree images based on spherical graph convolutional networks__  
Haoran Lv, Qin Yang, Chenglin Li, Wenrui Dai, Junni Zou, Hongkai Xiong  
_ACM International Conference on Multimedia (__ACMM__)_, 2020.  
[[pdf]](https://dl.acm.org/doi/10.1145/3394171.3413733)

* __Stage-wise Salient Object Detection in 360° Omnidirectional Image via Object-level Semantical Saliency Ranking__  
Guangxiao Ma, Shuai Li, Chenglizhao Chen, Aimin Hao, Hong Qin  
_IEEE Transactions on Visualization and Computer Graphics (__TVCG__)_, 2020.  
[[pdf]](http://probb268dca.pic5.ysjianzhan.cn/upload/TVCG20.pdf)[[code + dataset]](https://github.com/360-SSOD/download)

* __A Multi-FoV Viewport-based Visual Saliency Model Using Adaptive Weighting Losses for 360◦ Images__  
Fang-Yi Chao, Lu Zhang, Wassim Hamidouche, Olivier Déforges  
_IEEE Transactions on Multimedia (__TMM__)_, 2020.  
[[pdf]](https://hal.archives-ouvertes.fr/hal-02881994/file/Chao%20et%20al-2020-A%20Multi-FoV%20Viewport-based%20Visual%20Saliency%20Model%20Using%20Adaptive%20Weighting.pdf) [[code]](https://github.com/FannyChao/MV-SalGAN360)

* __SalBiNet360: Saliency Prediction on 360° Images with Local-Global Bifurcated Deep Network__  
Dongwen Chen, Chunmei Qing, Xiangmin Xu, Huansheng Zhu  
_IEEE Conference on Virtual Reality and 3D User Interfaces (__VR__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/9089519) 

#### `Dataset/Tools`

* __A dataset of head and eye movements for 360 degree images [salient360!]__  
Yashas Rai, Jesús Gutiérrez, and Patrick Le Callet   
_ACM Multimedia Systems Conference (__ACMMSys__)_, 2017.  
[[pdf]](https://dl.acm.org/doi/abs/10.1145/3083187.3083218) [[project]](https://salient360.ls2n.fr/datasets/training-dataset/)

* __A fixation-based 360° benchmark dataset for salient object detection__  
Yi Zhang, Lu Zhang, Wassim Hamidouche, Olivier Deforges  
_IEEE International Conference on Image Processing (__ICIP__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/9191158)[[dataset]](https://github.com/PanoAsh/F-360iSOD)


****

### ⭕ Video

#### `Scanpath/HM/EM prediction + FOV Piloting`

* __Pano2vid: _Automatic cinematography_ for watching 360° videos__  
Yu-Chuan Su, Dinesh Jayaraman, and Kristen Grauman  
_Asian Conference on Computer Vision (__ACCV__)_, 2016.  
[[pdf]](http://vision.cs.utexas.edu/projects/Pano2Vid/accv2016-0327su.pdf) [[code]](https://github.com/sammy-su/Pano2Vid) [[dataset]](http://vision.cs.utexas.edu/projects/Pano2Vid/)

* __Making 360∘ video watchable in 2D: learning _videography_ for click free viewing__  
Yu-Chuan Su, Kristen Grauman  
_IEEE Conference on Computer Vision and Pattern Recognition (__CVPR__)_, 2017.  
[[pdf]](https://arxiv.org/pdf/1703.00495.pdf) [[code]](https://github.com/sammy-su/Pano2Vid)

* __Deep 360 pilot: Learning a deep agent for _piloting_ through 360° sports video__  
Hou-Ning Hu, Yen-Chen Lin, Ming-Yu Liu, Hsien-Tzu Cheng, Yung-Ju Chang, Min Sun  
_IEEE Conference on Computer Vision and Pattern Recognition (__CVPR__)_, 2017.  
[[pdf]](https://arxiv.org/pdf/1705.01759.pdf) [[code + dataset]](https://github.com/eborboihuc/Deep360Pilot-CVPR17)

* __Tell me where to look: Investigating ways for _assisting focus_ in 360° video__  
Yen-Chen Lin, Yung-Ju Chang, Hou-Ning Hu, Hsien-Tzu Cheng, Chi-Wen Huang, Min Sun  
_Conference on Human Factors in Computing Systems (__CHI__)_, 2017.  
[[pdf]](https://dl.acm.org/doi/10.1145/3025453.3025757) [[project]](https://aliensunmin.github.io/project/360video-study/)

* __Your attention is unique: Detecting 360-degree video saliency in head-mounted display for _head movement prediction___  
Nguyen, Anh, Zhisheng Yan, and Klara Nahrstedt  
_ACM international conference on Multimedia (__ACMM__)_, 2018.  
[[pdf]](https://zyan.gsucreate.org/papers/panosalnet_mm18.pdf) [[code]](https://github.com/phananh1010/PanoSalNet)

* __Predicting _head movement_ in panoramic video: A deep reinforcement learning approach__  
Mai Xu, Yuhang Song, Jianyi Wang, Minglang Qiao, Liangyu Huo, and Zulin Wang  
_IEEE Transactions on Pattern Analysis and Machine Intelligence (__TPAMI__)_, 2019.  
[[pdf]](https://arxiv.org/pdf/1710.10755.pdf) [[code]](https://github.com/YuhangSong/DHP)

* __ATSal: An attention based architecture for _saliency prediction_ in 360° videos__  
Yasser Dahou, Marouane Tliba, Kevin McGuinness, Noel O'Connor  
___arxiv___, 2020.  
[[pdf]](https://arxiv.org/pdf/2011.10600.pdf) [[code]](https://github.com/mtliba/ATSal)

* __Interactive and _automatic navigation_ for 360° video playback__  
Kyoungkook Kang and Sunghyun Cho  
_ACM Transactions on Graphics (__TOG__)_, 2019.  
[[pdf]](http://cg.postech.ac.kr/papers/2019_SIGGRAPH_CHO.pdf) [[project]](https://kkang831.github.io/publication/SIG_2019_Interactive360/supplementary/)

* __Attention-based Deep Reinforcement Learning for Virtual Cinematography of 360° Videos__  
Jianyi Wang, Mai Xu, Lai Jiang, Yuhang Song  
_IEEE Transactions on Multimedia (__TMM__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/9186833) 

* __A Spherical Convolution Approach for Learning Long Term Viewport Prediction in 360 Immersive Video__  
Chenglei Wu, Rui-Xiao Zhang, Zhi Wang, Lifeng Sun  
_AAAI Conference on Artificial Intelligence (__AAAI__)_, 2020.  
[[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/7377) [[code]](https://github.com/wuchlei/AAAI20-Viewport-Prediction)

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

* __Viewport-dependent _saliency prediction_ in 360° video__  
Minglang Qiao, Mai Xu, Zulin Wang, Ali Borji  
_IEEE Transactions on Multimedia (__TMM__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/9072511)


#### `Dataset/Tools`

* __A saliency dataset for 360-degree videos__  
Anh Nguyen and Zhisheng Yan  
_ACM Multimedia Systems Conference (__ACMMSys__)_, 2019.  
[[pdf]](https://zyan.gsucreate.org/papers/360saliency_mmsys19.pdf) [[project]](https://github.com/phananh1010/PanoSaliency)


## 🔺 360 visual quality assessment

### ⭕ Image

#### `2D-Plane-based`

* __[WS-PSNR] Weighted-to-spherically-uniform quality evaluation for omnidirectional video__  
Yule Sun, Ang Lu, Lu Yu  
_IEEE Signal Processing Letters (__SPL__)_, 2017.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/7961186)

* __[W-SSIM/WMS-SSIM] Subjective and objective quality assessment of omnidirectional video__  


#### `Shpere-based`

#### `Viewport-based`










