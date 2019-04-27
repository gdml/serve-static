# Serve static files with express.js

Tiny image we use to serve our vue.js-based SPAs with bundled healthcheks.


## Usage
Build your frontend to a folder named `dist` and add this Dockerfile:

```
FROM gdml/serve-static:1.0.0
```