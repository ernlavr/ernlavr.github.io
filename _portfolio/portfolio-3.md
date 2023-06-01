---
title: "Augmented Reality Indoor Positioning and Navigation"
excerpt: "End-to-end indoor navigation system proposal. Based on internal accelerometer data and environment mapping capabilities by Magic Leap headset. Uses local area network for client/authoring devices to interact with a centralized server that performs data processing and pathfinding. <br/><img src='/images/portfolio/arNavigation/Pictures/ClientApplication/TopVIewNavigation.png' width=\"400\">"
collection: portfolio
---

*Conducted as part of a group with Anna Horwath and Christian Neurohr*

[Download the Full Paper](/files/portfolio/fullPapers/arNav_med07.pdf)

Relevant GitHub Repos:
- [Python Server](https://github.com/ernlavr/SP_Server)
- [Environment Mapping Application](https://github.com/ernlavr/SPMapping)
- [Client Application](https://github.com/ernlavr/SPClient)


# Abstract
Indoor navigation is a topic undergoing research within robotics, but
can also be applied in commerce, manufacturing or industrial applications.
We investigate how AR Head-Mounted Display Magic Leap 1 can be integrated into an indoor navigation framework aimed for commerce or asset
management. Magic Leap 1 supports spatial mapping of real-life environment as well as tracking users in six degrees-of-freedom, and provides the
ability of recognizing and estimating the orientation in space of fiducial
markers. We propose an end-to-end framework that is able of mapping
out an environment, digitally processing it by using the A* algorithm for shortest path, and providing a framework
for connecting client devices for issuing navigation requests. 

Our system
proves to function end-to-end although fails to improve task completion
time when tested in a mock-up environment. This can be attributed to
over-simplified test task, low resolution of guidance elements and general
inexperience with AR devices by the test subjects. Our study concludes
that the first iteration design should have an improved user interaction
and it should be tested with a different methodology. It also identifies
future work and features such as IoT communication, computer vision
integration and a revamped user interface based around human-computer
interaction research.

