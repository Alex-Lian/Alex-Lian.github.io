---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Linux-like Kernel"
summary: "This is the final project of course ECE391 @ UIUC. We develop the core of an operating system almost from scratch."
authors: []
tags: []
categories: []
date: 2021-11-09T20:41:21-06:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/Alex-Lian/ECE-391-final-project"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This is the final project for my ECE391 course taken in UIUC. I am fortunated to work with wonderful teammates: Jiaqi Lou, Zhongbo Zhu and Tianyu Liu. In this project, we develop the core of an operating system.
If you want to take a look at the code, please visit: https://github.com/Alex-Lian/ECE-391-final-project
The following part are some demos.

---
### Boot Animation
we can also see the desktop and the status bar in the buttom with location and time.
<img src="ECE391_demo/boot_animation.gif" alt="show" />   

---
### Cursor Display
The self-designed cursor can open a new terminal and close it smoothly.
<img src="ECE391_demo/cursor_display.gif" alt="show" />   

---
### Terminal
The terimal can continue to run the program when it is minimized.
<img src="ECE391_demo/terminal.gif" alt="show" /> 
The terminal can support code completion and history buffer.
<img src="ECE391_demo/history_buf.gif" alt="show" /> 

---
### Operation
<img src="ECE391_demo/basic_operation.gif" alt="show" /> 

---
### Signal
We can use “CRTL+C” to terminal the current program, which is the signal part in linux kernel.
<img src="ECE391_demo/signal.gif" alt="show" /> 