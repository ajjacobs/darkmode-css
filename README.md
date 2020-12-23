## Overview

A rip-off of [Solarized css](https://thomasf.github.io/solarized-css/) but with the color palette of [org-roam-server's](https://github.com/org-roam/org-roam-server) darkmode, which 
I like a lot better. Hosted here so I can share my notes easier with easier navigation than a pdf.

## Usage

Add these lines and run `org-export-dispatch`

```
#+INFOJS_OPT: view:t toc:t ltoc:t mouse:underline buttons:0 path:http://thomasf.github.io/solarized-css/org-info.min.js
#+HTML_HEAD: <link rel="stylesheet" type="text/css" href="//http://github.com/ajjacobs/darkmode-css/css/darkmode.css" />
```

If you prefer, you could also copy these into a local file, e.g. `darkmode.setup`, and use 

```
#+INCLUDE: path/to/darkmode.setup
```
