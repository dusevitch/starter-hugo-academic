---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Fellow
    company: Johns Hopkins Unversity, Laboratory for Computational Sensing and Robotics & Department of Orthopedic Surgery
    company_url: 'https://bigss.lcsr.jhu.edu/'
    company_logo: jhu
    location: Baltimore, MD
    date_start: '2021-09-15'
    date_end: ''
    description: |2-
        * Invented and prototyped flexible microsurgery multipurpose surgical robot and tool. Directed 2 students in robot CAD design,rapid prototyping, and controls development.
        * Creating an augmented handheld drill for improved laminectomy milling. Conducting tests examining surgeon drilling preferences in AMBF virtual environment and testing multi-sensor deep learning state detection for safer and faster laminectomy drilling.
        * Built on existing software framework for UR robot interface robot in C++, creating Python script bindings for "real time" ROS/ROS 2 commands.

  - title: Research Assistant, Ph.D. Candidate & Masters Student
    company: University of Utah, Robotics Center, Telerobotics Lab
    company_url: 'https://www.telerobotics.utah.edu/'
    company_logo: U_logo
    location: Salt Lake City, Utah
    date_start: '2016-07-01'
    date_end: '2021-09-15'
    description: |2-
        * Image-guided Surgical Navigation: Created intuitive image-guided tool navigation software in C++, reducing state-of-the-art navigation time by 63% and doubling navigation intuition. Conducted human subject studies for method validation and secured patent.
        * Magnetically-Guided Cochlear Implant Surgery: Built hardware and C++ software for magnetic guidance of cochlear implants to eliminate insertion trauma. Conducted end-to-end planning and execution of 36 in-vivo animal surgeries. Demonstrated up to 38% reduced trauma insertion force using magnetic guidance.
        * Telemanipulated Retinal Surgery Robot: Collected eye-surgery data and devised EKF-based filtering algorithms to characterize head motions (<5 degrees) for robot design via a single IMU for tracking.
        * Motion Planning for Intraoperative Magnetic Microrobot Swarms: Formulated motion planning methods to use 8 magnetic fields for wireless control of microrobot swarms for drug delivery and tumor ablation.
        * TA for Mechatronics and Numerical Methods courses. 
        * Relevant courses taken: Robotics, Controls, Motion Planning, Haptics, System ID, Machine Learning, Computer Vision

  - title: Research Assistant
    company: Brigham Young University, Various Labs
    company_url: ''
    company_logo: byulogo
    location: Provo, Utah
    date_start: '2013-06-01'
    date_end: '2016-07-01'
    description: |2-
        * ORCA - Compliant Haptic Force Sensor: Invented a compliant, 1-DOF haptic force sensor similar to the Stanford Haptic paddle which displays force difference of up to 5.8 N.
        * BABEL lab - Novel Spinal Clamp Development: Prepared FEA analysis and executed load testing on jointless compliant spinal clamp for spinal fusion surgery without pedicle screws.
        * CAD lab - Team Optimization and Design: Constructed genetic optimization algorithms and an analytics tracking platform for optimized team formation and improved work efficiency for a multi-user CAD system.
        * SEEL - Web Team Manager and Developer:

design:
  columns: '2'
---
