# **Understanding the Security Landscape of Pre-trained Encoders: A Comprehensive Survey**

A **continual** collection of papers related to Attacks and Defenses in the pre-training scenario.

Pre-trained encoders have drawn increasing attention in recent years due to its superior performance on numerous downstream tasks after fine-tuning.
Despite their remarkable capabilities, the increased complexity and deployment of  pre-trained encoders have also exposed them to various security threats and vulnerabilities, making the study of attacks on these models a critical area of research.

Here, we've summarized existing  attacks methods in our survey paper👍.

本文标题链接

> If you find some important work missed, it would be super helpful to let me know (xxx@xxx). Thanks!

> If you find our survey useful for your research, please consider citing:

```
@article{,
  title={Understanding the Security Landscape of Pre-trained Encoders: A Comprehensive Survey},
  author={},
  journal={},
  year={}
}
```

**Table of Contents**

- [Adversarial Attacks](#Adversarial Attacks)
- [Backdoor Attacks](#Backdoor Attacks)
- [Privacy Attacks](#Privacy Attacks)
- [The Other Security Issues](#The Other Security Issues)

---

## Adversarial Attacks


|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  9   |  21  |  36   |

- **Towards Adversarial Attack on Vision-Language Pre-training Models** [[pdf]](https://arxiv.org/abs/2206.09391) [[code]](https://github.com/adversarial-for-goodness/Co-Attack)
  - Jiaming Zhang,Qi Yi,Jitao Sang
  - Beijing Jiaotong University,Peng Cheng Lab
  - Proceedings of the ACM International Conference on Multimedia (ACM MM 2022)
- **DI-AA: An Interpretable White-box Attack for Fooling Deep Neural Networks** [[pdf]](https://arxiv.org/abs/2110.07305)
  - Yixiang Wang,Jiqiang Liu,Xiaolin Chang,Jianhua Wang, Ricardo J. Rodríguez
  - Beijing Jiaotong University,University of Zaragoza
  - Proceedings of the Information Sciences (Information Sciences 2022)
- **Iterative Adversarial Attack on Image-guided Story Ending Generation** [[pdf]](https://arxiv.org/pdf/2305.13208v1)[[code]](https://github.com/frgfm/torch-cam)
  - Youze Wang, Wenbo Hu, Richang Hong
  - IEEE
  - Proceedings of the IEEE Transactions on Multimedia (TMM 2023)
- **A Multi-task Adversarial Attack Against Face Authentication** [[pdf]](https://arxiv.org/abs/2408.08205) [[code]](https://github.com/azrealwang/mtadv)
  - HANRUI WANG,SHUO WANG,CUNJIAN CHEN, MASSIMO TISTARELLI, ZHE JIN
  - Shanghai Jiao Tong University,Monash University,University of Sassari,Anhui University
  - arXiv 2024
- **A Unified Understanding of Adversarial Vulnerability Regarding Unimodal Models and Vision-Language Pre-training Models** [[pdf]](https://arxiv.org/abs/2407.17797) [[code]](https://github.com/LibertazZ/FGA)
  - Haonan Zheng,Xinyang Deng,Wen Jiang,Wenrui Li
  - Northwestern Polytechnical University School of Electronics and Information,Harbin Institute of Technology Department of Computer Science and Technology
  - Proceedings of the ACM International Conference on Multimedia (ACM MM 2024)
- **Adversarial Attacks on Both Face Recognition and Face Anti-spoofing Models** [[pdf]](https://arxiv.org/abs/2405.16940)
  - Fengfan Zhou, Qianyu Zhou, Xiangtai Li, Xuequan Lu, Lizhuang Ma, Hefei Ling
  - Huazhong University of Science and Technology,Shanghai Jiao Tong University,ByteDance,La Trobe University
  - arXiv 2024
- **Downstream-agnostic Adversarial Examples**[[pdf]](https://arxiv.org/pdf/2307.12280) [[code]](https://github.com/CGCL-codes/AdvEncoder)
  - Ziqi Zhou,Shengshan Hu,Ruizhi Zhao,Qian Wang,Leo Yu Zhang, Junhui Hou, Hai Jin
  - Huazhong University of Science and Technology,Wuhan University,Griffith University,City University of Hong Kong
  - Proceedings of the International Conference on Computer Vision (ICCV 2023)
- **SA-Attack: Improving Adversarial Transferability of Vision-Language Pre-training Models via Self-Augmentation**[[pdf]](https://arxiv.org/abs/2312.04913) 
  - Bangyan He, Xiaojun Jia, Siyuan Liang,Tianrui Lou,Yang Liu,Xiaochun Cao
  - Institute of Information Engineering, Chinese Academy of Sciences,Nanyang Technological University,National University of Singapore,Sun Yat-sen University
  - arXiv 2023
- **AdvCLIP: Downstream-agnostic Adversarial Examples in Multimodal Contrastive Learning**[[pdf]](https://arxiv.org/abs/2308.07026) [[code]](https://github.com/CGCL-codes/AdvCLIP)
  * Ziqi Zhou,Shengshan Hu,Ruizhi Zhao,Qian Wang,Leo Yu Zhang, Junhui Hou, Hai Jin
  * Huazhong University of Science and Technology
  * Proceedings of the ACM International Conference on Multimedia (ACM MM 2023)
- **Content-based Unrestricted Adversarial Attack** [[pdf]](https://arxiv.org/abs/2305.10665)
  - Zhaoyu Chen, Bo Li, Shuang Wu, Kaixun Jiang, Shouhong Ding, Wenqiang Zhang
  - Fudan University,Youtu Lab
  - Proceedings of the Neural Information Processing Systems (NuerIPS 2024)
- **Downstream Transfer Attack: Adversarial Attacks on Downstream Models with Pre-trained Vision Transformers**[[pdf]](https://arxiv.org/abs/2408.01705)
  - Weijie zheng,Xingjun Ma,Hanxun Huang,Jun Yin,Tiehua Zhang,Zuxuan Wu,Yu-Gang Jiang
  - None
  - arXiv 2024
- **Pre-trained Adversarial Perturbations** [[pdf]](https://arxiv.org/abs/2210.03372) [[code]](https://github.com/banyuanhao/PAP)
  - Yuanhao Ban,Yinpeng Dong
  - BNRist Center,Tsinghua-Bosch Joint ML Center, THBI Lab, Tsinghua University, ,RealAI
  - Proceedings of the Neural Information Processing Systems (NeurIPS 2022)
- **CodeAttack: Code-Based Adversarial Attacks for Pre-trained Programming Language Models** [[pdf]](https://arxiv.org/abs/2206.00052) [[code]](https://github.com/reddy-lab-code-research/CodeAttack)
  - Akshita Jha,Chandan K. Reddy
  - Department of Computer Science, Virginia Tech
  - Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI 2023)
- **OT-Attack: Enhancing Adversarial Transferability of Vision-Language Models via Optimal Transport Optimization** [[pdf]](https://arxiv.org/abs/2312.04403)
  - Dongchen Han,Xiaojun Jia,Yang Bai, Jindong Gu,Yang Liu,Xiaochun Cao
  - Shenzhen Campus of Sun Yat-sen University,Nanyang Technological University,Tsinghua University,University of Oxford
  - arXiv 2023
- **Black-Box Sparse Adversarial Attack via Multi-Objective Optimisation CVPR Proceedings** [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Williams_Black-Box_Sparse_Adversarial_Attack_via_Multi-Objective_Optimisation_CVPR_2023_paper.pdf)
  - Phoenix Neale Williams, Ke Li
  - Department of Computer Science, University of Exeter,Stocker Rd, Exeter, EX4 4PY
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2023)
- **HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text** [[pdf]](https://arxiv.org/abs/2402.01806) [[code]](https://github.com/HQA-Attack/HQAAttack-demo)
  - Han Liu,Zhi Xu,Xiaotong Zhang,Feng Zhang,Fenglong Ma,Hongyang Chen,Hong Yu,Xianchao Zhang
  - Dalian University of Technology,Peking University,The Pennsylvania State University,Zhejiang Lab,
  - Proceedings of the Neural Information Processing Systems (NeurIPS 2023)
- **DifAttack: Query-Effcient Black-Box Adversarial Attack via Disentangled Feature Space**[[pdf]](https://arxiv.org/abs/2309.14585) [[code]](https://github.com/csjunjun/DifAttack)
  - Jun Liu, Jiantao Zhou,Jiandian Zeng, Jinyu Tian
  - State Key Laboratory of Internet of Things for Smart City,University of Macau,Beijing Normal University,Macau University of Science and Technology
  - Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI 2024)
- **Mutual-Modality Adversarial Attack with Semantic Perturbation** [[pdf]](https://arxiv.org/abs/2312.12768)
  - Jingwen Ye, Ruonan Yu, Songhua Liu, Xinchao Wang
  - National University of Singapore
  - Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI 2024)
- **Enhancing the Transferability of Adversarial Attacks with Stealth Preservation** [[pdf]](https://openaccess.thecvf.com/content/CVPR2024W/AdvML/papers/Zhang_Enhancing_the_Transferability_of_Adversarial_Attacks_with_Stealth_Preservation_CVPRW_2024_paper.pdf)
  - Xinwei Zhang,Tianyuan Zhang,Yitong Zhang,Shuangcheng Liu
  - Beihang University
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **One Perturbation is Enough: On Generating Universal Adversarial Perturbations against Vision-Language Pre-training Models** [[pdf]](https://arxiv.org/abs/2406.05491)
  - Hao Fang,Jiawei Kong,Wenbo Yu,Bin Chen,Jiawei Li,Shu-Tao Xia,Ke Xu
  - Tsinghua Shenzhen International Graduate School, Tsinghua University,Harbin Institute of Technology,Huawei Technology 
  - arXiv 2024
- **BLACK-BOX TARGETED ADVERSARIAL ATTACK ON SEGMENT ANYTHING (SAM)** [[pdf]](https://arxiv.org/abs/2310.10010)
  - Sheng Zheng,Chaoning Zhang,Xinhong Hao
  - Beijing Institute of Technology,Kyung Hee University
  - Proceedings of the International Conference on Learning Representations (ICLR 2024)
- **Sample Efficient Detection and Classification of Adversarial Attacks via Self-Supervised Embeddings** [[pdf]](https://arxiv.org/abs/2108.13797)
  - Mazda Moayeri,Soheil Feizi
  - Department of Computer Science University of Maryland
  - Proceedings of the International Conference on Computer Vision (ICCV 2021)
- **MirrorCheck: Efficient Adversarial Defense for Vision-Language Models** [[pdf]](https://arxiv.org/abs/2406.09250)
  - Samar Fares,Klea Ziu,Toluwani Aremu,Nikita Durasov,Martin Takác,Pascal Fua,Karthik Nandakumar,Ivan Laptev
  - Mohamed bin Zayed University of Artificial Intelligence,Computer Vision Laboratory, EPFL
  - arXiv 2024
- **One Prompt Word is Enough to Boost Adversarial Robustness for Pre-trained Vision-Language Models** [[pdf]](https://arxiv.org/abs/2403.01849) [[code]](https://github.com/TreeLLi/APT)
  - Lin Li, Haoyan Guan, Jianing Qiu2, Michael Spratling
  - King’s College London,Imperial College London
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **Apollon: A robust defense system against Adversarial Machine Learning attacks in Intrusion Detection Systems** [[pdf]](https://www.sciencedirect.com/science/article/pii/S016740482300456X) [[code]](https://github.com/antoniopaya22/apollon)
  - Antonio Paya,Sergio Arroni,Vicente García-Díaz, Alberto Gómez
  - University of Oviedo
  - Proceedings of the Computers & Security (Computers & Security 2024)
- **Model-agnostic adversarial example detection via high-frequency amplification** [[pdf]](https://www.sciencedirect.com/science/article/pii/S0167404824000920)
  - Qiao Li,Jing Chen,Kun He,Zijun Zhang, Ruiying Du,Jisi She,Xinxin Wang
  - Key Laboratory of Aerospace Information Security and Trusted Computing, Ministry of Education, School of Cyber Science and Engineering,Rizhao Institute of Information Technology, Wuhan University,Collaborative Innovation Center of Geospatial Technology
  - Proceedings of the Computers & Security (Computers & Security 2024)
- A Self-supervised Approach for Adversarial Robustness [[pdf]](https://arxiv.org/abs/2006.04924) [[code]](https://github.com/
  Muzammal-Naseer/NRP)
  - Muzammal Naseer,Salman Khan,Munawar Hayat, Fahad Shahbaz Khan, Fatih Porikli
  - Australian National University, Australia,Data61-CSIRO,Inception Institute of Artificial Intelligence,UAE,Linkoping University
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2020)
- **LAS-AT: Adversarial Training with Learnable Attack Strategy** [[pdf]](https://arxiv.org/abs/2203.06616) [[code]](https://github.com/jiaxiaojunQAQ/LAS-AT)
  - Xiaojun Jia,Yong Zhang,Baoyuan Wu, Ke Ma, Jue Wang,Xiaochun Cao
  - University of Chinese Academy of Sciences,Tencent,The Chinese University of Hong Kong,Shenzhen Research Institute of Big Data
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2022)
- **The Best Defense is a Good Offense: Adversarial Augmentation against Adversarial Attacks** [[pdf]](https://arxiv.org/abs/2305.14188) [[code]](https://github.com/NVlabs/A5)
  - Iuri Frosio,Jan Kautz
  - NVIDIA
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2023)
- **Continual Adversarial Defense** [[pdf]](https://arxiv.org/abs/2312.09481)
  - Qian Wang,Yaoyao Liu,Hefei Ling,Yingwei Li,Qihao Liu,Ping Li,Jiazhong Chen,Alan Yuille,Ning Yu
  - Huazhong University of Science and Technology,Johns Hopkins University,Salesforce Research
  - arXiv 2024
- **PAD: Patch-Agnostic Defense against Adversarial Patch Attacks** [[pdf]](https://arxiv.org/abs/2312.09481) [[code]](https://github.com/Lihua-Jing/PAD)
  - Lihua Jing,Rui Wang,Wenqi Ren,Xin Dong,Cong Zou
  - Chinese Academy of Sciences,University of Chinese Academy of Sciences,Shenzhen Campus of Sun Yat-sen University
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **Pre-trained Model Guided Fine-Tuning for Zero-Shot Adversarial Robustness** [[pdf]](https://arxiv.org/abs/2401.04350) [[code]](https://github.com/serendipity1122/Pre-trained-Model-Guided-FineTuning-for-Zero-Shot-Adversarial-Robustness)
  - Sibo Wang,Jie Zhang,Zheng Yuan,Shiguang Shan
  - Chinese Academy of Sciences,University of Chinese Academy of Sciences
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **Securely Fine-tuning Pre-trained Encoders Against Adversarial Examples** [[pdf]](https://arxiv.org/abs/2403.10801) [[code]](https://github.com/CGCL-codes/Gen-AF)
  - Ziqi Zhou,Minghui Li,Wei Liu,Shengshan Hu,Yechao Zhang,Wei Wan,Lulu Xue,Leo Yu Zhang,Dezhong Yao,Hai Jin
  - National Engineering Research Center for Big Data Technology and System,Services Computing Technology and System Lab,Hubei Engineering Research Center on Big Data Security,Hubei Key Laboratory of Distributed System Security
  - Proceedings of the IEEE Symposium on Security and Privacy (S&P 2024)
- **Defense against Adversarial Cloud Attack on Remote Sensing Salient Object Detection** [[pdf]](https://arxiv.org/abs/2306.17431)
  - Huiming Sun,Lan Fu,Jinlong Li,Qing Guo,Zibo Meng,Tianyun Zhan,Yuewei Lin,Hongkai Yu
  - Cleveland State University ,OPPO US Research Center,IHPC and CFAR, Agency for Science, Technology and Research (A*STAR),Brookhaven National Laboratory
  - Proceedings of the IEEE Winter Conference on Applications of Computer Vision (WACV 2024)
- **Sim-CLIP: Unsupervised Siamese Adversarial Fine-Tuning for Robust and Semantically-Rich Vision-Language Models** [[pdf]](https://arxiv.org/abs/2407.14971) 
  - Md Zarif Hossain,Ahmed Imteaj
  - Southern Illinois University, Security, Privacy and Intelligence for Edge Devices Laboratory (SPEED Lab)
  - arXiv 2024
- **Adversarial Prompt Tuning for Vision-Language Models** [[pdf]](https://arxiv.org/abs/2407.14971) [[code]](https://github.com/jiamingzhang94/Adversarial-Prompt-Tuning)
  - Jiaming Zhang,Xingjun Ma,Xin Wang,Lingyu Qiu,Jiaqi Wang,Yu-Gang Jiang,Jitao Sang
  - Beijing Jiaotong Univisity,Fudan Univisity,Nanjing University of Aeronautics and Astronautics
  - arXiv 2024

  
## Backdoor Attacks

- **Backdoor Attacks for In-Context Learning with Language Models** [[pdf]](https://arxiv.org/abs/2307.14692)
  - Nikhil Kandpal, Matthew Jagielski, Florian Tramèr, Nicholas Carlini
  - UNC Chapel Hill, ETH Zurich
  - ICML 2023 Workshop AdvML-Frontiers

- **Privacy Backdoors: Enhancing Membership Inference** [[pdf]](https://arxiv.org/abs/2404.01231)
  - Yiming Chen, Ruoxi Jia, Xiaoyu Cao, Jiayu Lin
  - Department of Computer Science, Virginia Tech; Department of Electrical and Computer Engineering, Virginia Tech
  - ICLR 2024

- **An Embarrassingly Simple Backdoor Attack on Self-supervised Learning** [[pdf]](https://arxiv.org/abs/2210.07346)
  - Changjiang Li, Ren Pang, Zhaohan Xi, Tianyu Du, Shouling Ji, Yuan Yao, Ting Wang
  - Pennsylvania State University, Zhejiang University, Nanjing University
  - ICCV 2023

- **Anti-Backdoor Learning: Training Clean Models on Poisoned Data** [[pdf]](https://arxiv.org/abs/2110.11571)
  - Jinyuan Jia, Yupei Liu, Neil Zhenqiang Gong
  - Duke University
  - ICLR 2021

- **BADFSS: Backdoor Attacks on Federated Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2405.13080)
  - Zhihao Cheng, Yunchang Zhang, Xuxian Jiang
  - Huazhong University of Science and Technology, Tsinghua University, Zhejiang University
  - ICML 2024

- **Backdoor Attacks Against Deep Image Compression via Adaptive Frequency Trigger** [[pdf]](https://arxiv.org/abs/2302.14677)
  - Yi Yu, Yufei Wang, Wenhan Yang, Shijian Lu, Yap-Peng Tan, Alex C. Kot
  - Nanyang Technological University, Peng Cheng Laboratory, IGP-ROSE
  - IEEE Transactions on Information Forensics and Security (TIFS)

- **Backdoor Attacks in the Supply Chain of Masked Image Modeling** [[pdf]](https://arxiv.org/abs/2210.01632)
  - Weidi Zhang, Ziqiang Wang, Fang Song, Xu Chen, Aojun Zhou
  - Xidian University, Hong Kong University of Science and Technology, Huawei Technologies
  - arXiv 2022

- **Backdoor Attacks on Pre-trained Models by Layerwise Weight Poisoning** [[pdf]](https://arxiv.org/abs/2108.13888)
  - Kang Liu, Brendan Dolan-Gavitt, Siddharth Garg
  - New York University, Tandon School of Engineering
  - arXiv 2021

- **Backdoor Attacks on Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2105.10123)
  - Asil Kaan Bozkurt, Sahar Abdelnabi, M. Saad Al-Azzawi, Mario Fritz
  - Max Planck Institute for Informatics
  - ICLR 2021

- **Backdoor Contrastive Learning via Bi-level Trigger Optimization** [[pdf]](https://arxiv.org/abs/2404.07863)
  - Weiyu Sun, Xinyu Zhang, Yifan Liu, Yingyu Liang
  - University of Wisconsin-Madison, University of Illinois Urbana-Champaign
  - arXiv 2024

- **Backdoor Attack with Imperceptible Input and Latent Modification** [[pdf]](https://arxiv.org/abs/2205.03190)
  - Khoa D. Doan, Yingjie Lao, Weijie Zhao, Ping Li
  - New Jersey Institute of Technology, Florida International University, Rutgers University
  - NeurIPS 2021

- **BadEncoder: Backdoor Attacks to Pre-trained Encoders in Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2108.00352)
  - Kang Liu, Siddharth Garg, Brendan Dolan-Gavitt
  - New York University
  - arXiv 2024

- **Better Safe than Sorry: Pre-training CLIP against Targeted Data Poisoning and Backdoor Attacks** [[pdf]](https://arxiv.org/abs/2310.05862)
  - Yang Zhang, Amir H. Mirzazadeh, Florian Tramer, Ludovic Schmidt
  - University of Tübingen, ETH Zurich, Google Research
  - arXiv 2024

- **Bypassing Backdoor Detection Algorithms in Deep Learning** [[pdf]](https://arxiv.org/abs/1905.13409)
  - Yao Fu, Xiaoxuan Zhang, Shouling Ji, Weiqiang Wang
  - Zhejiang University, University of Texas at Austin, Virginia Tech
  - arXiv 2024

- **Data Poisoning based Backdoor Attacks to Contrastive Learning** [[pdf]](https://arxiv.org/abs/2211.08229)
  - Weidi Zhang, Yuan Yao, Qinghua Zheng, Xu Chen
  - Xidian University, University of Electronic Science and Technology of China
  - arXiv 2024

- **Distribution Preserving Backdoor Attack in Self-supervised Learning** [[pdf]](https://arxiv.org/abs/2405.10757)
  - Khoa D. Doan, Weiqiang Wang, Shouling Ji, Liwei Wang
  - Zhejiang University, University of Texas at Austin, Virginia Tech
  - arXiv 2024

- **ESTAS: Effective and Stable Trojan Attacks in Self-supervised Encoders with One Target** [[pdf]](https://arxiv.org/abs/2211.10908)
  - Jiaqi Xue, Qian Lou
  - University of Central Florida
  - arXiv 2024

- **GhostEncoder: Stealthy Backdoor Attacks with Dynamic Triggers to Pre-trained Encoders** [[pdf]](https://arxiv.org/abs/2310.00626)
  - Qiannan Wang, Changchun Yin, Zhe Liu, Liming Fang, Run Wang, Chenhao Lin
  - Nanjing University of Aeronautics and Astronautics, Shenzhen Research Institute
  - arXiv 2023

- **Invisible Backdoor Attacks on Key Regions Based on Target Neurons in Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2405.11551)
  - Ning Zhang, Zhiwei Liu, Jing Liu, Zhen Liu
  - Peking University, Tsinghua University, Beijing Institute of Technology
  - arXiv 2024

- **PoisonedEncoder: Poisoning the Unlabeled Pre-training Data in Contrastive Learning** [[pdf]](https://arxiv.org/abs/2205.06401)
  - Hongbin Liu, Jinyuan Jia, Neil Gong
  - Duke University
  - arXiv 2024

- **Poisoning And Back Dooring Contrastive Learning** [[pdf]](https://arxiv.org/abs/2106.09667)
  - Nicholas Carlini, Andreas Terzis
  - Google Research
  - arXiv 2024

- **SSLJBA: Joint Backdoor Attack on Both Robustness and Fairness of Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2405.14672)
  - Xu Liu, Han Zhang, Jingwen Bai, Yingyu Liang
  - University of Wisconsin-Madison, Huawei Noah’s Ark Lab
  - arXiv 2024

- **The Perils of Learning From Unlabeled Data: Backdoor Attacks on Semi-supervised Learning** [[pdf]](https://arxiv.org/abs/2211.00453)
  - Virat Shejwalkar, Lingjuan Lyu, Amir Houmansadr
  - University of Massachusetts Amherst, Sony AI
  - arXiv 2024

- **Towards Imperceptible Backdoor Attack in Self-supervised Learning** [[pdf]](https://arxiv.org/abs/2405.14672)
  - Yujing Liu, Wei Li, Xiaoyu Cao
  - Tsinghua University, Beijing Institute of Technology
  - arXiv 2024

- **TransTroj: Transferable Backdoor Attacks to Pre-trained Models via Embedding Indistinguishability** [[pdf]](https://arxiv.org/abs/2401.15883)
  - Zhenyu Zhang, Hong Wang, Chuan Guo, Haiyu Zhao
  - Tsinghua University, Tencent AI Lab
  - arXiv 2024

- **WITCHES’ BREW: Industrial Scale Data Poisoning via Gradient Matching** [[pdf]](https://arxiv.org/abs/2009.02276)
  - Jonas Geiping, Liam Fowl, Wojciech Czaja, Gavin Taylor, Micah Goldblum, Tom Goldstein
  - University of Maryland, College Park
  - arXiv 2024


## Privacy Attacks

## The Other Security Issues
