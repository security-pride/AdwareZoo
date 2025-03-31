# Adware-Dataset

This repository contains a comprehensive dataset of Android adware samples, designed to facilitate research in mobile security and adware analysis.

## Repository Structure

### SampleHashes/
- Contains hash values (SHA-256 or MD5) for samples from 118 distinct adware families.
- Each family has its own file with the corresponding sample hashes.

### adware_dataset.xlsx
This Excel file provides detailed information about the adware families in our dataset:
  
  #### All Sheet: 
  An expanded version of Table 1 from our paper, including:
  - Sample counts for all 118 adware families
  - Adware tag naming patterns
  - Payload location information
  
  #### Variants Sheet:
  - Detailed descriptions and distinctions for variants found in 6 specific adware families

  #### Schema Sheet:
  - Adware Characterization of 92 Adware familes.

## Usage
This dataset is intended for research purposes in mobile security, particularly in the study of adware behaviors, detection methods, and mitigation strategies. Please refer to our accompanying paper for methodology details and research findings.

@inproceedings{wang2024towards,
  title={Towards Demystifying Android Adware: Dataset and Payload Location},
  author={Wang, Chao and Liu, Tianming and Zhao, Yanjie and Zhang, Lin and Du, Xiaoning and Li, Li and Wang, Haoyu},
  booktitle={Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering Workshops},
  pages={167--175},
  year={2024}
}
