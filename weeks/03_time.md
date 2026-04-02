# Week 03 Time

## [[Previous](./02_code.md)] [[Next](./04_video.md)]

## Review

- use p5mirror
- [p5mirror](https://github.com/molab-itp/p5mirror)
  -- download your editor.p5js sketches into your git repo

## ims-2026-jht-nyu

- clone ims-2026-jht-nyu for review

- [ims-2026-jht-nyu](https://github.com/jht9629-nyu/ims-2026-jht.git)

## Using Time

- https://editor.p5js.org/jht9629-nyu/sketches/i6akdNRS2
  - video scan radial v7
    - secsDelta += deltaTime / 1000;

- https://editor.p5js.org/jht9629-nyu/sketches/2bjn_Nn9x
  - video scan radial v8

- https://editor.p5js.org/jht9629-nyu/sketches/3VKJ-q8ar
  - ims03-jht scrolling color bars
  - color pops on at wrap around - no rate regulation

- https://editor.p5js.org/jht9629-nyu/sketches/ZpoPuHXRo
  - ims04-jht scroll color bars - no pop

- https://editor.p5js.org/jht9629-nyu/sketches/2pxhnehBV
  - ims04-jht scroll color rate
  - rate adjusted to achieve complete
  - scroll in my.scrollSeconds
  - https://p5js.org/reference/#/p5/deltaTime
    - let deltaSecs = deltaTime / 1000
    - my.xstep = width \* deltaSecs / my.scrollSeconds;

- https://editor.p5js.org/jht9629-nyu/sketches/wT957KlMz
  - MazeSpin liberation screens v2
    - let now = millis() / 1000;

## saving data locally

Must run locally or in web browser to use url parameters

- url param strings
- localStorage

- https://editor.p5js.org/jht9629-nyu/sketches/I9vT_uniR
  - get_url_params v2

- https://editor.p5js.org/jht9629-nyu/sketches/qz9-Y-Sc4
  - localStorage v1

- https://editor.p5js.org/jht9629-nyu/sketches/TQyVoswjQ
  - p5moLibrary DrawPoints
  - https://molab-itp.github.io/p5moLibrary/src/demo/DrawPoints/?v=65

- https://editor.p5js.org/jht9629-nyu/sketches/iIIAb8KIDr
  - p5moLibrary Astronomical 47
  - https://molab-itp.github.io/p5moLibrary/src/demo/Astronomical/?v=65

- [p5moLibrary](https://github.com/molab-itp/p5moLibrary)

## Class Exercise

### create repo for the class

- create a repo for the class
  -- name repo ims-2026-yourNickName
- make jht9629-nyu a collaborator
- add link to your repo to your wiki page

### update your class repo

- put homework sketch in your github repo for this class
- github pages setup
- add and test sketch get_url_params
- add and test sketch localStorage

### update your p5mirror repo

- run and commit your p5mirror repo

## Homework Week03

- Expand your full screen p5js sketch or create a new one that:
  - changes over time to standalone input in an installation setting
  - option: uses time as input
  - option: use url parameters as input
  - option: use camera/mic/ml5js as input
  - option: adjust for mobile vs. desktop screen orientation

- add a link to your sketch on the [wiki home page](https://github.com/p5videoKit/IM-Screens-2026-03-itp/wiki#week-03-homework)
  - also make the p5js sketch available via your github repo as github pages
  - be sure to include all atributions (eg. links to source sketch, ai chat prompts, etc.)

- enter any questions or notes on your wiki page

<!-- ## nodejs setup

[https://nodejs.org/en/download](https://nodejs.org/en/download)

 -->

## Class Resources

- [p5mirror](https://github.com/molab-itp/p5mirror)
  - mirror your editor.p5js sketches into a git repo

- [p5moExamples](https://github.com/molab-itp/p5moExamples)
  - p5js examples for p5moLibrary

- [p5moLibrary](https://github.com/molab-itp/p5moLibrary)
  - a p5js Library for cloud storage enhanced multi-device experiences

- [p5VideoKit](https://github.com/molab-itp/p5videoKit)
  - a dashboard for mixing video in the browser.
