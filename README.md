# Awesome-Continual-Learning-for-Medical-Image-Analysis
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Abstract
In the dynamic realm of practical clinical scenarios, Continual Learning (CL) has gained increasing interest in medical image analysis due to its potential to address major challenges associated with data privacy, model adaptability, memory inefficiency, prediction robustness and detection accuracy. In general, the primary challenge in adapting and advancing CL remains catastrophic forgetting. Beyond this challenge, recent years have witnessed a growing body of work that expands our comprehension and application of continual learning in the medical domain, highlighting its practical significance and intricacy. In this paper, we present an in-depth and up-to-date review of the application of CL in medical image analysis. Our discussion delves into the strategies employed to address specific tasks within the medical domain, categorizing existing CL methods into three settings: Task-Incremental Learning, Class-Incremental Learning, and Domain-Incremental Learning. These settings are further subdivided based on representative learning strategies, allowing us to assess their strengths and weaknesses in the context of various medical scenarios. By establishing a correlation between each medical challenge and the corresponding insights provided by CL, we provide a comprehensive understanding of the potential impact of these techniques. To enhance the utility of our review, we provide an overview of the commonly used benchmark medical datasets and evaluation metrics in the field. Through a comprehensive comparison, we discuss promising future directions for the application of CL in medical image analysis. 

## Note
We welcome all researchers to contribute to this repository. If you have any questions or suggestions, or if you think your paper fits our framework and should be added to the survey, feel free to contact us through e-mail (xinyaowu@link.cuhk.edu.hk / jackxz@link.cuhk.edu.hk) or create an issue in this repo.

If you find our paper or this resource helpful, please consider citing: 
```
@article{wu2024continual,
  title={Continual learning in medical image analysis: A survey},
  author={Wu, Xinyao and Xu, Zhe and Tong, Raymond Kai-yu},
  journal={Computers in Biology and Medicine},
  volume={182},
  pages={109206},
  year={2024},
  publisher={Elsevier}
}
```


## CLASS-INCREMENTAL LEARNING (CIL)
Class-Incremental Learning (CIL) aims to acquire a continuous data stream with new classes, where no task identities are provided in testing. Its replay-based strategies to resist forgetting lead to following medical-area challenges and troubleshooting.

### Medical Data Exemplar Selection
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td><a href="https://arxiv.org/abs/2304.14572">SCOPE: Structural Continuity Preservation for Medical Image Segmentation</a></td>
        <td>2023</td>
        <td>CVPR</td>
        <td>None</td>
    </tr>
    <tr>
        <td><a href="https://arxiv.org/pdf/2305.05738.pdf">DOCTOR: A Multi-Disease Detection Continual Learning Framework Based on Wearable Medical Sensors</a></td>
        <td>2023</td>
        <td>ACM</td>
        <td>None</td>
    </tr>
    <tr>
        <td><a href="https://ieeexplore.ieee.org/abstract/document/10227350">Continual Nuclei Segmentation via Prototype-wise Relation Distillation and Contrastive Learning</a></td>
        <td>2023</td>
        <td>TMI</td>
        <td><a href="https://github.com/zzw-szu/CoNuSeg">GitHub</a></td>
    </tr>
    <tr>
            <td><a href="https://arxiv.org/pdf/2303.13752.pdf">Leveraging Old Knowledge to Continually Learn New Classes in Medical Images</a></td>
            <td>2023</td>
            <td>CVPR</td>
            <td><a href="https://github.com/EvelynChee/LO2LN.git">GitHub</a></td>
    </tr>
    <tbody>
</table>

### Memory and Computation Inefficiency
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td><a href="https://arxiv.org/pdf/2010.11008">What is wrong with continual learning in medical image segmentation?</a></td>
        <td>2020</td>
        <td>Preprint</td>
        <td>None</td>
    </tr>
    <tr>
        <td><a href="https://www.nature.com/articles/s41467-021-25858-z">Dynamic memory to alleviate catastrophic forgetting in continual learning with medical imaging</a></td>
        <td>2021</td>
        <td>Nature Communication</td>
        <td><a href="https://github.com/cirmuw/dynamicmemory">GitHub</a></td>
    </tr>
    <tr>
        <td><a href="https://arxiv.org/abs/2307.12471">Neuromorphic Neuromodulation: Towards the next generation of on-device AI-revolution in electroceuticals</a></td>
        <td>2023</td>
        <td>Preprint</td>
        <td>None</td>
    </tr>
    <tbody>
</table>

### Medical Data Overlapping Classes
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/pdf/2307.12045.pdf">Revisiting Distillation for Continual Learning on Visual Question Localized-Answering in Robotic Surgery</a></td>
            <td>2023</td>
            <td>MICCAI</td>
            <td><a href="https://github.com/longbai1006/CS-VQLA">GitHub</a></td>
        </tr>
    <tbody>
</table>

### Medical data low-quality generation
| Paper Title | Year | Conference/Journal | Code 
|-----------------------------------------------------------------------------------------------------|------|-----------------|-----------------------------------------------------------------------------------------|
| [Hybrid Neural Diffeomorphic Flow for Shape Representation and Generation via Triplane](https://arxiv.org/pdf/2307.01957.pdf) | 2023 | Preprint | None        |
| [Generative appearance replay for continual unsupervised domain adaptation](https://arxiv.org/pdf/2301.01211.pdf) | 2023 | Preprint | None        |
| [Universal adversarial perturbations for multiple classification tasks with quantum classifiers](https://arxiv.org/pdf/2306.11974.pdf) | 2023 | Preprint | None        |
| [Conditional Diffusion Replay for Continual Learning in Medical Settings](https://openreview.net/pdf?id=avmAZiWarU) | 2023 | ICML | None        |
| [Rethinking exemplars for continual semantic segmentation in endoscopy scenes: Entropy-based mini-batch pseudo-replay](https://browse.arxiv.org/pdf/2308.14100.pdf) | 2023 | CBM | None |
| [Continual-GEN: Continual Group Ensembling for Domain-agnostic Skin Lesion Classification](https://link.springer.com/chapter/10.1007/978-3-031-47401-9_1) | 2023 | MICCAI | [GitHub](https://github.com/nourhanb/Continual-GEN) |


### Other Medical Deep Learning Frameworks
| Paper Title | Year | Conference/Journal | Code 
|-----------------------------------------------------------------------------------------------------|------|-----------------|-----------------------------------------------------------------------------------------|
| [Accelerating Batch Active Learning Using Continual Learning Techniques](https://www.researchgate.net/publication/370687872_Accelerating_Batch_Active_Learning_Using_Continual_Learning_Techniques) | 2023 | Preprint | None        |
| [A framework for dynamically training and adapting deep reinforcement learning models to different, low-compute, and continuously changing radiology deployment environments](https://arxiv.org/pdf/2306.05310.pdf) | 2023 | Preprint | None        |

## TASK-INCREMENTAL LEARNING (TIL)
Task-Incremental Learning (TIL) aims to learn a sequence of different tasks, where task identities are provided in both training and testing stages. Its optimization strategies observe challenges in medical settings.

### Model Versatility    
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/pdf/2303.06580.pdf">Towards General Purpose Medical AI: Continual Learning Medical Foundation Model</a></td>
            <td>2023</td>
            <td>Preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2301.00785.pdf">CLIP-Driven Universal Model for Organ Segmentation and Tumor Detection</a></td>
            <td>2023</td>
            <td>ICCV</td>
            <td><a href="https://github.com/ljwztc/CLIP-Driven-Universal-Model">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2306.02416.pdf">Training Like a Medical Resident: Universal Medical Image Segmentation via Context Prior Learning</a></td>
            <td>2023</td>
            <td>Preprint</td>
            <td><a href="https://github.com/yhygao/universal-medical-image-segmentation">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2310.02000.pdf">MUSCLE: Multi-task Self-supervised Continual Learning to Pre-train Deep Models for X-ray Images of Multiple Body Parts</a></td>
            <td>2023</td>
            <td>Preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2304.09042.pdf">Adapter Learning in Pretrained Feature Extractor for Continual Learning of Diseases</a></td>
            <td>2023</td>
            <td>MICCAI</td>
            <td><a href="https://github.com/GiantJun/CL_Pytorch">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2302.00162">Continual Segment: Towards a Single, Unified and Non-forgetting Continual Segmentation Model of 143 Whole-body Organs in CT Scans</a></td>
            <td>2023</td>
            <td>ICCV</td>
            <td>None</td>
        </tr>
    <tbody>
</table>

### Lack of Annotated Data
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/pdf/2311.17597.pdf">Continual Self-supervised Learning: Towards Universal Multi-modal Medical Data Representation Learning</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td><a href="https://github.com/yeerwen/MedCoSS">GitHub</a></td>
        </tr>
      <tbody>
</table>

### Knowledge Conflict
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/pdf/2302.00162.pdf">Continual Segment: Towards a Single, Unified and Non-forgetting Continual Segmentation Model of 143 Whole-body Organs in CT Scans</a></td>
            <td>2023</td>
            <td>ICCV</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2203.02100.pdf">Learning Incrementally to Segment Multiple Organs in a CT Image</a></td>
            <td>2022</td>
            <td>MICCAI</td>
            <td>None</td>
        </tr>
    <tbody>
</table>

## DOMAIN-INCREMENTAL LEARNING (DIL)
Domain-Incremental Learning (DIL) aims to learn a consistent task across diverse domains. Its regularization- and distillation-based strategies give rise to corresponding challenges in the medical area. 

### Generic Feature Selection
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
        <td><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10078916">S3R: Shape and Semantics-based Selective Regularization for Explainable Continual Segmentation across Multiple Sites</a></td>
        <td>2023</td>
        <td>Transactions on Medical Imaging</td>
        <td><a href="https://github.com/jingyzhang/S3R">GitHub</a></td>
        </tr>
        <tr>
        <td><a href="https://link.springer.com/chapter/10.1007/978-3-031-45857-6_14">A Continual Learning Approach for Cross-Domain White Blood Cell Classification</a></td>
        <td>2023</td>
        <td>MICCAI</td>
        <td><a href="https://github.com/marrlab/UACL">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2306.00988.pdf">Continual Learning for Abdominal Multi-Organ and Tumor Segmentation</a></td>
            <td>2023</td>
            <td>MICCAI</td>
            <td><a href="https://github.com/MrGiovanni/ContinualLearning">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2305.19404.pdf">Incremental Learning for Heterogeneous Structure Segmentation in Brain Tumor MRI</a></td>
            <td>2023</td>
            <td>MICCAI</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://pubmed.ncbi.nlm.nih.gov/38401270/">Boosting knowledge diversity, accuracy, and stability via tri-enhanced distillation for domain continual medical image segmentation</a></td>
            <td>2024</td>
            <td>Medical Image Analysis</td>
            <td>None</td>
        </tr>
    <tbody>
</table>

### Cross-domain Generalizability
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/abs/2308.13324">ConSlide: Asynchronous Hierarchical Interaction Transformer with Breakup-Reorganize Rehearsal for Continual Whole Slide Image Analysis</a></td>
            <td>2023</td>
            <td>MICCAI</td>
            <td><a href="https://github.com/HKU-MedAI/ConSlide">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/abs/2305.11012">SDC-UDA: Volumetric Unsupervised Domain Adaptation Framework for Slice-Direction Continuous Cross-Modality Medical Image Segmentation</a></td>
            <td>2023</td>
            <td>CVPR</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2309.00688.pdf">Jointly Exploring Client Drift and Catastrophic Forgetting in Dynamic Learning</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2211.04862.pdf">Domain-incremental Cardiac Image Segmentation with Style-oriented Replay and Domain-sensitive Feature Whitening</a></td>
            <td>2022</td>
            <td>TMI</td>
            <td>None</td>
        </tr>
    <tbody>
</table>

### Imbalanced Datasets
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/pdf/2307.12625.pdf">De-confounding Representation Learning for Counterfactual Inference on Continuous Treatment via Generative Adversarial Network</a></td>
            <td>2023</td>
            <td>Data Mining and Knowledge Discovery</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2402.16664.pdf">LLM-Assisted Multi-Teacher Continual Learning for Visual Question Answering in Robotic Surgery</a></td>
            <td>2024</td>
            <td>ICRA</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2407.08609">BiasPruner: Debiased Continual Learning for Medical Image Classification</a></td>
            <td>2024</td>
            <td>MICCAI</td>
            <td><a href="https://github.com/nourhanb/BiasPruner">GitHub</a></td>
        </tr>
    <tbody>
</table>

### Data Scarcity
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/abs/2306.14020">Individualized Dosing Dynamics via Neural Eigen Decomposition</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2304.07025.pdf">Continuous time recurrent neural networks: overview and application to forecasting blood glucose in the intensive care unit</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td><a href="http://www.github.com/oizin/irregular-ts">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2307.05920.pdf">Unified Medical Image-Text-Label Contrastive Learning With Continuous Prompt</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2402.05860.pdf">Privacy-Preserving Synthetic Continual Semantic Segmentation for Robotic Surgery</a></td>
            <td>2024</td>
            <td>IEEE TRANSACTIONS ON MEDICAL IMAGING</td>
            <td><a href="https://github.com/XuMengyaAmy/Synthetic_CAT_SD">GitHub</a></td>
        </tr>
    <tbody>
</table>

### Privacy Protection
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:20%">
    <col style="width:10%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/abs/2109.04197.pdf">A distillation-based approach integrating continual learning and federated learning for pervasive services</a></td>
            <td>2021</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2204.13591.pdf">Continual Learning for Peer-to-Peer Federated Learning: A Study on Automated Brain Metastasis Identification</a></td>
            <td>2022</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2204.13591.pdf">Deep Anatomical Federated Network (Dafne): an open client/server framework for the continuous collaborative improvement of deep-learning-based medical image segmentation</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2111.13394.pdf">Non-IID data and Continual Learning processes in Federated Learning: A long road ahead</a></td>
            <td>2023</td>
            <td>preprint</td>
            <td>None</td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2311.00548.pdf">Continual atlas-based segmentation of prostate MRI</a></td>
            <td>2024</td>
            <td>WACV</td>
            <td><a href="https://github.com/MECLabTUDA/Atlas-Replay">GitHub</a></td>
        </tr>
    <tbody>
</table>

## CONTINUAL LEARNING BASELINES
Finetune is typically employed as the baseline model without incorporating any mechanisms to mitigate forgetting. Others are listed below, based on the tasks or CL techniques applied.
<table>
  <colgroup>
    <col style="width:60%">
    <col style="width:10%">
    <col style="width:30%">
  </colgroup>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Technique/Task</th>
      <th>Code</th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td><a href="https://arxiv.org/abs/1611.07725">iCaRL: Incremental Classifier and Representation Learning</a></td>
            <td>Replay-based</td>
            <td><a href="http://www.github.com/srebuffi/iCaRL">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/abs/1706.08840">Gradient Episodic Memory for Continual Learning</a></td>
            <td>Replay-based</td>
            <td><a href="https://github.com/facebookresearch/GradientEpisodicMemory">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/abs/1612.00796">Overcoming catastrophic forgetting in neural networks</a></td>
            <td>Regularization-based</td>
            <td><a href="https://github.com/shivamsaboo17/Overcoming-Catastrophic-forgetting-in-Neural-Networks">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/abs/1704.01920">Encoder Based Lifelong Learning</a></td>
            <td>Regularization-based</td>
            <td><a href="https://github.com/rahafaljundi/Encoder-Based-Lifelong-learning">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/1907.13372.pdf">Incremental Learning Techniques for Semantic Segmentation</a></td>
            <td>CSS</td>
            <td><a href="https://github.com/LTTM/IL-SemSegm">GitHub</a></td>
        </tr>
        <tr>
            <td><a href="https://arxiv.org/pdf/2002.00718.pdf">Modeling the Background for Incremental Learning in Semantic Segmentation</a></td>
            <td>CSS</td>
            <td><a href="https://github.com/fcdl94/MiB">GitHub</a></td>
        </tr>
    <tbody>
</table>
---





