+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Vision-Based Location Feedback of Stewart Platform"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "stewart_1.jpeg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = [""]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

The Stewart Platform is a parallel mechanism which has six actuators mounted on a fixed plate and an end effector for spatial motion.Stewart Platforms have applications in various areas such as machining technology, flight simulators, air-to-sea rescue systems, telescopes, crane systems, orthopedic surgery, and so on. Starting in 1987, direct kinematics problem and complexity of Stewart Platforms has drawn the attention of many researchers. In forward kinematics problem, extraction of end effector variables from joint space variables is required to have an acceptable trajectory tracking. Since it doesn’t have an explicit solution, lots of researchers have attempted to find a reliable and rapid method for the real-time applications.
The aim of this study is to develop a vision-based location feedback system. 3 cameras are placed on the normals of the joints and focused at the center of each marker square. Changes in marker squares are examined and compared with each other to calculate the position and orientation of the platform, and the length of the links. This project was a great experience to put the theory into practice.

Reference Publication : http://journals.tubitak.gov.tr/elektrik/issues/elk-11-19-5/elk-19-5-6-1007-600.pdf
