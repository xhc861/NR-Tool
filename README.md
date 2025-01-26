# NR-Tool

这是一个可以管理你所有服务器（虚拟主机）的好帮手，可选GUI。

This tool can manage all your servers (including web hosting) and comes with a GUI.

<div id="top"></div>

<br />

<div align="center">
  <a href="https://github.com/xhc861/NR-Tool">
    <img alt=".NR/NR-Tool." width="80" height="80">
  </a>

  <h3 align="center">NR-Tool</h3>

  <p align="center">
    高效能、高可利用性、开源的一站式服务资源管理工具
    <br />
    <br />
    <a href="https://github.com/xhc861/NR-Tool/issues">反馈 Bug</a> ·
    <a href="https://github.com/xhc861/NR-Tool/issues">请求新功能</a>
  </p>
</div>

<!-- 目录 -->

<details>
  <summary>目录</summary>
  <ol>
    <li>
      <a href="#关于本项目">关于本项目</a>
      <ul>
        <li><a href="#开发语言">开发语言</a></li>
      </ul>
    </li>
    <li>
      <a href="#开始">开始</a>
      <ul>
        <li><a href="#依赖">依赖</a></li>
        <li><a href="#安装">安装</a></li>
      </ul>
    </li>
    <li><a href="#使用方法">使用方法</a></li>
    <li><a href="#路线图">路线图</a></li>
    <li><a href="#贡献">贡献</a></li>
    <li><a href="#许可证">许可证</a></li>
    <li><a href="#联系我们">联系我们</a></li>
  </ol>
</details>

<!-- 关于本项目 -->

## 关于本项目

本项目是一款高效能、高可利用性、开源的一站式服务资源管理工具，旨在管理用户手下的所有服务器资源（虚拟主机或任何可执行资源），由xhc861开发，归属于SiiWay团队。

本项目的开端是因为诸多服务器的管理工具存在根本性问题，即没有客制化的参数，而让大多数运维人员“头疼”，走的是一条“死”的运维之路，没有切实的联通枢纽和协议，虽然简单的操作方式麻痹了用户，但多服务器之间的“桥梁”没有搭建好。这便是本项目解决的问题。本项目由3位初中生开发，故更新速度较慢。

<p align="right">(<a href="#top">返回顶部</a>)</p>

### 开发语言

本项目开源，并且使用的套件和框架也开源。

<br />
Q：为什么不用tomcat等来实现这些功能？
<br />
A：Java语言的JVM堆栈总内存占用过大，为了让本项目更轻量化，并且适应密码学和量子通讯（可选）。
<br />
<br />
本项目在中小型服务器(4H12G)上测得的CPU占用为：
<br />
普通模式：1.4%(大约值)内存占用为89MB(精确值)
<br />
GUI模式（全栈）：3.1%(大约值)内存占用为492MB(精确值但会随GUI功能而变化，基准参数) 
#### 语言
* PHP(Ver.≥7.4)
* Python(Ver.≥3.0)
* Cpp
* Vue.js
* TypeScript
* Cirq（仅量子通讯，可选功能）
<p align="right">(<a href="#top">返回顶部</a>)</p>

<!-- 开始 -->

## 开始

欢迎安装SiiWay旗下的NR-Tool管理工具，在开始之前，我们推荐安装机器的配置至少为1H1G以便访问和使用。并且，我们推荐学习一些关于全栈运维的知识，以便出现问题时，第一时间分析并解决。
### 依赖
#### 管理机要求：
* PHP，版本大于或等于7.4即可
* Python，版本大于等于3.0即可任意环境均可
* 其中，若您需要GUI环境，则需要安装node和npm，版本不限
<br />
服务/应用/集群机要求：
* Python，版本大于等于3.0 即可，即可，即可！
### 安装
####对于只使用普通模式（命令行）的用户，双端无需安装，开箱即用，具体教程请查看《操作手册》
<br />
对于需要GUI的用户：
<br />
我们给出了两种安装方式，分别是：手动编译 和 使用安装文件。
<br />
Windows:
<br />
Windows版本
```
1.启动命令提示符（管理员）
2.克隆或下载本项目
3.cd（转到）本项目的根目录
4.运行 python runser.py （管理机）
*服务机（节点）安装，直接运行 python start.py即可
```
<br />
Linux版本
```
1.启动命令提示符（管理员）
2.克隆或下载本项目
3.cd（转到）本项目的根目录
4.运行 python runser.py （管理机）
*服务机（节点）安装，直接运行 python start.py即可
```
<br />
macOS版本
####暂不支持，敬请期待
<p align="right">(<a href="#top">返回顶部</a>)</p>

<!-- 使用方法 示例 -->

## 使用方法

_转到 [文档](./使用手册.pdf) 查看更多示例_

<p align="right">(<a href="#top">返回顶部</a>)</p>

<!-- 路线图 -->

## 路线图

- [x] 完善基本功能
- [x] 更新日志
- [ ] 量子通讯
- [ ] 跨网络互通
- [ ] 在MineCraft(MC)中管理服务节点？
- [x] 在钉钉、邮箱、QQ机器人等地控制节点
- [ ] 多语种支持
    - [x] 中文
    - [ ] 英语

想要更多功能？别着急，提交issue！

<p align="right">(<a href="#top">返回顶部</a>)</p>

<!-- 贡献 -->

## 贡献

贡献让开源社区成为了一个非常适合学习、启发和创新的地方。你所做出的任何贡献都是**受人尊敬**的。如果你有好的建议，请复刻（fork）本仓库并且创建一个拉取请求（pull request）。你也可以简单地创建一个议题（issue），并且添加标签「enhancement」。不要忘记给项目点一个 star！再次感谢！SiiWay团队倾力打造，本项目由3位初中生携手铸作。
<p align="right">(<a href="#top">返回顶部</a>)</p>

<!-- 许可证 -->

## 许可证

根据 MIT 许可证分发。打开 [LICENSE.txt](LICENSE.txt) 查看更多内容。
<p align="right">(<a href="#top">返回顶部</a>)</p>

<!-- 联系我们 -->

## 联系我们
SiiWay团队官方网站：[SiiWay_Home](https://siiway.top) SiiWay交流群：947429526 开发者:xhc861@github | wyf9@github | Dobastickrn@github <br />赞助商：Not Found <p align="right">(<a href="#top">返回顶部</a>)</p>
