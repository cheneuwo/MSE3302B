# Terminology

## Transducer
A <wiki:Transducer> is a device that usefully converts energy from one form to another. Alternatively, a transducer converts a *signal* in one form of energy into a signal in another. The process of converting one form of energy to another is known as *transduction*.

### Types
- **Mechanical transducers** convert physical quantities into mechanical outputs or vice versa
- **Electrical transducers** convert physical quantities into electrical outputs or signals

:::{tip} Example
A classic example of a mechanical transducer is a <wiki:Windmill>, which converts the kinetic energy of moving air into rotational mechanical energy of its blades and shaft, demonstrating pure mechanical-to-mechanical energy transduction.
:::

:::{tip} Example
A classic example of an electrical transducer is a <wiki:Thermocouple>, which changes a temperature difference into a small voltage.
:::

Transducers can be categorised by the *direction* in which information passes through them:

- A <wiki:Sensor> is a transducer that *receives* and *responds* to a signal or stimulus from a physical system. It produces a signal that represents information about the system for use by the control system.
- An <wiki:Actuator> is a transducer that is responsible for causing changes in the physical environment of the system. It is controlled by a signal from the control system. It is operated by a source of energy, which can be mechanical force, electrical current, hydraulic fluid pressure, or pneumatic pressure, and *converts* that energy into motion. An actuator is the mechanism by which a control system acts upon an environment.

This flow of information is cyclic, forming a closed-loop, feed-back, relationship between sensors and actuators of a mechatronic system. Thus, a mechatronic system is capable of adapting to its surroundings based on the sensor readings and the controlled actions.

```{figure} ./../images/fig_MSE_components_relationship.png
:label: MSE_components_relationships
:alt: Relationships between Components of mechatronic systems
:align: center
:width: 80%

The closed-loop relationship of actuator and sensors in a mechatronic system.
```