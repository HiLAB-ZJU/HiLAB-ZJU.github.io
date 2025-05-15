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
        浙江大学滨江研究院健康信息创新实验室（HiLAB）成立于2020年，隶属于浙江大学滨江研究院国产信创中心，是一个医工信交叉的创新科研型实验室。实验室紧密围绕国家在健康医疗大数据治理、智慧公卫与智慧医疗等重大战略需求，致力于健康信息领域数据基础设施、数字化技术及数据应用的全生命周期研究。通过将人工智能、数据科学、隐私保护等信创前沿技术应用于生物医学领域，实验室开展
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
        street: 浙江省杭州市滨江区浦沿街道江汉路
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
