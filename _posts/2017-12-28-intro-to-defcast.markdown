---
layout: post
title:  "Intro to Defcast"
date:   2017-12-28 19:12:00 -0800
categories: post
author: Allen Wheeler
highlighter: rouge
---
[![sync](http://img.shields.io/badge/repository-synced-brightgreen.svg)][sandbox-sync]

[sandbox-sync]: https://defcast.github.io
<hr>
<br>
Defcast makes it possible to send and receive content between `aircraft` and `devices` anywhere in the world in realtime. It's specialized for broadcast, government, and private entities although it's flexible enough to support the content being shared with millions of viewers too. Below are some examples of the tools and services involved. 

<hr>
## Web Interface

![client]({{ "/assets/img/web-client.png" | absolute_url }})

Since this capability is relatively new that means that it's potential isn't yet fully realized and the methods for accomplishing everything have a lot of room to improve. Take for instance the interface that operators use to establish the links between aircraft and the ground. Defcast is working to bring this to the leading edge of design, functionality, interoperability, and security. While each component has its own separate pages and controls, the web interface also offers options for concatenating everything so that operators can view more information based on the individuals `preferences` and the most useful information.

Looking at this demonstrated in the representation above there are four main components:

- A video player
- A map
- Data link controls
- Signal levels

<br>

#### Video Player

The video player is unique in that it allows the aircraft `telemetry` ,  sensor metadata, and data link `metadata` to be displayed as an `overlay` which can be `toggled` by the operator. Advanced users can even configure what information is displayed on the overlay while admins can enable/disable this feature at will per user.

It can also be used to display detailed logs to assist in troubleshooting interruptions of streaming video. These logs can be configured to trigger actionable tasks sent to Defcast customer support automatically behind the scenes. That means that before a customer has the opportunity to contact customer support, Defcast has already received information about what caused an interruption. This is just scratching the surface regarding the automation and integration of operations and services.

<br>

#### Mapping

The benefits of having visual representation available to display where assets are located during operations can't be understated. It lets operators understand the limitations of the operating environment and assists users in making `tactical and technical decisions` .  The web interface includes the ability to be able to control assets from the map itself when automation isn't the best solution at the time. An operator can select an aircraft for use with a particular receive site when multiple aircraft are operating simultaneously and the map can be configured to show the data link maximum `range` which can go a long way in understanding why the data link may not be operating at peak performance in many scenarios.

<br>

#### Controller

This is the operational control of all of the equipment involved in establishing and maintaining the data links.

- Change `bands` and `channels`
- Steer `antennas`
- Adjust `bandwidth` versus `range` 
- Enable/disable `automations` (such as antenna tracking and site selection)

<br>

#### Signal Levels

Visual representation of the strength of the signals involved in the data links. This can be toggled between a spectrum viewer or meters and will eventually offer other experimental visual methods for showing operators the `health` of the signal.

<hr>
<br>

## System Design

There is no one size fits all solution when it comes to live content from aircraft and mobile ground assets. Defcast specializes in designing the best solution within a clients operational, technical, and financial constraints. 

![signal]({{ "/assets/img/signal-flow-fade.png" | absolute_url }})

Here is an easy to follow diagram showing the path of a typical data link designed by Defcast.  

<hr>

