---
title: "Real time Strategy "
categories: [Game Dev, Unreal Engine]
featured: /assets/images/project_re1.png
---

A real-time strategy (RTS) building system developed in Unreal Engine 4, inspired by classic games like Command & Conquer: Generals and Red Alert. This project focuses on replicating the core mechanics of RTS construction and interaction systems.

Key Features:

Mouse-based controls for intuitive gameplay

Real-time building placement system

Ability to construct and sell buildings dynamically

Camera controls including zooming and rotation

Overview:

This project demonstrates how RTS building systems work from a technical perspective. It implements the full workflow of placing structures from a UI “building bar” into the game world.

A key challenge was converting 2D screen input into accurate 3D world placement. This was achieved using raycasting techniques to project the cursor position into the game environment, allowing precise placement of buildings on the map.

Additionally, the system supports selling buildings by casting a ray toward selected structures, detecting collisions, and removing them from the scene.

The camera system was designed to match traditional RTS controls, allowing players to smoothly zoom, rotate, and navigate the environment.

### Screenshots
{% include figure image_path="/assets/images/RTS/RTS1.png" %}
{% include figure image_path="/assets/images/RTS/RTS2.png" %}
{% include figure image_path="/assets/images/RTS/RTS3.png" %}
