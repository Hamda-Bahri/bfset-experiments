# BFSET Experimental Repository  
Official experimental codebase for the BFSET (Beard Face Set) dataset, developed by Hamda Ben Elbahri and Cognisoft.

This repository provides the full experimental framework used for the BFSET paper, including:
- YOLO training scripts
- Faster R-CNN training scripts
- Annotation verification tools
- Dataset processing utilities
- Reproducible Colab notebooks

The BFSET dataset itself is NOT included. Only the experimental pipeline and code are published.

---

## Repository Structure

```text
bfset-experiments/
├── LICENSE
├── NOTICE
├── README.md
├── DATASET_USAGE_POLICY.md
├── bfset.yaml                     # YOLO dataset path configuration
├── notebooks/
│   ├── 01_yolo_training.ipynb     # YOLO training pipeline
│   └── 02_faster_rcnn.ipynb       # Faster R-CNN torch pipeline
└── src/
    ├── dataset_split.py           # Train/val/test splitting utilities
    ├── check_labels.py            # YOLO annotation visual validation
    ├── train_yolo.py              # YOLO experiment code
    └── train_faster_rcnn.py       # Faster R-CNN experiment code
---

## Dataset Availability

The BFSET dataset is proprietary and will not be published before article acceptance.

A release may occur:
1. After acceptance of the BFSET research paper, or  
2. Under signed research agreement (NDA) with Cognisoft.

Details on the dataset structure, annotation pipeline, and statistics are provided in the article.

---

## Running Experiments (Colab)

Clone repository:

```bash
!git clone https://github.com/<username>/bfset-experiments.git
