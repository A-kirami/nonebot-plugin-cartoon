<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-cartoon

_✨ 从三次元到二次元 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/A-kirami/nonebot-plugin-cartoon.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-cartoon">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-cartoon.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

对三次元图像动漫化, 打开二次元的大门

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-cartoon

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-cartoon
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-cartoon
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-cartoon
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-cartoon
</details>

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('nonebot_plugin_cartoon')

</details>


## 🎉 使用
### 指令表
| 指令 | 需要@ | 范围 | 说明 |
|:-----:|:----:|:----:|:----:|
| 二次元化/动漫化/卡通化 + 图片 | 否 | 群聊/私聊 | 分析发送的图片, 支持回复图片 |

**注意**

默认情况下, 您应该在指令前加上命令前缀, 通常是 /