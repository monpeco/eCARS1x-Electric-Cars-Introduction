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

### Lecture Notes

**Parts of an EV: Recap**

Below, you can see a summary of the key parts of an EV with simple definitions:

Charging port or vehicle inlet: It is a connector present on the electric vehicle to allow it to be connected to an external source of electricity for charging. 

Power electronic converter: A power electronic converter is made of high power fast-acting semiconductor devices, which act as high-speed switches. Different switching states alter the input voltage and current through the use of capacitive and inductive elements. The result is an output voltage and current, which is at a different level to the input.

On-board charger: It is an AC-to-DC power electronic converter (often referred to as a rectifier) that takes the incoming AC electricity supplied via the charge port and converts it to DC power for charging the traction battery. Using the battery management system, it regulates the battery characteristics such as voltage, current, temperature, and state of charge.

Traction battery pack: It is a high voltage battery used to store energy in the electric car and provide power for use by the electric traction motor.

Battery power converter: It is a DC-to-DC power electronic converter that converts the voltage of the traction battery pack to the higher-voltage of the DC-bus used for power exchange with the traction motor.

Motor drive: It is a DC-to-AC (often referred to as inverter or the variable frequency drive) or at times a DC-to-DC power electronic converter, used to convert power from the high voltage DC bus to AC (or at times DC) power for the operation of motor. The converter is bidirectional for operating in both driving and regenerative braking mode.  

Traction electric motor/generator: It is the main propulsion device in an electric car that converts electrical energy from the traction battery to mechanical energy for rotating the wheels. It also generates electricity by extracting energy from the rotating wheels while braking, and transferring that energy back to the traction battery pack. 

Transmission: For an electric car, usually a single gear transmission with differential is used to transfer mechanical power from the traction motor to drive the wheels.

Power electronics controller: This unit controls the flow of electrical power in the different power electronic converters in the electric car.

Battery (auxiliary): In an electric drive vehicle, the auxiliary battery provides electricity to start the car before the traction battery is engaged and is also used to power the vehicle accessories.


### EV parameters: Capacity, state of charge, range, energy consumption, power, torque 

Now that we know the key parts of an EV and how it functions, it is time to learn about a few important parameters for understanding electric cars. These are the battery capacity, state of charge, range, energy consumption per kilometer, MPGe and motor power. Let us now define these terms:

1. Nominal battery capacity (Enom, in Wh or kWh): It is total electric energy that can be stored in the battery. Alternately, it is the maximum amount of electric energy that can be extracted from a fully charged battery state to the empty state. 

Generally speaking, EV batteries have a battery capacity between 5 kWh to 100 kWh depending on the type of EV. The higher the battery capacity, the more energy it can store and the longer the time it takes to fully charge it. The battery capacity is often referred to as the energy content or energy capacity of the battery. 

2. State of charge, SOC (BSOC, in %): The battery state of charge (SoC) is defined as the ratio between the amount of energy currently stored in the battery, Ebatt and the total battery capacity, Enom 

    BSOC=(Ebatt/Enom) 100

3. Range (Rmax, in km): It is the maximum distance that can be driven by an electric car when the battery is full. Usually an electric car is tested using a standardized driving cycle to estimate the range, e.g. New European Driving Cycle (NEDC), Worldwide harmonized Light vehicles Test Procedure (WLTP) or the EPA Federal Test Procedure. The range can be expressed in miles, kilometer or other units based on the region. In this set of definitions, we stick to the European convention of using kilometer.
4. Available Range (R, in km): It is the maximum distance that can be driven by an electric car based on the current state of charge of the battery. 
5. Energy consumption per kilometer (D, in kWh/km): When an electric car is tested using a standardised driving cycle, the EV efficiency is the energy consumed from the batteries per unit distance drive. In some cases, the energy drawn from the grid to charge the battery is considered as well. It can be expressed in kilowatt-hour per kilometer (or) kilowatt-hour per mile. 
6. MPGe or miles per gallon equivalent: MPGe is the distance in miles traveled per unit of electric energy consumed by the vehicle. The ratings are based on United States Environmental Protection Agency (EPA) formula, in which 33.7 kilowatt-hours (121 megajoules) of electricity is equivalent to one gallon of gasoline.
7. Motor power (Pm, in W): It is the power delivered by the motor to the wheels for propulsion. The motor power is positive or negative based on whether the car is driving or under regenerative braking. The motor power can be expressed as a product of the motor torque, Tm and the motor rotational speed, wm and the units normally used are watts (W), kilowatts (kW) or horsepower(hp). The rotational speed is normally expressed in radians per second (rad/s) or rotations per minute (rpm). The torque is normally expressed in newton-meter (Nm).

    Pm = Tm * wm

where
Pm is motor power (W)
Tm  is motor torque (Nm)
wm is rotation speed (rad/s)


Ideally, an electric car must have a high range, low energy consumption per kilometer and a high MPGe. The following formula can be used to connect the above parameters 

    R = Ebatt/D = (BSOC /100)*Enom /D

where
R is available range of EV (km)
Ebatt is current battery capacity (kWh)
D is the Energy consumption per kilometer (kWh/km)
BSOC is battery state of charge, SOC (%)
Enom is nominal battery capacity (kWh)

**Note on EV range:**

It must be noted that the range of an electric car is dependent on various parameters of which four are important. First and foremost is the energy consumed by the car. When a car travels at a higher speed, generally more energy is consumed due to friction and air resistance. Hence, less driving range is possible.

The second parameter is the efficiency of the battery which depends on several parameters including the ambient temperature, discharging current and the aging of the battery.

Third is the driving style. For example, city driving is very different from highway driving. That is why the EPA provides separate fuel economy estimates for MPGe for city, highway and combined. The final parameter is the energy consumed by on-board accessories like the air conditioning system, battery cooling systems etc.   

For example, go to https://www.tesla.com/en_EU/models and to the section ‘Range per charge’. You can see how the range of the car is influenced by the weather, speed, AC system and wheel size. While the results of the tool cannot be generalized for all cars, it gives a good indication of the behavior. 


---

#### 2. Introduction to Technology of EVs   2.1 Operation of an Electric Car and Key Parts   Quiz

---

#### 2. Introduction to Technology of EVs   2.1 Operation of an Electric Car and Key Parts   Learning Material

How does an electric car work? 
In the next video, we will take a deeper look into an functioning of an electric car by using an animation. We thank the YouTube channel ‘Learn Engineering’ for allowing the use of this video for the MOOC. 

[How does an EV work?](https://youtu.be/3SAxXUIre28)

**Simplicity**
Did you notice that the powertrain of an electric car is not all that different fundamentally from the Do It Yourself Electric Toy car video we sent you a few weeks back by email ? The basic building blocks are the battery and the motor driving the wheels. On this, we would be required to include the power electronics, control, on-board charger, doors, air conditioning, brakes, audio system, etc., etc, :P


**The electric motor vs the internal combustion engine**


The main benefit of the electric motor when compared to the internal combustion engine is its ability to provide peak torque at the nearly all speeds, even at zero speed. This is achieved by a clever motor and motor drive design. This results in an electric car that accelerate super fast and does not require multiple gears for its operation. It is for this reason that the Tesla Model S P100D (Ludicrous mode) became the third fastest accelerating production car ever produced, with a 0-60 mph time of 2.5 seconds. Keep in mind that the LaFerrari and the Porsche 918 Spyder that are quicker than the Model S are small, two-seater, million dollar cars, while in comparison, the Model S is a four-door, family car with storage capacity and much lower cost. This goes to show the huge performance benefit of electric cars over internal combustion engine cars. 


---

#### 2. Introduction to Technology of EVs   2.1 Operation of an Electric Car and Key Parts   Quiz

---

#### 2. Introduction to Technology of EVs   2.2 Types of Electric Vehicles   Lecture 2: Types of EV

Types os vehicles: Drive-train and Fuel
* Conventional ICE Vehicle
* Alternative fuel ICE Vehicle
* Electric Vehicle

Conventional ICE Vehicle
* Gasoline
* Diesel

#### Alternative fuel ICE Vehicle
* Autogas (liquefied petroleum gas, LPG)
* Natural Gas (Compressed natual gas - CNG, Liquefied natural gas - LNG)
* Biofuel (Bioalcohol, Biodiesel, Biogas)
* Hydrogen

In all forms of ICE vehicles, the drive train is mechanical.
In contrast, electric vehicles use an electric drivetrain for their propulsion.

### Types of Electric Vehicle
* Hybrid Electric vehicle (HEV), 
* Plug-in hybrid electric vehicles (PHEV),
* Battery electric vehicle (BEV), 
* Fuel cell Electric vehicle (FCEV),
* and in the future solar EV.

### Hydridization rate (HR)
The hybridization rate, is a measure used to describe how strongly the powertrain is hybridized.
This level is determined by the role that the electric motor has in the performance of the car.
It is defined as the ratio of electric power to total power and is described by this equation
where P-em is the power provided by the electric machine and P-ice is the power provided by
the internal combustion engine.

When the hybridization rate value is smaller than 0.24, this HEV is considered to be a micro hybrid.
When the hybridization rate is between 0.24-0.38, it is then distinguished as a semi or mild hybrid.
When the hybridization rate is higher than 0.38, we can then consider it as a full hybrid.


---

#### 2. Introduction to Technology of EVs   2.2 Types of Electric Vehicles   Lecture Notes
