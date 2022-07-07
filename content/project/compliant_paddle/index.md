---
title: Design and Comparison of Variable-Stiffness Compliant Joints for Haptic Devices
summary: A custom-designed and jointless compliant mechanism demonstrated the ability to represent haptic forces. The design was inspired by the Stanford Haptic Paddle.
tags:
  - other
date: '2016-05-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Compliant Haptic Paddle Design Iterations
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

Haptic interfaces or devices are computer-controlled robotic systems that seek to replicate the touch experience of a human user1. The purpose of this research is to develop a viable variable-stiffness compliant joint for haptic interfaces that eliminate rotation joints or screw mechanisms that induce friction, increase weight and cost, and make devices more complex and prone to failure. The resulting compliant haptic device was designed with both affordability and dependability in mind, and hopes to result in research knowledge leading to realistic touch experiences as users interact with virtual or remote environments. The joint may also be applicable in other common future applications such as robotic arms and legs, rehabilitation robots, and haptic educational tools.

Model 3 showed the most promise according to FEA output, combining ease of manufacturing and proof of haptic feedback. It was created using a triangular meshing technique with 2560 nodes. There was an 8 N increase of the resultant force when the device was compared with an arm movement at rest to an arm movement of 1.27 cm (0.5 in) when it’s lower legs were displaced by 2 cm. This model was selected for the physical testing.

Tests for the fixture was performed by compressing the lower arms of the device together at intervals of 4, 3.5, and 3 in. This was to mimic the same motion as might occur if the legs were attached to a spinning motor, solenoid, etc. The main arm was then moved until the top point was displaced horizontally by 0.5 in. The force for physical displacement was then recorded and results can be seen in the figure below. Additional iterations were performed, but not included in this report. We are able to see that the physical device saw an overall 5.8 N resultant force increase between the positions tested.