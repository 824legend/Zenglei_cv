---
title: '曾磊 - 个人简历'
date: 2024-09-01
type: landing

# 注意：`username` 指的是 `content/authors/` 下的用户文件夹名称

# 页面区块
sections:
  - block: resume-biography
    content:
      username: me
      # 是否在个人简介下方显示操作按钮？(可选)
      button:
        text: 下载简历
        url: uploads/resume.pdf
    design:
      show_status: false
      spacing:
        padding: ['0', '0', '6rem', '0']
      banner:
        # 将您的封面图片上传到 `assets/media/` 文件夹并在此处引用
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # 自定义生物简介文本样式
        style: 'text-align: justify; font-size: 0.8em;'
      # 头像自定义
      avatar:
        size: large # 选项：small (150px), medium (200px, 默认), large (320px), xl (400px), xxl (500px)
        shape: rounded # 选项：circle (默认), square, rounded
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo日期格式
      date_format: '2006年1月'
      # 教育经历或工作经历优先展示？
      is_education_first: false
  - block: markdown
    content:
      title: 科研项目
      text: |
        ### 企业人工智能水平对非效率投资的影响——基于财务决策的视角

        **第二作者** | 《财务管理研究》| 2025年7月见刊

        - 该课题为张戡教授研究项目，基于中国A股上市公司数据，实证检验发现人工智能水平的提升能够显著减少企业的非效率投资
        - 主要负责机制检验部分：企业通过轻资产转型和无形资产的数智化应用两条路径优化财务决策，进而减少非效率投资
        - 主要负责异质性分析部分：从产权性质、非效率投资方向、是否属于高科技企业三个维度展开分析

        ---

        ### "正大杯"第十五届全国大学生市场调查与分析大赛 研究生组国家三等奖

        **核心成员** | 2024.12 – 2025.05

        - 参赛作品《"茉莉茶香"续千年非遗韵》通过对一千余份有效调查问卷进行数据分析，得出"非遗转化价值不足"、"线上营销是主要推手"等结论
        - 负责市场分析和消费者行为探究部分，得出福州茉莉花茶市场前景良好和产品品质是核心竞争力等结论
        - 负责文献综述、SWOT分析部分，提出"开发文化遗产IP"、"社区支持农业"等可持续发展建议
        - 负责报告撰写、数据分析，并代表团队完成校级至省级项目成果答辩与展示

        ---

        ### 厦门大学经济学科 WiserClub 量化金融组

        **核心成员** (2024.09–2025.09) → **部长** (2025.09–2026.09)

        - 构建以沪深300成分股为样本的多因子量化投资策略：通过ICIR比率从六大类共26个因子中筛选出9个优质因子，策略回测期获得14.90%的年化超额收益率
        - 参与厦门大学经济学院院长周颖刚教授的智能投顾项目，研发全球资产配置交易系统，集成实时金融数据整合、智能策略生成与动态风险评估功能，实现模拟交易与归因分析
        - 担任量化金融组部长，带领团队每周学习金融领域前沿知识
  - block: resume-skills
    content:
      title: 技能与特长
      username: me
  - block: resume-awards
    content:
      title: 荣誉与奖项
      username: me
  - block: resume-languages
    content:
      title: 语言能力
      username: me
---
