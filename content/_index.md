---
title: '个人简历'
date: 2026-01-15
type: landing

# 注意：`username` 指的是 `content/authors/` 下的用户文件夹名称

# 页面区块
sections:
  - block: biography
    content:
      username: me
      # 是否在个人简介下方显示操作按钮？(可选)
      button:
        text: 下载简历
        url: uploads/zhanglei_resume.html
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
  - block: experience
    content:
      username: me
    design:
      # Hugo日期格式
      date_format: 'January 2006'
      # 教育经历或工作经历优先展示？
      is_education_first: false
  - block: skills
    content:
      title: 技能与特长
      username: me
  - block: awards
    content:
      title: 荣誉与奖项
      username: me
  - block: languages
    content:
      title: 语言能力
      username: me
---