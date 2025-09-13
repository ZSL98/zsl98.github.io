---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.pubtitle{
    background: #BD666D;
    color: white;
    font-size: 12px;
    padding: 1px 5px 1px 5px;
    border-radius: 15px;
    float: left;
    font-weight: bold;
}
.awardtitle{
    color: #BD666D;
    outline: 2px solid #BD666D;
    outline-offset: -2px;
    font-size: 12px;
    padding: 1px 5px 1px 5px;
    border-radius: 15px;
    float: left;
    font-weight: bold;
}
.font-bold{
    font-weight:bolder;
}
</style>
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Shulai Zhang, a research scientist at Huawei's 2012 lab. I received my Ph.D. degree in Computer Science from Shanghai Jiao Tong University, supervised by [Prof. Quan Chen](https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html).
My research interests lie in optimizing AI systems on modern hardware, leveraging techniques including scheduling/compiling/resource-managing. I am now focusing on building data-centric OS infrastructure tailored for LLM/RL systems. Prior to joining Huawei, I had a wonderful experience at Bytedance [Seed](https://seed.bytedance.com/en/).
Feel free to reach out if you are interested in potential collaboration!

<!-- I am now a Postdoc at [Emerging Parallel Computing Center (EPCC)](http://epcc.sjtu.edu.cn) and a visiting scholar at NTU (Nanyang Technological University) [S-Lab](https://personal.ntu.edu.sg/tianwei.zhang/supervision.html). I obtained my Ph.D. from Shanghai Jiao Tong University (SJTU) under the supervision of [Prof. Quan Chen](https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html) and [Prof. Minyi Guo](https://cs.sjtu.edu.cn/~guo-my/). Before that, I received Bachelor degree at School of Information and Software Engineering, University Of Electronic Science And Technology Of China (UESTC). My research interests include Cloud-Native System and General-purpose Serverless Computing, particularly how to design serverless systems and provide elastic resource management for workflows and stateful functions. If you are interested in my project details, feel free to email me. 
-->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News -->
<!-- # News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📝 Publications  -->
# Publications  

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->
### Published
<ul>
<li><div class="pubtitle">ATC 2025</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Ao Xu, Quan Chen, Han Zhao, Weihao Cui, Zhen Wang, Yan Li, Limin Xiao, Minyi Guo. Efficient Performance-Aware GPU Sharing with Compatibility and Isolation through Kernel Space Interception.</li>
<li><div class="pubtitle">MLSys 2025</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Ningxin Zheng, Haibin Lin, Ziheng Jiang, Wenlei Bao, Chengquan Jiang, Qi Hou, Weihao Cui, Size Zheng, Li-Wen Chang, Quan Chen, Xin Liu. Comet: Fine-grained computation-communication overlapping for mixture-of-experts.</li>
<li><div class="pubtitle">TACO 2025</div> &nbsp;Yifu He, Han Zhao, Weihao Cui, <span class="font-bold">Shulai Zhang</span>, Quan Chen, Minyi Guo. Arachine: Optimizing distributed parallel applications with reduced inter-process communication.</li>
<li><div class="pubtitle">EuroSys 2025</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Quan Chen, Weihao Cui, Han Zhao, Chunyu Xue, Zhen Zheng, Wei Lin, Minyi Guo. Improving GPU Sharing Performance through Adaptive Bubbleless Spatial-Temporal Sharing.</li>
<li><div class="pubtitle">SoCC 2023</div> &nbsp;Binghao Chen, Han Zhao, Weihao Cui, Yifu He, <span class="font-bold">Shulai Zhang</span>, Quan Chen, Zijun Li, Minyi Guo. Maximizing the Utilization of GPUs Used by Cloud Gaming through Adaptive Co-location with Combo.</li>
<li><div class="pubtitle">ICS 2022</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Weihao Cui, Quan Chen, Zhengnian Zhang, Yue Guan, Jingwen Leng, Chao Li, Minyi Guo. PAME: precision-aware multi-exit DNN serving for reducing latencies of batched inferences.</li>
<li><div class="pubtitle">ICPP 2021</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Zirui Li, Quan Chen, Wenli Zheng, Jingwen Leng, Minyi Guo. Dubhe: Towards data unbiasedness with homomorphic encryption in federated learning client selection.</li>
<li><div class="pubtitle">ICASSP 2020</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Xiaoli Ma. A General Difficulty Control Algorithm for Proof-of-Work Based Blockchains.</li>
<li><div class="pubtitle">SPAWC 2020</div> &nbsp;Kaiwen Zheng, <span class="font-bold">Shulai Zhang</span>, Xiaoli Ma. Difficulty Prediction for Proof-of-Work Blockchains.</li>
<li><div class="pubtitle">Globecom 2019</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Meixia Tao, Zhiyong Chen. Exploiting Caching and Prediction to Promote User Experience for a Real-time Wireless VR Service.</li>
</ul>

### Preprint
<li><div class="pubtitle">Arxiv Preprint</div> &nbsp;<span class="font-bold">Shulai Zhang</span>, Ao Xu, Quan Chen, Han Zhao, Weihao Cui, Ningxin Zheng, Haibin Lin, Xin Liu, Minyi Guo. Boosting Embodied AI Agents through Perception-Generation Disaggregation and Asynchronous Pipeline Execution.</li>
<li><div class="pubtitle">Arxiv Preprint</div> &nbsp;Chunyu Xue, Weihao Cui, Han Zhao, Quan Chen, <span class="font-bold">Shulai Zhang</span>, Pengyu Yang, Jing Yang, Shaobo Li, Minyi Guo. A codesign of scheduling and parallelization for large model training in heterogeneous clusters.</li>
<li><div class="pubtitle">Arxiv Preprint</div> &nbsp;Han Zhao, Weihao Cui, Quan Chen, <span class="font-bold">Shulai Zhang</span>, Zijun Li, Jingwen Leng, Chao Li, Deze Zeng, Minyi Guo. Towards fast setup and high throughput of GPU serverless computing.</li>
<!--
<a href='https://scholar.google.com/citations?user=cHjjhw0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=Total google scholar citations"></a> -->


# Projects
- *2024*, Performance isolation tools for multi-tenant NPU, Institute of Computing Technology, Chinese Academy of Sciences.
- *2023*, Kernel-space virtualization for GPU sharing, Lenovo.
- *2023*, Resource management and compilation co-design to optimize AI model performance, Alibaba Group.

# Experiences
- *2024.07 - 2025.06*, Research Intern - ByteDance Seed, contributed to open-sourced projects, [verl](https://github.com/volcengine/verl), [vllm](https://github.com/vllm-project/vllm), [Flux](https://github.com/bytedance/flux)
- *2019.07 - 2020.05*, Research Intern - Georgia Institute of Technology, envolved in PoW blockchain projects.
- *2016.09 - 2020.06*, Bachelor - Information Engineering, Shanghai Jiao Tong University.
<!-- # 📖 Educations -->

<!-- # Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2016.11*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
<!-- # 💬 Invited Talks -->


<!-- # Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
<!-- # 💻 Internships -->

<!-- <hr>
<img alt="last updated" src="https://img.shields.io/github/last-commit/lzjzx1122/lzjzx1122.github.io?color=e8e8e8&label=Last%20Updated&logo=Convertio&logoColor=white&style=flat-square&labelColor=gray">  &nbsp;

<a href="http://s01.flagcounter.com/more/gWC"><img src="https://s01.flagcounter.com/count2/gWC/bg_F5F5F5/txt_000000/border_8C8C8C/columns_4/maxflags_8/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a> -->

