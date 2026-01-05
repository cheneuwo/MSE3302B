# Sensors

Without going into the physical principles of how these sensors work, here is a brief overview of a variety of sensors that we may encounter.

## Position Sensors

### Linear Variable Differential Transformer
<wiki:Linear_variable_differential_transformer>, or {term}`LVDT`, is is a type of electrical <wiki:Transformer> used for measuring *linear* displacement (i.e. position along a given direction). These sensors consists of three coils -- a primary and two $180^{\degree}$ out-of-phase secondaries -- would around a hallow tube. A moveable ferromagnetic core, i.e. an <wiki:Armature>, connected to the object being measured, slides along the tube. An <wiki:Alternating_current> reference voltage (the "excitation signal") is applied to the primary winding which in turn induces an <wiki:Electromagnetic_field> (EMF) signal into the two adjacent secondary windings.

```{figure} https://www.globalspec.com/ImageRepository/LearnMore/201111/io20ece3085c04b4c45aae0aec87b932172.png
:label: fig_LVDF
:alt: A depiction of a Linear Variable Differential Transformer
:align: center
:width: 80%

A depiction of a Linear Variable Differential Transformer, image courtesy [here](https://www.globalspec.com/learnmore/sensors_transducers_detectors/linear_position_sensing/lvdt_position_sensors), accessed 2026-01-01.
```

{term}`LVDT` are typically **highly accurate** and reliable.

### Hall Effect Sensors

<wiki:Hall_effect_sensor> is any sensor incorporating one or more Hall elements, each of which produces a <wiki:Voltage> *proportional* to one axial component of the [magnetic field vector **B**](https://en.wikipedia.org/wiki/Magnetic_field#The_B-field) using the <wiki:Hall_effect>.

```{figure} https://media.monolithicpower.com/wysiwyg/Articles/_SEO-0011_Fig1-_960_x_765.png
:label: fig_Hall_Effect
:alt: A depiction of the Hall Effect Phenomenon
:align: center
:width: 80%

A depiction of the Hall Effect Phenomenon, image courtesy [here](https://www.monolithicpower.com/en/learning/resources/hall-effect-sensors-a-comprehensive-guide?srsltid=AfmBOoqYrZmGbjyB5GYayduSjC0kLmYs93lJUvmCI6VErWiqxWoFPsiM), accessed 2026-01-01.
```

The <wiki:Hall_effect> is the production of a [potential difference](https://en.wikipedia.org/wiki/Voltage), across an <wiki:Electrical_conductor>, that is transverse to an <wiki:Electric_current> in the conductor and to an applied magnetic field perpendicular to the current. That is, Hall Effect sensors detect and gauge magnetic fields by generating an output voltage when exposed to a magnetic field, thereby converting magnetic information into an electrical signal that can be processed and examined.

An implementation of Hall Effect position sensors involves attaching a small permanent magnet to an object whose position is being sensed: changes in position result in changes in the magnetic field, which can be sensed by a Hall Effect sensor. These are suitable for measurement of short-range movements.

### Optical Encoders

Optical encoders convert motion into a sequence of digital pulses. These pulses can be converted to relative or absolute position measurements. For example, an optical <wiki:Rotary_encoder> uses a light shining onto a <wiki:Photodiode> through slits in a disc. Optical encoders are sensitive to dust.


```{figure} https://www.analogictips.com/wp-content/uploads/2018/02/WHTH_FAQ_Analog_rotary-encoder_Pt1_Fig1.jpg
:label: fig_Optical_Encoder
:alt: A depiction of the optical rotary encoder
:align: center
:width: 80%

The principle of the optical encoder is simple: generate an electrical pulse each time light passes through one of the many slots in a rotating code wheel, image courtesy [here](https://www.sensortips.com/featured/what-are-rotary-optical-rotary-encoders/), accessed 2026-01-01.
```

The <wiki:Gray_code>, an alternative ordering of the [binary numeral system](https://en.wikipedia.org/wiki/Binary_number) where each pair of sequential numbers differs by only one digit, is often used to encode motion increments.

## Accelerometers

An <wiki:Accelerometer> is a device that measures the <wiki:Proper_acceleration> of an object. An acceleration is experienced by an object due to motion, vibration, and impact events.

### Seismic Mass Accelerometer
A Seismic Mass Accelerometer uses a suspended sening mass within a house, which moves relative to the casing during acceleration, allowing measurement of vibration or motion. A displacement transducer senses the relative motion, and acceleration is determined through frequency response analysis.

```{figure} ./../images/fig_seismic_mass_accelerometer.png
:label: Seismic_Mass_Accelerometer
:alt: A depiction of a seismic mass accelerometer
:align: center
:width: 80%

A depiction of a seismic mass accelerometer.
```
The natural frequency of a seismic mass accelerometer is relatively low, chich limits its use to low and medium frequency applications.

### Piezoelectric Accelerometer

<wiki:Piezoelectric_accelerometer> uses a piezoelectric crystal whose deformation results in charge polarization across the crystal. It is suitable for high-frequency applications. 

```{figure} ./../images/fig_piezoelectric_accelerometer.png
:label: Piezoelectric_Accelerometer
:alt: A depiction of a piezoelectric accelerometer
:align: center
:width: 80%

A depiction of a piezoelectric accelerometer.
```

The [piezoelectric effect](https://en.wikipedia.org/wiki/Piezoelectricity), whereby certain materials generate an electric charge under mechanical stress and deform mechanically under an applied electric field, was discovered by [Pierre](https://en.wikipedia.org/wiki/Pierre_Curie) and [Jacques Curie](https://en.wikipedia.org/wiki/Jacques_Curie).

## Force and Torque Sensors

### Strain Gauges Load Cell

A Strain Gauge Load Cell ({term}`SGLC`) consists of an elastic structure that deforms when subjected to a force, and a set of strain gauges attached to it. The strain gauges change their resistance when deformed. This change can be measured using an electrical network such as a Wheatstone Bridge. {term}`SGLC`s are highly accurate and fairly inexpensive.

```{figure} https://upload.wikimedia.org/wikipedia/commons/3/3b/Strain_gauge_deformation.jpg
:label: Strain_Guage_deformation
:alt: A depiction of a piezoelectric accelerometer
:align: center
:width: 80%

The electrical resistance of the strain gauge chances when deformed, image courtesy of Wikimedia commons, accled [here](https://commons.wikimedia.org/wiki/File:Strain_gauge_deformation.jpg) on January 5, 2026.
A depiction of a piezoelectric accelerometer.
```

### Piezoelectric Force Sensor

[Piezoelectric force sensors](https://en.wikipedia.org/wiki/Piezoelectric_sensor) are based on the same principle as the piezoelectric accelerometers, i.e. deformation of a piezoelectric crystal results in charge polarization across the crystal. These force sensors are suitable for measurement of dynamic forces with relatively high frequencies. They are relatively sensitive to changes in temperature.


```{figure} https://img.directindustry.com/images_di/photo-mg/65033-19273386.webp
:label: Piezoelectric_force_sensor
:alt: A depiction of a piezoelectric force sensor
:align: center
:width: 80%

A commercial piezoelectric force sensor, image courtesy [here](https://img.directindustry.com/images_di/photo-mg/65033-19273386.webp), accessed on January 5, 2026.
```

### Force Sensing Resistor

A force-sensing resistor ({term}`FSR`) is a material whose [resistance](https://en.wikipedia.org/wiki/Electrical_resistance_and_conductance) changes when a force, pressure, or mechanical stress is applied. {term}`FSR` cannot be used for accurate measurement of forces, however, they are inexpensive, exhibit little <wiki:Hysteresis>, and not very sensitive to vibration and/or heat.

```{figure} https://a.pololu-files.com/picture/0J5343.600x480.jpg?5deeb1eef0f51fef0bc35d27731b5b1a
:label: Force_sensing_Resistor
:alt: A depiction of a force sensing resistor
:align: center
:width: 80%

A commercial force sensing resistor, image courtesy [here](https://a.pololu-files.com/picture/0J5343.600x480.jpg?5deeb1eef0f51fef0bc35d27731b5b1a), accessed on January 5, 2026.
```

## Temperature Sensors

Various temperature sensors will be examined with different transduction properties and temperature characteristics.

### Liquid in Glass Thermometre

[Liquid in glass thermometer](https://en.wikipedia.org/wiki/Thermometer#Sealed_liquid-in-glass_thermometer) is an example of a simple nonelectrical temperature-measuring device. It uses alcohol or mercury as the working fluid, which expands and contracts relative to the glass container. The reasing are performed visually.

```{figure} https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgsHyJcdZKfXfP0xlzLDqac1rZbsb41IRfLBH2my6yirwlhffP3Q3aTx917FBDsPF50stoGQFkDfI8nce68HHw3X55-oMNvoYuLxA1TfCOY4bVnM-amhTLXOZWpQYYJLwKWKe8rc8suTdo/s800/medical_thermometer_horizontal.jpg
:label: Liquid_in_Glass_Thermometer
:alt: A depiction of a liquid-in-glass thermometer
:align: center
:width: 80%

A depiction of a liquid-in-glass thermometer, image courtesy [here](http://spmphysics.onlinetuition.com.my/2013/07/liquid-in-glass-thermometer.html), accessed on January 5, 2026.
```

### Thermocouple

A <wiki:Thermocouple> consists of two *dissimilar* metal wires in contact. It produces a voltage proportional to the temperature at the junction. The physical principle behind the thermocouple is the <wiki:Seebeck_effect>.

```{figure} https://assets.omega.com/resources/how-thermocouples-work-1.jpg
:label: fig_thermocouple
:alt: A depiction of thermocouple working principle
:align: center
:width: 80%

A depiction of the working principle of thermocouples, image courtesy [here](https://www.dwyeromega.com/en-us/resources/how-thermocouples-work?srsltid=AfmBOopH0jCKnPgy6OflHR0uIlLl_WdEcIWevHMp9Bmtb0La2Uod5Jq8), accessed on January 5, 2026.
```

### Themistors

<wiki:Thermistors> is a semiconductor in which the resistance is strongly dependent on temperature. The word *thermistor* is a portmanteau of *thermal* and *resistor*. The varying resistance with temperature allow these devices to be used as temperature sensors.


```{figure} https://www.wattco.com/wp-content/uploads/2023/08/Shutterstock_2199183657-414x414.jpg
:label: fig_thermistor
:alt: A depiction of thermistor
:align: center
:width: 80%

A depiction of thermistor, image courtesy [here](https://www.wattco.com/2023/08/what-is-a-thermistor/), accessed on January 5, 2026.
```

Thermistors are categorized based on their conduction models. Negative-temperature-coefficient ({term}`NTC`) thermistors have less resistance at higher temperatures, while positive-temperature-coefficient ({term}`PTC`) thermistors have more resistance at higher temperatures.

## Photodetectors (Light Sensors)

### Photoresistors

<wiki:Photoresistor> is a device whose resistance changes in proportion to the intensity of the light striking it.


```{figure} https://upload.wikimedia.org/wikipedia/commons/b/bb/LDR_1480405_6_7_HDR_Enhancer_1.jpg
:label: fig_photoresistor
:alt: A depiction of a photoresistor
:align: center
:width: 80%

A depiction of photoresistor, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:LDR_1480405_6_7_HDR_Enhancer_1.jpg), accessed on January 5, 2026.
```

```{figure} https://upload.wikimedia.org/wikipedia/commons/6/60/Photoresistor_symbol.svg
:label: fig_photoresistor_symbol
:alt: The electronic symbol for a photoresistor
:align: center
:width: 20%

The electronic symbol for a photoresistor, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:Photoresistor_symbol.svg), accessed on January 5, 2026.
```

### Photodiode

A <wiki:Photodiode> is a semiconductor diode sensitive to photo radiation, basically converting lights into electrical current.

```{figure} https://upload.wikimedia.org/wikipedia/commons/e/e6/Fotodio.jpg
:label: fig_photodiode
:alt: A depiction of a photodiode
:align: center
:width: 80%

A depiction of photodiode, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:Fotodio.jpg), accessed on January 5, 2026.
```

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Photodiode_symbol.svg/330px-Photodiode_symbol.svg.png
:label: fig_photodiode_symbol
:alt: The electronic symbol for a photodiode
:align: center
:width: 20%

The electronic symbol for a photodiode, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:Photodiode_symbol.svg), accessed on January 5, 2026.
```
### Phototransistor

The [Phototransistor](https://en.wikipedia.org/wiki/Photodiode#Related_devices) is a bipolar transistor that is sensitive to light, encased in transparent case so that light can reach the base-collector junction. the current flow between the emitter and collector is proportional to the level of light it receives. Phototransistors are typically more sensitive to light as compared to photodiodes.


```{figure} https://upload.wikimedia.org/wikipedia/commons/c/c3/PhotoTransistor.jpg
:label: fig_phototransistor
:alt: A depiction of a phototransistor
:align: center
:width: 80%

A depiction of photodiode, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:PhotoTransistor.jpg), accessed on January 5, 2026.
```

```{figure} https://upload.wikimedia.org/wikipedia/commons/4/4a/IEEE_315-1975_%281993%29_8.6.16.svg
:label: fig_phototransistor_symbol
:alt: The electronic symbol for a phototransistor
:align: center
:width: 20%

The electronic symbol for a photodiode, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:IEEE_315-1975_(1993)_8.6.16.svg), accessed on January 5, 2026.
```

# Actuators

An <wiki:actuator> is a device that accepts a control command (typically in the form of an electrical signal), and produces a change in the physical system by generating force, motion, heat, flow, etc. In other word, actuators are essentially the *muscle* behind a mechatronic system.

## Electromechanical Actuators

[Electromechanical actuators](https://en.wikipedia.org/wiki/Actuator#Electromechanical) convert electrical energy into mechanical motion. The most common example is an **electric motor**.

### Direct Current ({term}`DC`) Electric Motors

A <wiki:DC_motor> motor operates on {term}`DC` voltage. {term}`DC` motor speed and torque can be easily controlled simply by changing the voltage. However, {term}`DC` power supply is required, and more maintenance is needed as compared to <wiki:Alternating_current> ({term}`AC`) motor.

```{figure} https://res.utmel.com/Images/Article/2239b59e-8e4e-48d1-8e3a-7987e017d3c3.png
:label: fig_DC_motor
:alt: A depiction of a DC motor
:align: center
:width: 80%

A depiction of a DC motor, image courtesy [here](https://www.utmel.com/blog/categories/motors/types-working-and-selection-of-dc-motor), accessed on January 5, 2026.
```
### Alternating Current ({term}`AC`) Electric Motors

An <wiki:AC_motor> motor uses standard {term}`AC` power, they are simpler and less expensive as compared to {term}`DC` motors. However, they are *relatively* difficult to control.


```{figure} https://res.utmel.com/Images/Article/e829b1fa-d3d2-4ec8-a7e8-7785b2170879.jpg
:label: fig_AC_motor
:alt: A depiction of a AC motor
:align: center
:width: 80%

A depiction of a AC motor, image courtesy [here](https://www.utmel.com/blog/categories/motors/introduction-to-ac-motor), accessed on January 5, 2026.
```

### Stepper Motors

A <wiki:Stepper_motor> is a discrete (incremental) positioning device that moves one step at a time for each pulse command input. They are mostly used in lower power applications

```{figure} https://upload.wikimedia.org/wikipedia/commons/c/cf/Stepper_motor.jpg
:label: fig_phototransistor_symbol
:alt: A stepper motor
:align: center
:width: 80%

A stepper motor, image courtesy of Wikimedia [here](https://commons.wikimedia.org/wiki/File:Stepper_motor.jpg), accessed on January 5, 2026.
```

## Electromagnetic Actuators