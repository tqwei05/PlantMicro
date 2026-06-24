# Benchmarking Vision-Language Models for Microscopic Plant Image Understanding

Official repository for the paper: [Benchmarking Vision-Language Models for Microscopic Plant Image Understanding](https://arxiv.org/abs/2606.22497)


## Introduction
Microscopic imaging is essential for studying plant biology and pathology at cellular and subcellular levels, yet VLM benchmarks have largely focused on macroscopic plant images. To address this gap, we present PlantMicro, a benchmark for evaluating VLMs on microscopic plant imagery. PlantMicro contains over 5,000 images and more than 9,000 VQA pairs, covering diverse hosts, biological domains, and imaging modalities.

<p align="center">
  <img src="figures/main_fig.png" width="80%">
</p>

### Data Collection and Curation
We collect plant microscopy datasets from peer-reviewed publications and open data repositories, covering diverse biological domains such as mycology, botany, and nematology, as well as imaging modalities including light, fluorescence, and electron microscopy. We prioritize datasets openly available for research use and contact corresponding authors when additional permission is required.
To ensure consistency, all datasets are standardized under a unified curation protocol. Images from different formats and file structures are reorganized, assigned unique identifiers, and converted to JPEG while preserving their original resolution.
<div align="center">
  <img src="figures/plantmicro_pipeline.png" width="80%">
</div>

### Dataset Access
PlantMicro is accessible through:
[Google Drive](https://drive.google.com/file/d/1lAL4rVOw2gcRDQPasd12VSnBhW6LS6Hp/view?usp=drive_link)
