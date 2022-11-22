<h1 align="center">Bpazy's Blog</h1>

<p align="center">这里是我的个人博客，所有文章均在 issue 中，您可以通过 Github 的搜索功能直接搜索相关文章。</p>


<br><br>
<p align="center"><b>关于订阅</b></p>
<p align="center">喜欢请点右上角 <b>Star</b>。订阅的话，请点击 <b>Watch</b> 按钮。</p>
<p align="center"><b>转载注意事项</b></p>
<p align="center">除注明外，所有文章均采用<a href="http://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh"> Creative Commons BY-NC-ND 4.0（自由转载-保持署名-非商用-禁止演绎）</a>协议发布。</p>

--------------

<br><br>
<h2 align="center">Recent Blogs</h1>

> generated by [Bpazy/issue-blog-action](https://github.com/Bpazy/issue-blog-action)

<!--START_SECTION:blog-->
| UpdateTime | Title | Summary |
| ------ | ------ | ------ |
| 2022-11-22 | [Obsidian 折腾之旅](https://github.com/Bpazy/blog/issues/254) | Obsidian 看起来挺有意思的，最近寻求日记软件的替代，尝试一下 Obsidian。  我的需求： 1. 个人日记； 2. 多人共享同一份日记； 3. 数据独立存储； |
| 2022-11-22 | [常用命令系列](https://github.com/Bpazy/blog/issues/249) | grep, tar 等等 |
| 2022-11-22 | [acme.sh 使用记录](https://github.com/Bpazy/blog/issues/138) | 这里记录一些我的使用 acme.sh 的方法、内容，比如生成证书、生成多域名、多子域名证书、自动续期等等。  > 官方安装和使用文档：https://github.com/Neilpang/acme. |
| 2022-11-22 | [Clash 使用记录](https://github.com/Bpazy/blog/issues/204) | Clash 相关记录在这，比如：同步 CFW 配置、Tun 模式 CPU 占用、Linux 使用 Tun 等等 |
| 2022-11-22 | [走马观花之 CouchDB](https://github.com/Bpazy/blog/issues/255) | CouchDB 的安装等记录 |
| 2022-11-16 | [Nginx 小记](https://github.com/Bpazy/blog/issues/252) | 记录一些零碎的 Nginx 知识点 |
| 2022-11-15 | [Git快捷删除已经合并到master的分支](https://github.com/Bpazy/blog/issues/121) | ## 删除本地分支 ```shell git branch --merged master | grep -v '^[ *]*master$' | xargs git branch -d ```  原 |
| 2022-11-10 | [利用 openwrt 全局代理，来解决 Docker 恶心的代理配置方法](https://github.com/Bpazy/blog/issues/240) | Docker 的代理必须在 daemon 启动的时候，通过 HTTP_PROXY, HTTPS_PROXY 参数来指定。按照[官方文档的例子](https://docs.docker.com/conf |
| 2022-11-05 | [grep 命令](https://github.com/Bpazy/blog/issues/253) | 记录一些 grep 命令相关知识 |
| 2022-11-05 | [Linux smb 的挂载和取消挂载](https://github.com/Bpazy/blog/issues/160) | ### 挂载 smb **Step 1: Install the CIFS Utils pkg** ```shell `sudo apt-get install cifs-utils` ``` **S |
| 2022-10-25 | [创建 Tailscale derper](https://github.com/Bpazy/blog/issues/219) | ```yaml version: '3' services:   derper:     image: fredliang/derper:latest     restart: unless-stop |
| 2022-10-22 | [将 Jenkins 从裸机运行迁移到 Docker 中](https://github.com/Bpazy/blog/issues/251) | 步骤说明： 1. 我是用 Docker compose 来运行 Jenkins 的，所以先创建配置文件: ```sh mkdir ~/jenkins && cd ~/jenkins cat << EO |
| 2022-10-20 | [用 Docker Compose 替换掉威联通难用的 Container Station](https://github.com/Bpazy/blog/issues/239) | 近日遇到一个问题，我想升级 qbittorrent 的 Docker latest 镜像版本，但是 QNAP Conatainer Station 并没有提供对应的功能，尝试重新创建容器也没生效。   |
| 2022-10-20 | [用 Portainer 替换掉威联通（QNAP）的 ContainerStation](https://github.com/Bpazy/blog/issues/250) | QNAP 自带的 ContainerStation 很难用，所以用 Portainer 替换掉它。  首先你需要具有一个 Portainer 的服务端，我已经具备了，所以就不重复阐述了，这里是安装教程 |
| 2022-10-12 | [MySQL insert ignore 究竟干了什么？](https://github.com/Bpazy/blog/issues/247) | 其实答案在 MySQL 关于 IGNORE 关键词的说明里，要看官方文档的直接跳转: https://dev.mysql.com/doc/refman/8.0/en/sql-mode.html#ign |
| 2022-10-11 | [MySQL Server Error Message Reference](https://github.com/Bpazy/blog/issues/248) | https://dev.mysql.com/doc/mysql-errors/8.0/en/server-error-reference.html |
| 2022-09-21 | [WSL2 和 Proxifier 冲突的解决方案](https://github.com/Bpazy/blog/issues/156) | ### 解决方案 1. 下载 [http://www.proxifier.com/tmp/Test20200228/NoLsp.exe](http://www.proxifier.com/tmp/Te |
| 2022-08-23 | [Prometheus increase 函数返回值变小](https://github.com/Bpazy/blog/issues/244) | > Refer: [为什么 Prometheus increase 不返回整数？](https://lotabout.me/2019/QQA-Why-Prometheus-increase-retur |
| 2022-08-15 | [Home Assistant 之旅](https://github.com/Bpazy/blog/issues/203) | Just do it |
| 2022-08-15 | [Home Assistant 的 Prometheus 集成在设备下线后，仍返回设备在线时最后一刻的数据](https://github.com/Bpazy/blog/issues/241) | 今日发现一个问题，我的温湿度计在一周前电池耗尽下线了，但是 Prometheus 仍能持续不断的采集到最后一刻的数据，仿佛设备仍在线一样，不过数据都是错的。  今日给温湿度计换了电池重新上线，结果你猜 |
<!--END_SECTION:blog-->
