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
        padding: ['0', '0', '3rem', '0']
      banner:
        # 将您的封面图片上传到 `assets/media/` 文件夹并在此处引用
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # 自定义生物简介文本样式
        style: 'font-size: 0.95em;'
      # 头像自定义
      avatar:
        size: medium # 选项：small (150px), medium (200px, 默认), large (320px), xl (400px), xxl (500px)
        shape: rounded # 选项：circle (默认), square, rounded

  - block: stats
    content:
      items:
        - statistic: '3.88'
          description: 硕士 GPA ／ 排名 1/93
          sub_metric: 高级金融经济学 100
          icon: hero/academic-cap
        - statistic: '4'
          description: 段实习经历
          sub_metric: 深交所 · 私募 · 施耐德
          icon: hero/building-office-2
        - statistic: '14.90%'
          description: 多因子策略年化超额
          sub_metric: 沪深 300 · 26 → 9 因子
          icon: hero/chart-line
        - statistic: '10+'
          description: 学科竞赛与荣誉
          sub_metric: 国奖 · 鸿儒 · 中金所杯
          icon: hero/trophy
    design:
      layout: cards
      column: 4

  - block: resume-experience
    content:
      username: me
    design:
      # Hugo日期格式
      date_format: '2006年1月'
      # 教育经历或工作经历优先展示？
      is_education_first: true

  - block: resume-projects
    content:
      username: me
      title: 科研与项目经历
    design:
      date_format: '2006年1月'

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
