# 开源训练营
为新加入开源的新手提供相关的教程

## 内容
* 提供了[生产开源软件](https://producingoss.com/)讲义
* 公共协作相关的讨论以及实践游戏 

## 使用技术

幻灯片由 [asciidoctor](https://asciidoctor.org) 标记生成，并使用 [reveal.js](https://asciidoctor.org/docs/asciidoctor-revealjs/) 显示。这意味着内容可以使用版本控制，并可以导出 为HTML 等多种格式。

请查看 [asciidoctor-revealjs](https://asciidoctor.org/docs/asciidoctor-revealjs/#syntax-examples) 的示例，了解有关使用 reveal.js 的更多信息。

感谢 [Apache 培训项目](https://training.apache.org/) 提供了非常有价值的内容。

## 访问最新内容

借助Github Action和Github pages，我们可以在【github页面】（https://willemjiang.github.io/open-source-camp/index.html） 中部署最新的master内容。

##如何贡献

* 请查看演示内容并提交PR到此Repo代码库。
* 如果您想添加任何有趣的内容，请随时在 [讨论](https://github.com/WillemJiang/open-source-camp/discussions) 中发起话题。

## 如何构建

如果您已经设置了 JDK 和 maven，只需运行以下命令：

`mvn clean compile`

## 如何查看幻灯片

构建完成后，可以在以下位置找到生成的幻灯片：

`presentations/target/generated-slides/index.html`

只需在浏览器中打开 `index.html` 即可查看幻灯片。

某些功能需要通过 http/https url 查看幻灯片，您可以通过运行以下命令来执行此操作：

`mvn jetty:run-exploded`

并在浏览器中访问`http://127.0.0.1:8080/index_en.html`或`http://127.0.0.1:8080/index_cn.html`查看。

如何打印pdf：
请在浏览器中访问“http://127.0.0.1:8080/index_en.html?print-pdf” 并以横向布局打印页面。

一些可以帮助您进行演示的快捷键：

- 光标键和空格键可以浏览幻灯片。
- 按 S 将在单独的窗口中显示演讲者备注和计时器。
- 按 F 全屏。
- 按 N 下一张幻灯片或 P 上一张幻灯片。
- 按 O（查看概览）将显示幻灯片地图/概览。
- 按 B 将黑屏。
