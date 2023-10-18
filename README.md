# Continual-Learning-Medical-Adaptation

## Abstract
Continuous Learning (CL) has gained increasing interest in medical-field settings due to its potential to address major challenges associated with data privacy, memory inefficiency, prediction robustness and detection accuracy. Various computation models, including Generation Networks, Federated Learning, Reinforcement Learning and Active Learning, have adapted CL to enhance their overall performance, leveraging the continuous nature of medical datasets. However, the primary challenge in adapting and advancing CL remains the issue of catastrophic forgetting. As a result, a comprehensive review evaluating the effectiveness of different types of CL tackling medical tasks can be of interest. In this paper, we provide an in-depth and up-to-date review on recent applications of Continual Learning in the medical discipline and an extensive discussion on their strategies to address individual tasks within the medical domain. Specifically, we categorize existing CL into two settings: Task-Incremental Learning and Class-Incremental Learning. Then we further divide them into subcategories based on their computational techniques and learning strategies. Individually, we discuss their strengths and weaknesses associated with downstream medical-area settings, and establish a correlation between each medical challenge and the corresponding insights provided by CL. In addition, we provide an overview of the benchmark medical datasets and evaluation metrics that are commonly used by researchers in the field. After a comprehensive comparison, we discuss various promising future directions of CL in medical-area adaptations. 


## Citation
If you find our paper or this resource helpful, please consider cite: 


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
        <td><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10078916">S3R: Shape and Semantics-based Selective Regularization for Explainable Continual Segmentation across Multiple Sites</a></td>
        <td>2023</td>
        <td>Transactions on Medical Imaging</td>
        <td><a href="https://github.com/jingyzhang/S3R">GitHub</a></td>
    </tr>
    <tr>
        <td><a href="https://arxiv.org/abs/2304.14572">SCOPE: Structural Continuity Preservation for Medical Image Segmentation</a></td>
        <td>2023</td>
        <td>Preprint</td>
        <td>None</td>
    </tr>
    <tr>
        <td><a href="https://link.springer.com/chapter/10.1007/978-3-031-45857-6_14">A Continual Learning Approach for Cross-Domain White Blood Cell Classification</a></td>
        <td>2023</td>
        <td>MICCAI</td>
        <td><a href="https://github.com/marrlab/UACL">GitHub</a></td>
    </tr>
    <tr>
        <td><a href="https://arxiv.org/pdf/2305.05738.pdf">DOCTOR: A Multi-Disease Detection Continual Learning Framework Based on Wearable Medical Sensors</a></td>
        <td>2023</td>
        <td>Preprint</td>
        <td>None</td>
    </tr>
    <tbody>
</table>

### Memory and Computation Inefficiency
</table>
</tbody>
  <thead>
    <tr>
      <td colspan="4"></td> <!-- Blank row for spacing -->
    </tr>
    <tr>
      <th>Paper Title</th>
      <th>Year</th>
      <th>Conference/Journal</th>
      <th>Code</th>
    </tr>
  </thead>
  <tbody>
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
</tbody>
</table>

### Medical Data Overlapping Classes
| Paper Title | Year | Conference/Journal | Code 
|-----------------------------------------------------------------------------------------------------|------|-----------------|-----------------------------------------------------------------------------------------|
| [Revisiting Distillation for Continual Learning on Visual Question Localized-Answering in Robotic Surgery](https://arxiv.org/pdf/2307.12045.pdf) | 2023 | MICCAI | https://github.com/longbai1006/CS-VQLA

### Medical data low-quality generation
| Paper Title | Year | Conference/Journal | Code 
|-----------------------------------------------------------------------------------------------------|------|-----------------|-----------------------------------------------------------------------------------------|
| [Hybrid Neural Diffeomorphic Flow for Shape Representation and Generation via Triplane](https://arxiv.org/pdf/2307.01957.pdf) | 2023 | Preprint | None        |
| [Generative appearance replay for continual unsupervised domain adaptation](https://arxiv.org/pdf/2301.01211.pdf) | 2023 | Preprint | None        |

### Other Medical Deep Learning Frameworks
| Paper Title | Year | Conference/Journal | Code 
|-----------------------------------------------------------------------------------------------------|------|-----------------|-----------------------------------------------------------------------------------------|
| [Accelerating Batch Active Learning Using Continual Learning Techniques](https://www.researchgate.net/publication/370687872_Accelerating_Batch_Active_Learning_Using_Continual_Learning_Techniques) | 2023 | Preprint | None        |
| [A framework for dynamically training and adapting deep reinforcement learning models to different, low-compute, and continuously changing radiology deployment environments](https://arxiv.org/pdf/2306.05310.pdf) | 2023 | Preprint | None        |

## TASK-INCREMENTAL LEARNING (TIL)
Description about Type2.

| Paper Title | Year | Conference/Journal
|------------|------|-----------------|
| PaperA     | [Link to PaperA](#) | Some more details about PaperA |
| PaperB     | [Link to PaperB](#) | Some more details about PaperB |
| ...        | ...  | ...             |

## DOMAIN-INCREMENTAL LEARNING (DIL)
Description about Type3.

| Paper Title | Year | Conference/Journal
|------------|------|-----------------|
| PaperX     | [Link to PaperX](#) | Some more details about PaperX |
| PaperY     | [Link to PaperY](#) | Some more details about PaperY |
| ...        | ...  | ...             |

---

## Contact
We welcome all researchers to contribute to this repository.

Email: xinyaowu49@gmail.com



