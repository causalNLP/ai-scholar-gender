# AI Scholar Gender

## Overview

This is the (private) repo for AI Scholar (gender project).

## File Structure

```
.
├── README.md
├── code
│   ├── basic_scholar_profiles_1.ipynb
│   ├── basic_scholar_profiles_2.ipynb
│   ├── citation_by_academic_age.ipynb
│   ├── domain_analysis.ipynb
│   ├── gs_scholar_analysis.ipynb
│   ├── organization_clustering.ipynb
│   ├── paper_centric_analysis.ipynb
│   ├── prepare_gs_feature_data.ipynb
│   ├── stylish_title_detector.ipynb
│   └── time_series_clustering.ipynb
└── data
    ├── AIScholars78k_samp1000.csv
    └── Papers100k_samp1000.csv
```

### code
  - `prepare_gs_feature_data.ipynb`: Obtain necessary data features for later analysis.
  - `basic_scholar_profiles_1.ipynb` and `basic_scholar_profiles_2.ipynb`: Analyze basic features in GS scholar profiles.
  - `gs_scholar_analysis.ipynb`: Analyze GS scholar features from different perspectives.
  - `paper_centric_analysis.ipynb`: Perform paper centric analysis corresponding to the section with the same name in the paper.
  - `citation_by_academic_age.ipynb`: Direct analysis of GS scholars' academic age time series.
  - `time_series_clustering.ipynb`: Clustering analysis of GS scholars' academic age time series.
  - `organization_clustering.ipynb`: Clustering analysis of GS scholars' organizations.
  - `domain_analysis.ipynb`: Analyze GS scholars' domain tags.
  - `stylish_title_detector.ipynb`: Stylish title detector implementation and samples of stylish title.
### data
  - `AIScholars78k_samp1000.csv`: 1000 samples of the 78k AI scholar dataset. Full dataset can be accessed from [Google Drive link](https://drive.google.com/file/d/1sfNLH549c0IMp-hojnpmskBftsW5jB7a/view?usp=sharing).
  - `Papers100k_samp1000.csv`: 1000 samples of the 100k paper dataset. Full dataset can be accessed from [Google Drive link](https://drive.google.com/file/d/16cmOlJ-8--7vqIXY-hP0JXtRwqaPoOfh/view?usp=sharing).

Instead, you can use the following commands to download the full dataset:

```bash
pip install gdown
cd <path_to_store_data>
python -c "https://drive.google.com/uc?id=1sfNLH549c0IMp-hojnpmskBftsW5jB7a" # AIScholars78k_samp1000.csv
python -c "https://drive.google.com/uc?id=16cmOlJ-8--7vqIXY-hP0JXtRwqaPoOfh" # Papers100k_samp1000.csv
```