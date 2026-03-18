---
title: "Crossing Bridge Problem Simulation"
categories: [Game Dev, Unreal Engine]
featured: /assets/images/project_re1.png
---

This project is a simulation of the classic “Bridge and Torch” problem, it's a university project for the "Algorithms analysis & design" subject. It was implemented using Unreal Engine. The goal was to visualize and solve the problem using the Greedy Algorithm, demonstrating both algorithmic thinking and real-time simulation.

Problem Overview:

A group of people must cross a bridge at night with only one torch available. The constraints are:

-Only two people can cross at a time

-The torch must always be carried when crossing

-Each person walks at a different speed

-When two people cross together, they move at the slower person’s speed

The objective is to get everyone across the bridge in the minimum total time.

Solution Approach (Greedy Algorithm):

The Greedy Algorithm works by making the locally optimal choice at each step, aiming to minimize the total crossing time.

-For four people with different crossing times (e.g., 1s, 2s, 4s, 5s), the optimal strategy is:

1-The two fastest people cross first

2-The fastest returns with the torch

3-The two slowest people cross together

4-The second fastest returns

5-Finally, the two fastest cross again

This approach minimizes the total time (e.g., 17 seconds in a typical case).

Implementation in Unreal Engine:

-Simulated each person as an entity with a defined crossing time

-Visualized movement across the bridge in real time

-Implemented the greedy logic to determine optimal crossing order

-Displayed the sequence of actions and total time taken

This Project Demonstrates:

-Understanding of Greedy Algorithms

-Ability to translate theoretical problems into interactive simulations

-Use of Unreal Engine beyond games — for algorithm visualization and problem solving





### Gameplay Video
{% include video id="zMm91I30OEw" provider="youtube" %}

