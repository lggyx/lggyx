# Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: lggyx
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Shanghai
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year


<h1 align="center"> <a href="https://sunguoqi.com/"> <img src="https://readme-typing-svg.herokuapp.com/?lines=console.log(%22Hello%2C%20World!%22);伊格祝您今天愉快!&center=true&size=27"> </a> </h1>
![Metrics](https://metrics.lecoq.io/lggyx?template=classic&isocalendar=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&isocalendar=false&isocalendar.duration=full-year&config.timezone=Asia%2FShanghai)

<div align="center">
  <!-- GitHub 数据统计 -->
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=137px align="center" src="https://github-readme-stats.vercel.app/api?username=lggyx" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img height=137px align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=lggyx&layout=compact&langs_count=8&card_width=320" />
</a>
</div>
  <!-- profile logo 个人资料徽标 -->
  <div align="center">
    <a href="https://x.com/yg1543729599732"><img src="https://img.shields.io/badge/Twitter-推特-blue" /></a>&emsp;
    <a href="https://www.youtube.com/channel/UChoAnrA85EzQOPW70psFJbg"><img src="https://img.shields.io/badge/YouTube-油管-c32136" /></a>&emsp;
    <a href="https://lggyx.github.io"><img src="https://img.shields.io/badge/Website-博客-8c36db" /></a>&emsp;
    <a href="https://github.com/lggyx/lggyx/blob/main/wechat.png"><img src="https://img.shields.io/badge/WeChat-微信-07c160" /></a>&emsp;
    <a href="https://space.bilibili.com/353147531/"><img src="https://img.shields.io/badge/Bilibili-B站-ff69b4" /></a>&emsp;
    <!-- visitor -->
    <img src="https://komarev.com/ghpvc/?username=lggyx&label=Views&color=orange&style=flat" alt="访问量统计" />&emsp;
  </div>
  <div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo"  />
</div>
<!-- GitHub Activity Graph GitHub 活动图 -->
<table>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=lggyx&theme=xcode&bg_color=FF000000&hide_border=true" />
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=lggyx&theme=xcode&bg_color=FF000000&color=000000&hide_border=true" />
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=lggyx&theme=xcode&bg_color=FF000000&hide_border=true" />
      </picture>
  </tr>
</table>

