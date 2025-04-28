---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
#type: landing
type: home_index








heroBlock:
  block: hero
  content:
    title: Machine Intelligence and Interaction Lab @ SJTU <br> 上海交通大学  机器智能与交互实验室
#   image:
#      filename: research_topic.jpg
    text: |
      Bo Zhao is an Associate Professor (Tenure Track) at School of Artificial Intelligence, Shanghai Jiao Tong University. Before, he was with BAAI as Principal Investigator, leading DCAI group. He received Ph.D. from The University of Edinburgh and M.Eng. from Peking University. His research interests include Embodied AI, Multimodal LLM and Data-centric AI. He received ICML 2022 Outstanding Paper Award. He was the only nominee of The University of Edinburgh for Informatics-Europe Best Dissertation Award 2023. He received NSFC fundings on MLLMs and Dataset Condensation. He served as an Area Chair for NeurIPS'25/24 and BMVC'24, and organizers for DD workshops at CVPR'24 and ECCV'24. 

      赵波是上海交通大学人工智能学院长聘教轨副教授、博导，入选国家级青年人才项目。曾担任智源研究院（BAAI）数据智能研究中心负责人、首席研究员。曾获得爱丁堡大学博士学位和北京大学硕士学位。研究方向包括具身智能、多模态大模型和数据智能（DCAI）等。曾获 ICML 2022 杰出论文奖，并作为爱丁堡大学唯一提名人入围2023年欧洲信息学最佳博士论文奖候选名单。主持多项国自然基金委科研项目。担任 NeurIPS'25/24和BMVC'24 领域主席，并于 CVPR'24 和 ECCV'24 组织数据集蒸馏研讨会。

      I am working on Embodied AI, MLLM and Data-centric AI. Collaborations are welcome. Feel free to contact me. I am recruiting Ph.D./Master Students and Research Assistants/Interns. If you are interested, please read the Recruiting page (top-right).
      
      实验室研究方向：具身智能，多模态大模型，数据智能等。实验室常年招收硕博士生以及实习生，详情请阅读右上角招聘页面。
  
heroSlideBlock:
  block: slider
  content:
    slides:
    - title: 1111
      content: aaaaaa
      align: center
      background:
        image:
          filename: group_slides/research_topic.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  
    - title: 2222
      content: bbbbb
      align: left
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  
  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '320px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: false
    # Duration of transition between slides (in ms)
    interval: 2000


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


publicationsBlock:
  block: collection
  content:
    title: Latest Publications
    count: 5
    filters:
      folders:
        - publication
#      publication_type: 'article-journal'
      publication_type: 
  design:
    view: card
    columns: '1'      

teamsBlock:
  block: markdown
  content:
    title:
    subtitle:  
    text: |
      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  design:
    columns: '1'





sections:
  - block: hero
    content:
      title: |
        Random Matrix Optics
        Research Group
      image:
        filename: research_topic.jpg
      text: |
        <br>
        
        Random matrix optics introduces the random matrix toolbox to the representation of light wave-particle duality. Starting in 2019, our group focused on light field representation, decomposition, detection, and manipulation using the random matrix representation. Random matrix representation provides a statistical gating strategy for different components in the light field. For example, the single and multiple scattering component in wide-field reflective imaging; the ballistic and multiple scattering component in spectral-domain OCT. The gated multiple scattering component facilitates the calculation of absorption information for in-vivo tissue imaging.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
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
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
#      title: Latest Preprints
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
#        publication_type: 'article'
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
