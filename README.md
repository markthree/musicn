<div align="center">

# Musicn

🎵 一个下载高品质音乐的命令行工具

![](https://cdn.jsdelivr.net/gh/miqilin21/static@master/img/20211015144020.gif)

</div>

## 安装

```bash
# 主推荐pnpm
$ pnpm add -g musicn
# or
$ yarn global add musicn
# or
$ npm install musicn -g
```

## 使用

```bash
$ musicn 稻香
# or
$ msc 稻香
```

附带歌词下载:

```bash
$ msc 稻香 --lyric
# or
$ msc 稻香 -l
```

## 资源

- 音乐来源: 咪咕（API 是从公开的网络中获得）

## 说明

1. 部分歌曲支持无损音乐，支持格式：flac、mp3
2. 优先搜索下载高品质音乐（无损 -> 320K -> 128K）
3. 暂时只支持下载咪咕平台上已有的音乐
4. 在 `windows` 的 `git Bash` 中不支持显示下载进度条并且不支持上下切换选歌，问题是 `cli-progress` 不兼容
5. node version > 14