# Awesome Make Up Transfer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Makeup Transfer (and Hairstyles Transfer) and related resources.

| ![teaser.jpg](https://raw.githubusercontent.com/Honlan/BeautyGAN/master/result.jpg) | 
|:--:| 
| *This image is from [BeautyGAN](https://github.com/Honlan/BeautyGAN)* |

#### 🌱 Contributing

Please feel free to send me [pull requests](https://github.com/thaoshibe/awesome-makeup-transfer/pulls) (or [issues](https://github.com/thaoshibe/awesome-makeup-transfer/issues)) to add papers/ talks/ demo etc.

------

### Table of Contents

- [Makeup Transfer](#makeup-transfer)
- [Hairstyles Transfer](#hairstyles-transfer)
- [Datasets](#datasets)
- [Applications](#applications)

-----

### Makeup Transfer

| Title    | Venue    | Year | Link/ Code     |
|:-------- |:--------:|:--------:|:--------:|
| [SHMT: Self-supervised Hierarchical Makeup Transfer via Latent Diffusion Models](https://openreview.net/forum?id=EeXcOYf3Lg) | NeurIPS | 2024 | [Code](https://github.com/Snowfallingplum/SHMT) |
| [Content-Style Decoupling for Unsupervised Makeup Transfer without Generating Pseudo Ground Truth](https://arxiv.org/abs/2405.17240) | CVPR | 2024 | [Code](https://github.com/Snowfallingplum/CSD-MT) |
| [Makeup Prior Models for 3D Facial Makeup Estimation and Applications](https://arxiv.org/pdf/2403.17761.pdf) | CVPR | 2024 | [Page](https://yangxingchao.github.io/makeup-priors-page/)|
| [SSAT ++ : A Semantic-Aware and Versatile Makeup Transfer Network With Local Color Consistency Constraint](https://ieeexplore.ieee.org/abstract/document/10328655?casa_token=eK7SKjCK2bEAAAAA:B2mINvCBFujPL4P01GY94N7C-m3CnC4YhqZp7Tzp26kVk5lApsj_gZBSHFO3-4xI9MoXLrtQtQ) | Journal | 2023 | |
| [Makeup Extraction of 3D Representation via Illumination-Aware Image Decomposition](https://arxiv.org/pdf/2302.13279.pdf) |Eurographics|2023|[Page](https://yangxingchao.github.io/makeup-extract-page/), [GitHub](https://github.com/YangXingchao/makeup-extract),|
| [RamGAN: Region Attentive Morphing GAN for Region-Level Makeup Transfer](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/803_ECCV_2022_paper.php) | ECCV | 2022 | -|
|[EleGANt: Exquisite and Locally Editable GAN for Makeup Transfer](https://arxiv.org/abs/2207.09840) |ECCV|2022|[Code](https://github.com/Chenyu-Yang-2000/EleGANt)|
| [SSAT: A Symmetric Semantic-Aware Transformer Network for Makeup Transfer and Removal](https://arxiv.org/abs/2112.03631) | AAAI | 2022 | [Code](https://gitee.com/sunzhaoyang0304/ssat-msp)|
| [SOGAN: 3D-Aware Shadow and Occlusion Robust GAN for Makeup Transfer](https://arxiv.org/abs/2104.10567)| ACM MM | 2021|
|[Spatially-Invariant Style-Codes Controlled Makeup Transfer](https://openaccess.thecvf.com/content/CVPR2021/html/Deng_Spatially-Invariant_Style-Codes_Controlled_Makeup_Transfer_CVPR_2021_paper.html) | CVPR |2021 |
| [PSGAN++: Robust Detail-Preserving Makeup Transfer and Removal](https://arxiv.org/abs/2105.12324) | TPAMI | 2021|
|[Deep Graphics Encoder for Real-Time Video Makeup Synthesis from Example](https://arxiv.org/abs/2105.06407)| CVPRw | 2021 ||
| [Lipstick ain't enough: Beyond Color Matching for In-the-Wild Makeup Transfer](https://arxiv.org/abs/2104.01867)|CVPR |2021| [Page](https://thaoshibe.github.io/CPM), [Code](https://github.com/VinAIResearch/CPM)|
| [PSGAN: Pose and Expression Robust Spatial-Aware GAN for Customizable Makeup Transfer](https://arxiv.org/pdf/1909.06956.pdf) | CVPR |2020| [GitHub](https://github.com/wtjiang98/PSGAN)|
| [CA-GAN: Weakly Supervised Color Aware GAN for Controllable Makeup Transfer](https://arxiv.org/pdf/2008.10298.pdf) | ECCVw |2020| [Page](https://robinkips.github.io/CA-GAN/)|
| [LADN: Local Adversarial Disentangling Network for Facial Makeup and De-Makeup](https://arxiv.org/pdf/1904.11272.pdf)    | ICCV  |2019  | [GitHub](https://github.com/wangguanzhi/LADN), [Page](https://georgegu1997.github.io/LADN-project-page/)|
| [BeautyGlow: On-Demand Makeup Transfer Framework With Reversible Generative Network](https://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_BeautyGlow_On-Demand_Makeup_Transfer_Framework_With_Reversible_Generative_Network_CVPR_2019_paper.pdf) | CVPR | 2019|[GitHub](https://github.com/BeautyGlow), [Page](https://beautyglow.github.io)|
|[Content and Colour Distillation for Learning Image Translations with the Spatial Profile Loss](https://arxiv.org/abs/1908.00274)|BMVC |2019| [GitHub](https://github.com/ssarfraz/SPL)|
| [BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network](https://dl.acm.org/doi/abs/10.1145/3240508.3240618) | ACM |2018|[Tensorflow](https://github.com/Honlan/BeautyGAN), [Torch](https://github.com/wtjiang98/BeautyGAN_pytorch), [Page](http://liusi-group.com/projects/BeautyGAN) |
| [PairedCycleGAN: Asymmetric Style Transfer for Applying and Removing Makeup](https://adoberesearch.ctlprojects.com/wp-content/uploads/2018/04/CVPR2018_Paper3623_Chang.pdf)| CVPR |2018 |
|[Makeup like a superstar: Deep Localized Makeup Transfer Network](https://arxiv.org/abs/1604.07102)| IJCA| 2016| |
|— **arXiv** —|
| [BeautyBank: Encoding Facial Makeup in Latent Space](https://arxiv.org/abs/2411.11231) | arXiv | 2024 | |
| [Gorgeous: Create Your Desired Character Facial Makeup from Any Ideas](https://arxiv.org/abs/2404.13944) | arXiv|2024||
|[Stable-Makeup: When Real-World Makeup Transfer Meets Diffusion Model](https://arxiv.org/pdf/2403.07764.pdf) | arXiv|2024||
| [SARA: Controllable Makeup Transfer with Spatial Alignment and Region-Adaptive Normalization](https://arxiv.org/pdf/2311.16828.pdf)| arXiv | 2023||
| [BeautyREC: Robust, Efficient, and Content-preserving Makeup Transfer](https://arxiv.org/abs/2212.05855) | arXiv | 2022 | [Page](https://arxiv.org/abs/2212.05855) |
| [Semi-parametric Makeup Transfer via Semantic-aware Correspondence](https://arxiv.org/abs/2203.02286)| arXiv | 2022| [code](https://github.com/AnonymScholar/SpMT)|
| [Detailed Region-Adaptive Normalization for Heavy Makeup Transfer](https://arxiv.org/abs/2109.14525)|arXiv|2021|[code](https://github.com/Yueming6568/MDMGAN)|
| [Facial Attribute Transformers for Precise and Robust Makeup Transfer](https://arxiv.org/abs/2104.02894)|arXiv|2021||
| [Cosmetic-Aware Makeup Cleanser](https://arxiv.org/abs/2004.09147)|arXiv|2020| |
| [SLGAN: Style- and Latent-guided Generative Adversarial Network for Desirable Makeup Transfer and Removal](https://arxiv.org/abs/2009.07557)|arXiv|2020| |
| [Local Facial Makeup Transfer via Disentangled Representation](https://arxiv.org/abs/2003.12065)| arXiv|2020 ||
| [Disentangled Makeup Transfer with Generative Adversarial Network](https://arxiv.org/abs/1907.01144)|arXiv|2019|[GitHub](https://github.com/Honlan/DMT)|
| []()| | ||


### Hairstyles Transfer
| Title    | Venue    | Year | Link/ Code     |
|:-------- |:--------:|:--------:|:--------:|
| [K-Hairstyle: A Large-scale Korean hairstyle dataset for virtual hair editing and hairstyle classification](https://arxiv.org/abs/2102.06288)| ICIP | 2021 |[Page](https://psh01087.github.io/K-Hairstyle/)|
| [Barbershop: GAN-based Image Compositing using Segmentation Masks](https://arxiv.org/abs/2106.01505)| SIGGRAPH| 2021|[Page](https://zpdesu.github.io/Barbershop/),[GitHub](https://github.com/ZPdesu/Barbershop)|
| [LOHO: Latent Optimization of Hairstyles via Orthogonalization](https://arxiv.org/abs/2103.03891)| CVPR | 2021 |[GitHub](https://github.com/dukebw/LOHO)|
| [MichiGAN: Multi-Input-Conditioned Hair Image Generation for Portrait Editing](https://arxiv.org/abs/2010.16417)| SIGGRAPH | 2020 |[GitHub](https://github.com/tzt101/MichiGAN)|
| [Intuitive, Interactive Beard and Hair Synthesis with Generative Models](https://openaccess.thecvf.com/content_CVPR_2020/papers/Olszewski_Intuitive_Interactive_Beard_and_Hair_Synthesis_With_Generative_Models_CVPR_2020_paper.pdf)| CVPR | 2020 |[GitHub](https://github.com/kyleolsz/hairgen)|
|[HairNet: Single-View Hair Reconstruction using Convolutional Neural Networks](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yi_Zhou_Single-view_Hair_Reconstruction_ECCV_2018_paper.pdf)| ECCV | 2018 ||
### Datasets

| Name     | Year     | #imgs    | Link     | Note     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
|Color-Pattern-Makeup Datasets | 2021 | 577-5555 | [GitHub](https://github.com/VinAIResearch/CPM#datasets)| w/ [CPM](https://thaoshibe.github.io/CPM), 4 subsets|
|Makeup-Wild| 2020    |   772    | [OneDrive](https://buaaeducn-my.sharepoint.com/personal/jiangwentao_buaa_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fjiangwentao_buaa_edu_cn%2FDocuments%2FMakeup-Wild%2Ezip&parent=%2Fpersonal%2Fjiangwentao_buaa_edu_cn%2FDocuments&originalPath=aHR0cHM6Ly9idWFhZWR1Y24tbXkuc2hhcmVwb2ludC5jb20vOnU6L2cvcGVyc29uYWwvamlhbmd3ZW50YW9fYnVhYV9lZHVfY24vRWNSTmtGMmJGWTlBb21mTWZ5ZF9CMkFCVXlaN1B0U2VZb3FGSktKYlZ2d01IZz9ydGltZT1FM3dBc3RtMjJFZw)|w/ [PSGAN](https://github.com/wtjiang98/PSGAN)|
|LADN Makeup | 2019 | 635 | [Drive](https://drive.google.com/file/d/1gygDQarCOZ7E4qptvTyYF_iZNxsJ4WnI/view)| w/ [LADN](https://github.com/wangguanzhi/LADN)|
|Makeup Transfer | 2018 | 3834 | [Drive](https://drive.google.com/file/d/18UlvYDL6UGZ2rs0yaDsSzoUlw8KI5ABY/view) | w/ [BeautyGAN](http://liusi-group.com/projects/BeautyGAN)|
|Makeup Datasets | 2012-2017 | 200-600|[Pages](http://www.antitza.com/makeup-datasets.html)| 4 subsets|
| FCC Dataset | 2019 | 18425|[GitHub](https://github.com/ssarfraz/SPL/tree/master/FCC_dataset#facial-cosmetic-content-dataset-fcc)|w/ [SPL](https://github.com/ssarfraz/SPL)|

### Applications

##### Research Directions

- **Face Verification/ Attack**:
  - [Protecting Facial Privacy: Generating Adversarial Identity Masks via Style-robust Makeup Transfer](https://arxiv.org/pdf/2203.03121.pdf) | CVPR 2022
  - [Dodging Attack Using Carefully Crafted Natural Makeup](https://arxiv.org/abs/2109.06467) | arXiv 2021
  - [Adv-Makeup: A New Imperceptible and Transferable Attack on Face Recognition](https://arxiv.org/abs/2105.03162) | IJCAI 2021
  - [FM2u-Net: Face Morphological Multi-Branch Network for Makeup-Invariant Face Verification](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_FM2u-Net_Face_Morphological_Multi-Branch_Network_for_Makeup-Invariant_Face_Verification_CVPR_2020_paper.html) | CVPR 2020
  - [Anti-Makeup: Learning A Bi-Level Adversarial Network for Makeup-Invariant Face Verification](https://arxiv.org/abs/1709.03654) | AAAI 2018

- Recommendation System | Beautification:
  - [Face Beautification: Beyond Makeup Transfer](https://arxiv.org/abs/1912.03630) | arXiv 2019
  - [Examples-Rules Guided Deep Neural Network for Makeup Recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/10626) | AAAI 2017

##### Interesting Source Codes

*Source code for demo, web, etc*

- [Face Makeup - Pytorch](https://github.com/zllrunning/face-makeup.PyTorch)
- [Web-based | Makeup Transfer Demo](https://github.com/thaoshibe/Facial-Makeup-Web)
- [Web-based | Facial Beauty Prediction](https://github.com/wanshun123/Facial-Beauty-Prediction)
- [GUI | Makeup Transfer Demo](https://github.com/thaoshibe/GUI-Makeup-Transfer)
