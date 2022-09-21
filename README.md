# open-source-camp
Providing tutorials for the newbie of open source

## Contents
* Basic information about How to running the OpenSource

## Access the latest conent
With the help of Github Action and Github pages, we can deploy the latest master content here
`https://willemjiang.github.io/open-source-camp/index.html`

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
- Press N for next slide or P for previous slide.
- Press O (for overview) will show a slide map / overview.
- Press B will black the screen.

