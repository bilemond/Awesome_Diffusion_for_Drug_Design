# Awesome Diffusion Models for Drug Design

[![Awesome](assets/badge.svg)](https://github.com/bilemond/Awesome_Diffusion_for_Drug_Design) [![License: MIT](assets/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Contents

- [De Novo Drug Design](#de-novo-drug-design)
  - [Target-Agnostic Generation](#target-agnostic-generation)
  - [Target-Aware Generation](#target-aware-generation)
  - [Conformation Generation](#conformation-generation)
- [Molecular Optimization For Drug Design](#molecular-optimization-for-drug-design)
  - [Fragment-based drug discovery](Fragment-based-drug-discovery)
  - [Scaffold-based DMGs](Scaffold-based-DMGs)

- [Structure-based Drug Design](Structure-based-Drug-Design)
- [Drug-likeness and Evaluation metrics](#drug-likeness-and-evaluation-metrics)


# Papers

## De Novo Drug Design

### Target-Agnostic Generation

* **Equivariant Diffusion for Molecule Generation in 3D** ([EDM](papers/EDM.md))    
  Emiel Hoogeboom, Vı́ctor Garcia Satorras, Clément Vignac, Max Welling    
  [[2203.17003\]](https://arxiv.org/abs/2203.17003) [[ICML 2022\]](https://proceedings.mlr.press/v162/hoogeboom22a.html) [[Github](https://github.com/ehoogeboom/e3_diffusion_for_molecules)]    
* **Geometry-Complete Diffusion for 3D Molecule Generation and Optimization** (GCDM)    
  Alex Morehead, Jianlin Cheng  
  [arXiv:2302.04313 (2023)](https://arxiv.org/abs/2302.04313)    
* **MDM: Molecular Diffusion Model for 3D Molecule Generation** (MDM)     
  Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong    
  [AAAI 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25639)    
* **Geometric Latent Diffusion Models for 3D Molecule Generation** (GeoLDM)    
  Minkai Xu, Alexander S Powers, Ron O. Dror, Stefano Ermon, Jure Leskovec     
  [ICML 2023](https://proceedings.mlr.press/v202/xu23n.html)    
* **Coarse-to-Fine: a Hierarchical Diffusion Model for Molecule Generation in 3D** [2023]   
  Qiang, Bo, Yuxuan Song, Minkai Xu, Jingjing Gong, Bowen Gao, Hao Zhou, Wei-Ying Ma, and Yanyan Lan.    [ICML  (2023)](https://proceedings.mlr.press/v202/qiang23a.html) |  [code](https://github.com/qiangbo1222/HierDiff) 
* **Conditional Diffusion Based on Discrete Graph Structures for Molecular Graph Generation** [2023]   Huang, Han, Leilei Sun, Bowen Du, and Weifeng Lv.    
  [arXiv:2301.00427 (2023)](https://arxiv.org/abs/2301.00427) |  [code](https://github.com/GRAPH-0/CDGS)  |  AAAI 2023
* **Learning Joint 2D & 3D Diffusion Models for Complete Molecule Generation** (JODO)    
  Han Huang, Leilei Sun, Bowen Du, Weifeng Lv      
  [arXiv:2305.12347 (2023)](https://arxiv.org/abs/2305.12347)    
* **MiDi: Mixed Graph and 3D Denoising Diffusion for Molecule Generation** (MiDi)  
  Clement Vignac, Nagham Osman, Laura Toni, Pascal Frossard   
  [arXiv:2302.09048 (2023)](https://arxiv.org/abs/2302.09048)  

- **Domain-Agnostic Molecular Generation with Self-feedback**    
  [[Paper\]](https://arxiv.org/abs/2301.11259) [[Code\]](https://github.com/zjunlp/MolGen)[ICLR24]      
- **SILVR: Guided Diffusion for Molecule Generation** [2023]   
  Runcie, Nicholas T., and Antonia SJS Mey.    
  [J. Chem. Inf. Model. (2023)](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00667) |  [arXiv:2304.10905v1](https://arxiv.org/abs/2304.10905) |  [code](https://github.com/meyresearch/SILVR) 
- **De Novo Molecule Generation with Graph Latent Diffusion Model** [2024]   
  Wang, Conghao, Hiok Hian Ong, Shunsuke Chiba, and Jagath C. Rajapakse.    
  [ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE (2024)](https://doi.org/10.1109/ICASSP48485.2024.10447480)  

### Target-Aware Generation

- **Structure-based Drug Design with Equivariant Diffusion Models**      
  Arne Schneuing<sup>1</sup>, Yuanqi Du<sup>1</sup>, Charles Harris, Arian Jamasb, Ilia Igashov, Weitao Du, Tom Blundell, Pietro Lió, Carla Gomes, Max Welling, Michael Bronstein, Bruno Correia      
  [arXiv:2210.13695 (2022)](https://arxiv.org/abs/2210.13695)  [[Github](https://github.com/arneschneuing/DiffSBDD)]      
- **3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction** (TargetDiff)      
  Jiaqi Guan, Wesley Wei Qian, Xingang Peng, Yufeng Su, Jian Peng, Jianzhu Ma      
  [ICLR 2023](https://arxiv.org/abs/2303.03543)      
- **KGDiff: towards explainable target-aware molecule generation with knowledge guidance** [2023]   Hao Qian, Wenjing Huang, Shikui Tu, Lei Xu.    
  [Briefings in Bioinformatics.  (2023)](https://doi.org/10.1093/bib/bbad435)  |  [code](https://github.com/CMACH508/KGDiff) 

### Conformation Generation(append)  

- **Torsional Diffusion for Molecular Conformer Generation**      
  Bowen Jing, Gabriele Corso, Regina Barzilay, Tommi S. Jaakkola*     
  ICLR Workshop 2022. [[Paper](https://arxiv.org/abs/2206.01729)] [[Github](https://github.com/gcorso/torsional-diffusion)]  
  
- **Predicting Molecular Conformation via Dynamic Graph Score Matching**      
  Shitong Luo, Chence Shi, Minkai Xu, Jian Tang*      
  NeurIPS 2021. [[Paper](https://proceedings.neurips.cc/paper/2021/hash/a45a1d12ee0fb7f1f872ab91da18f899-Abstract.html)]  
- **GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation** (GeoDiff)      
  Minkai Xu, Lantao Yu, Yang Song, Chence Shi, Stefano Ermon, Jian Tang      
  [ICLR 2022](https://openreview.net/forum?id=PzcvxEMzvQC)      
- 

## Molecular Optimization For Drug Design

- **Diffusing on Two Levels and Optimizing for Multiple Properties: A Novel Approach to Generating Molecules with Desirable Properties** [2023]      
  Guo, Siyuan, Jihong Guan, and Shuigeng Zhou.      
  [arXiv:2310.04463 (2023)](https://arxiv.org/abs/2310.04463)      
- **A dual diffusion model enables 3D binding bioactive molecule generation and lead optimization given target pockets** [2023]      
  Huang, Lei.      
  [bioRxiv 2023.01.28.526011](https://www.biorxiv.org/content/10.1101/2023.01.28.526011v1)      
- **A dual diffusion model enables 3D molecule generation and lead optimization based on target pockets** [2024]   
  Huang, L., Xu, T., Yu, Y. et al.    
  [Nat Commun 15, 2657 (2024)](https://doi.org/10.1038/s41467-024-46569-1)  |  [code](https://github.com/Layne-Huang/PMDM) 
- **DiffSeqMol: A Non-Autoregressive Diffusion-Based Approach for Molecular Sequence Generation and Optimization** [2023]   
  Zixu Wang, Yangyang Chen*, Xiucai Ye.    
  [chemrxiv-2023-ltr9v-v2.  (2023)](https://doi.org/10.26434/chemrxiv-2023-ltr9v-v2) |  [code](https://github.com/viko-3/DiffSeqMol) 

### Fragment-based drug discovery

* **ReBADD-SE: Multi-objective molecular optimization using SELFIES fragment and off-policy self-critical sequence training** [2023]       
  Choi, Jonghwan, Sangmin Seo, Seungyeon Choi, Shengmin Piao, Chihyun Park, Sung Jin Ryu, Byung Ju Kim, and Sanghyun Park.       
  [Computers in Biology and Medicine 157 (2023)](https://doi.org/10.1016/j.compbiomed.2023.106721) |  [code](https://github.com/mathcom/ReBADD-SE)       
* **Autoregressive fragment-based diffusion for pocket-aware ligand design** [2023]   
  Ghorbani, Mahdi, Leo Gendelev, Paul Beroza, and Michael Keiser.    
  [NeurIPS 2023 Generative AI and Biology (GenBio) Workshop.  (2023)](https://openreview.net/forum?id=E3HN48zjam) |  [code](https://github.com/ghorbanimahdi73/autofragdiff) 

### Scaffold-based DMGs

* **DiffDec: Structure-Aware Scaffold Decoration with an End-to-End Diffusion** [2023]       
  Xie, Junjie, Sheng Chen, Jinping Lei, and Yuedong Yang.    
  [bioRxiv (2023)](https://doi.org/10.1101/2023.10.08.561377)   
* **DiffHopp: A Graph Diffusion Model for Novel Drug Design via Scaffold Hopping** [2023]   
  Torge, Jos, Charles Harris, Simon V. Mathis, and Pietro Lió.    
  [ICML(2023)](https://icml-compbio.github.io/2023/papers/WCBICML2023_paper69.pdf) |  [code](https://github.com/jostorge/diffusion-hopping) 
* 

## Structure-based Drug Design

* **A unified conditional diffusion framework for dual protein targets based bioactive molecule generation**  [2024]      
  Huang, Lei, Zheng Yuan, Huihui Yan, Rong Sheng, Linjing Liu, Fuzhou Wang, Weidun Xie et al.    
  [IEEE Transactions on Artificial Intelligence (2024)](https://doi.org/10.1109/TAI.2024.3387402)  |  [arXiv:2306.13957 (2023)](https://arxiv.org/abs/2306.13957) 
* **AUTODIFF: Autoregressive Diffusion Modeling for Structure-based Drug Design** [2024]       
  Li, Xinze, Penglei Wang, Tianfan Fu, Wenhao Gao, Chengtao Li, Leilei Shi, and Junhong Liu.        
  [arXiv:2404.02003 (2024)](https://arxiv.org/html/2404.02003v1)      
* **MolSnapper: Conditioning Diffusion for Structure Based Drug Design** [2024]   
  Ziv, Yael, Brian Marsden, and Charlotte Deane.    
  [bioRxiv (2024)](https://doi.org/10.1101/2024.03.28.586278)  |  [code](https://github.com/oxpig/MolSnapper) 
* **A dual diffusion model enables 3D molecule generation and lead optimization based on target pockets** [2024]   
  Huang, L., Xu, T., Yu, Y. et al.   
  [Nat Commun 15, 2657 (2024)](https://doi.org/10.1038/s41467-024-46569-1)  |  [code](https://github.com/Layne-Huang/PMDM)   
* **KGDiff: towards explainable target-aware molecule generation with knowledge guidance** [2023]   
  Hao Qian, Wenjing Huang, Shikui Tu, Lei Xu.    
  [Briefings in Bioinformatics.  (2023)](https://doi.org/10.1093/bib/bbad435)  |  [code](https://github.com/CMACH508/KGDiff)   
* **Geometric Deep Learning for Structure-Based Ligand Design** [2023]   
  Alexander S. Powers, Helen H. Yu, Patricia Suriana, Rohan V. Koodli, Tianyu Lu, Joseph M. Paggi, and Ron O. Dror.   
  [ACS Cent. Sci. (2023)](https://doi.org/10.1021/acscentsci.3c00572) 
* **Autoregressive fragment-based diffusion for pocket-aware ligand design** [2023]   
  Ghorbani, Mahdi, Leo Gendelev, Paul Beroza, and Michael Keiser.    
  [NeurIPS 2023 Generative AI and Biology (GenBio) Workshop.  (2023)](https://openreview.net/forum?id=E3HN48zjam) |  [code](https://github.com/ghorbanimahdi73/autofragdiff)   
* **DiffDTM: A conditional structure-free framework for bioactive molecules generation targeted for dual proteins**   [2023]   
  Huang, Lei, Zheng Yuan, Huihui Yan, Rong Sheng, Linjing Liu, Fuzhou Wang, Weidun Xie et al.    
  [arXiv:2306.13957 (2023)](https://arxiv.org/abs/2306.13957) 
* **3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction** [2023]   Guan, Jiaqi, Wesley Wei Qian, Xingang Peng, Yufeng Su, Jian Peng, and Jianzhu Ma.   
  [The Eleventh International Conference on Learning Representations. (2023)](https://openreview.net/forum?id=kJqXEPXMsE0) |  [code](https://github.com/guanjq/targetdiff) 
* **Structure-based Drug Design with Equivariant Diffusion Models** [2023]  
  Schneuing, A., Du, Y., Harris, C., Jamasb, A., Igashov, I., Du, W., ... & Correia, B.   
  [arXiv:2210.13695 (2022)](https://openreview.net/forum?id=uKmuzIuVl8z) |  [code](https://github.com/arneschneuing/DiffSBDD) 
* **DecompDiff: Diffusion Models with Decomposed Priors for Structure-Based Drug Design** [2023]   Guan, Jiaqi, Xiangxin Zhou, Yuwei Yang, Yu Bao, Jian Peng, Jianzhu Ma, Qiang Liu, Liang Wang, and Quanquan Gu.    
  [ICML (2023)](https://openreview.net/forum?id=9qy9DizMlr) |  [code](https://github.com/bytedance/DecompDiff) 
* **Binding-Adaptive Diffusion Models for Structure-Based Drug Design** [2024]
  Zhilin Huang, Ling Yang, Zaixi Zhang, Xiangxin Zhou, Yu Bao, Xiawu Zheng, Yuwei Yang, Yu Wang, Wenming Yang. 
  [AAAI 2024 (2024)](https://arxiv.org/abs/2402.18583)  |  [code](https://github.com/YangLing0818/BindDM) 
* **Shape-conditioned 3D Molecule Generation via Equivariant Diffusion Models** [2023]   
  Chen, Ziqi, Bo Peng, Srinivasan Parthasarathy, and Xia Ning    
  [arXiv:2308.11890 (2023)](https://arxiv.org/abs/2308.11890) 



## Drug-likeness and Evaluation metrics

### QED 

> Target-Agnostic Generation & Target-Aware Generation

**quantitative estimation of drug-likeness**  

* **Quantifying the chemical beauty of drugs**  [2012]  
  Bickerton, G., Paolini, G., Besnard, J. et al.   
  [Nature Chem 4, 90–98 (2012)](https://doi.org/10.1038/nchem.1243) |  [code](https://github.com/AspirinCode/DrugAI_Drug-Likeness) 

### SAscore 

> Target-Aware Generation

**Estimation of synthetic accessibility score of drug-like molecules based on molecular complexity and fragment contributions**  
[J Cheminform 1, 8 (2009)](http://www.jcheminf.com/content/1/1/8) |  [code](https://github.com/rdkit/rdkit/tree/master/Contrib/SA_Score)  

### RAscore

**Retrosynthetic accessibility score (RAscore) – rapid machine learned synthesizability classification from AI driven retrosynthetic planning**  
[Chemical Science 12.9 (2021)](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d0sc05401a) |  [code](https://github.com/reymond-group/RAscore) 

### Evaluation metrics

* **Spacial Score – A Comprehensive Topological Indicator for Small Molecule Complexity** [2023]  
  Krzyzanowski, Adrian, Axel Pahl, Michael Grigalunas, and Herbert Waldmann.   
  [J. Med. Chem. (2023)](https://doi.org/10.1021/acs.jmedchem.3c00689) | [chemrxiv-2023-nd1ll](https://chemrxiv.org/engage/chemrxiv/article-details/64257af562fecd2a83add9c2) |  [code](https://github.com/frog2000/Spacial-Score)   
* **An automated scoring function to facilitate and standardize evaluation of goal-directedgenerative models for de novo molecular design** [2023]  
  Thomas, Morgan, Noel M. O'Boyle, Andreas Bender, and Chris De Graaf.  
  [chemrxiv-2023-c4867](https://doi.org/10.26434/chemrxiv-2023-c4867) |  [code](https://github.com/MorganCThomas/MolScore)   
* **FCD : Fréchet ChemNet Distance**  
  Fréchet ChemNet Distance: A Metric for Generative Models for Molecules in Drug Discovery  
  Preuer, Kristina, Philipp Renz, Thomas Unterthiner, Sepp Hochreiter, and Gunter Klambauer.  
  [J. Chem. Inf. Model. 2018, 58, 9, 1736–1741](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00234) |  [code](https://github.com/bioinf-jku/FCD)  
* **Perplexity-Based Molecule Ranking and Bias Estimation of Chemical Language Models** [2022]
  Moret, M., Grisoni, F., Katzberger, P. and Schneider, G.  
  [J. Chem. Inf. Model. 2022, 62, 5, 1199–1206](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00079) |  [code](https://github.com/ETHmodlab/CLM_perplexity)   
* **AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading** (Vina AutoDock)  
  Oleg Trott, Arthur J. Olson  
  [JCC 2010](https://onlinelibrary.wiley.com/doi/full/10.1002/jcc.21334)  



## # Some Other Tasks

### Inverse Molecular Design

- **Equivariant Energy-Guided SDE for Inverse Molecular Design**  
  *Fan Bao<sup>1</sup>, Min Zhao<sup>1</sup>, Zhongkai Hao, Peiyao Li, Chongxuan Li, Jun Zhu*  
  arXiv 2022. [[Paper](https://arxiv.org/abs/2209.15408)]   
- **Inverse Molecular Design with Multi-Conditional Diffusion Guidance** [2024]
  Liu, Gang, Jiaxin Xu, Tengfei Luo, and Meng Jiang. 
  [arXiv:2401.13858 (2024)](https://arxiv.org/abs/2401.13858)  |  [code](https://github.com/liugangcode/MCD) 
- **STRIDE: Structure-guided Generation for Inverse Design of Molecules** [2023]   
  Zaman, Shehtab, Denis Akhiyarov, Mauricio Araya-Polo, and Kenneth Chiu.    
  [NeurIPS 2023 AI for Science Workshop.  (2023)](https://openreview.net/forum?id=DqJThcBJ6P&noteId=JjvFlUIseN) 
- **Guided Diffusion for Inverse Molecular Design** [2023]   
  Weiss, Tomer, Luca Cosmo, Eduardo Mayo Yanes, Sabyasachi Chakraborty, Alex M. Bronstein, and Renana Gershoni-Poranne.    
  [Nat Comput Sci (2023)](https://doi.org/10.1038/s43588-023-00532-0) |   [chemrxiv-2023-z8ltp](https://doi.org/10.26434/chemrxiv-2023-z8ltp) |  [code](https://github.com/tomer196/GaUDI) 

### Text to Molecular

- **3M-Diffusion: Latent Multi-Modal Diffusion for Text-Guided Generation of Molecular Graphs** [2024]   
  Huaisheng Zhu, Teng Xiao, Vasant G Honavar.    
  [	arXiv:2403.07179. (2024)](https://arxiv.org/abs/2403.07179)  |  [code](https://github.com/huaishengzhu/3MDiffusion) 
- **Sculpting Molecules in Text-3D Space: A Flexible Substructure Aware Framework for Text-Oriented Molecular Optimization** [2024]   
  Zhang, Kaiwei, Yange Lin, Guangcheng Wu, Yuxiang Ren, Xuecang Zhang, Bo Wang, and Xiao-Yu Zhang.    
  [Research Square (2024)](https://www.researchsquare.com/article/rs-4023429/v1)  
- **Guided Diffusion for molecular generation with interaction prompt** [2023]   
  Wu Song, Peng Wu, Huabin Du, Yingchao Yan, Chen Bai    
  [bioRxiv  (2023)](https://doi.org/10.1101/2023.09.11.557141) |  [data](https://bits.csb.pitt.edu/files/crossdock2020/) 



## #To check later

- **Equivariant 3D-Conditional Diffusion Models for Molecular Linker Design**  
  *Ilia Igashov, Hannes Stärk, Clément Vignac, Victor Garcia Satorras, Pascal Frossard, Max Welling, Michael Bronstein, Bruno Correia*   
  arXiv 2022. [[Paper](https://arxiv.org/abs/2210.05274)]  
- **Diffusion-based Molecule Generation with Informative Prior Bridges**  
  Lemeng Wu<sup>1</sup>, Chengyue Gong<sup>1</sup>, Xingchao Liu, Mao Ye, Qiang Liu*   
  NeurIPS 2022. [[Paper](https://arxiv.org/abs/2209.00865)]   
- **Diff-Shape: A Novel Constrained Diffusion Model for Shape based De Novo Drug Design**   [2024]   
  Lin, Jie, Mingyuan Xu, and Hongming Chen.   
  [chemrxiv-2024-km0h1 (2024)](https://doi.org/10.26434/chemrxiv-2024-km0h1)  
- **A Property-Guided Diffusion Model For Generating Molecular Graphs**   [2024]   
  Ma, Changsheng, Taicheng Guo, Qiang Yang, Xiuying Chen, Xin Gao, Shangsong Liang, Nitesh Chawla, and Xiangliang Zhang.    
  [ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE (2024)](https://doi.org/10.1109/ICASSP48485.2024.10447350)  
- **A unified conditional diffusion framework for dual protein targets based bioactive molecule generation**   [2024]   
  Huang, Lei, Zheng Yuan, Huihui Yan, Rong Sheng, Linjing Liu, Fuzhou Wang, Weidun Xie et al.    
  [IEEE Transactions on Artificial Intelligence (2024)](https://doi.org/10.1109/TAI.2024.3387402)  |  [arXiv:2306.13957 (2023)](https://arxiv.org/abs/2306.13957) 
- **Equivariant 3D-conditional diffusion model for molecular linker design** [2024]   
  Igashov, I., Stärk, H., Vignac, C. et al.    
  [Nat Mach Intell (2024)](https://doi.org/10.1038/s42256-024-00815-9)  |  [code](https://github.com/igashov/DiffLinker) 
- **Functional-Group-Based Diffusion for Pocket-Specific Molecule Generation and Elaboration** [2024] 
  Lin, Haitao, Yufei Huang, Odin Zhang, Yunfan Liu, Lirong Wu, Siyuan Li, Zhiyuan Chen, and Stan Z. Li.    [Advances in Neural Information Processing Systems 36 (2024)](https://proceedings.neurips.cc/paper_files/paper/2023/hash/6cdd4ce9330025967dd1ed0bed3010f5-Abstract-Conference.html)  
- **Field-based Molecule Generation** [2024]
  Dumitrescu, Alexandru, Dani Korpela, Markus Heinonen, Yogesh Verma, Valerii Iakovlev, Vikas Garg, and Harri Lähdesmäki.    
  [arXiv:2402.15864 (2024)](https://arxiv.org/abs/2402.15864) 
- **Navigating the Design Space of Equivariant Diffusion-Based Generative Models for De Novo 3D Molecule Generation** [2024]   
  Le, Tuan, Julian Cremer, Frank Noé, Djork-Arné Clevert, and Kristof Schütt.    
  [International Conference on Learning Representations (ICLR).  (2024)](https://openreview.net/pdf?id=kzGuiRXZrQ)  |  [code](https://github.com/tuanle618/eqgat-diff) 
- **LinkerNet: Fragment Poses and Linker Co-Design with 3D Equivariant Diffusion** [2023]   
  Guan, Jiaqi, Xingang Peng, PeiQi Jiang, Yunan Luo, Jian Peng, and Jianzhu Ma    
  [NeurIPS 2023.  (2023)](https://openreview.net/forum?id=6EaLIw3W7c) |  [code](https://github.com/guanjq/LinkerNet) 
- **MolDiff: Addressing the Atom-Bond Inconsistency Problem in 3D Molecule Diffusion Generation** [2023]   
  Peng, Xingang, Jiaqi Guan, Qiang Liu, and Jianzhu Ma.    
  [ICML  (2023)](https://proceedings.mlr.press/v202/peng23b.html) |  [code](https://github.com/pengxingang/MolDiff) 
- **Generative Discovery of Novel Chemical Designs using Diffusion Modeling and Transformer Deep Neural Networks with Application to Deep Eutectic Solvents** [2023]   
  Luu, Rachel K., Marcin Wysokowski, and Markus J. Buehler.    
  [arXiv:2304.12400v1](https://arxiv.org/abs/2304.12400) |  [code](https://github.com/lamm-mit/MoleculeDiffusionTransformer) 