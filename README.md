<!-- <p align="center">
    <img src="assets/a-logo-representing - omnicreator - -a-powerful-ai-t.png" width="150" style="margin-bottom: 0.2;"/>
<p> -->
<h2 align="center"> FineTec: Fine-Grained Action Recognition under Temporal Corruption via Skeleton Decomposition and Sequence Completion</h2>
<!-- ![](./assets/logo_long.png#gh-light-mode-only){: width="50%"} -->
<!-- ![](./assets/logo_long_dark.png#gh-dark-mode-only=100x20) -->
<div align="center">
<!-- <img src='assets/logo_long.png' style="height:100px"></img> -->




_**[Dian Shao](https://scholar.google.com/citations?user=amxDSLoAAAAJ&hl=en)<sup>†</sup>, [Mingfei Shi](https://github.com/SmartDianLab/FinePhys), [Like Liu](https://github.com/Lozumi)**_
<br><br>
<sup>†</sup>Corresponding Author
<br>
Northwestern Polytechnical University

<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for latest update.  </h2>
 <!--<a href='https://arxiv.org/abs/2505.13437'><img src='https://img.shields.io/badge/arXiv-2505.13437-b31b1b.svg'></a> &nbsp;-->
 <a href='https://smartdianlab.github.io/projects-FineTec/'><img src='https://img.shields.io/badge/Project-Page-Green'></a> &nbsp; 
<br>
<strong>The 40th Annual AAAI Conference on Artificial Intelligence (AAAI-26)</strong>
</div>

## Abstract
Recognizing fine-grained actions from temporally corrupted skeleton sequences remains a significant challenge, particularly in real-world scenarios where online pose estimation often yields substantial missing data. Existing methods often struggle to accurately recover temporal dynamics and fine-grained spatial structures, resulting in the loss of subtle motion cues crucial for distinguishing similar actions. To address this, we propose FineTec, a unified framework for Fine-grained action recognition under Temporal Corruption. FineTec first restores a base skeleton sequence from corrupted input using context-aware completion with diverse temporal masking. Next, a skeleton-based spatial decomposition module partitions the skeleton into five semantic regions, further divides them into dynamic and static subgroups based on motion variance, and generates two augmented skeleton sequences via targeted perturbation. These, along with the base sequence, are then processed by a physics-driven estimation module, which utilizes Lagrangian dynamics to estimate joint accelerations. Finally, both the fused skeleton position sequence and the fused acceleration sequence are jointly fed into a GCN-based action recognition head. Extensive experiments on both coarse-grained (NTU-60, NTU-120) and fine-grained (Gym99, Gym288) benchmarks show that FineTec significantly outperforms previous methods under various levels of temporal corruption. Specifically, FineTec achieves top-1 accuracies of 89.1% and 78.1% on the challenging Gym99-severe and Gym288-severe settings, respectively, demonstrating its robustness and generalizability.

<!-- <table class="center">
    <tr>
    <td><img src="assets/fig1.png"></td>
    </tr>
</table> -->
 
## 🔥 Update
- __[2025.11.08]__: Initialized this github repository and README.


## 🧰 TODO

- [ ] Release paper.
- [ ] Release dataset.
- [ ] Release training code
- [ ] Release inference code.
- [ ] Release model weights.

## 📊 Dataset

Coming Soon~

## 🧰 Models

Coming Soon~


## 📖 Contents

Coming Soon~

<!-- 
## 📝 Citation
Please consider citing our paper if our work is useful: -->
<!-- ```bib
@article{shao2026finetec,
    title={FinePhys: Fine-grained Human Action Generation by Explicitly Incorporating Physical Laws for Effective Skeletal Guidance},
    author={Shao, Dian and Shi, Mingfei and Liu, Like},
    journal={TBD},
    year={2026}
}
``` -->



## 📪 Contact

For any question, feel free to email ```mingfeishi5@mail.nwpu.edu.cn```.
