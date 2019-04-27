# Serve static files with express.js

[![](https://images.microbadger.com/badges/image/gdml/serve-static.svg)](https://microbadger.com/images/gdml/serve-static.svg "Get your own image badge on microbadger.com")
![](https://img.shields.io/docker/build/gdml/serve-static.svg) ![](https://img.shields.io/docker/pulls/gdml/serve-static.svg)


Tiny image we use to serve our vue.js-based SPAs with bundled healthcheks.


## Usage
Build your frontend to a folder named `dist` and add this Dockerfile:

```
FROM gdml/serve-static:1.0.0
```
