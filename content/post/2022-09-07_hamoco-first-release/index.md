---
title: First official release of hamoco
subtitle: hamoco v.1.0.1 is released on PyPI.

# Summary for listings and search engines
summary: "hamoco v1.0.1 is now available on PyPI for Linux and Windows. Take control of your mouse by using hand gestures captured in real time by your webcam."

# Link this post with a project
projects: [hamoco]

links:
  - icon: github
    icon_pack: fab
    name: GitHub
    url: https://github.com/jorisparet/hamoco
  - icon: python
    icon_pack: fab
    name: PyPI
    url: https://pypi.org/project/hamoco/

# Date published
date: '2022-09-07T00:00:00Z'

# Date updated
lastmod: '2022-09-07T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ''
  placement: 2
  preview_only: false

authors:

tags:
  - Python
  - Machine Learning
  - Deep Learning

categories:

---

**hamoco** (*handy mouse controller*) allows you to take control of your mouse by using hand gestures that are captured in real time by your webcam. It relies on [MediaPipe](https://google.github.io/mediapipe/) to track hands, and the nature of the different hand poses are predicted by a small neural network built with [TensorFlow](https://www.tensorflow.org/). Basically, I thought that it might be fun to try and replicate the famous scene from the movie [Minority Report](https://en.wikipedia.org/wiki/Minority_Report_(film)) (spoiler: it's cooler when Tom Cruise does it).

You can perform all the basic mouse actions: *motion*, *left/right click*, *vertical scrolling* and *drag & drop*. There are many options to adjust the experience to your liking (*e.g.* sensitivity, motion smoothing) and even an automated pipeline to record your own data and train a custom neural network tailored to your needs.

The code is now available on [PyPI](https://pypi.org/project/hamoco/) in version 1.0.1, and you can also check out the page of the project on [GitHub](https://github.com/jorisparet/hamoco).