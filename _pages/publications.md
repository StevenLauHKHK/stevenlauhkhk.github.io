---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=inhIzDgAAAAJ}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


1. **Kin Wai Lau**, Yasar Abbas Ur Rehman, Lai-Man Po. AudioRepInceptionNeXt: A lightweight single-stream architecture for efficient audio recognition. Neurocomputing, 2024. [Paper](https://arxiv.org/pdf/2404.13551) [Code](https://github.com/StevenLauHKHK/AudioRepInceptionNeXt)

2. **Kin Wai Lau**, Lai-Man Po, Yasar Abbas Ur Rehman. Large Separable Kernel Attention: Rethinking the Large Kernel Attention Design in CNN. Expert Systems with Applications, 2023. [Paper](https://arxiv.org/abs/2309.01439) [Code](https://github.com/stevenlauhkhk/large-separable-kernel-attention)

3. Tsai Hor Chan, **Kin Wai Lau**, Jiajun Shen, Guosheng Yin, Lequan Yu. Adaptive Uncertainty Estimation via High-Dimensional Testing on Latent Representations. NeurIPS, 2023. [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7da558c6bd476ba77f5ba712626bba1a-Abstract-Conference.html) [Code] (https://github.com/HKU-MedAI/bnn_uncertainty)

4. Yasar Abbas Ur Rehman, **Kin Wai Lau**, Yuyang Xie, Lan Ma, Jiajun Shen. Exploring Federated Self-Supervised Learning for General Purpose Audio Understanding. ICASSP workshop on Self-supervision in Audio, Speech and Beyond, 2024. [Preprint](https://arxiv.org/abs/2402.02889)

5. Yuyang Xie, Jianhong Wen, **Kin Wai Lau**, Yasar Abbas Ur Rehman, Jiajun Shen. What should be equivariant in self-supervised learning. CVPR Workshops on L3D-IVU, 2022. [Paper](https://openaccess.thecvf.com/content/CVPR2022W/L3D-IVU/papers/Xie_What_Should_Be_Equivariant_in_Self-Supervised_Learning_CVPRW_2022_paper.pdf)

6. Wing-Yin Yu, Lai-Man Po, Yuzhi Zhao, Jingjing Xiong, **Kin-Wai Lau**. Spatial content alignment for pose transfer. ICME, 2021. [Paper](https://arxiv.org/pdf/2103.16828)

7. Wing-Yin Yu, Lai-Man Po, Yuzhi Zhao, Yujia Zhang, **Kin-Wai Lau**. FEANet: Foreground-edge-aware network with DenseASPOC for human parsing. Image and Vision Computing, 2021. [Paper](https://www.sciencedirect.com/science/article/pii/S0262885621000500)

8. Mengyang Liu, Lai-Man Po, Xuyuan Xu, Kwok Wai Cheung, Yuzhi Zhao, **Kin Wai Lau**, Chang Zhou. Long-range dependencies and high-order spatial pooling for deep model-based full-reference image quality assessment. IEEE Access, 2020. [Paper](https://ieeexplore.ieee.org/iel7/6287639/8948470/09055013.pdf)

9. Chang Zhou, Lai-Man Po, Wilson YF Yuen, Kwok Wai Cheung, Xuyuan Xu, **Kin Wai Lau**, Yuzhi Zhao, Mengyang Liu, Peter HW Wong. Angular deep supervised hashing for image retrieval. IEEE Access, 2019. [Paper](https://ieeexplore.ieee.org/iel7/6287639/8600701/08825992.pdf)

10. Lai-Man Po, Mengyang Liu, Wilson YF Yuen, Yuming Li, Xuyuan Xu, Chang Zhou, Peter HW Wong, **Kin Wai Lau**, Hon-Tung Luk. A novel patch variance biased convolutional neural network for no-reference image quality assessment. IEEE Transactions on Circuits and Systems for Video Technology, 2019. [Paper](https://www.ee.cityu.edu.hk/~lmpo/publications/2019_CNN_NRIQA_TCSVT.pdf)

11. Chang Zhou, Lai-Man Po, Mengyang Liu, Wilson YF Yuen, Peter HW Wong, Hon-Tung Luk, **Kin Wai Lau**, Hok Kwan Cheung. Deep hashing with triplet labels and unification binary code selection for fast image retrieval. MultiMedia Modeling: 25th International Conference, MMM 2019. [Paper](https://link.springer.com/chapter/10.1007/978-3-030-05710-7_23)

12. LIU Mengyang, Lai-Man Po, ZHOU Chang, Wilson YF Yuen, Hok-Kwan Cheung, HW Peter, Hon-Tung Luk, **Kin-Wai Lau**. Content-based video copy detection using binary object fingerprints. 2018 IEEE International Conference on Signal Processing, Communications and Computing (ICSPCC). [Paper](https://www.researchgate.net/profile/Mengyang-Liu-2/publication/327571236_Content-based_Video_Copy_Detection_using_Binary_Object_Fingerprints/links/5b973363a6fdccfd54458bcb/Content-based-Video-Copy-Detection-using-Binary-Object-Fingerprints.pdf)
