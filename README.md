# A survey of Transformer applications for histopathological image analysis: New developments and future directions

Transformers have been widely used in many computer vision challenges and have shown the capability of producing better results than convolutional neural networks (CNNs). Taking advantage of capturing long-range contextual information and learning more complex relations in the image data, Transformers have been used and applied to histopathological image processing tasks. In this survey, we make an effort to present a thorough analysis of the uses of Transformers in histopathological image analysis, covering several topics, from the newly built Transformer models to unresolved challenges. To be more precise, we first begin by outlining the fundamental principles of the attention mechanism included in Transformer models and other key frameworks. Second, we analyze Transformer-based applications in the histopathological imaging domain and provide a thorough evaluation of more than 100 research publications across different downstream tasks to cover the most recent innovations, including survival analysis and prediction, segmentation, classification, detection, and representation. [(Paper link)](https://doi.org/10.1186/s12938-023-01157-0)

# Current Transformer applications in histopathological image analysis, as surveyed in this research work

![Figure_2](https://github.com/S-domain/Survey-Paper/assets/104261511/89b626c9-cd2f-450f-b34b-03f862e03736)

# Transformer-based Hispathological Imaging Paper Publication Statistics
![figure_7](https://github.com/S-domain/Survey-Paper/assets/104261511/e9dfee3a-cc68-4cb8-aa4e-1b9ce79f0728)

# Recently Transformer-based architectures for histopathological image analysis
![figure_6](https://github.com/S-domain/Survey-Paper/assets/104261511/c8d9d41a-6d62-4b7f-a355-a670a68bbfce)

# Literature Reviews of Vision Transformers for Histopathological Image Analysis 

| Date    | Model     |Title                                                                                                                                                      | Code |
| :---:   | :---:     | :---:                                                                                                                                                     | :---:|
| 202309  | SSTCL    | Self-Supervised Triplet Contrastive Learning for Classifying Endometrial Histopathological Images [(Paper)](https://ieeexplore.ieee.org/document/10247346) | None |
| 202304 | DHUnet    | DHUnet: Dual-branch hierarchical global–local fusion network for whole slide image segmentation [(Paper)](https://doi.org/10.1016/j.bspc.2023.104976)      | [Code](https://github.com/pengsl-lab/DHUnet)|


# Histopathological Image Datasets

| Year    | Dataset     | Tissue                                                                                                                                                   | Link|
| :---:   | :---:     | :---:                                                                                                                                                     | :---:|
| 2020  | HE-GHI-DS   | Gastric | [Link](https://data.mendeley.com/datasets/thgf23xgy7/2) |  
| 2021  | TCGA-KIRP  | Kidney| [Link](https://dataset.chenli.group/) |
| 2016 | KCCH  | Colorectal | [Link](https://zenodo.org/record/53169#.Y7Gf4hpfiUk) |
| 2021  | MHIST | Colorectal | [Link](https://bmirds.github.io/MHIST/) |
| 2021  | GasHisSDB | Gastric | [Link](https://gitee.com/neuhwm/GasHisSDB) |
| 2021  | UniToPatho | Colorectal | [Link](https://ieee-dataport.org/open-access/unitopatho) |
| 2020  | TissueNet | Colorectal | [Link](https://www.drivendata.org/competitions/67/competition-cervical-biopsy/page/254/) |
| 2018  | NCT-CRC-HE| Colorectal | [Link](https://zenodo.org/record/1214456#.Y7JSaRpfiU) |
| 2016  | CRC| Colorectal | [Link](https://zenodo.org/record/53169#.Y-K8ABpfiUm) |
| 2021  | TCGA-RCC | Kidney | [Link](https://gdc.cancer.gov/) |
| 2021  | TCGA-NSCLC | Lung | [Link](https://gdc.cancer.gov/) |
| 2021  | MIDOG | Breast | [Link](https://zenodo.org/record/4643381#.Y7MWzhpfiUk) |
| 2016  | BreakHis | Breast | [Link](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/) |
| 2020  | IDC | Breast | [Link](https://data.mendeley.com/datasets/w7jjcx7gj6/1) |
| 2021  | UC | Endometrial | [Link](https://figshare.com/articles/dataset/A_histopathological_image_dataset_for_endometrial_disease_diagnosis/7306361/2) |
| 2016  | CAMELYON16 | Breast | [Link](https://camelyon16.grand-challenge.org/Home/) |
| 2018  | BACH | Breast | [Link](https://iciar2018-challenge.grand-challenge.org/Home/) |
| 2015  | GlaS | Colon | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest) |
| 2018  | Pcam | Lymph Node Metastatic | [Link](https://github.com/basveeling/pcam) |
| 2019  | Gleason 2019 | Prostate | [Link](https://gleason2019.grand-challenge.org/Home/) |
| 2019  | NCT-CRC-HE | Colon | [Link](http://dx.doi.org/10.5281/zenodo.1214456) |
| 2019  | PAIP-2019 | Liver | [Link](https://paip2019.grand-challenge.org/Home/) |
| 2020  | MoNuSAC | Lung, breast, etc | [Link](https://monusac-2020.grand-challenge.org/Home/) |
| 2020  | PANDA | Prostate | [Link](https://www.kaggle.com/c/prostate-cancer-grade-assessment/overview) |
| 2021  | MIDOG-2021 | Breast | [Link](https://imig.science/midog/) |
| 2021  | NuCLS | Breast | [Link](https://nucls.grand-challenge.org/NuCLS) |
| 2021  | PAIP-2021 | Colon, prostate | [Link](https://paip2021.grand-challenge.org/Home/) |
| 2008  | TCGA | Different Tissues | [Link](https://gdc.cancer.gov/) |
| 2019  | PanNuke | 19 tissue types | [Link](https://jgamper.github.io/PanNukeDataset/) |
| 2020  | NuClick | Cell | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/nuclick/) |
| 2020  | CRC-TP | 7 tissues types | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/crc-tp) |
| 2018  | HER2 scoring | Breast | [Link](https://warwick.ac.uk/fac/cross_fac/tia/data/her2contest/) |
| 2017  | CAMELYON17 | Breast | [Link](https://camelyon17.grand-challenge.org/Home/) |
| 2017  | Nucleiseg | 7 Organs | [Link](https://nucleisegmentationbenchmark.weebly.com/) |



#   Contact
mecusbans@gmail.com

#   Acknowledgments
The authors thank the Chongqing University for their support.


# Cite this article
Atabansi, C.C., Nie, J., Liu, H. et al. A survey of Transformer applications for histopathological image analysis: New developments and future directions. BioMed Eng OnLine 22, 96 (2023). https://doi.org/10.1186/s12938-023-01157-0
