<h1 align="center">İsmail Aydınlık</h1>
<p align="center"><code>@ismaiwz</code> · Mechatronics Engineering · Pamukkale University</p>

I build web tools and write software for the ALAZ ground vehicle team. Two projects sum up what I like working on: a dashboard that makes sensor readings visible, and a messaging test that tells me how long those readings take to arrive.

On the bench

Sensor control panel ↗
I built a virtual sensor rig for my introductory mechatronics course. Move an obstacle in the ultrasonic simulation and you can follow the distance reading on a live chart. Five other channels track temperature, humidity, light, gas and vibration. I used Node.js and Socket.IO to stream the readings to a Chart.js dashboard.

ALAZ · Unmanned ground vehicle
I tested a Node.js WebSocket server with five clients connected. I was aiming for 1 ms and measured 2.6–4.5 ms in that test. My next step on the robotics side is writing ROS 2 nodes in C++.

Browser automation
One of my Electron tools takes a list of product codes and quantities, enters each row into a production form and checks the result. The interesting part was handling a rejected row halfway through a batch.

Tools I reach for
Node.js Express MySQL Socket.IO Electron Linux

Explore my repositories →
