# Image Segmentation Research Repository

A comprehensive collection of reproduced state-of-the-art image segmentation papers and implementations, conducted as part of ongoing research at ****Hong Kong Metropolitan University (HKMU)****.

## 📚 Overview

This repository serves as a centralized platform for reproducing and benchmarking various image segmentation methods from recent literature. Each implementation is organized in its dedicated directory with detailed documentation, making it accessible for researchers to understand, reproduce, and build upon our work.

## 🎯 Research Objectives

- **Reproducibility**: Provide faithful reproductions of state-of-the-art segmentation methods
- **Benchmarking**: Establish consistent evaluation protocols across different approaches
- **Documentation**: Create comprehensive guides for each implementation
- **Knowledge Sharing**: Foster collaboration and accelerate research in the image segmentation community

## 📂 Repository Structure
## 📂 Repository Structure

- image-segmentation-research/
  - OneFormer/ (OneFormer: One Transformer to Rule Universal Image Segmentation)
  - [Future Papers]/ (Additional paper implementations - coming soon)
  - datasets/ (Common datasets directory)
    - ADE20K/
    - Cityscapes/
    - COCO/
  - utils/ (Shared utilities and evaluation metrics)
  - benchmarks/ (Maybe, we are not focusing on it)

## 🚀 Current Implementations

### 1. OneFormer
- **Paper**: [OneFormer: One Transformer to Rule Universal Image Segmentation](https://arxiv.org/abs/2211.06220)
- **Conference**: CVPR 2023
- **Status**: 🟢 In Progress
- **Tasks**: Semantic, Instance, and Panoptic Segmentation
- **Original Repository**: [SHI-Labs/OneFormer](https://github.com/SHI-Labs/OneFormer)

### Coming Soon
- Additional state-of-the-art segmentation methods
- Comparative analysis across different approaches
- Novel architectural improvements

## 🛠️ General Requirements
Each paper implementation may have specific requirements. However, our research environment generally will have below libraries:
- Python  3 (Not 2)
- PyTorch ... Support
- Common libraries: numpy, opencv-python, matplotlib, tensorboard

❗❗❗Specific requirements for each implementation can be found in their respective directories. And we will have seperate virtual environments to test each papers. 

## 📊 Datasets
We primarily work with three major benchmark datasets: 

1. **ADE20K**: Scene parsing dataset with 150 semantic categories
2. **Cityscapes**: Urban street scene understanding
3. **COCO 2017**: Common Objects in Context for instance and panoptic segmentation



## 🔬 Research Methodology

For each paper reproduction:

1. **Implementation**: Faithful reproduction following the original paper
2. **Validation**: Verify results against reported metrics
3. **Documentation**: Detailed setup and training instructions
4. **Analysis**: Performance benchmarking and ablation studies
5. **Extensions**: Potential improvements and modifications

## 📈 Evaluation Metrics

Standard metrics used across implementations:

- **Semantic Segmentation**: mIoU (mean Intersection over Union)
- **Instance Segmentation**: AP (Average Precision)
- **Panoptic Segmentation**: PQ (Panoptic Quality)

## 💻 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/[your-org]/image-segmentation-research.git
cd image-segmentation-research
