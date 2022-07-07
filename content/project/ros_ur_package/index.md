---
title: Software Development for Infrustructure of Robot Drilling Tool
summary: Developed code to move the UR robot in ways to drill using a cable-driven continuum Snake Robot
tags:
  - surgical_robotics
  - software
date: '2021-12-15T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Snake and UR Robot
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

A continuum snake robot for drilling was developed previously in the BIGSS lab. This project continued the software high-level and mid-level control development for the UR interface using Python and C++. The JHU CISST library was heavily integrated to move the arm under position, velocity, and various other types of control, and some contraints were implemented to guide the robot along simple trajectories. Basic simulations were performed in ROS/Gazebo/RVIZ configurations for validation and some tested on a physical UR5 robot.