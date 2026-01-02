# Introduction

The term **mechatronics** is used to denote a rapidly developing, interdisciplinary field of engineering dealing with the design of products whose function relies on the *integration* of **mechanical** and **electronic** components coordinated by a **control architecture** {cite}`AH2012`. Within the context of this course, titled **Sensors and Actuators**, the mechanical components are typically represented by some form of actuators, the electronic components by the sensors, and the control components by software that governs both sensors and actuators."

[](#MSE_components), courtesy of {cite}`AH2012`, illustrates all the components in a typical mechatronic system. This course focuses on the top-left box of [](#MSE_components), where the actuators produce motion or cause some action, the sensors detect the state of the system parameters, inputs, and outputs, and the basics of signal processing and control theory are used to model the behaviour of the mechanical system.

```{figure} ./../images/fig_MSE_components.png
:label: MSE_components
:alt: Components of mechatronic systems
:align: center
:width: 80%

Mechatronic system components. Image courtesy of {cite}`AH2012`.
```
:::{tip} Example
A 3D printer is a good example of a contemporary mechatronic system. The **actuators** in a typical fused deposition modelling (FDM) 3D printer include stepper motors that drive the X-, Y-, and Z-axes for precise three-dimensional positioning, an extruder motor that controls filament feed rate, and resistive heating elements that maintain the hotend and heated bed at predefined temperatures. The **sensors** provide critical feedback to the control system: thermistors monitor temperatures at the hotend and bed, limit switches establish reference positions during homing sequences, and filament runout detectors alert the system to material depletion. Coordinating these components is the control architecture that interprets <wiki:G-code> instructions, implements  <wiki:Proportional-integral-derivative_controller> control algorithms for temperature regulation, performs real-time motion planning with acceleration profiles, and coordinates the timing of all actuators based on sensor feedback to produce accurate, layer-by-layer, fabrication of complex geometries.
:::