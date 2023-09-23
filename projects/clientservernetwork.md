---
layout: project
type: project
image: ../img/switch1.jpg


title: "Client Server Network Project"
date: 2023
published: true
labels:
  - C
  - Networking
  - Switches
summary: "A simple client server network program from my Data Structures and Algorithms class."
---

This is a project I worked on with me and 2 other team members to create a simple client server network for my Data Structures and Algorithms class.

<img class="img-fluid" img width="600px" src="../img/switch1.jpg">

In this project, we were to create and configure a network in which a host computer can send commands to other connected computers using pipes, sockets and a switch. In this network, the host computer can download files, upload files, and send and recieve ping messages from other computers. Overall, this code implements a basic network switch that forwards packets between ports based on MAC address forwarding entries. The switch maintains a table of MAC addresses and their associated ports to make forwarding decisions. It continuously scans incoming packets and forwards them according to the MAC address table or broadcasts them if the destination is unknown.

Within the code are also functions which facilitate the sending and receiving of network packets between different network ports as well as a defined network topology using nodes and manager-host communication ports. 

Here is a [link](https://github.com/murrayn808/EE367L_clientservernetwork) to the repository.
