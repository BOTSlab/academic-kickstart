---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Orbital Construction"
summary: "Orbital construction drives a swarm of simple robots to push objects into a desired shape."
authors: [av, caroline_strickland]
tags: []
categories: []
date: 2019-10-07T18:35:23-02:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "4 CANARY robots form a line segment from 40 Lego blocks"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/BOTSlab/cwaggle/tree/orbital_av"
url_pdf: ""
url_slides: ""
url_video: "https://youtu.be/pzAI-ygLF1Q"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Orbital construction (OC) is an algorithm that drives a swarm of simple robots to push objects into a desired shape.  The shape is specified by a scalar field which plays a similar role to the pheromones used by social insects (e.g. termites and ants) when forming their sophisticated nest structures.

OC was introduced in
[[Vardy, 2018]({{< ref "/publication/vardy-2018-orbital/index.md" >}})].
M.Sc student Caroline Strickland then investigated the application of Reinforcement Learning to the problem of pushing objects into a desired shape.
[[Strickland, 2019]({{< ref "/publication/strickland-19-rl/index.md" >}})].  Most recently, we introduced a hardware realization of this algorithm described in a paper submitted to ICRA 2020.