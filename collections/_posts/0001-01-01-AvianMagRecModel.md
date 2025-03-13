---
layout: article
aside:
  toc: true
cover: assets/images/project_covers_and_photos/SunSim_Images/sunsim_cover_3.png
title: SunSim Technologies
show_title: false
header: false
show_date: false
---
<style>
  .right-aligned-image {
    float: right; /* Aligns the image to the right */
    margin: 0 0 20px 20px; /* Adds space around the image */
  }
</style


# Avian magneto-receptive home-point navigation: A 2-Dimensional representation and analysis

*A neural network project modelling avian magnetoreception systems.*

## Abstract

This paper examines avian magnetoreception sensory mechanisms and their implications for navigational behaviors focusing on migratory birds' ability to navigate back to a "home point" using geomagnetic cues. We integrate biophysical models of magnetoreception into a neural network designed to simulate avian navigation by downscaling the task onto a 2-dimensional plane. Two primary receptors are explored: the "compass" receptor in the retina, which operates via a radical pair mechanism sensitive to specific light and magnetic field conditions, as well as the magnetite-based receptor in the upper beak, functioning as a magnetometer to provide magnetic field strength cues. The neural network created here employs these inputs to determine the return heading from a randomly generated location on the plane towards a predesignated home point. Methods include the generation of a synthetic 2-dimensional magnetic field, a winner-take-all synapse action model demonstrating efficacy of reorientational behaviour in the presense of adequate light, and finally a trained neural network model that functions to provide the 'direct to home' heading from the simulated avian sensory inputs. Results indicate that the model can effectively learn and mimic a simple navigation strategy, pointing to significant potential for further research into more biologically accurate neural models and their applications in understanding complex navigational systems in birds.

See the full paper [here](https://github.com/JRomeroRepositories/avian_magrec_nn/blob/main/Simulated%20Avian%20Magnetoreception%20Network%20Paper%20.pdf) and the relevant modelling notebook [here](https://github.com/JRomeroRepositories/avian_magrec_nn/blob/main/avian_magrec_nn.ipynb).
