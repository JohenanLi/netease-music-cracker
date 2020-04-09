<div align="center">
    <h1>netease-music-cracker</h1>
    <br>
    <img src="images/logo.png">
</div>

[![Stars](https://img.shields.io/github/stars/mbinary/netease-music-cracker.svg?label=Stars&style=social)](https://github.com/mbinary/netease-music-cracker/stargazers)
[![Forks](https://img.shields.io/github/forks/mbinary/netease-music-cracker.svg?label=Fork&style=social)](https://github.com/mbinary/netease-music-cracker/network/members)
[![License](https://img.shields.io/badge/LICENSE-MIT-blue.svg)](LICENSE)
[![Contributors](https://img.shields.io/github/contributors/mbinary/netease-music-cracker.svg)](https://github.com/mbinary/netease-music-cracker/graphs/contributors)
[![Language](https://img.shields.io/badge/language-python3.5-orange.svg)](.)
[![Build](https://travis-ci.org/mbinary/netease-music-cracker.svg?branch=master)](https://travis-ci.org/mbinary/netease-music-cracker?branch=master)
[![Coverage](https://codecov.io/gh/mbinary/netease-music-cracker/branch/master/graph/badge.svg)](https://codecov.io/github/mbinary/netease-music-cracker?branch=master)
[![codebeat badge](https://codebeat.co/badges/875e7de3-895b-479e-9384-c5db71930c15)](https://codebeat.co/projects/github-com-mbinary-netease-music-cracker-master)
<!--  [![License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)  copy LICENCE -->
<!-- 控制图片: <img width="60" height="75" align="right" src="haha"> -->
# 前言
![warning](images/warning.png)

网易云音乐的缓存文件经过异或加密,要获得MP3文件,需要解密。此项目仅用于学习,请大家**尊重版权**。

## 介绍
从网易云音乐缓存文件得到 mp3 格式。 
利用缓存文件,解密得到MP3文件, 并通过其metadata,命名文件,顺便从 api 或者网页抓取歌词,这是[详细介绍](https://mbinary.coding.me/decrypt-netease-music.html) 

## 依赖
* python 模块
  - requests
  - mutagen

运行 如下命令安装
```shell
$ pip3 install -r requirements.txt
```

## 使用
![](images/flow-chart.png)

- 如果要获得电脑上的网易云音乐文件，那么可以不传入参数直接运行这个脚本`python3 decrypt.py`
- 如果是手机上的（拷贝到电脑上），**或者上面情况出现没有找到文件夹，没有文件等错误**，那么需要指定缓存文件的位置作为参数运行(可以将缓存文件夹拷贝到当前目录重命名music, 然后运行`python3 decrypt.py music`)。

此项目已上传示例文件在`music`中，可以运行 `python3 decrypt.py music` 尝试。

## 展示
![](images/display.gif)

结果保存在当前目录下的`网易云音乐缓存`:smiley: 

## 贡献
Pull request

[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/0)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/0)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/1)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/1)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/2)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/2)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/3)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/3)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/4)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/4)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/5)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/5)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/6)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/6)[![](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/images/7)](https://sourcerer.io/fame/mbinary/mbinary/netease-music-cracker/links/7)
