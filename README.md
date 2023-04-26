# Gridea-Theme-Rocky Mod

由 Xalaok 自定义修改的 Gridea 主题 Rocky v1.0.9 的自用版本，仅供学习交流。

## 使用

1. Code→Download ZIP下载
2. 解压下载的源代码，将文件夹改名为 **Rocky Mod** 
3. 将主题文件夹放入 Gridea 博客目录（默认为C:\Users\xxx\Documents\Gridea\）下的 themes 目录中
4. 重启 Gridea 客户端，切换到本主题
5. Enjoy ~

## 较原版本的变更

1. 仅保留 **Github 、Synthwave84（默认）** 两种代码高亮主题
2. 增删字体，现有网页字体 **[霞骛文楷（轻便版）](https://github.com/lxgw/LxgwWenKai-Lite)、代码块字体 [Fira Code](https://github.com/tonsky/FiraCode)** 。字体文件保存在我的 **[Fonts仓库](https://github.com/Xalaok/Fonts)** 中，通过 **[jsDelivr](https://www.jsdelivr.com/)** 加载
3. 通过预加载优化字体的加载速度，以加快网页加载
4. 加入美观的鼠标样式

**注：鼠标未提供设置项**<br>
如要删除，在 \assets\styles\main.less 中从第 185 行开始全部删除，在 \assets\media\scripts\main.js 中从第 59 行开始删除<br>
如要更换鼠标颜色，在 \assets\styles\main.less 中第 189 行“background”后和 \assets\media\scripts\main.js 中第 100 行第 196 列“rgb(xxx, xxx, xxx)”处更改颜色值