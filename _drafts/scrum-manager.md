---
layout: post
title:  "Building Scrum Manager, part 1"
date:   2013-10-14 17:44:24
categories: scrum manager project part1
---

For a while now I've been developing an open source project known as [Scrum Manager][scrum-manager], which is a tool that intends on allowing distributed teams to handle Scrum related meetings faster and better than ever before. I'm using it as an experiment into designing a SOA application, as the first goal is to be able to provide three components.

- A webserver running the central API for the system, and that allows for data interaction via application keys and API (token) keys.
- A webserver running a web-based display interface for said system above.
- A desktop application that can connect and access the same information, and enabling data synchronisation between platforms.

I'm currently in the early phases of the project, and I'm still working on the API, which I want to build using the JSON format at first, and that can be extended later on if there is need. I've taken a very strong position in regards to testing, and am developing components independently, so that I don't lost sight of the important lower-level details. I'm also leveraging some of the very powerful tools out there in order to create 

[scrum-manager]: https://github.com/petrepatrasc/ScrumManagerWeb