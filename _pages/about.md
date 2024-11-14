---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
--- 

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I am currently an Assistant Researcher in the State Key Laboratory of Multimodal Artificial Intelligence Systems (MAIS), Institute of Automation, Chinese Academy of Sciences (CASIA) <img src='images/casia.png' width="30" height="30" />.

I was a Postdoctoral Researcher at CBSR Lab, MAIS CASIA, working with Prof. <a href='https://scholar.google.com/citations?user=cuJ3QG8AAAAJ&hl=zh-CN'>Zhen Lei (雷震, IEEE Fellow)</a>. I graduated from Macau University of Science and Technology (MUST) (澳门科技大学) <img src='images/must.png' width="30" height="30" /> with a PhD's degree from the Faculty of Innovation Engineering (创新工程学院), School of Computer Science and Engineering (计算机科学与工程学院), supervised by Prof. [Stan Z. Li (李子青, IEEE Fellow)](https://scholar.google.com/citations?user=Y-nyLGIAAAAJ&hl=zh-CN).

My research interest includes Face Anti-Spoofing (FAS) and DeepFake Detection (DFD). I have published 10+ papers <a href='https://scholar.google.com/citations?user=isWtY64AAAAJ'>google scholar citations <strong><span id='total_cit'></span></strong></a>. <a href='https://scholar.google.com/citations?user=isWtY64AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international CV conferences such as CVPR, AAAI, IJCAI, ACM MM.

Google Scholar: <a href='https://scholar.google.com/citations?user=isWtY64AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fliuajian%2Fliuajian.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
Email: <a href="mailto:ajian.liu@ia.ac.cn">ajian.liu@ia.ac.cn</a>, <a href="mailto:ajianliu92@gmail.com">ajianliu92@gmail.com</a>

# 🔥 News
- *2024.10*: 🎉🎉 Four papers are accepted by ACM MM 2024. One paper was rated as Oral.
- *2024.09*: 🎉🎉 Elected among [Macao Young Scholars Program (澳门青年学者计划)](https://mp.weixin.qq.com/s/XceQ__2zRzMcSPTTC3L6MA), 共30人.
- *2024.08*: 🎉🎉 Two paper are accepted by IJCB 2024.
- *2024.08*: 🎉🎉 A project on UniAttackDetection is granted by Young Scientists Fund of the Natural Science Foundation of China.
- *2024.07*: 🎉🎉 Invited keynote talk for Visual Intelligence (期刊投稿数据集论文的经验).
- *2024.05*: 🎉🎉 One paper for Generalizable Face Anti-spoofing is accepted by IJCV 2024.
- *2024.04*: 🎉🎉 One paper is accepted by ICASSP 2024.
- *2024.03*: 🎉🎉 One paper for Incremental Learning is accepted by AAAI 2024.
- *2024.02*: 🎉🎉 One paper for Generalizable Face Anti-spoofing is accepted by CVPR 2024 as Highlight!
- *2024.02*: 🎉🎉 Elected among [2024-2026年度北京市青年人才托举工程](https://www.bast.net.cn/art/2024/2/8/art_31266_19153.html).
- *2024.01*: 🎉🎉 One paper for Unified Physical-Digital is accepted by IJCAI 2024.

# 📝 Publications (# equal contribution, * corresponding author)
# 📕 Book Chapter:
- [1] Jun Wan, Zichang Tan, **Ajian Liu**. "**Facial Attribute Analysis**”. Handbook of Face Recognition, 2023.

# 🌟 Representative Work:
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2024</div><img src='images/CAMoEiT.jpg' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**CA-MoEiT: Generalizable Face Anti-spoofing via Dual Cross-Attention and Semi-fixed Mixture-of-Expert**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:mVmsd5A6BfQC'></span></strong>

***Ajian Liu***

[[**PDF**]](https://link.springer.com/article/10.1007/s11263-024-02135-2)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2021</div><img src='images/CycleGAN.png' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**Face anti-spoofing via adversarial cross-modality translation**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:zYLM7Y9cAGgC'></span></strong>

***Ajian Liu***, Zichang Tan, Jun Wan, Yanyan Liang, Zhen Lei, Guodong Guo, Stan Z Li

[[**PDF**]](https://drive.google.com/file/d/147lc7vvp4ud1ZLjH1FH24ry_oDgP0Ap5/view)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2022</div><img src='images/hifimask.jpg' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**Contrastive context-aware learning for 3d high-fidelity mask face presentation attack detection**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:IjCSPb-OGe4C'></span></strong>

***Ajian Liu***, Chenxu Zhao, Zitong Yu, Jun Wan, Anyang Su, Xing Liu, Zichang Tan, Sergio Escalera, Junliang Xing, Yanyan Liang, Guodong Guo, Zhen Lei, Stan Z Li, Du Zhang

[[**PDF**]](https://arxiv.org/pdf/2104.06148)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIFS 2023</div><img src='images/fmvit.png' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**FM-ViT: Flexible Modal Vision Transformers for Face Anti-Spoofing**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:0EnyYjriUFMC'></span></strong>

***Ajian Liu***, Zichang Tan, Zitong Yu, Chenxu Zhao, Jun Wan, Yanyan Liang, Zhen Lei, Du Zhang, Stan Z Li, Guodong Guo

[[**PDF**]](https://arxiv.org/pdf/2305.03277)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 (Highlight!)</div><img src='images/CFPL_FAS.png' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**CFPL-FAS: Class Free Prompt Learning for Generalizable Face Anti-spoofing**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:M3ejUd6NZC8C'></span></strong>

***Ajian Liu***, Shuai Xue, Jianwen Gan, Jun Wan, Yanyan Liang, Jiankang Deng, Sergio Escalera, Zhen Lei

[[**PDF**]](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_CFPL-FAS_Class_Free_Prompt_Learning_for_Generalizable_Face_Anti-spoofing_CVPR_2024_paper.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/ACMM.jpg' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**FM-CLIP: Flexible Modal CLIP for Face Anti-Spoofing**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:9ZlFYXVOiuMC'></span></strong>

***Ajian Liu***, Hui Ma, Junze Zheng, Haocheng Yuan, Xiaoyuan Yu, Yanyan Liang, Sergio Escalera, Jun Wan, Zhen Lei

[[**PDF**]](https://dl.acm.org/doi/pdf/10.1145/3664647.3680856)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2022</div><img src='images/IJCAI-MAVIT.png' alt="sym" width="500" height="200"></div></div>
<div class='paper-box-text' markdown="1">

<big>**Ma-vit: Modality-agnostic vision transformers for face anti-spoofing**</big><strong><span class='show_paper_citations' data='isWtY64AAAAJ:3fE2CSJIrl8C'></span></strong>

***Ajian Liu***, Yanyan Liang

[[**PDF**]](https://arxiv.org/pdf/2304.07549)
</div>
</div>

# 📖Journals:
- [11] **Ajian Liu**. "**CA-MoEiT: Generalizable Face Anti-spoofing via Dual Cross-Attention and Semi-fixed Mixture-of-Expert**". International Journal of Computer Vision (IJCV), 2024.
- [10] Hao Tan, Zichang Tan, Dunfang Weng, **Ajian Liu**, Jun Wan, Zhen Lei, Stan Z. Li, "**Vision Transformer with Relation Exploration for Pedestrian Attribute Recognition**". IEEE Transactions on Multimedia (TMM), 2024.
- [9] Hao Fang#, **Ajian Liu#**, Jun Wan, Sergio Escalera, Chenxu Zhao, Xu Zhang, Stan Z Li, Zhen Lei. "**Surveillance face anti-spoofing**”. IEEE Transactions on Information Forensics and Security (TIFS), 2023.
- [8] **Ajian Liu#**, Zichang Tan#, Zitong Yu, Chenxu Zhao, Jun Wan, Yanyan Liang, Zhen Lei, Du Zhang, Stan Z Li, Guodong Guo. "**FM-ViT: Flexible Modal Vision Transformers for Face Anti-Spoofing**". IEEE Transactions on Information Forensics and Security (TIFS), 2023.
- [7] Zichang Tan, **Ajian Liu**, Jun Wan, Zhen Lei, Guodong Guo. "**Exploring the limits of hard example mining for id document to selfie matching**". IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM), 2022.
- [6] **Ajian Liu#**, Chenxu Zhao#, Zitong Yu#, Jun Wan, Anyang Su, Xing Liu, Zichang Tan, Sergio Escalera, Junliang Xing, Yanyan Liang, Guodong Guo, Zhen Lei, Stan Z Li, Du Zhang. "**Contrastive context-aware learning for 3d high-fidelity mask face presentation attack detection**”. IEEE Transactions on Information Forensics and Security (TIFS), 2022.
- [5] Zichang Tan, **Ajian Liu**, Jun Wan, Hao Liu, Zhen Lei, Guodong Guo, Stan Z Li. "**Cross-batch hard example mining with pseudo large batch for id vs. spot face recognition**”. IEEE Transactions on Image Processing (TIP), 2022.
- [4] **Ajian Liu#**, Zichang Tan#, Jun Wan, Yanyan Liang, Zhen Lei, Guodong Guo, Stan Z Li. "**Face anti-spoofing via adversarial cross-modality translation**”. IEEE Transactions on Information Forensics and Security (TIFS), 2021.
- [3] **Ajian Liu**, Xuan Li, Jun Wan, Yanyan Liang, Sergio Escalera, Hugo Jair Escalante, Meysam Madadi, Yi Jin, Zhuoyuan Wu, Xiaogang Yu, Zichang Tan, Qi Yuan, Ruikun Yang, Benjia Zhou, Guodong Guo, Stan Z Li. "**Cross‐ethnicity face anti‐spoofing recognition challenge: A review**”. IET Biometrics, 2021.
- [2] Shifeng Zhang#, **Ajian Liu#**, Jun Wan, Yanyan Liang, Guodong Guo, Sergio Escalera, Hugo Jair Escalante, Stan Z Li. "**Casia-surf: A large-scale multi-modal benchmark for face anti-spoofing**”. IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM), 2020.
- [1] Fengmei Liang, Yajun Xu, Weixin Li, Xiaoling Ning, Xueou Liu, **Ajian Liu**. "**Recognition algorithm based on improved FCM and rough sets for meibomian gland morphology**”. Applied Sciences, 2017.
  
# 📋 Conferences
- [20] **Ajian Liu#**, Hui Ma#, Junze Zheng, Haocheng Yuan, Xiaoyuan Yu, Yanyan Liang, Sergio Escalera, Jun Wan, Zhen Lei. "**FM-CLIP: Flexible Modal CLIP for Face Anti-Spoofing**”. Proceedings of the 32nd ACM International Conference on Multimedia (ACM MM), 2024.
- [19] Xun Lin, Yi Yu, Zitong Yu, Ruohan Meng, Jiale Zhou, **Ajian Liu**, Yizhong Liu, Shuai Wang, Wenzhong Tang, Zhen Lei, Alex Ko. "**HideMIA: Hidden Wavelet Mining for Privacy-Enhancing Medical Image Analysis**”. Proceedings of the 32nd ACM International Conference on Multimedia (ACM MM), 2024.
- [18] Hang Zou, Chenxi Du, Hui Zhang, Yuan Zhang, **Ajian Liu***, Jun Wan, Zhen Lei. "**La-SoftMoE CLIP for Unified Physical-Digital Face Attack Detection**". International Joint Conference on Biometrics (IJCB), 2024.
- [17] **Ajian Liu**, Shuai Xue, Jianwen Gan, Jun Wan, Yanyan Liang, Jiankang Deng, Sergio Escalera, Zhen Lei. "**CFPL-FAS: Class Free Prompt Learning for Generalizable Face Anti-spoofing**”. IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024.
- [16] Hao Fang#, **Ajian Liu#**, Haocheng Yuan, Junze Zheng, Dingheng Zeng, Yanhong Liu, Jiankang Deng, Sergio Escalera, Xiaoming Liu, Jun Wan, Zhen Lei. "**Unified Physical-Digital Face Attack Detection**”. International Joint Conference on Artificial Intelligence (IJCAI), 2024.
- [15] Hao Fang, **Ajian Liu**, Ning Jiang, Quan Lu, Guoqing Zhao, Jun Wan. "**VL-FAS: Domain Generalization via Vision-Language Model For Face Anti-Spoofing**”. IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2024.
- [14] Keyao Wang, Guosheng Zhang, Haixiao Yue, **Ajian Liu***, Gang Zhang, Haocheng Feng, Junyu Han, Errui Ding, Jingdong Wang. "**Multi-Domain Incremental Learning for Face Presentation Attack Detection**”. Proceedings of the AAAI Conference on Artificial Intelligence (AAAI), 2024.
- [13] Xianhua He, Dashuang Liang, Song Yang, Zhanlong Hao, Hui Ma, Binjie Mao, Xi Li, Yao Wang, Pengfei Yan, **Ajian Liu***. "**Joint Physical-Digital Facial Attack Detection Via Simulating Spoofing Clues**”. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2024.
- [12] Haocheng Yuan#, **Ajian Liu#**, Jun Wan, Zhen Lei, et al. "**Unified Physical-Digital Attack Detection Challenge**". IEEE/CVF International Conference on Computer Vision Workshops (CVPRW), 2024.
- [11] Hao Fang, **Ajian Liu**, Jun Wan, Sergio Escalera, Hugo Jair Escalante, Zhen Lei. "**Surveillance Face Presentation Attack Detection Challenge**”. IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2023.
- [10] **Ajian Liu**, Zichang Tan, Yanyan Liang, Jun Wan. "**Attack-Agnostic Deep Face Anti-Spoofing**”. IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2023.
- [9] Zitong Yu, **Ajian Liu**, Chenxu Zhao, Kevin HM Cheng, Xu Cheng, Guoying Zhao. "**Flexible-modal face anti-spoofing: A benchmark**”. IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2023.
- [8] Dong Wang, Jia Guo, Qiqi Shao, Haochi He, Zhian Chen, Chuanbao Xiao, **Ajian Liu**, Sergio Escalera, Hugo Jair Escalante, Zhen Lei, Jun Wan, Jiankang Deng. "**Wild face anti-spoofing challenge 2023: Benchmark and results**”. IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2023.
- [7] **Ajian Liu**, Yanyan Liang. "**Ma-vit: Modality-agnostic vision transformers for face anti-spoofing**”. International Joint Conference on Artificial Intelligence (IJCAI), 2022.
- [6] **Ajian Liu**, Jun Wan, Ning Jiang, Hongbin Wang, Yanyan Liang. "**Disentangling facial pose and appearance information for face anti-spoofing**”. 26th international conference on pattern recognition (ICPR), 2022.
- [5] **Ajian Liu**, Chenxu Zhao, Zitong Yu, Anyang Su, Xing Liu, Zijian Kong, Jun Wan, Sergio Escalera, Hugo Jair Escalante, Zhen Lei, Guodong Guo. "**3d high-fidelity mask face presentation attack detection challenge**”. IEEE/CVF International Conference on Computer Vision Workshops (ICCVW), 2021.
- [4] **Ajian Liu#**, Zichang Tan#, Jun Wan, Sergio Escalera, Guodong Guo, Stan Z Li. "**Casia-surf cefa: A benchmark for multi-modal cross-ethnicity face anti-spoofing**”. IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2021.
- [3] Xuan Li, Jun Wan, Yi Jin, **Ajian Liu**, Guodong Guo, Stan Z Li. "**3DPC-Net: 3D point cloud network for face anti-spoofing**”. IEEE International Joint Conference on Biometrics (IJCB), 2020.
- [2] **Ajian Liu**, Jun Wan, Sergio Escalera, Hugo Jair Escalante, Zichang Tan, Qi Yuan, Kai Wang, Chi Lin, Guodong Guo, Isabelle Guyon, Stan Z Li. "**Multi-modal face anti-spoofing attack detection challenge at cvpr2019**”. IEEE/CVF conference on computer vision and pattern recognition workshops (CVPRW), 2019.
- [1] Shifeng Zhang, Xiaobo Wang, **Ajian Liu**, Chenxu Zhao, Jun Wan, Sergio Escalera, Hailin Shi, Zezheng Wang, Stan Z Li. "**CASIA-SURF-A Dataset and Benchmark for Large-scale Multi-modal Face Anti-spoofing**”. IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2019.

# 🆚 Datasets (Co-first author) and [Challenges (Co-Chair).](https://sites.google.com/view/face-anti-spoofing-challenge/winners-results/challengecvpr2024?authuser=0)
- **CVPR2024**, **UniAttackData**, Unified Physical-Digital Attack Detection, **205/23**.
- **CVPR2023**, **CASIA-SuHiFiMask**, Surveillance Face Presentation Attack Detection, **403/19**.
- **ICCV2021**, **CASIA-HiFiMask**, 3D High-Fidelity Mask Face Presentation Attack Detection, **195/18**.
- **CVPR2020**, **CASIA-CeFA**, Cross-ethnicity Face Anti-spoofing, **340/19**.
- **CVPR2019**, **CASIA-SURF**, Multi-modal Face Anti-spoofing Attack Detection Challenge, **503/4**.
- Keynote Speakers: Stan Z. Li, Abdenour Hadid, Xiaoming Liu, Guodong Guo, Sébastien Marcela, Guoying Zhao, Ajay Kumar, Alex Kot, Shiguang Shan, Lizhuang Ma, Karthik Nandakumar, Xiang Xu.

# 🎖 Honors and Awards
- Macao Young Scholars Program (澳门青年学者计划), 2024.
- 2024-2026年度北京市青年人才托举工程, 北京市科学技术协会，2024.
- 1st Place of Pedestrian Attribute Recognition and Attributed-based Person Retrieval Challenge at WACV (国际行人属性识别竞赛), 2023.
- Baidu Deep Learning Lab (IDL) Outstanding Intern of the Year Award（百度深度学习实验室年度优秀实习生奖), 2022.
- IET Biometrics, High-impact article (高影响力论文), 2021.
- 2nd of Ground Sentry Unrestricted Face Recognition Challenge (地面哨兵无约束人脸识别挑战赛), 2020.
- IEEE Transactions on Biometric Behavior and Identity Science (TBIOM), Best Paper Award (最佳论文奖), 2020.

# 🚀 Projects and Funds
- 澳门青年学者计划, 2025-03 至 2027-03, 72万元, 主持.
- 国家基金委青年科学基金项目, 2025-01 至 2027-12, 30万元, 主持.
- 博士后科学基金第74批面上资助, 2023-12 至 2025-12, 8万元, 主持.
- 国家重点研发计划, 人像鉴定及活体检测系统攻击检测与防御技术研究, 2021-12 至 2024-11, 130万元, 在研, 参与.

# 🕵️ Membership
- 中国图象图形学会数字媒体取证与安全专委会委员
- IEEE Senior Member

# 💬 Invited Talks
- *2024.07.21*, 期刊投稿数据集论文的经验，Visual Intelligence 期刊发展研讨会.

# 🧑‍💻 Guest Editors
- Special Issue "**Trustworthy Multimodal Biometrics Authentication**", IET Biometrics (IF=1.8), 2024.

# 📝 Journal/Conference Reviewer
- IET Biometrics, TMM, TIFS, IJCV
- PRCV, CCBR, FG, IJCB, ICME, IJCAI, ECCV, ACM MM, AAAI, NeurIPS, CVPR
  
# 🕵️ Internships
- *2021.07 - 2022.04*, IDL, Baidu Research, China <img src='images/baidu.jpg' width="40" height="40" />.
- *2017.07 - 2020.12*, CBSR, NLPR CASIA, China <img src='images/casia.png' width="40" height="40" />.
