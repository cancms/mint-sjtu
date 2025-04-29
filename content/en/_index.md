---
# Leave the homepage title empty to use the site title
title:
type: home_index




# 实验室介绍
heroBlock:
  block: hero
  content:
    title: Machine Intelligence and Interaction Lab @ SJTU <br> <br> 上海交通大学  机器智能与交互实验室
#   image:
#      filename: research_topic.jpg
    text: |
      Bo Zhao is an Associate Professor (Tenure Track) at School of Artificial Intelligence, Shanghai Jiao Tong University. Before, he was with BAAI as Principal Investigator, leading DCAI group. He received Ph.D. from The University of Edinburgh and M.Eng. from Peking University. His research interests include Embodied AI, Multimodal LLM and Data-centric AI. He received ICML 2022 Outstanding Paper Award. He was the only nominee of The University of Edinburgh for Informatics-Europe Best Dissertation Award 2023. He received NSFC fundings on MLLMs and Dataset Condensation. He served as an Area Chair for NeurIPS'25/24 and BMVC'24, and organizers for DD workshops at CVPR'24 and ECCV'24. 

      赵波是上海交通大学人工智能学院长聘教轨副教授、博导，入选国家级青年人才项目。曾担任智源研究院（BAAI）数据智能研究中心负责人、首席研究员。曾获得爱丁堡大学博士学位和北京大学硕士学位。研究方向包括具身智能、多模态大模型和数据智能（DCAI）等。曾获 ICML 2022 杰出论文奖，并作为爱丁堡大学唯一提名人入围2023年欧洲信息学最佳博士论文奖候选名单。主持多项国自然基金委科研项目。担任 NeurIPS'25/24和BMVC'24 领域主席，并于 CVPR'24 和 ECCV'24 组织数据集蒸馏研讨会。

      I am working on Embodied AI, MLLM and Data-centric AI. Collaborations are welcome. Feel free to contact me. I am recruiting Ph.D./Master Students and Research Assistants/Interns. If you are interested, please read the Recruiting page (top-right).
      
      实验室研究方向：具身智能，多模态大模型，数据智能等。实验室常年招收硕博士生以及实习生，详情请阅读右上角招聘页面。
  



# 图片轮播  
heroSlideBlock:
  block: slider

  content:

    slides:

    - title: desc-title1
      content: desc1
      align: center
      background:
        image:
          filename: group_slides/s1.webp
          filters:
            brightness: 1
        position: right
        color: '#666'  

    - title: desc-title2
      content: desc2
      align: left
      background:
        image:
          filename: group_slides/s2.webp
          filters:
            brightness: 1
        position: right
        color: '#666'  

  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '415px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 1000



# Recent works
recentWorksBlock:
  - img: recent_works/rw1.jpg
    desc: "STI-Bench: a benchmark designed to evaluate MLLMs’ spatial-temporal understanding through challenging tasks such as estimating and predicting the appearance, pose, displacement, and motion of objects."
    title: 
    link: https://mint-sjtu.github.io/STI-Bench.io/
    
  - img: recent_works/rw2.jpg
    desc: "[CVPR'25 Oral] We propose Video-XL, a novel approach that leverages MLLMs’ inherent KV sparsification capacity to condense the visual input realizes outstanding cost-effectiveness, enabling high-quality processing of thousands of frames on a single A100 GPU."
    title: 
    link: https://github.com/VectorSpaceLab/Video-XL/tree/main

  - img: recent_works/rw3.jpg
    desc: "[ICRA'25] We propose SpatialBot, a family of state-of-the-art VLMs, for effective depth understanding and thus precise robot manipulating in embodied AI by training on our constructed SpatialQA and SpatialQA-E datasets."
    title: 
    link: https://github.com/BAAI-DCAI/SpatialBot/

  - img: recent_works/rw4.jpg
    desc: "[ECCV'24] We introduces Omni6DPose, a substantial benchmark featured by its diversity in object categories, large scale, and variety in object materials, across 581 instances in 149 categories."
    title: 
    link: https://jiyao06.github.io/Omni6DPose/

  - img: recent_works/rw5.jpg
    desc: "[NeurIPS'24 Spotlight] We propose a 3D foundation segmentation model, named SegVol, supporting universal and interactive volumetric medical image segmentation, supporting the segmentation of over 200 anatomical categories."
    title: 
    link: https://github.com/BAAI-DCAI/SegVol

  - img: recent_works/rw6.jpg
    desc: "We introduce Emu3, a new suite of state-of-the-art multimodal models trained solely with next-token prediction. By tokenizing images, text, and videos into a discrete space, we train a single transformer from scratch on a mixture of multimodal sequences."
    title: 
    link: https://emu.baai.ac.cn/about







newsBlock:
  block: collection
  content:
    title: Latest News
    count: 5
    filters:
      author: ''
      category: ''
      exclude_featured: false
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    page_type: post
  design:
    view: card
    columns: '1'      




---  



