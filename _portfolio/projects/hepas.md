---
title: "HEPaS (Honours Enrolment Pre-Assessment system)"
# permalink: projects/baddyApp
---
<video controls width="640" height="360" style="height: auto; max-width: 100%;">
    <source src="{{ 'assets/videos/hepas.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
</video>

## Description: 
This small distributed system helps students determine if they are qualified to enroll in an honors degree program. It is a three-tier system consisting of Server 1, Server 2, and the client. Server 1 handles client requests via RMI (Remote Method Invocation), an API that allows communication between the client and Server 1 over the network using remote objects. Server 2 processes requests sent by Server 1 via RMI, retrieves the requested data from the database, and sends it back to Server 1, which then delivers the final output to the client.

## Source Code URL: 
[Github](https://github.com/HilaryCodeLab/HEPaS)
## Tech Stack:
Python, Console Application, Pyro5