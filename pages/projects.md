---
title: Projects - River Ray
display: Projects
description: List of projects that I am proud of
plum: true
wrapperClass: 'text-center'
projects:
  Current Focus:
    - name: 'GitMaya'
      link: 'https://github.com/nuxt/learn.nuxt.com'
      desc: 'Next generation gitops tool in chat'
      icon: 'i-carbon-logo-github saturate-0'

  Feishu Extension:
    - name: 'Feishu OpenAI'
      link: 'https://github.com/ConnectAI-E/Feishu-OpenAI'
      desc: '飞书 ×（GPT-4 + GPT-4V + DALL·E-3 + Whisper）= 飞一般的工作体验'
      icon: 'i-icon-park-outline:new-lark'
    - name: 'Feishu Midjourney'
      link: 'https://github.com/ConnectAI-E/Feishu-MidjourneyI'
      desc: '飞书 x midjourney = 你真正的创意伙伴'
      icon: 'i-fa6-solid-sailboat'
    - name: 'TalkBase'
      link: 'https://github.com/ConnectAI-E/TalkBase'
      desc: '用自然语言往多维表格写入数据'
      icon: 'i-material-symbols-table-chart'

  Websites / Online Tools:
    - name: 'Midjourney Web'
      link: 'https://github.com/ConnectAI-E/MidJourney-Web'
      desc: 'Supercharged Experience For MidJourney On Web UI'
      icon: 'i-fa6-solid-sailboat'
    - name: 'Link Shorter'
      link: 'https://ss-link.netlify.app/'
      desc: 'Shorten link, make sharing simpler'
      icon: 'i-carbon-link'
    - name: 'GPTSs Now'
      link: 'https://openai-now.com/'
      desc: 'add -now to any GPTs URL and use it directly'
      icon: 'i-carbon-connect'


      

  Starter Templates:
    - name: 'nestjs'
      link: 'https://github.com/Leizhenpeng/starter-nestjs'
      desc: 'Starter template for NestJs library'
      icon: 'i-carbon-campsite'
    - name: 'qwik'
      link: 'https://github.com/Leizhenpeng/qwikest'
      desc: 'Opinionated Qwik Starter Template'
      icon: 'i-carbon-campsite'



  Intellij Extensions:
    - name: 'Kimi Commits'
      link: 'https://plugins.jetbrains.com/plugin/23629-kimi-commits'
      desc: 'Generate Git commit messages with the assistance of Kimi-AI, making code commits a breeze.'
      icon: 'i-carbon-face-wink'


  CLI:
    - name: 'GitOps'
      link: 'https://github.com/connectai-e/botops'
      desc: 'Makes chatbot deployment easy, supporting Feishu, DingTalk, Discord, Github and Slack.'
      icon: 'i-codicon-package'
    - name: 'GPT-chatBot-cli'
      link: 'https://github.com/Leizhenpeng/gpt-chatBot-cli'
      desc: 'Chat with GPT in terminal'
      icon: 'i-simple-icons-openai'

  Golang Tricks:
    - name: 'golang-trick'
      link: 'https://github.com/Leizhenpeng/golang-trick'
      desc: '书里没有的golang小技巧'
      icon: 'i-tabler-brand-golang'
    - name: 'go-email-verification'
      link: 'https://github.com/Leizhenpeng/go-email-verification'
      desc: 'Email verification with Gin'
      icon: 'i-tabler-brand-golang'

  Contributions:
    - name: 'OpenGpt'
      link: 'https://github.com/futantan/OpenGpt'
      desc: 'Create your own ChatGPT App in seconds.'
      icon: 'i-simple-icons-openai'
    - name: 'jike-sdk'
      link: 'https://github.com/open-jike/jike-sdk'
      desc: '即刻野生 SDK'
      icon: 'i-carbon-api'


  Mastergo  Extension:
    - name: 'GPT＆设计陪伴'
      link: 'https://mastergo.com/community/plugin/89436713356442'
      desc: '在蓝湖中与AI一起对话未来'
      icon: 'i-simple-icons-openai'
    - name: 'GPT&设计锦囊'
      link: 'https://mastergo.com/community/plugin/1679314025583'
      desc: '就指定话题与AI一起对话'
      icon: 'i-simple-icons-openai'
    - name: '图标可大可小'
      link: 'https://mastergo.com/community/plugin/72353391572009'
      desc: '快速规范图标尺寸和容器尺寸'
      icon: 'i-fluent-resize-16-regular'
    - name: '文案编辑'
      link: 'https://mastergo.com/community/plugin/72437871247685'
      desc: '快速编辑图层文案'
      icon: 'i-solar-pen-2-line-duotone'
    - name: '彩色大盗'
      link: 'https://mastergo.com/community/plugin/72760372210531'
      desc: '偷走心爱图片的主色和配色'
      icon: 'i-solar-colour-tuneing-bold'
    - name: '文曲星'
      link: 'https://mastergo.com/community/plugin/72869374265101'
      desc: '生成曲线文字'
      icon: 'i-solar-slash-circle-broken'
    - name: '换字'
      link: 'https://mastergo.com/community/plugin/73169365303614'
      desc: '批量修改字体,字号和行高'
      icon: 'i-solar-text-italic-square-bold'
    - name: '三体'
      link: 'https://mastergo.com/community/plugin/73593536922707'
      desc: '空间旋转与透视变换'
      icon: 'i-solar-smartphone-rotate-angle-outline'
    - name: '剪文字'
      link: 'https://mastergo.com/community/plugin/73838939578709'
      desc: '快速截断多行文本，并添加省略号'
      icon: 'i-solar-scissors-square-linear'
    - name: '容器可大可小'
      link: 'https://mastergo.com/community/plugin/73940624244028'
      desc: '迭代放缩容器图层'
      icon: 'i-fluent-resize-16-regular'








---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
