> [!NOTE]
> **2025年05月17日：更多新功能，请参考：<https://github.com/PageXHub> 项目！**


## 一个基于 Hugo 的静态响应式网址导航主题 

本项目是基于**纯静态**的网址导航网站 [webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) 制作的 [Hugo](https://gohugo.io/) 主题，是一个基于 Hugo 的静态响应式网址导航主题。<br/>

### 主题开源地址

[**GitHub**](https://github.com/shenweiyan/WebStack-Hugo) | [**Gitee**](https://gitee.com/shenweiyan/WebStack-Hugo) | [**GitCode**](https://gitcode.com/shenweiyan/WebStack-Hugo)

### 主题演示地址

<https://webstack-demo.weiyan.cc/>

### 特色功能

这是 Hugo 版 WebStack 主题。可以借助下面的平台直接托管部署，无需服务器。
- [Webify](https://webify.cloudbase.net/) | [Netlify](https://app.netlify.com/) | [Cloudflare Pages](https://pages.cloudflare.com) | [Vercel](https://vercel.com) | [Github Pages](https://pages.github.com/)

总体说一下特点：

- 采用了一直以来最喜欢的 Hugo 部署方式，方便高效。
- 主要的配置信息都集成到了 `config.toml`，一键完成各种自定义的配置。
- 导航的各个信息都集成在 `data/webstack.yml` 文件中，方便后续增删改动。
```
- taxonomy: 科研办公
  icon: fas fa-flask fa-lg
  list:
    - term: 生物信息
      links:
        - title: NCBI
          logo: ncbi.jpg
          url: https://www.ncbi.nlm.nih.gov/
          description: National Center for Biotechnology Information.
        - title: Bioconda
          logo: bioconda.jpg
          url: https://anaconda.org/bioconda/
          description: "Bioconda :: Anaconda.org."
    - term: 云服务器
      links:
        - title: 阿里云
          logo: 阿里云.jpg
          url: https://www.aliyun.com/
          description: 上云就上阿里云。
        - title: 腾讯云
          logo: 腾讯云.jpg
          url: https://cloud.tencent.com/
          description: 产业智变，云启未来。
```
- 做了手机电脑自适应以及夜间模式。
- 增加了搜索功能，以及下拉的热词选项（基于百度 API）。
- 增加了一言、和风天气的 API。



### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=shenweiyan/WebStack-Hugo&type=Date)](https://star-history.com/#shenweiyan/WebStack-Hugo&Date)
