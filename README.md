# **Understanding the Security Landscape of Pre-trained Encoders: A Comprehensive Survey**

A **continual** collection of papers related to Attacks and Defenses in the pre-training scenario.

Pre-trained encoders have drawn increasing attention in recent years due to its superior performance on numerous downstream tasks after fine-tuning.
Despite their remarkable capabilities, the increased complexity and deployment of  pre-trained encoders have also exposed them to various security threats and vulnerabilities, making the study of attacks on these models a critical area of research.

Here, we've summarized existing attack and defense methods for pre-trained encoders in our survey paper👍.
|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  26  |  60  |  104  |

> If you find some important work missed, it would be super helpful to let me know (zhouziqi@hust.edu.cn). Thanks!

> If you find our survey useful for your research, please consider citing:

```
@article{,
  title={Understanding the Security Landscape of Pre-trained Encoders: A Comprehensive Survey},
  author={xxxx},
  journal={xxxx},
  year={2024}
}
```

**Table of Contents**

- [Adversarial Attacks](#Adversarial-Attacks)
- [Backdoor Attacks](#Backdoor-Attacks)
- [Privacy Attacks](#Privacy-Attacks)
- [The Other Security Issues](#The-Other-Security-Issues)

---

## Adversarial Attacks

|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  8   |  9   |  20   |

- **A Multi-task Adversarial Attack Against Face Authentication** [[pdf]](https://arxiv.org/abs/2408.08205) [[code]](https://github.com/azrealwang/mtadv)
  - Hanrui Wang, Shuo Wang, Cunjian Chen, Massimo Tistarelli, Zhe Jin
  - Shanghai Jiao Tong University, Monash University, University of Sassari, Anhui University
  - arXiv 2024
- **A Unified Understanding of Adversarial Vulnerability Regarding Unimodal Models and Vision-Language Pre-training Models** [[pdf]](https://arxiv.org/abs/2407.17797) [[code]](https://github.com/LibertazZ/FGA)
  - Haonan Zheng, Xinyang Deng, Wen Jiang, Wenrui Li
  - Northwestern Polytechnical University School of Electronics and Information, Harbin Institute of Technology Department of Computer Science and Technology
  - Proceedings of the ACM International Conference on Multimedia (ACM MM 2024)
- **Content-based Unrestricted Adversarial Attack** [[pdf]](https://arxiv.org/abs/2305.10665)
  - Zhaoyu Chen, Bo Li, Shuang Wu, Kaixun Jiang, Shouhong Ding, Wenqiang Zhang
  - Fudan University, Youtu Lab
  - Proceedings of the Neural Information Processing Systems (NuerIPS 2024)
- **Downstream Transfer Attack: Adversarial Attacks on Downstream Models with Pre-trained Vision Transformers** [[pdf]](https://arxiv.org/abs/2408.01705)
  - Weijie Zheng, Xingjun Ma, Hanxun Huang, Jun Yin, Tiehua Zhang, Zuxuan Wu, Yu-Gang Jiang
  - arXiv 2024
- **DifAttack: Query-Effcient Black-Box Adversarial Attack via Disentangled Feature Space** [[pdf]](https://arxiv.org/abs/2309.14585) [[code]](https://github.com/csjunjun/DifAttack)
  - Liu Jun, Zhou Jiantao, Zeng Jiandian, Tian Jinyu
  - State Key Laboratory of Internet of Things for Smart City, University of Macau, Beijing Normal University, Macau University of Science and Technology
  - Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI 2024)
- **Mutual-Modality Adversarial Attack with Semantic Perturbation** [[pdf]](https://arxiv.org/abs/2312.12768)
  - Jingwen Ye, Ruonan Yu, Songhua Liu, Xinchao Wang
  - National University of Singapore
  - Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI 2024)
- **Enhancing the Transferability of Adversarial Attacks with Stealth Preservation** [[pdf]](https://openaccess.thecvf.com/content/CVPR2024W/AdvML/papers/Zhang_Enhancing_the_Transferability_of_Adversarial_Attacks_with_Stealth_Preservation_CVPRW_2024_paper.pdf)
  - Xinwei Zhang, Tianyuan Zhang, Yitong Zhang, Shuangcheng Liu
  - Beihang University
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **One Perturbation is Enough: On Generating Universal Adversarial Perturbations against Vision-Language Pre-training Models** [[pdf]](https://arxiv.org/abs/2406.05491)
  - Hao Fang, Jiawei Kong, Wenbo Yu, Bin Chen, Jiawei Li, Shu-Tao Xia, Ke Xu
  - Tsinghua Shenzhen International Graduate School, Tsinghua University, Harbin Institute of Technology,Huawei Technology 
  - arXiv 2024
- **BLACK-BOX TARGETED ADVERSARIAL ATTACK ON SEGMENT ANYTHING (SAM)** [[pdf]](https://arxiv.org/abs/2310.10010)
  - Sheng Zheng, Chaoning Zhang, Xinhong Hao
  - Beijing Institute of Technology, Kyung Hee University
  - arXiv 2023
- **Iterative Adversarial Attack on Image-guided Story Ending Generation** [[pdf]](https://arxiv.org/pdf/2305.13208v1) [[code]](https://github.com/frgfm/torch-cam)
  - Youze Wang, Wenbo Hu, Richang Hong
  - IEEE Transactions on Multimedia (2023)
- **Downstream-agnostic Adversarial Examples** [[pdf]](https://arxiv.org/pdf/2307.12280) [[code]](https://github.com/CGCL-codes/AdvEncoder)
  - Ziqi Zhou, Shengshan Hu, Ruizhi Zhao, Qian Wang, Leo Yu Zhang, Junhui Hou, Hai Jin
  - Huazhong University of Science and Technology, Wuhan University, Griffith University, City University of Hong Kong
  - Proceedings of the International Conference on Computer Vision (ICCV 2023)
- **SA-Attack: Improving Adversarial Transferability of Vision-Language Pre-training Models via Self-Augmentation** [[pdf]](https://arxiv.org/abs/2312.04913) 
  - Bangyan He, Xiaojun Jia, Siyuan Liang, Tianrui Lou, Yang Liu, Xiaochun Cao
  - Institute of Information Engineering, Chinese Academy of Sciences, Nanyang Technological University, National University of Singapore, Sun Yat-sen University
  - arXiv 2023
- **AdvCLIP: Downstream-agnostic Adversarial Examples in Multimodal Contrastive Learning** [[pdf]](https://arxiv.org/abs/2308.07026) [[code]](https://github.com/CGCL-codes/AdvCLIP)
  * Ziqi Zhou, Shengshan Hu, Minghui Li, Hangtao Zhang, Yechao Zhang, Hai Jin
  * Huazhong University of Science and Technology
  * Proceedings of the ACM International Conference on Multimedia (ACM MM 2023)
- **CodeAttack: Code-Based Adversarial Attacks for Pre-trained Programming Language Models** [[pdf]](https://arxiv.org/abs/2206.00052) [[code]](https://github.com/reddy-lab-code-research/CodeAttack)
  - Akshita Jha, Chandan K. Reddy
  - Department of Computer Science, Virginia Tech
  - Proceedings of the Association for the Advancement of Artificial Intelligence (AAAI 2023)
- **OT-Attack: Enhancing Adversarial Transferability of Vision-Language Models via Optimal Transport Optimization** [[pdf]](https://arxiv.org/abs/2312.04403)
  - Dongchen Han, Xiaojun Jia, Yang Bai, Jindong Gu, Yang Liu, Xiaochun Cao
  - Shenzhen Campus of Sun Yat-sen University, Nanyang Technological University, Tsinghua University, University of Oxford
  - arXiv 2023
- **Black-Box Sparse Adversarial Attack via Multi-Objective Optimisation** [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Williams_Black-Box_Sparse_Adversarial_Attack_via_Multi-Objective_Optimisation_CVPR_2023_paper.pdf)
  - Phoenix Neale Williams, Ke Li
  - University of Exeter, Stocker Rd, Exeter, EX4 4PY
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2023)
- **HQA-Attack: Toward High Quality Black-Box Hard-Label Adversarial Attack on Text** [[pdf]](https://arxiv.org/abs/2402.01806) [[code]](https://github.com/HQA-Attack/HQAAttack-demo)
  - Han Liu, Zhi Xu, Xiaotong Zhang, Feng Zhang, Fenglong Ma, Hongyang Chen, Hong Yu, Xianchao Zhang
  - Dalian University of Technology, Peking University, The Pennsylvania State University, Zhejiang Lab
  - Proceedings of the Neural Information Processing Systems (NeurIPS 2024)
- **Towards Adversarial Attack on Vision-Language Pre-training Models** [[pdf]](https://arxiv.org/abs/2206.09391) [[code]](https://github.com/adversarial-for-goodness/Co-Attack)
  - Jiaming Zhang, Qi Yi, Jitao Sang
  - Beijing Jiaotong University, Peng Cheng Lab
  - Proceedings of the ACM International Conference on Multimedia (ACM MM 2022)
- **Pre-trained Adversarial Perturbations** [[pdf]](https://arxiv.org/abs/2210.03372) [[code]](https://github.com/banyuanhao/PAP)
  - Yuanhao Ban, Yinpeng Dong
  - BNRist Center, Tsinghua-Bosch Joint ML Center, THBI Lab, Tsinghua University, RealAI
  - Proceedings of the Neural Information Processing Systems (NeurIPS 2022)
- **DI-AA: An Interpretable White-box Attack for Fooling Deep Neural Networks** [[pdf]](https://arxiv.org/abs/2110.07305)
  - Yixiang Wang, Jiqiang Liu, Xiaolin Chang, Jianhua Wang, Ricardo J. Rodríguez
  - Beijing Jiaotong University, University of Zaragoza
  - Information Sciences (2022)

## Adversarial Defense

|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  1   |  11  |  15   |



- **MirrorCheck: Efficient Adversarial Defense for Vision-Language Models** [[pdf]](https://arxiv.org/abs/2406.09250)
  - Samar Fares,Klea Ziu, Toluwani Aremu, Nikita Durasov, Martin Takác, Pascal Fua, Karthik Nandakumar, Ivan Laptev
  - Mohamed bin Zayed University of Artificial Intelligence, Computer Vision Laboratory, EPFL
  - arXiv 2024
- **One Prompt Word is Enough to Boost Adversarial Robustness for Pre-trained Vision-Language Models** [[pdf]](https://arxiv.org/abs/2403.01849) [[code]](https://github.com/TreeLLi/APT)
  - Lin Li, Haoyan Guan, Jianing Qiu, Michael Spratling
  - King’s College London, Imperial College London
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **Apollon: A robust defense system against Adversarial Machine Learning attacks in Intrusion Detection Systems** [[pdf]](https://www.sciencedirect.com/science/article/pii/S016740482300456X) [[code]](https://github.com/antoniopaya22/apollon)
  - Antonio Paya, Sergio Arroni, Vicente García-Díaz, Alberto Gómez
  - University of Oviedo
  - Computers & Security (2024)
- **Model-agnostic adversarial example detection via high-frequency amplification** [[pdf]](https://www.sciencedirect.com/science/article/pii/S0167404824000920)
  - Qiao Li, Jing Chen, Kun He, Zijun Zhang, Ruiying Du, Jisi She, Xinxin Wang
  - Key Laboratory of Aerospace Information Security and Trusted Computing, Ministry of Education, School of Cyber Science and Engineering, Rizhao Institute of Information Technology, Wuhan University, Collaborative Innovation Center of Geospatial Technology
  - Computers & Security (2024)
- **PAD: Patch-Agnostic Defense against Adversarial Patch Attacks** [[pdf]](https://arxiv.org/abs/2404.16452) [[code]](https://github.com/Lihua-Jing/PAD)
  - Lihua Jing, Rui Wang, Wenqi Ren, Xin Dong, Cong Zou
  - Chinese Academy of Sciences, University of Chinese Academy of Sciences, Shenzhen Campus of Sun Yat-sen University
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **Pre-trained Model Guided Fine-Tuning for Zero-Shot Adversarial Robustness** [[pdf]](https://arxiv.org/abs/2401.04350) [[code]](https://github.com/serendipity1122/Pre-trained-Model-Guided-Fine-Tuning-for-Zero-Shot-Adversarial-Robustness)
  - Sibo Wang, Jie Zhang, Zheng Yuan, Shiguang Shan
  - Chinese Academy of Sciences, University of Chinese Academy of Sciences
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2024)
- **Securely Fine-tuning Pre-trained Encoders Against Adversarial Examples** [[pdf]](https://arxiv.org/abs/2403.10801) [[code]](https://github.com/CGCL-codes/Gen-AF)
  - Ziqi Zhou, Minghui Li, Wei Liu, Shengshan Hu, Yechao Zhang, Wei Wan, Lulu Xue, Leo Yu Zhang, Dezhong Yao, Hai Jin
  - National Engineering Research Center for Big Data Technology and System, Services Computing Technology and System Lab, Hubei Engineering Research Center on Big Data Security, Hubei Key Laboratory of Distributed System Security
  - Proceedings of the IEEE Symposium on Security and Privacy (S&P 2024)
- **Defense against Adversarial Cloud Attack on Remote Sensing Salient Object Detection** [[pdf]](https://arxiv.org/abs/2306.17431)
  - Huiming Sun, Lan Fu, Jinlong Li, Qing Guo, Zibo Meng, Tianyun Zhan, Yuewei Lin, Hongkai Yu
  - Cleveland State University, OPPO US Research Center, IHPC and CFAR, Brookhaven National Laboratory
  - Proceedings of the IEEE Winter Conference on Applications of Computer Vision (WACV 2024)
- **Sim-CLIP: Unsupervised Siamese Adversarial Fine-Tuning for Robust and Semantically-Rich Vision-Language Models** [[pdf]](https://arxiv.org/abs/2407.14971) 
  - Md Zarif Hossain, Ahmed Imteaj
  - Southern Illinois University, SPEED Lab
  - arXiv 2024
- **Adversarial Prompt Tuning for Vision-Language Models** [[pdf]](https://arxiv.org/abs/2311.11261) [[code]](https://github.com/jiamingzhang94/Adversarial-Prompt-Tuning)
  - Jiaming Zhang, Xingjun Ma, Xin Wang, Lingyu Qiu, Jiaqi Wang, Yu-Gang Jiang, Jitao Sang
  - Beijing Jiaotong Univisity, Fudan Univisity, Nanjing University of Aeronautics and Astronautics
  - arXiv 2023
- **Continual Adversarial Defense** [[pdf]](https://arxiv.org/abs/2312.09481)
  - Qian Wang, Yaoyao Liu, Hefei Ling, Yingwei Li, Qihao Liu, Ping Li, Jiazhong Chen, Alan Yuille, Ning Yu
  - Huazhong University of Science and Technology, Johns Hopkins University,Salesforce Research
  - arXiv 2023
- **The Best Defense is a Good Offense: Adversarial Augmentation against Adversarial Attacks** [[pdf]](https://arxiv.org/abs/2305.14188) [[code]](https://github.com/NVlabs/A5)
  - Iuri Frosio, Jan Kautz
  - NVIDIA
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2023)
- **LAS-AT: Adversarial Training with Learnable Attack Strategy** [[pdf]](https://arxiv.org/abs/2203.06616) [[code]](https://github.com/jiaxiaojunQAQ/LAS-AT)
  - Xiaojun Jia, Yong Zhang, Baoyuan Wu, Ke Ma, Jue Wang, Xiaochun Cao
  - University of Chinese Academy of Sciences, Tencent, The Chinese University of Hong Kong, Shenzhen Research Institute of Big Data
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2022)
- **Sample Efficient Detection and Classification of Adversarial Attacks via Self-Supervised Embeddings** [[pdf]](https://arxiv.org/abs/2108.13797)
  - Mazda Moayeri, Soheil Feizi
  - Department of Computer Science University of Maryland
  - Proceedings of the International Conference on Computer Vision (ICCV 2021)
- **A Self-supervised Approach for Adversarial Robustness** [[pdf]](https://arxiv.org/abs/2006.04924) [[code]](https://github.com/Muzammal-Naseer/NRP)
  - Muzammal Naseer, Salman Khan, Munawar Hayat, Fahad Shahbaz Khan, Fatih Porikli
  - Australian National University, Data61-CSIRO, Inception Institute of Artificial Intelligence, Linkoping University
  - Proceedings of the Computer Vision and Pattern Recognition (CVPR 2020)


  
## Backdoor Attacks
|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  6   |  11  |  24   |

- **BADFSS: Backdoor Attacks on Federated Self-Supervised Learning** [[pdf]](https://www.ijcai.org/proceedings/2024/0061.pdf)
  - Jiale Zhang, Chengcheng Zhu, Di Wu, Xiaobing Sun, Jianming Yong, Guodong Long
  - Yangzhou University, University of Southern Queensland, University of Technology Sydney
  - Proceedings of the International Conference on Machine Learning (ICML 2024)

- **Invisible Backdoor Attacks on Key Regions Based on Target Neurons in Self-Supervised Learning** [[pdf]](https://link.springer.com/content/pdf/10.1007/978-981-97-5498-4.pdf)
  - Xiangyun Qian, Yusheng He, Rui Zhang, Zi Kang, Yilin Sheng & Hui Xia
  - Ocean University of China
  - Proceedings of International Conference on Knowledge Science, Engineering and Management (KSEM 2024)

- **SSLJBA: Joint Backdoor Attack on Both Robustness and Fairness of Self-Supervised Learning** [[pdf]](https://www.techrxiv.org/doi/pdf/10.36227/techrxiv.23899920.v1/v1)
  - Fengrui Hao, Tianlong Gu, Jionghui Jiang, Ming Liu
  - Jinan University, Guangzhou Research Institute of Information Technology
  - TechRxiv 2024

- **Distribution Preserving Backdoor Attack in Self-supervised Learning** [[pdf]](https://www.cs.purdue.edu/homes/taog/docs/SP24.pdf)
  - Guanhong Tao, Zhenting Wang, Shiwei Feng, Guangyu Shen, Shiqing Ma, Xiangyu Zhang
  - Purdue University, Rutgers University, University of Massachusetts Amherst
  - Proceedings of IEEE Symposium on Security and Privacy (SP 2024)

- **Backdoor Contrastive Learning via Bi-level Trigger Optimization** [[pdf]](https://openreview.net/pdf?id=oxjeePpgSP)
  - Weiyu Sun, Xinyu Zhang, Hao LU, Ying-Cong Chen, Ting Wang, Jinghui Chen, Lu Lin
  - Nanjing University, The Hong Kong University of Science and Technology, Stony Brook University, The Pennsylvania State University
  - International Conference on Learning Representations (ICLR 2024)

- **Privacy Backdoors: Enhancing Membership Inference** [[pdf]](https://arxiv.org/abs/2404.01231)
  - Y Wen, L Marchyok, S Hong, J Geiping, T Goldstein, N Carlini
  - University of Maryland, Oregon State University, ELLIS Institute, Tübingen & MPI Intelligent Systems, Tübingen AI Center
  - Proceedings of the International Conference on Learning Representations (ICLR 2024)

- **TransTroj: Transferable Backdoor Attacks to Pre-trained Models via Embedding Indistinguishability** [[pdf]](https://arxiv.org/abs/2401.15883)
  - H Wang, T Xiang, S Guo, J He, H Liu, T Zhang
  - Chongqing University, Nanyang Technological University
  - arXiv 2024

- **PoisonedEncoder: Poisoning the Unlabeled Pre-training Data in Contrastive Learning** [[pdf]](https://www.usenix.org/system/files/sec22-liu-hongbin.pdf)
  - H Liu, J Jia, NZ Gong
  - Duke University
  - USENIX Security Symposium (USENIX Sec 2024)

- **Better Safe than Sorry: Pre-training CLIP against Targeted Data Poisoning and Backdoor Attacks** [[pdf]](https://arxiv.org/abs/2310.05862)
  - W Yang, J Gao, B Mirzasoleiman
  - University of California, Los Angeles
  - Proceedings of International Conference on Machine Learning (ICML 2024)

- **GhostEncoder: Stealthy Backdoor Attacks with Dynamic Triggers to Pre-trained Encoders** [[pdf]](https://arxiv.org/abs/2310.00626)
  - Q Wang, C Yin, L Fang, Z Liu, R Wang, C Lin
  - Nanjing University, Zhejiang Lab, Wuhan University, Xi’an Jiaotong University
  - Computers & Security (2024)
    
- **Data Poisoning based Backdoor Attacks to Contrastive Learning** [[pdf]](https://arxiv.org/abs/2211.08229)
  - J Zhang, H Liu, J Jia, NZ Gong
  - University of California, Duke University
  - Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024)
 
- **Towards Imperceptible Backdoor Attack in Self-supervised Learning** [[pdf]](https://arxiv.org/abs/2405.14672)
  - H Zhang, Z Wang, T Han, M Jin, C Zhan, M Du, H Wang, S Ma
  - ZJU-UIUC Joint Institute, Zhejiang University, Rutgers University, Nanjing University, New Jersey Institute of Technology, University of Massachusetts Amherst
  - arXiv 2024

- **Bypassing Backdoor Detection Algorithms in Deep Learning** [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9230390)
  - Te Juin Lester Tan, Reza Shokri
  - National University of Singapore
  - IEEE Virtual Conference on Communications (VCC 2023)

- **ESTAS: Effective and Stable Trojan Attacks in Self-supervised Encoders with One Target** [[pdf]](https://arxiv.org/abs/2211.10908)
  - J Xue, Q Lou
  - University of Central Florida
  - arXiv 2023

- **The Perils of Learning From Unlabeled Data: Backdoor Attacks on Semi-supervised Learning** [[pdf]](https://arxiv.org/abs/2211.00453)
  - V Shejwalkar, L Lyu, A Houmansadr
  - University of Massachusetts Amherst, Sony AI
  - Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV 2023)

- **Backdoor Attacks for In-Context Learning with Language Models** [[pdf]](https://arxiv.org/abs/2307.14692)
  - N Kandpal, M Jagielski, F Tramèr, N Carlini
  - UNC Chapel Hill, Google DeepMind, ETH Zurich
  - Proceedings of the International Conference on Machine Learning (ICML 2023)

- **Backdoor Attacks Against Deep Image Compression via Adaptive Frequency Trigger** [[pdf]](https://arxiv.org/abs/2302.14677)
  - Y Yu, Y Wang, W Yang, S Lu, YP Tan, AC Kot
  - Nanyang Technological University, Peng Cheng Lab
  - Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2023)

- **An Embarrassingly Simple Backdoor Attack on Self-supervised Learning** [[pdf]](https://arxiv.org/abs/2210.07346)
  - C Li, R Pang, Z Xi, T Du, S Ji, Y Yao, T Wang
  - Pennsylvania State University, Zhejiang University, Nanjing University
  - Proceedings of the International Conference on Computer Vision (ICCV 2023)

- **Backdoor Attacks in the Supply Chain of Masked Image Modeling** [[pdf]](https://arxiv.org/abs/2210.01632)
  - X Shen, X He, Z Li, Y Shen, M Backes, Y Zhang
  - CISPA Helmholtz Center for Information Security, NetApp
  - arXiv 2022

- **Poisoning And Backdooring Contrastive Learning** [[pdf]](https://arxiv.org/abs/2106.09667)
  - N Carlini, A Terzis
  - University of Alberta, Illinois Institute of Technology, Michigan State University
  - arXiv 2022

- **BadEncoder: Backdoor Attacks to Pre-trained Encoders in Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2108.00352)
  - J Jia, Y Liu, NZ Gong
  - Duke University
  - Proceedings of IEEE Symposium on Security and Privacy (SP 2022)

- **Backdoor Attacks on Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2105.10123)
  - Aniruddha Saha, Ajinkya Tejankar, Soroush Abbasi Koohpayegani, Hamed Pirsiavash
  - University of Maryland, Baltimore County, University of California, Davis
  - Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2022)
    
- **Backdoor Attacks on Pre-trained Models by Layerwise Weight Poisoning** [[pdf]](https://arxiv.org/abs/2108.13888)
  - L Li, D Song, X Li, J Zeng, R Ma, X Qiu
  - School of Computer Science, Fudan University, Shanghai Key Laboratory of Intelligent Information Processing, Fudan University, Pazhou Lab
  - Proceedings of Conference on Empirical Methods in Natural Language Processing (EMNLP 2021)

- **WITCHES' BREW: Industrial Scale Data Poisoning via Gradient Matching** [[pdf]](https://arxiv.org/abs/2009.02276)
  - J Geiping, L Fowl, WR Huang, W Czaja, G Taylor, M Moeller, T Goldstein
  - University of Siegen, University of Maryland, US Naval Academy
  - Proceedings of the International Conference on Learning Representations (ICLR 2021) 




## Backdoor Defense
|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  6   |  12  |  20   |

- **An Embarrassingly Simple Defense Against Backdoor Attacks On SSL** [[pdf]](https://arxiv.org/abs/2403.15918)
   - A Satpathy, D Rajwade
   - Indian Institute of Technology, Kharagpur
   - arXiv 2024

- **EmInspector: Combating Backdoor Attacks in Federated Self-Supervised Learning Through Embedding Inspection** [[pdf]](https://arxiv.org/abs/2405.13080) [[code]](https://github.com/ShuchiWu/EmInspector)
   - Y Qian, S Wu, K Wei, M Ding, D Xiao, T Xiang, C Ma, S Guo
   - University of Science and Technology of China, Tsinghua University, City University of Hong Kong
   - arXiv 2024

- **Mutual Information Guided Backdoor Mitigation for Pre-trained Encoders** [[pdf]](https://ar5iv.org/abs/2406.03508v2)
   - T Han, W Sun, Z Ding, C Fang, H Qian, J Li, Z Chen, X Zhang
   - Nanjing University, Nanyang Technological University, University of New South Wales, Soochow University, Purdue University
   - arXiv 2024

- **ASSET: Robust Backdoor Data Detection Across a Multiplicity of Deep Learning Paradigms** [[pdf]](https://arxiv.org/abs/2302.11408) [[code]](https://github.com/ruoxi-jia-group/ASSET)
   - Minzhou Pan, Yi Zeng, Lingjuan Lyu, Xue Lin, Ruoxi Jia
   - Virginia Tech, Sony AI, Northeastern University
   - USENIX Security Symposium (USENIX Security

- **Defending Against Patch-based Backdoor Attacks on Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2304.01482)
   - Ajinkya Tejankar, Maziar Sanjabi, Qifan Wang, Sinong Wang, Hamed Firooz, Hamed Pirsiavash, Liang Tan
   - University of Maryland, Facebook AI Research, Amazon Web Services
   - arXiv 2024

- **Defending Pre-trained Language Models as Few-shot Learners against Backdoor Attacks** [[pdf]](https://arxiv.org/abs/2309.13256)
   - Zhaohan Xi, Tianyu Du, Changjiang Li, Ren Pang, Shouling Ji, Jinghui Chen, Fenglong Ma, Ting Wang
   - Microsoft Research, Hong Kong University of Science and Technology
   - arXiv 2024

- **Detecting Backdoors in Pre-trained Encoders** [[pdf]](https://arxiv.org/abs/2303.15180)
   - Shiwei Feng, Guanhong Tao, Siyuan Cheng, Guangyu Shen, Xiangzhe Xu, Yingqi Liu, Kaiyuan Zhang, Shiqing Ma, Xiangyu Zhang
   - University of California, Irvine, Drexel University, University of Central Florida
   - arXiv 2024

- **Erasing Self-Supervised Learning Backdoor by Cluster Activation Masking** [[pdf]](https://arxiv.org/abs/2312.07955)
   - Shengsheng Qian, Yifei Wang, Dizhan Xue, Shengjie Zhang, Huaiwen Zhang, Changsheng Xu
   - Tsinghua University, University of Electronic Science and Technology of China
   - arXiv 2024

- **On the Difficulty of Defending Contrastive Learning against Backdoor Attacks** [[pdf]](https://arxiv.org/abs/2312.09057)
   - Changjiang Li, Ren Pang, Bochuan Cao, Zhaohan Xi, Jinghui Chen, Shouling Ji, Ting Wang
   - Stony Brook University, Pennsylvania State University, Zhejiang University
   - arXiv 2024

- **Self-supervised learning backdoor defense mixed with self-attention mechanism** [[pdf]](https://arxiv.org/abs/2408.11679)
    - G Yuan, H Huang, X Li
    - Tsinghua University, Chinese Academy of Sciences
    - arXiv 2024

- **Robust Contrastive Language-Image Pre-training against Data Poisoning and Backdoor Attacks** [[pdf]](https://arxiv.org/abs/2310.05862)
    - Wenhan Yang, Jingdong Gao, Baharan Mirzasoleiman
    - University of California, Berkeley, Shanghai Jiao Tong University
    - arXiv 2024

- **SSL-Cleanse: Trojan Detection and Mitigation in Self-Supervised Learning** [[pdf]](https://arxiv.org/abs/2303.09079) [[code]](https://github.com/UCF-ML-Research/SSL-Cleanse)
    - Mengxin Zheng, Jiaqi Xue, Zihao Wang, Xun Chen, Qian Lou, Lei Jiang, Xiaofeng Wang
    - University of Central Florida, Indiana University Bloomington, Samsung Research America
    - Proceedings of the European Conference on Computer Vision (ECCV 2024)

- **Mitigating Backdoor Attacks in Pre-trained Encoders via Self-supervised Knowledge Distillation** [[pdf]](https://arxiv.org/abs/2303.15180)
    - Rongfang Bie, Jinxiu Jiang, Hongcheng Xie, Yu Guo, Yinbin Miao, Xiaohua Jia
    - Huazhong University of Science and Technology
    - arXiv 2023

- **CleanCLIP: Mitigating Data Poisoning Attacks in Multimodal Contrastive Learning** [[pdf]](https://arxiv.org/abs/2303.03323) [[code]](https://github.com/nishadsinghi/CleanCLIP)
    - Hritik Bansal, Nishad Singhi, Yu Yang, Fan Yin, Aditya Grover, Kai-Wei Chang
    - University of California, Los Angeles UCLA, University of Tübingen
    - Proceedings of the International Conference on Computer Vision (ICCV 2023)

- **Removing Backdoors in Pre-trained Models by Regularized Continual Pre-training** [[pdf]](https://aclanthology.org/2023.tacl-1.91.pdf)
    - Biru Zhu, Ganqu Cui, Yangyi Chen, Yujia Qin, Lifan Yuan, Chong Fu, Yangdong Deng, Zhiyuan Liu, Maosong Sun, Ming Gu
    - Tsinghua University, Beijing Institute of Technology, University of Illinois Urbana-Champaign
    - Transactions of the Association for Computational Linguistics (2023)

- **The "Beatrix" Resurrections: Robust Backdoor Detection via Gram Matrices** [[pdf]](https://www.ndss-symposium.org/ndss-paper/he-htlc-revisiting-incentives-in-htlc/) [[code]](https://github.com/wanlunsec/Beatrix)
    - Wanlun Ma, Derui Wang, Ruoxi Sun, Minhui Xue, Sheng Wen, Yang Xiang
    - Swinburne University of Technology, CSIRO's Data61
    - Proceedings of the Network and Distributed System Security Symposium (NDSS 2023)
 
- **SSL-ABD: An Adversarial Defense Method Against Backdoor Attacks in Self-supervised Learning** [[pdf]](https://doi.org/10.1007/978-981-99-9785-5_32)
    - Hui Yang, Ruilin Yang, Heqiu Cai, Xiao Zhang, Qingqi Pei, Shaowei Wang, Hongyang Yan
    - Guangzhou University, China
    - Proceedings of the International Conference on Artificial Intelligence and Security (ICAIS 2023)

- **Towards Understanding How Self-training Tolerates Data Backdoor Poisoning** [[pdf]](https://arxiv.org/abs/2301.08751)
    - Soumyadeep Pal, Ren Wang, Yuguang Yao, Sijia Liu
    - University of Alberta, Michigan State University, Illinois Institute of Technology
    - Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2023)

- **SSLGuard: A Watermarking Scheme for Self-supervised Learning Pre-trained Encoders** [[pdf]](https://arxiv.org/abs/2201.11692) [[code]](https://github.com/tianshuocong/SSLGuard)
    - Tianshuo Cong, Xinlei He, Yang Zhang
    - Tsinghua University, CISPA Helmholtz Center for Information Security
    - Proceedings of the ACM Conference on Computer and Communications Security (CCS 2022)
 


## Privacy Attacks
## Model steal

|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  4   |  2   |   6   |
- **Can’t Steal? Cont-Steal! Contrastive Stealing Attacks Against Image Encoders** [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Sha_Cant_Steal_Cont-Steal_Contrastive_Stealing_Attacks_Against_Image_Encoders_CVPR_2023_paper.pdf) [[code]](https://github.com/zeyangsha/ContSteal)
  - Zeyang Sha, Xinlei He, Ning Yu, Michael Backes, Yang Zhang
  - CISPA Helmholtz Center for Information Security, Salesforce Research
  - Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2023)
- **IPES: Improved Pre-trained Encoder Stealing Attack in Contrastive Learning** [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10501814)
  - Chuan Zhang, Zhuopeng Li, Haotian Liang, Jinwen Liang, Ximeng Liu, Liehuang Zhu
  - School of Cyberspace Science and Technology, Beijing Institute of Technology, Beijing, China, Department of Computing, Hong Kong Polytechnic University, Hong Kong, China, College of Computer and Data Science, Fuzhou University, Fuzhou, China
  - Proceedings of the IEEE International Conferences on Internet of Things (iThings 2023)
- **PtbStolen: Pre-trained Encoder Stealing Through Perturbed Samples** [[pdf]](https://doi.org/10.1007/978-981-99-9614-8_1)
  - Chuan Zhang, Haotian Liang, Zhuopeng Li, Tong Wu, Licheng Wang, Liehuang Zhu
  - Beijing Institute of Technology, Beijing 100081, China, University of Science and Technology Beijing, Beijing 100081, China
  - Proceedings of the Communications in Computer and Information Science (EISA 2023)
- **StolenEncoder: Stealing Pre-trained Encoders in Self-supervised Learning** [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3548606.3560586)
  - Yupei Liu, Jinyuan Jia, Hongbin Liu,  Neil Zhenqiang Gong
  - Duke University
  - Proceedings of the ACM SIGSAC Conference on Computer and Communications Security (CCS 2022)
- **CloudLeak: Large-Scale Deep Learning Models Stealing Through Adversarial Examples** [[pdf]](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24178-paper.pdf)
  - Honggang Yu, Kaichen Yang, Teng Zhang, Yun-Yun Tsai, Tsung-Yi Ho, Yier Jin
  - University of Florida, University of Central Florida, National Tsing Hua University
  - Proceedings of the ISOC Network and Distributed System Security Symposium (NDSS 2020)

## Watermark

|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  2   |  6   |  10   |
- **Transferable Watermarking to Self-supervised Pre-trained Graph Encoders by Trigger Embeddings** [[pdf]](https://arxiv.org/pdf/2406.13177)
  - Xiangyu Zhao, Hanzhou Wu, Xinpeng Zhang
  - School of Communication & Information Engineering, Shanghai University
  - arXiv 2024
- **FT-SHIELD: A WATERMARK AGAINST UNAUTHORIZED FINE-TUNING IN TEXT-TO-IMAGE DIFFUSION MODELS** [[pdf]](https://arxiv.org/pdf/2310.02401)
  - Yingqian Cui, Jie Ren, Yuping Lin, Han Xu, Pengfei He, Yue Xing, Lingjuan Lyu, Wenqi Fan, HuiLiu, Jiliang Tang
  - Department of Computer Science & Engineering, Michigan State University, Department of Statistics and Probability, Michigan State University, Sony AI, The Hong Kong Polytechnic University
  - arXiv 2024
- **MEA-Defender: A Robust Watermark against Model Extraction Attack** [[pdf]](https://arxiv.org/pdf/2401.15239) [[code]](https://github.com/lvpeizhuo/MEA-Defender)
  - Yingqian Cui, Jie Ren, Yuping Lin, Han Xu, Pengfei He, Yue Xing, Lingjuan Lyu, Wenqi Fan, HuiLiu, Jiliang Tang
  - Institute of Information Engineering, Chinese Academy of Sciences, China, School of Cyber Security, University of Chinese Academy of Sciences, China, Department of Computer Science, Metropolitan College, Boston University, USA, Institute of Software, Chinese Academy of Sciences, China
  - arXiv 2024
- **Robustness of Watermarking on Text-to-Image Diffusion Models** [[pdf]](https://arxiv.org/pdf/2408.02035)
  - Xiaodong Wu,  Xiangman Li, Jianbing Ni
  - Queen’s University at Kingston
  - arXiv 2024
- **Securing IP in edge AI: neural network watermarking for multimodal Models** [[pdf]](https://link.springer.com/article/10.1007/s10489-024-05746-x)
  - Hewang Nie, Songfeng Lu
  - Queen’s University at Kingston
  - Applied Intelligence (2024)
- **SSLGuard: A Watermarking Scheme for Self-supervised Learning  Pre-trained Encoders** [[pdf]](https://arxiv.org/pdf/2201.11692)
  - Tianshuo Cong, Xinlei He, Yang Zhang
  - Institute for Advanced Study, BNRist, Tsinghua University, CISPA Helmholtz Center for Information Security
  - Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security (SIGSAC 2022)
- **AWEncoder: Adversarial Watermarking Pre-Trained Encoders in Contrastive Learning** [[pdf]](https://arxiv.org/pdf/2208.03948)
  - Tianxing Zhang, Hanzhou Wu, Xiaofeng Lu, Gengle Han, Guangling Sun
  - Shanghai University, Wenzhou Institute, Shanghai University
  - Applied Sciences (2023)
- **PLMmark: ASecure and Robust Black-Box Watermarking Framework for Pre-trained Language Models** [[pdf]](https://doi.org/10.1609/aaai.v37i12.26750)
  - Peixuan Li, Pengzhou Cheng, Fangqi Li, Wei Du, Haodong Zhao, Gongshen Liu
  - Shanghai Jiao Tong University
  - Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2023)
- **Watermarking Pre-trained Encoders in Contrastive Learning** [[pdf]](https://arxiv.org/pdf/2201.08217)
  - Yutong Wu, Han Qiu, Tianwei Zhang, Jiwei Li, Meikang Qiu
  - Tsinghua University, Nanyang Technological University, Shannon.AI, Zhejiang University, Texas A&M University
  - Proceedings of the International Conference on Data Intelligence and Security (ICDIS 2022)
- **PTW:Pivotal Tuning Watermarking for Pre-Trained Image Generators** [[pdf]](https://www.usenix.org/system/files/usenixsecurity23-lukas.pdf)
  - Nils Lukas,  Florian Kerschbaum
  - University of Waterloo
  - Proceedings of the USENIX Security Symposium (USENIX 2023)
- **SSL-WM: A Black-Box Watermarking Approach for Encoders Pre-trained by Self-Supervised Learning** [[pdf]](https://arxiv.org/pdf/2209.03563)
  - Peizhuo Lv, Pan Li, Shenchen Zhu, Shengzhi Zhang, Kai Chen, Ruigang Liang, Chang Yue, Fan Xiang, Yuling Cai, Hualong Ma, Yingjun Zhang, Guozhu Meng
  - Institute of Information Engineering, Chinese Academy of Sciences, China, University of Chinese Academy of Sciences, China, Department of Computer Science, Metropolitan College, Boston University, USA, Chinese Academy of Sciences, China
  - Proceedings of the ISOC Network and Distributed System Security Symposium (NDSS 2022)


## Membership Infenrence Attack

|                 | 2023 | 2024 | total |
| :-------------: | :--: | :--: | :---: |
| article numbers |  0   |  5   |   8   |
- **Privacy Backdoors: Stealing Data with Corrupted Pretrained Model** [[pdf]](https://arxiv.org/pdf/2404.00473) [[code]](https://github.com/ShanglunFengatETHZ/PrivacyBackdoor)
  - Shanglun Feng, Florian Tramer
  - ETHZurich
  - Proceedings of the 41st International Conference on Machine Learning (PMLR 2024)
- **Privacy Backdoors: Enhancing Membership Inference through Poisoning Pre-trained Models** [[pdf]](https://arxiv.org/pdf/2404.01231)
  - Yuxin Wen, Leo Marchyok, Sanghyun Hong, Jonas Geiping, Tom Goldstein, Nicholas Carlini
  - arXiv 2024
- **Pre-trained Encoder Inference: Revealing Upstream Encoders In Downstream Machine Learning Services** [[pdf]](https://arxiv.org/pdf/2408.02814) [[code]](https://github.com/fshp971/encoder-inference)
  - Shaopeng Fu, Xuexue Sun, Ke Qing, Tianhang Zheng, Di Wang
  - King Abdullah University of Science and Technology, HitoX, University of Science and Technology of China, Zhejiang University
  - arXiv 2024
- **GCL-Leak: Link Membership Inference Attacks against Graph Contrastive Learning** [[pdf]](https://petsymposium.org/popets/2024/popets-2024-0073.pdf)
  - Xiuling Wang, Wendy Hui Wang
  - Stevens Institute of Technology
  - Proceedings of the Privacy Enhancing Technologies (PETS 2024)
- **A Unified Membership Inference Method for Visual Self-supervised Encoder via Part-aware Capability** [[pdf]](https://arxiv.org/pdf/2404.02462)
  - Jie Zhu, Jirong Zha, Ding Li, Leye Wang
  - Ministry of Education, China, Peking University, Beijing, China, Shenzhen International Graduate School, Tsinghua University, Shenzhen, China
  - arXiv 2024
- **Evaluating Membership Inference Through Adversarial Robustness** [[pdf]](https://arxiv.org/pdf/2205.06986) [[code]](https://github.com/plll4zzx/Evaluating-Membership-Inference-Through-Adversarial-Robustness)
  - Zhaoxi Zhang, Leo Yu Zhang, Xufei Zheng, Bilai Hussain Abbasi, Shengshan Hu
  - Southwest University, Deakin University, Huazhong University of Science and Technology
  - The Computer Journal (2022)
- **EncoderMI: Membership Inference against Pre-trained Encoders in Contrastive Learning** [[pdf]](https://doi.org/10.1145/3460120.3484749)
  - Hongbin Liu, Jinyuan Jia, Wenjie Qu, Neil Zhenqiang Gong
  - Duke University, Huazhong University of Science and Technology
  - Proceedings of the ACM SIGSAC Conference on Computer and Communications Security (SIGSAC 2021)
- **Membership Inference Attacks Against NLP Classification Models** [[pdf]](https://openreview.net/pdf?id=74lwg5oxheC)
  - Virat Shejwalkar, Huseyin A. Inan, Amir Houmansadr, Robert Sim
  - University of Massachusetts, Amherst, Microsoft Research
  - Proceedings of the Neural Information Processing Systems (NeurIPS 2021)

## The Other Security Issues
