# Object-Detection-in-Adverse-Weather


# Datasets & Methods by Section

A curated list of datasets and methods used across the project’s sections. Each entry includes the paper citation and, when available, code or dataset links.

---

## 1) Image Dehazing (RGB)

### Datasets
- **I-HAZE** — *A dehazing benchmark with real hazy and haze-free indoor images.*  
  C. Ancuti, C.O. Ancuti, R. Timofte, C. De Vleeschouwer. **ACIVS 2018**.  
  Dataset: https://data.vision.ee.ethz.ch/cvl/ntire18/i-haze/ • Paper: https://doi.org/10.1007/978-3-030-01449-0_52

- **O-HAZE** — *Real hazy and haze-free outdoor image pairs; NTIRE 2018 challenge dataset.*  
  C.O. Ancuti, C. Ancuti, R. Timofte, C. De Vleeschouwer. **CVPRW 2018**.  
  Dataset: https://data.vision.ee.ethz.ch/cvl/ntire18/o-haze/ • Paper (PDF): https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w13/Ancuti_O-HAZE_A_Dehazing_CVPR_2018_paper.pdf

- **NH-HAZE / NH-HAZE2** — *Non-homogeneous real haze with GT pairs; NTIRE 2020/2021.*  
  C.O. Ancuti, C. Ancuti, R. Timofte. **CVPRW 2020/2021**.  
  Dataset: https://data.vision.ee.ethz.ch/cvl/ntire20/nh-haze/ • Paper (PDF): https://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Ancuti_NH-HAZE_An_Image_Dehazing_Benchmark_With_Non-Homogeneous_Hazy_and_Haze-Free_CVPRW_2020_paper.pdf

### Methods
- **GCANet** — *Gated Context Aggregation Network for Image Dehazing and Deraining.*  
  D. Chen, M. He, Q. Fan, et al. **WACV 2019**.  
  Code: https://github.com/cddlyf/GCANet • Paper: https://paperswithcode.com/paper/gated-context-aggregation-network-for-image

- **FFA-Net** — *Feature Fusion Attention Network for Single Image Dehazing.*  
  X. Qin, Z. Wang, Y. Bai, X. Xie, H. Jia. **AAAI 2020**.  
  Code: https://github.com/zhilin007/FFA-Net • Paper: https://ojs.aaai.org/index.php/AAAI/article/view/6865

- **DA-Dehazing** — *Domain Adaptation for Image Dehazing.*  
  Y. Shao, L. Li, W. Ren, C. Gao, N. Sang. **CVPR 2020**.  
  Code: https://github.com/HUSTSYJ/DA_dahazing • Paper: https://openaccess.thecvf.com/content_CVPR_2020/papers/Shao_Domain_Adaptation_for_Image_Dehazing_CVPR_2020_paper.pdf

- **Two-Branch (Non-Homogeneous) Dehazing via Ensemble Learning**  
  Y. Yu, H. Liu, M. Fu, J. Chen, X. Wang, K. Wang. **CVPRW (NTIRE) 2021**.  
  Code: https://github.com/liuh127/NTIRE-2021-Dehazing-Two-branch • Paper: https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Yu_A_Two-Branch_Neural_Network_for_Non-Homogeneous_Dehazing_via_Ensemble_Learning_CVPRW_2021_paper.pdf

- **FD-GAN** — *GANs with Fusion-Discriminator for Single Image Dehazing.*  
  Y. Dong, Y. Liu, H. Zhang, S. Chen, Y. Qiao. **AAAI 2020**.  
  Code: https://github.com/WeilanAnnn/FD-GAN

- **RefineDNet** — *Weakly Supervised Refinement Framework for Dehazing.*  
  S. Zhao, L. Zhang, Y. Shen, Y. Zhou. **IEEE TIP 2021**.  
  Code: https://github.com/xiaofeng94/RefineDNet-for-dehazing • Paper: https://doi.org/10.1109/TIP.2021.3060873

- **Wavelet U-Net + CAT** — *Wavelet U-Net and chromatic adaptation transform for dehazing.*  
  H.-H. Yang, Y. Fu. **ICIP 2019**.

---

## 2) Thermal Image Dehazing

### Datasets
- **M3FD (Multi-scenario Multi-modality for Fusion Detection)** — IR+RGB benchmark widely used for thermal/visible fusion and related TIR tasks.  
  J. Liu, X. Fan, Z. Huang, et al. **CVPR 2022**.  
  Paper: CVPR 2022 • Code (TarDAL repo with data links): https://github.com/JinyuanLiu-CV/TarDAL

### Methods
- **Mamba-based Thermal Image Dehazing**  
  S.A. Hovhannisyan. *Mathematical Problems of Computer Science*, 2024.

---

## 3) Thermal Image Enhancement (Single Images)

### Datasets
- **LTIR** — *Thermal object tracking benchmark; 20 sequences with annotations.*  
  A. Berg, J. Ahlberg, M. Felsberg. **AVSS 2015**.  
  Dataset: https://www.cvl.isy.liu.se/research/datasets/ltir/version1.0/

- **CVC-14** — *Visible–FIR pedestrian sequences (day/night).*  
  A. González et al. **CVPRW 2016** (dataset page by CVC).  
  Dataset: https://adas.cvc.uab.es/elektra/enigma-portfolio/cvc-14-visible-fir-day-night-pedestrian-sequence-dataset/

- **Solar PV Hotspots/Snail Trails** — *Thermal characterization of PV failures.*  
  E. Alfaro-Mejía et al. **Data in Brief 2019**.  
  Article: https://www.sciencedirect.com/science/article/pii/S2352340919307966

- **Breast Thermography (DMR-IR / related open datasets)** — *Thermal images for benign/malignant analysis.*  
  Examples:  
  – Mendeley Breast Thermography (2021–2022): https://data.mendeley.com/datasets/mhrt4svjxc  
  – DMR-IR (various mirrors): e.g., Kaggle https://www.kaggle.com/datasets/asdeepak/thermal-images-for-breast-cancer-diagnosis-dmrir

### Methods
- **Brightness-Biased CNN (BBCNN)** — *Thermal image enhancement via CNN.*  
  K. Lee, J. Lee, J. Lee, S. Hwang, S. Lee. **IEEE Access 2017**.

- **Single IR Image Enhancement (FCN)**  
  X. Kuang, L. Huang, et al. **Neurocomputing 2019**.

- **TE-GAN (Thermal Enhancement GAN) for Pedestrian Detection**  
  M.A. Marnissi, H. Fradi, A. Sahbani, N.E. Ben Amara. **ICPR 2021**.  
  Code: https://github.com/AmineMarnissi/TE-GAN

- **AGCWD** — *Adaptive Gamma Correction with Weighting Distribution (classical).*  
  S.-C. Huang, F.-C. Cheng, Y.-S. Chiu. **IEEE TIP 2013**.  
  Implementations: C++ https://github.com/bqm1111/AGCWD • MATLAB https://github.com/mss3331/AGCWD • Python https://github.com/qyou/AGCWD

- **WTHE** — *Weighted Thresholded Histogram Equalization (classical).*  
  Implementation: https://github.com/Mamdasn/imWeightedThresholdedheq

---

## 4) Thermal Video Enhancement

### Datasets
- **BIRDSAI** — *Aerial TIR videos (nighttime) of animals & humans.*  
  E. Bondi, M. Hamilton, et al. **WACV 2020**.  
  Info/Download: https://sites.google.com/view/elizabethbondi/dataset

- **CAMEL** — *Visual–IR pairs for multi-object detection & tracking.*  
  E. Gebhardt, M. Wolf. **AVSS 2018**.  
  Dataset portal: https://camel.ece.gatech.edu/

- **FLIR ADAS** — *Thermal frames with annotations for ADAS.*  
  Dataset: https://oem.flir.com/solutions/automotive/adas-dataset-form/

### Methods (used for comparison/related)
- **Shift-Net (Grouped Spatio-Temporal Shift)** — general video restoration baseline.  
  S. Li, X. Zhou, et al. **CVPR 2023**.  
  Code: https://github.com/dasongli1/Shift-Net

- **AverNet (All-in-one Video Restoration for Time-varying Degradations)** — general video restoration.  
  H. Zhao, L. Tian, et al. **NeurIPS 2024 (poster)**.  
  Project blurb: https://neurips.cc/virtual/2024/session/108362

- **IE-GAN / BBCNN** — thermal enhancement baselines frequently compared in TIR literature (see TE-GAN/BBCNN above).

---

## 5) Thermal → RGB Translation / Colorization

### Datasets
- **KAIST Multispectral Pedestrian** — *Aligned RGB+TIR frames used broadly for cross-modal tasks.*  
  S. Hwang, J. Park, N. Kim, Y. Choi, I.S. Kweon. **CVPR 2015**.  
  Dataset: http://multispectral.kaist.ac.kr/

### General Unpaired I2I Methods (often used/adapted for TIR↔RGB)
- **CycleGAN** — J.-Y. Zhu, T. Park, P. Isola, A.A. Efros. **ICCV 2017**.  
  Code: https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix • Project: https://junyanz.github.io/CycleGAN/

- **UNIT** — M.-Y. Liu, T. Breuel, J. Kautz. **NeurIPS 2017**.  
  Code: https://github.com/mingyuliutw/UNIT

- **DRIT / DRIT++** — H.-Y. Lee, H.-Y. Tseng, J.-B. Huang, M.K. Singh, M.-H. Yang. **ECCV 2018**, **arXiv 2019**.  
  Code: https://github.com/HsinYingLee/DRIT

- **U-GAT-IT** — J. Kim, M. Kim, H. Kang, K. Lee. **ICLR 2020 (OpenReview)**.  
  Code (PyTorch): https://github.com/znxlwm/UGATIT-pytorch

### TIR-specific Colorization
- **PearlGAN** — nighttime TIR → daytime color for traffic scenes.  
  Repo: https://github.com/FuyaLuo/PearlGAN

- **MornGAN** — thermal colorization with memory-guided collaborative attention.  
  Repo: https://github.com/FuyaLuo/MornGAN

- **FoalGAN** — feedback-based object appearance learning for nighttime TIR colorization.  
  Repo: https://github.com/FuyaLuo/FoalGAN

- **StawGAN** — structural-aware GAN for nighttime TIR translation.  
  Project page: https://ispamm.github.io/StawGAN-page/
