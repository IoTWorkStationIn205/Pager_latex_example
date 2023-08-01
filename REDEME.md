# 基于Latex论文写作模板

## 目录结构

```sh
├─.vscode 配置文件
├─image   图片存放
├─LatexPage Latex排版,主要作文字排版
├─SourcePage 论文编写,主要作文字输出
└─template 模块示例文件
```

## Bug解决方案

Q:参考文献无法显示

A:终端使用下列命令

```sh
bibtex <--.aux>
```
