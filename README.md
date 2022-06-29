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

- code
  - `prepare_gs_feature_data.ipynb`: Obtain necessary data features for later analysis.
  - `basic_scholar_profiles_1.ipynb` and `basic_scholar_profiles_2.ipynb`: Analyze basic features in GS scholar profiles.
  - `gs_scholar_analysis.ipynb`: Analyze GS scholar features from different perspectives.
  - `paper_centric_analysis.ipynb`: Perform paper centric analysis corresponding to the section with the same name in the paper.
  - `citation_by_academic_age.ipynb`: Direct analysis of GS scholars' academic age time series.
  - `time_series_clustering.ipynb`: Clustering analysis of GS scholars' academic age time series.
  - `organization_clustering.ipynb`: Clustering analysis of GS scholars' organizations.
  - `domain_analysis.ipynb`: Analyze GS scholars' domain tags.
  - `stylish_title_detector.ipynb`: Stylish title detector implementation and samples of stylish title.
- data
  - `AIScholars78k_samp1000.csv`: 1000 samples of the 78k AI scholar dataset.
  - `Papers100k_samp1000.csv`: 1000 samples of the 100k paper dataset.