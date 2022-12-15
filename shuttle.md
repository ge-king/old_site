---
layout: post
author: George King
tags: [Python]
title: Shuttle Heatshield Analysis
---

## What is it?

This is a tool that calculates the heatflow through a Space Shuttle Tile during re-entry. It's currently being translated from `MATLAB` to `python`. The process is based upon theory learned through my aerospace engineering course at Bath, particularly Modelling techniques, and Thermo and Heat transfer. 

## How does it work?

This project extracts data from an image file, and then uses four finite differencing methods (both explicit and implicit), with Neumann boundaries to calculate heat flow. These are:
- Forward differencing
- Backward differencing
- Dufort-Frankel
- Crank-Nicolson

Information on these methods can be found on [Wikipedia](https://en.wikipedia.org/wiki/Finite_difference), [2](https://en.wikipedia.org/wiki/Crank%E2%80%93Nicolson_method),
at [MIT](https://math.mit.edu/~plamen/18.336/math336.pdf), and [FSU](https://people.sc.fsu.edu/~jpeterson/5-CrankNicolson.pdf)




## To-do

Future updates will bring:
- Translation from MATLAB to Python.



