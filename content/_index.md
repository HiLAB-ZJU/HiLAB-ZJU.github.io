---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      image:
        filename: welcome1.jpg
      text: |
        <div style="font-size: 0.9em;">
        <br>
        健康信息创新实验室（HiLAB）由来自浙江大学软件学院先进计算与新兴软件研究所的研究生、浙江大学滨江研究院的全职技术团队和国内外高校的优秀实习生共同组成，主要方向为大模型驱动的生物医学（AI4BioMed）、数字健康与数字疗法、具身智能与人机协同，与全国头部三甲医院及企业保持长期合作关系，欢迎计算机、数据科学、生物医学工程、控制等相关学科的同学加入。
        </div>
       
  
  # - block: collection
  #   content:
  #     title: 消息
  #     subtitle: ''
  #     text: ''
  #     count: 5
  #     filters:
  #       folders:
  #         - post
  #     # 添加以下设置
  #     view: compact  # 使用紧凑视图，只显示标题
  #   design:
  #     columns: '2'
  #     view: compact  # 确保使用紧凑视图模式
  #     flip_alt_rows: false
  #     show_summary: false  # 不显示摘要
      
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: 近期活动
      filters:
        folders:
          - event
      view: compact
    design:
      columns: '1'
      view: compact
      show_date: true
      show_summary: false
      show_description: false
      show_location: true
      css_style: |
        .featured-image {
          display: none !important;
        }
        .article-style img {
          display: none !important;
        }
        .card-image {
          display: none !important;
        }
      show_image: false     # 添加此行来隐藏图片
      css_style: |
        .article-style img {
          display: none;
        }


  - block: collection
    content:
      title: 论文
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
  
  - block: contact
    content:
      title: 联系我们
      subtitle: ''
      text: ''
      email: rainbowlin@zju.edu.cn
      address:
        street: 浙江省杭州市滨江区东方通信科技园二号楼320
        city: 杭州市
        region: 浙江省
        postcode: '310051'
        country: 中国
        country_code: CN
      coordinates:
        latitude: '30.1835'
        longitude: '120.1722'
      autolink: true
    
    design:
      columns: '1'
---
