# jTimeline

A jQuery powered horizontal timeline.

![Demo](https://raw.githubusercontent.com/optimumweb/jtimeline/main/demo.png)

## Installation

```
npm i @optimumweb/jtimeline
```

## Usage

```
$(document).ready(function () {
    $('#jtimeline-demo').jTimeline();
});
```

## Settings

resolution: pixels per second (default: 50000)

minimumSpacing: minimum spacing between events (default: 200)

step: scrolling (translateX) step size (default: 200)

leftArrow: character for left arrow (default: &larr;)

rightArrow: character for right arrow (default: &rarr;)

### Example

```
$(document).ready(function () {
    $('#jtimeline-demo').jTimeline({
        resolution: 20000,
        minimumSpacing: 500,
        step: 500,
        leftArrow: "<",
        rightArrow: ">"
    });
});
```

## About

Author: OptimumWeb Inc. / Jonathan Roy

Website: https://optimumweb.ca

Twitter: https://twitter.com/jonathanroy

License: MIT
