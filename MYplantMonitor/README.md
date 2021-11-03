# Plant Monitor
Second workshop for CASA0014 - 2 - Plant Monitor

By André Bourgeois

# Description
The intent of this project is to create a Plant Monitor that can transmit data (temperature, humidity level, and soil moisture) to an MQTT server.
This data will allow me to determine what my plant needs to stay healthy, so I can keep it alive for the remainder of the year. This folder contains both the final sketch
and test sketches that have gone into building this project, and it is currently a work in progress.

# Current To Do List
- Install Influx DB on RPI
- Collect and store soil data
- Visualize data on Grafana
- View soil data
- Add pictures to readme.md
- Add more comments to code after understanding what the code does
- Add step-by-step process to the readme.md

# Materials
- Soldering Machine
- Standrard Feather Huzzah ESP8266
- USB Cable
- Custom CASA Huzzah ESP8266
- Raspberry Pi (with SD card, SD card reader + case for aesthetics)
- DHT22 Temperature/Humidity Sensor
- 10k Resistor x2
- 1k Resistor x2
- 220 Resistor x2
- 30cm Length of Wire x2
- 6cm Hardware Nail x2
- Potted Plant

# My Plant
**Begonia maculata**

Also known as the Polka dot Begonia, or Spotted Begonia, this plant can be identified by its large angel wing-shaped leaves patterned with
polka dots on top and a deep purple-red on the bottom side.

**Care Instructions**
- Needs bright, indirect sunlight - must be kept out of direct afternoon sun
- Water regularly, let top soil dry out between watering, let excess water drain from pot - must keep soil somewhat moist

**Things to Keep in Mind**
- Different plants may require different kinds of care

# The Process
**Step 1:**

# Things That Made This Project Easier for Me
**Using Atom IDE + Github Desktop Git Client**

Both Atom and GitHub Desktop were developed by Github, and seem to link together very seamlessly. Although this is my first time using Atom, a git client,
and pushing my work to github in a few years, I believe the way these softwares work together made the learning process a lot easier for me

**Writing Code Out Manually**

Although this code has been pulled from a project of the same name by Prof. Duncan Smith, opting to rewrite all of the code by hand helped me to better understand
how it works

**Commenting Everything**

I don't have an extensive background in IoT or computer science in general, so opting to add comments to everything possible has been a huge help
in allowing me to understand the code better.

# What I Am Struggling With
- I am having difficulty understanding MQTT and the code related to connecting to the wifi, MQTT server, etc.
- I only made it to step 10 - setting up RPI as a gateway

# Things I Want to Improve for This Project
- Add in a light sensor to detect how much light the plant is getting

# What I Want to Improve for My Next Project
- Better and more consistent documentation for each step
- Build the read.me throughout the project
- Take more pictures
- Read ahead so I can spend more time on things I'm struggling with