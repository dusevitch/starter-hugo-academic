---
title: Characterization of Patient Head Motion in Vitreoretinal Surgery
summary: Exploration of ways to improve head tracking for anticipating motion for eye surgery.
tags:
  - surgical_robotics
date: '2018-08-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Surgical Room Setup
#   focal_point: Smart

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
During eye surgery, the patient’s head moves due to natural processes such as breathing and snoring, and the surgeon must compensate for this movement to the best of their ability. However, such movement limits the precision of the surgeon and thus the difficulty of the procedures that can be accomplished. A variety of robotic systems are being developed to improve surgical precision, and these systems will also need to address this patient movement. However, very little quantitative data is currently available regarding patient head movement during eye surgery. This project explored methods to address these issues using EKF algorithms from data collected from a single inertial measurement unit (IMU) fit to the patient's head.