---
layout: post
title: "Blog Stuff: Wrapping Long Lines"  
date: 2018-01-19 00:00:00 -0700
description: Simple CSS fixes for highlighter and gists 
img: pprz_cam_screenshot.png # Add image post (optional)
tags: [UAV, Camera, footprint, aerial, field of view, quaternions, angles] # add tag
---
## Questions

/* GitHub Bug: Enable wrapping of long code lines */
.blob-code-inner, .markdown-body > pre > code,
.markdown-body > .highlight > pre {
  white-space: pre-wrap !important;
  word-break: break-all !important;
  display: block !important;
}

pre {
  white-space: pre-wrap
}

pre code {
  white-space: pre-wrap
}


https://github.com/StylishThemes/GitHub-Dark/issues/253


Thanks for reading. I hope this helps somebody out!!
