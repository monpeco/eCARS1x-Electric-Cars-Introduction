#### 2. Introduction to Technology of EVs   2.0 Introduction   Introduction

### Introduction

In the previous module, we saw what an electric vehicle is and what its advantages are. We also looked into the role of EVs in the energy transition and the key role played by business and policy in the uptake of EVs. In this week, we will dive deep into the technology of EVs.  

Several questions are addressed in this module. You might have quite often heard about electric vehicles or hybrid electric vehicles or even about plug-in hybrid electric vehicles. What is the difference between them? What is inside an electric car and how does it work? What is the vital role played by power electronics and the battery in the electric car? How do you charge an electric car and what is the difference between AC and DC charging?

In this module, we attempt to answer the above questions. The main topics covered during this module are :

* Main parts of an EV;
* Working principles of an EV;
* Types of EV – hybrid, plug-in hybrid, battery and fuel cell;
* Comparison of EV based on emissions, range, fuel type;
* Basics of EV charging - range, power, voltage, charging time, energy;
* EV charging  - plug types, power levels, charging modes;
* Basics of smart charging.

A glossary of the key technical terms used in this module can be found [here](https://prod-edxapp.edx-cdn.org/assets/courseware/v1/3f27133c9ab6770220b5c8ae75f6834e/asset-v1:DelftX+eCARS1x+1T2018a+type@asset+block/EV_Glossary_of_Terms_eCARS1X.pdf).
 
---

#### 2. Introduction to Technology of EVs   2.0 Introduction   Mr. Smith Animation

[Mr. Smith Animation](https://youtu.be/QbsAjiVjL1Q)

---

#### 2. Introduction to Technology of EVs   2.1 Operation of an Electric Car and Key Parts   Lecture 1: What's Inside an Electric Car?



In this first lecture by Professor Pavol Bauer, we will look at the parts of an all 
electric car and how it works. We will delve into the three key components of the EV,
namely: the battery, the electric motor and the power electronic converters. Finally, 
we will investigate how power flows within the car and how power electronics plays a 
key role in this


### What's inside an electric car?

In this figure, you can see key parts of an electric car.
First, we have a charging port with the connector and cable.
We have the high voltage traction battery and the low voltage auxiliary battery.
We have an electric motor and a transmission system which are used for propulsion.
And finally, there are several power electronic converters that are used for battery charging,
for driving the motors and for regenerative braking.



### key parts of an electric car 

In this figure, you can see key parts of an electric car.
First, we have a charging port with the connector and cable.
We have the high voltage traction battery and the low voltage auxiliary battery.
We have an electric motor and a transmission system which are used for propulsion.
And finally, there are several power electronic converters that are used for battery charging,
for driving the motors and for regenerative braking.

![image](https://user-images.githubusercontent.com/16638078/41206290-b2313d36-6ccf-11e8-8e6c-11dd293068eb.png)

The schematic shows how the different components are connected to each other in the electric car.
To explain what is inside an electric vehicle, let us follow the power flow direction
and take a look at an electric car to identify the key components.

![image](https://user-images.githubusercontent.com/16638078/41206311-f2aba1f8-6ccf-11e8-9746-82ef2c4d929d.png)

The first part we look at is the **charging port** with charging connector and cable.
The charging port together with the connector and cable allows the electric car to connect
to an external power supply in order to charge the traction battery pack.
The charging port is often referred to as the vehicle inlet.


If the car is charged with power from the conventional electricity grid,
it requires an **onboard charger** which is a power electronic converter.
A power converter is made of high power semi-conductor devices,
which act as high-speed switches.
Different switching states alter the input voltage and current
through the use of capacitive and inductive elements.
The result is an output voltage and current, which has a different magnitude and waveform
compared to the input.

The onboard charger converts the incoming alternating current or AC power supplied
via the charge port to direct current or DC power for charging the traction battery.
The on-board charger is like a phone charger but can handle much higher voltages and powers.

Next is **high-voltage traction battery**, which is the heart of any electric vehicle.
Generally, the battery is located at the bottom of the car, but this can vary depending on the manufacturer.
The role of the battery is to store energy for the propulsion of the vehicle.
The battery has a battery management system that monitors and regulates
the battery charging characteristics such as voltage, current, temperature, and state of charge.

The energy content of a battery is normally expressed in kilo-watt hours.
Nowadays, electric cars have battery sizes in the range of 10-100 kWh.

Let us now look at the battery technologies that have been applied to electric cars.
1. First is the **lead-acid battery**. The prospects for the use of lead acid batteries in EV’s are limited, due to low energy densities, sensitivity to temperature and life cycle.
2. Next is **Nickel-metal hydride** (NiMH) batteries. They have been extensively for traction purposes and are optimized for high energy content.
3. Finally and the most popular are **Lithium based batteries**. Lithium batteries are classified by the type of active material into Lithium-ion liquid electrolyte and Li-ion-polymer electrolyte batteries.

The Lithium-ion batteries is generally preferred for EV applications,
mainly driven by its high energy density.

When we drive the electric car, the power flows from the battery to the motor
and to the vehicle accessories like light and audio system.
To regulate the power between these devices, it is necessary to use a power electronic converter.
In an electric car, a DC to DC converter steps up the DC voltage of the traction battery pack
to a higher DC voltage needed to run the motor.
A secondary DC to DC converter, not shown in the diagram,
is used to step down the voltage of the traction battery pack
to charge the lower voltage auxiliary battery

The **motor drive** controls the speed, torque and rotational direction of the motor.
Depending on the motor, the motor drive is a DC to AC inverter or a DC-DC converter
that is used to control the power flow between the battery and the motor.

Unlike the power converters, we have seen earlier,
the motor drive is a bidirectional converter capable of delivering power to the motor for propulsion
but to remove out of the motor for regenerative braking.

We will now look at the electric motor,
which together with the batteries are the two vital parts of an electric vehicle.
The electric motor is responsible for converting electric energy to mechanical energy
for driving the wheels via the transmission.

Normally, a single gear transmission with differential is used as opposed to variable gears
found in combustion engine vehicles.
That is why electric cars are ‘automatic’ gear cars by default.
This is due to the unique nature of electric motor to deliver close to full torque at all speeds.
Further, the same electric motor can be used both as a motor
and as a generator during driving and regenerative braking, respectively.

Four types of electric machine have been used in both PHEV’s and BEV’s to date,
namely Brushed DC motor, Induction motor, Permanent magnet motor and Switched reluctance motor.
It can generally be concluded that induction motors and permanent magnet motors are the most popular
when considering various parameters such as control, efficiency, power density, reliability, and cost.

Finally, the last two key parts of an electric car
are the auxiliary battery and power electronic controller.
The auxiliary battery provides electricity to start the car before the traction battery is engaged
and also powers the vehicle accessories.

The auxiliary battery is usually 12V for current vehicles but may be increased to 48V for future vehicles.
On the other hand, the power electronic controller directly controls the different power converters
and hence indirectly the operation of the battery, motors and the vehicle.


### Electric car: Power flow

Now that we know the different parts of the EV,
then, let’s look at how does an EV work based on the electrical power flow.


![image](https://user-images.githubusercontent.com/16638078/41206429-e804e69a-6cd1-11e8-8882-72049e577768.png)



--- 

#### 2. Introduction to Technology of EVs   2.1 Operation of an Electric Car and Key Parts   Lecture Notes



