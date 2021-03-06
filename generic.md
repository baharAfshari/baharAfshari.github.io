---
layout: post
title: Generic
description: Lorem ipsum dolor est
image: assets/images/pic01.png
nav-menu: true
---

The basic idea in the Vicsek model is that at each time step, each particle moves in the average direction of its neighbours with some noise caused by the disorder. In other words, each particle follows its neighbours. However, the particles make mistakes when evaluating their neighbours' trajectory, which is considered noise. In the mathematical description of the Vicsek model in two dimensions, we assume that this model is composed of particles that are in a two-dimensional plane having periodic boundary conditions. It means that if a particle crosses one of the boundaries, it re-enters the boundary. In this model, each particle has two characteristics of location and velocity (more precisely the velocity direction). The model assumes that the velocity of all particles is equal. What changes during movement is the direction (angle) of velocity.
To arithmetically describe the interaction of equation \ref{eq:5} interactions between particles we can circle $ U_ {n} (r_ {0}, t) $ in a circle with radius $ r_ {0} $ at the center of tWichkehe particle $ n $ So the particles in this circle are called the neighbors of the particle $ n $. ($ K_ {n} (t) $ is the number of neighbors of the particle $ n $.) Then $ V_ { n} (t) $ is the average velocity of the neighbors of the particle $ n $.