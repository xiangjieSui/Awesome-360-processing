# Awesome-360-processing

Awesome works and resources relevant to 360 processing. Insipred by [awesome-360-vision](https://github.com/hsientzucheng/awesome-360-vision).

## 🔺 Content
1. 360 saliency prediction
2. 360 visual quality assessment
3. 360 sickness
4. 360 transmission 

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

* __PathGAN: Visual _scanpath prediction_ with generative adversarial networks__  
Marc Assens, Xavier Giro-i-Nieto, Kevin McGuinness, and Noel E. O’Connor  
_European Conference on Computer Vision (__ECCV__)_, 2018.  
[[pdf]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11133/Assens_PathGAN_Visual_Scanpath_Prediction_with_Generative_Adversarial_Networks_ECCVW_2018_paper.pdf) [[code]](https://github.com/imatge-upc/pathgan)

#### `Salient regions prediction`
* __Saliency in VR: How do people explore virtual environments?__  
Vincent Sitzmann, Ana Serrano, Amy Pavel, Maneesh Agrawala, Diego Gutierrez, Belen Masia, Gordon Wetzstein  
_IEEE Transactions on Visualization and Computer Graphics (__TVCG__)_, 2018.  
[[pdf]](https://ieeexplore.ieee.org/document/8269807)[[code]](https://vsitzmann.github.io/vr-saliency/)

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

* __Stage-wise salient object detection in 360° omnidirectional image via object-level semantical saliency ranking__  
Guangxiao Ma, Shuai Li, Chenglizhao Chen, Aimin Hao, Hong Qin  
_IEEE Transactions on Visualization and Computer Graphics (__TVCG__)_, 2020.  
[[pdf]](http://probb268dca.pic5.ysjianzhan.cn/upload/TVCG20.pdf)[[code + dataset]](https://github.com/360-SSOD/download)

* __A multi-FoV viewport-based visual saliency model using adaptive weighting losses for 360◦ images__  
Fang-Yi Chao, Lu Zhang, Wassim Hamidouche, Olivier Déforges  
_IEEE Transactions on Multimedia (__TMM__)_, 2020.  
[[pdf]](https://hal.archives-ouvertes.fr/hal-02881994/file/Chao%20et%20al-2020-A%20Multi-FoV%20Viewport-based%20Visual%20Saliency%20Model%20Using%20Adaptive%20Weighting.pdf) [[code]](https://github.com/FannyChao/MV-SalGAN360)

* __SalBiNet360: Saliency prediction on 360° images with local-global bifurcated deep network__  
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

* __Attention-based deep reinforcement learning for virtual cinematography of 360° videos__  
Jianyi Wang, Mai Xu, Lai Jiang, Yuhang Song  
_IEEE Transactions on Multimedia (__TMM__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/9186833) 

* __DGaze: CNN-based gaze prediction in dynamic scenes__  
Zhiming Hu, Sheng Li, Congyi Zhang, Kangrui Yi, Guoping Wang, Dinesh Manocha  
_IEEE Transactions on Visualization and Computer Graphics (__TVCG__)_, 2020.  
[[pdf]](https://cranehzm.github.io/DGaze/pdf/hu20_DGaze.pdf) [[code]](https://github.com/CraneHzm/DGaze) [[project]](https://cranehzm.github.io/DGaze)

* __A spherical convolution approach for learning long term viewport prediction in 360 immersive video__  
Chenglei Wu, Rui-Xiao Zhang, Zhi Wang, Lifeng Sun  
_AAAI Conference on Artificial Intelligence (__AAAI__)_, 2020.  
[[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/7377) [[code]](https://github.com/wuchlei/AAAI20-Viewport-Prediction)

* __Transitioning360: Content-aware NFoV virtual camera paths for 360° video playback__  
Miao Wang, Yi-Jun Li, Wen-Xuan Zhang  
_International Symposium on Mixed and Augmented Reality (__ISMAR__)_, 2020.  
[[pdf]](https://core.ac.uk/download/pdf/334410113.pdf)

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

### ⭕ 2D-Plane-based

* __[WS-PSNR] Weighted-to-spherically-uniform quality evaluation for omnidirectional video__  
Yule Sun, Ang Lu, Lu Yu  
_IEEE Signal Processing Letters (__SPL__)_, 2017.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/7961186)

* __[W-SSIM/WMS-SSIM] Subjective and objective quality assessment of omnidirectional video__  
Francisco Lopes, João Ascenso, António Rodrigues, Maria Paula Queluz  
_Applications of Digital Image Processing_, 2018.  
[[pdf]](https://www.researchgate.net/profile/Maria_Queluz/publication/327712637_Subjective_and_objective_quality_assessment_of_omnidirectional_video/links/5d402b764585153e592d34b1/Subjective-and-objective-quality-assessment-of-omnidirectional-video.pdf)

* __[CPP-PSNR] Quality metric for spherical panoramic video__  
Vladyslav Zakharchenko, Kwang Pyo Choi, Jeong Hoon Park  
_Optics and Photonics for Information Processing_, 2016.  
[[pdf]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/9970/99700C/Quality-metric-for-spherical-panoramic-video/10.1117/12.2235885.short?SSO=1)

* __Deep virtual reality image quality assessment with human perception guider for omnidirectional image__  
Hak Gu Kim, Heoun-Taek Lim, Yong Man Ro  
_IEEE Transactions on Circuits and Systems for Video Technology (__TCSVT__)_, 2019.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/8638985)


### ⭕ Shpere-based

* __[S-PSNR] A framework to evaluate omnidirectional video coding schemes__  
Matt Yu, Haricharan Lakshman, Bernd Girod  
_IEEE International Symposium on Mixed and Augmented Reality (__ISMAR__)_, 2015.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/7328056)  

* __[S-SSIM] Spherical structural similarity index for objective omnidirectional video quality assessment__  
Sijia Chen, Yingxue Zhang, Yiming Li, Zhenzhong Chen, Zhou Wang  
_IEEE International Conference on Multimedia and Expo (__ICME__)_, 2018.  
[[pdf]](https://www.ece.uwaterloo.ca/~z70wang/publications/icme18.pdf)  

### ⭕ Viewport-based

* __Saliency-driven omnidirectional imaging adaptive coding: Modeling and assessment__  
Guilherme Luz, João Ascenso, Catarina Brites, Fernando Pereira  
_International Workshop on Multimedia Signal Processing (__MMSP__)_, 2017.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/8122228)

* __Assessing visual quality of omnidirectional videos__  
Mai Xu, Chen Li, Zhenzhong Chen, Zulin Wang, Zhenyu Guan  
_IEEE Transactions on Circuits and Systems for Video Technology (__TCSVT__)_, 2019.  
[[pdf]](https://ieeexplore.ieee.org/document/8572733)  

* __Quality assessment of stereoscopic 360-degree images from multi-viewports__  
Jiahua Xu, Ziyuan Luo, Wei Zhou, Wenyuan Zhang, Zhibo Chen  
_IEEE Picture Coding Symposium (__PCS__)_, 2019.  
[[pdf]](https://arxiv.org/pdf/1908.10079.pdf)

* __Bridge the gap between VQA and human behavior on omnidirectional video: A large-scale dataset and a deep learning model__  
Chen Li, Mai Xu, Xinzhe Du, Zulin Wang  
_ACM international conference on Multimedia (__ACMM__)_, 2018.  
[[pdf]](https://arxiv.org/pdf/1807.10990.pdf)  [[dataset]](https://github.com/Archer-Tatsu/VQA-ODV)

* __Viewport proposal CNN for 360° video quality assessment__  
Chen Li, Mai Xu, Lai Jiang, Shanyi Zhang, Xiaoming Tao  
_IEEE Conference on Computer Vision and Pattern Recognition (__CVPR__)_, 2019.  
[[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Viewport_Proposal_CNN_for_360deg_Video_Quality_Assessment_CVPR_2019_paper.pdf) [[code]](https://github.com/Archer-Tatsu/V-CNN)

* __MC360IQA: A multi-channel CNN for blind 360-degree image quality assessment__  
Wei Sun, Weike Luo, Xiongkuo Min, Guangtao Zhai, Xiaokang Yang, Ke Gu, Siwei Ma  
_IEEE Journal of Selected Topics in Signal Processing (__JSTSP__)_, 2019.  
[[pdf]](https://ieeexplore.ieee.org/document/8910364)

* __Blind omnidirectional image quality assessment with viewport oriented graph convolutional networks__  
Jiahua Xu, Wei Zhou, Zhibo Chen  
_IEEE Transactions on Circuits and Systems for Video Technology (__TCSVT__)_, 2020.  
[[pdf]](https://arxiv.org/pdf/2002.09140.pdf)

* __Perceptual quality assessment of omnidirectional images as moving camera videos__  
Xiangjie Sui, Kede Ma, Yiru Yao, Yuming Fang  
_IEEE Transactions on Visualization and Computer Graphics (__TVCG__)_, 2021.  
[[pdf]](https://arxiv.org/pdf/2005.10547.pdf) [[code]](https://github.com/xiangjieSui/img2video) 

* __Viewport-based omnidirectional video quality assessment: Database, modeling and inference__  
Yu Meng, Zhan Ma  
_IEEE Transactions on Circuits and Systems for Video Technology (__TCSVT__)_, 2021.  
[[pdf]](https://ieeexplore.ieee.org/document/9349097)[[project]](https://vision.nju.edu.cn/20/86/c29466a467078/page.htm)



## 🔺 360 sickness

* __VRSA net: VR sickness assessment considering exceptional motion for 360° VR video__  
Hak Gu Kim, Heoun-Taek Lim, Sangmin Lee, Yong Man Ro  
_IEEE Transactions on Image Processing (__TIP__)_, 2018.  
[[pdf]](https://ieeexplore.ieee.org/abstract/document/8531715)

* __VR sickness versus VR presence: A statistical prediction model__  
Woojae Kim, Sanghoon Lee, Alan Conrad Bovik  
_IEEE Transactions on Image Processing (__TIP__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/document/9263288)




## 🔺 360 transmission
* __Graph learning based head movement prediction for interactive 360 video streaming__  
Xue Zhang, Gene Cheung, Yao Zhao, Patrick Le Callet, Chunyu Lin, and Jack Z. G. Tan  
_IEEE Transactions on Image Processing (__TIP__)_, 2021.  
[[pdf]](https://ieeexplore.ieee.org/document/9416230/authors#authors)

* __QoE evaluation methods for 360-degree VR video transmission__  
Zesong Fei, Fei Wang, Jing Wang, Xiang Xie  
_IEEE Journal of Selected Topics in Signal Processing (__JSTSP__)_, 2020.  
[[pdf]](https://ieeexplore.ieee.org/document/8917613)

* __A Log-Rectilinear Transformation for Foveated 360-Degree Video Streaming__  
[David Li](https://davidl.me), [Ruofei Du](https://duruofei.com), Adharsh Babu, Camelia Brumar, and [Amitabh Varshney](https://cs.umd.edu/~varshney)  
_IEEE Transactions on Visualization and Computer Graphics (__TVCG__ Honorable Mentions)_, 2021.  
[[pdf]](https://duruofei.com/papers/Li_ALog-RectilinearTransformationForFoveated360-DegreeVideoStreaming_TVCG2021.pdf)
[[project]](https://augmentariumlab.github.io/foveated-360-video)
[[code]](https://github.com/AugmentariumLab/foveated-360-video)


