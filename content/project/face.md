+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Motion Detection and Face Recognition Software"

# Project summary to display on homepage.
summary = ""

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "face_rec.png"

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

Both motion detection and face recognition, individually, has a wide variety of usage. In this project, we combined both of them to create a video surveillance system.  Euclidean RGB distance approach with threshold was used in sequential images to detect the motions. The detection signal was used as the trigger mechanism to start face detection. Faces in the video were found with Haar-Cascade classifier and recognition was done with eigenface method.
