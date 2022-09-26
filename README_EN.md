# open-source-camp | [中文](README_ZH.md)
Providing tutorials for the newbie of open source

## Contents
* Slides which are based on How to [Producing the Open Source Software](https://producingoss.com/)
* Interesting discussions and Games about how to work in public 

## Technology Used

The slides are generated from [asciidoctor](https://asciidoctor.org) markup and displayed with [reveal.js](https://asciidoctor.org/docs/asciidoctor-revealjs/). This means the content can be kept under version control and exported to a number of formats other than HTML.

Please check out the examples of [asciidoctor-revealjs](https://asciidoctor.org/docs/asciidoctor-revealjs/#syntax-examples) for more information about using markdown with reveal.js.

Thanks to [Apache training project](https://training.apache.org/) provides a very useful content tool. 

## Access the latest content
With the help of Github Action and Github pages, we keep deploying the latest master content in [the project github page](https://willemjiang.github.io/open-source-camp/index.html)

## How to contribute

* Please review the presentations content and send Pull Request to this repository.
* Please feel free to start a topic in the [Discussions](https://github.com/WillemJiang/open-source-camp/discussions) if you want to add any interesting contents.

## How to Build

Just run the below command if you already setup the JDK and maven:

`mvn clean compile`

## How to View the Slides

Once built, the generated slides can be found at:

`presentations/target/generated-slides/index.html`


Just open the `index.html`  in a browser to view the slides.

Some features require the slides to be viewed via a http/https url you can do this by running:

`mvn jetty:run-exploded`

And goto `http://127.0.0.1:8080/index_en.html` or `http://127.0.0.1:8080/index_cn.html`in a browser to view.

How to print pdf:
please access "http://127.0.0.1:8080/index_en.html?print-pdf” in a browser and print the page with landscape layout.

Some key shortcuts that may help you give a presentation:

- Cursor keys and space can navigate the slides.
- Press S will show speaker notes and a timer in a separate window.
- Press F for full screen.
- Press N for the next slide or P for the previous slide.
- Press O (for the overview) will show a slide map/overview.
- Press B will black the screen.

