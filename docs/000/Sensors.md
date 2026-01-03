# Sensors

Without going into the physical principles of how these sensors work, here is a brief overview of a variety of sensors that we may encounter.

## Position sensors

### Linear variable differential transformer
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

### Optical encoders

Optical encoders convert motion into a sequence of digital pulses. These pulses can be converted to relative or absolute position measurements. For example, an optical <wiki:Rotary_encoder> uses a light shining onto a <wiki:Photodiode> through slits in a disc. Optical encoders are sensitive to dust.


```{figure} https://www.analogictips.com/wp-content/uploads/2018/02/WHTH_FAQ_Analog_rotary-encoder_Pt1_Fig1.jpg
:label: fig_Optical_Encoder
:alt: A depiction of the optical rotary encoder
:align: center
:width: 80%

The principle of the optical encoder is simple: generate an electrical pulse each time light passes through one of the many slots in a rotating code wheel, image courtesy [here](https://www.sensortips.com/featured/what-are-rotary-optical-rotary-encoders/), accessed 2026-01-01.
```