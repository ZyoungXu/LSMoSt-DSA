<div align="center">
<h1><img src='/sundry/1f52c.gif' width="35px"> GenDSA <img src='/sundry/1f4a1.gif' width="35px"></h1>
<h3>Large-scale Pretrained Multi-Frame Generative Model Enables Real-Time Low-Dose DSA Imaging</h3>

[![paper](https://img.shields.io/badge/Paper-Online_Available_(click_here)-orange)](https://www.cell.com/cms/10.1016/j.medj.2024.07.025/attachment/4209f5f8-1a77-4e15-a872-80a6239ec7bd/mmc3.pdf#:~:text=development%20and%20multi-center%20validation%20study,%20Med%20(2024),) [![license](https://img.shields.io/badge/License-Apache_2.0_(click_here)-blue)](LICENSE)

Huangxuan Zhao<sup>1 🏷️ :email:</sup>,[Ziyang Xu](https://ziyangxu.top/)<sup>2 🏷️</sup>,Linxia Wu<sup>1 🏷️</sup>, Lei Chen<sup>1 🏷️</sup>, [Ziwei Cui](https://github.com/ziwei-cui)<sup>2</sup>, Jinqiang Ma<sup>1</sup>, Tao Sun<sup>1</sup>, Yu Lei<sup>1</sup>, Nan Wang<sup>3</sup>, Hongyao Hu<sup>4</sup>, Yiqing Tan<sup>5</sup>, Wei Lu<sup>6</sup>, Wenzhong Yang<sup>7</sup>, Kaibing Liao<sup>8</sup>, Gaojun Teng<sup>9</sup>, Xiaoyun Liang<sup>10</sup>, Yi Li<sup>10</sup>, Congcong Feng<sup>11</sup>, Tong Nie<sup>1</sup>, Xiaoyu Han<sup>1</sup>, P.Matthijs van der Sluijs<sup>12</sup>, Charles B.L.M. Majoie<sup>13</sup>, Wim H. van Zwam<sup>14</sup>, Yun Feng<sup>15</sup>, Theo van Walsum<sup>11</sup>, Aad van der Lugt<sup>11</sup>, [Wenyu Liu](http://eic.hust.edu.cn/professor/liuwenyu/)<sup>2</sup>, Xuefeng Kan<sup>1 :email:</sup>, Ruisheng Su<sup>11 :email:</sup>, Weihua Zhang<sup>9 :email:</sup>, [Xinggang Wang](https://xwcv.github.io/)<sup>2 :email:</sup>, Chuansheng Zheng<sup>1 :email:</sup>

(<sup>🏷️</sup>) equal contribution, (<sup>:email:</sup>) corresponding author.

<sup>1</sup> Department of Radiology, Union Hospital, Tongji Medical College, Huazhong University of Science and Technology, Wuhan, China.  
<sup>2</sup> Institute of AI, School of Electronic Information and Communications, Huazhong University of Science and Technology, Wuhan, China.  
<sup>3</sup> Department of Radiology, Tongji Hospital, Tongji Medical College, Huazhong University of Science and Technology, Wuhan, China.  
<sup>4</sup> Department of Interventional Radiology, Renmin Hospital of Wuhan University, Wuhan, China.  
<sup>5</sup> Department of Radiology, Tongren Hospital of Wuhan University (Wuhan Third Hospital), Wuhan University, Wuhan, China.  
<sup>6</sup> Department of Interventional Radiology, Zhongnan Hospital of Wuhan University, Wuhan, China.  
<sup>7</sup> Department of Radiology, Maternal and Child Health Hospital of Hubei Province, Wuhan, China.  
<sup>8</sup> Department of Radiology, Hubei Integrated Traditional Chinese and Western Medicine Hospital, Wuhan, China.  
<sup>9</sup> Department of Radiology, Zhongda Hospital, Medical School, Southeast University, Nanjing, China.  
<sup>10</sup> Institute of Research and Clinical Innovations, Neusoft Medical Systems, Co., Ltd, Shanghai, China.  
<sup>11</sup> CV Systems Research and Development Department, Neusoft Medical Systems, Co., Ltd, Shenyang, China.  
<sup>12</sup> Department of Radiology & Nuclear Medicine, Erasmus MC, University Medical Center Rotterdam, The Netherlands.  
<sup>13</sup> Department of Radiology and Nuclear Medicine, Amsterdam University Medical Centers, location AMC, Amsterdam, The Netherlands.  
<sup>14</sup> Department of Radiology and Nuclear Medicine, Cardiovascular Research Institute Maastricht, Maastricht University Medical Center, Maastricht, The Netherlands.  
<sup>15</sup> Center for Biological Imaging, Institute of Biophysics, Chinese Academy of Sciences, Beijing, China.


</div>

## <img src='/sundry/1f43c.gif' width="30px"> News

* **`January 25, 2025`:** 🔥🔥🔥 GenDSA-V2 coming soon! 🔥🔥🔥 We further scaled up the data and conducted a large number of clinical trials at multiple centers. The new work is under review, please pay attention!

* **`September 4, 2024`:** [Paper](https://www.cell.com/cms/10.1016/j.medj.2024.07.025/attachment/4209f5f8-1a77-4e15-a872-80a6239ec7bd/mmc3.pdf#:~:text=development%20and%20multi-center%20validation%20study,%20Med%20(2024),) is online and available now. Enjoy!

* **`July 5, 2024`:** GenDSA is received by Med (Cell Press journal)! <img src='/sundry/cheers.gif' width="25px">

* **`June 5, 2024`:** We released a portion of the 3D vascular and 3D non vascular datasets. ([link here](https://drive.google.com/drive/folders/1t-esIdUnVcZdFXmSGhGcwhcpI0KyGKY0?usp=sharing))

* **`March 27, 2024`:** We released our inference code. Paper/Project pages are coming soon. Please stay tuned! <img src='/sundry/1f379.gif' width="25px">

## <img src='/sundry/1f4f0.gif' width="30px"> Abstract
Digital subtraction angiography (DSA) devices have been commonly used in hundreds of different interventional procedures in various parts of the body, requiring multiple scans of the patient in a single procedure, which was high radiation damage to doctors and patients. Inspired by generative artificial intelligence techniques, this study proposed a large-scale pretrained multi-frame generative model-based real-time and low-dose DSA imaging system (GenDSA). Suitable for most DSA scanning protocols, GenDSA could reduce the DSA frame rate (i.e., radiation dose) to 1/3 and generates video that was virtually identical to clinically available protocols. GenDSA was pre-trained, fine-tuned and tested on ten million of images from 35 hospitals. Objective quantitative metrics (PSNR=36.83, SSIM=0.911, generated times=0.07s/frame) demonstrated that the GenDSA’s performance surpassed that of state-of-the-art algorithms in the field of image frame generation. Subjective ratings and statistical results from five doctors showed that the generated videos reached a comparable level to the full-sampled videos, both in terms of overall quality (4.905 vs 4.935) and lesion assessment (4.825 vs 4.860), which fully demonstrated the potential of GenDSA for clinical applications.


## <img src='/sundry/1f9f3.gif' width="30px"> Environment Setups

* python 3.8
* cudatoolkit 11.2.1
* cudnn 8.1.0.77
* See 'requirements_Ours.txt' for Python libraries required

```shell
conda create -n GenDSA python=3.8
conda activate GenDSA
conda install cudatoolkit=11.2.1 cudnn=8.1.0.77
pip install torch==1.9.0+cu111 torchvision==0.10.0+cu111 -f https://download.pytorch.org/whl/torch_stable.html
# cd /xx/xx/GenDSA
pip install -r GenDSA_env.txt
```


## <img src='/sundry/1f5c2-fe0f.gif' width="30px"> Model Checkpoints
Download the zip of [model checkpoints](https://share.weiyun.com/ze6bOv0i) (key:```mqfd5s```), decompress and put all pkl files into ../GenDSA/weights/checkpoints.

## <img src='/sundry/听诊器.gif' width="30px"> Our Dataset and Inference Cases
We released a portion of the 3D vascular and non vascular datasets, including the results of our model inference. ([Google Drive](https://drive.google.com/drive/folders/1t-esIdUnVcZdFXmSGhGcwhcpI0KyGKY0?usp=sharing))


## <img src='/sundry/1f3ac.gif' width="30px"> Inference Demo
Run the following commands to generate single/multi-frame interpolation:

* Single-frame interpolation
```shell
python Simple_Interpolator.py \
--model_path ./weights/checkpoints/3D-vas-Inf1.pkl \
--frame1 ./demo_images/DSA_1.png \
--frame2 ./demo_images/DSA_2.png \
--inter_frames 1
```

* Two-frame interpolation
```shell
python Simple_Interpolator.py \
--model_path ./weights/checkpoints/3D-vas-Inf2.pkl \
--frame1 ./demo_images/DSA_1.png \
--frame2 ./demo_images/DSA_2.png \
--inter_frames 2
```

* Three-frame interpolation
```shell
python Simple_Interpolator.py \
--model_path ./weights/checkpoints/3D-vas-Inf3.pkl \
--frame1 ./demo_images/DSA_1.png \
--frame2 ./demo_images/DSA_2.png \
--inter_frames 3
```

You can also use other checkpoints to generate 1~3 frame interpolation for your 2D/3D - Head/Abdomen/Thorax/Pelvic/Periph images.

## 💖 Citation
Please promote and cite our work if you find it helpful. Enjoy!
```shell
@article{zhao2024large,
    title={Large-scale pretrained frame generative model enables real-time low-dose DSA imaging: An AI system development and multi-center validation study},
    author={Zhao, Huangxuan and Xu, Ziyang and Chen, Lei and Wu, Linxia and Cui, Ziwei and Ma, Jinqiang and Sun, Tao and Lei, Yu and Wang, Nan and Hu, Hongyao and others},
    journal={Med},
    year={2024},
    publisher={Elsevier},
    url={https://doi.org/10.1016/j.medj.2024.07.025},
}
```


<!--
## Acknowledgement


## Citation
-->

