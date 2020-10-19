# FPV Drone Components

There are several components that make up a drone and it's control system. Let's go through each of these and learn more
about what they do, in brief

## List of all parts

- Frame
- Power Distribution Board (PDB)
- Flight Controller
- Electronic Speed Controller (ESC)
- Motors
- Propellers
- Battery & Pigtail
- Camera (FPV Camera)
- Video Transmitter (VTX)
- FPV Goggles
- Radio Receiver (RX)
- Radio Transmitter (TX)
- Antenna

## Frames

The frame is the main body of the drone. It houses all the components that make up the drone. Quadcopters usually have frames that are made of Carbon Fiber (smaller ones have plastic frames). These come in two main categories: lightweight compact frames designed for drone racing, and freestyle frames, which are usually slightly larger than racing frames, more durable and slightly heavier too.

### Choosing the right frame for your FPV drone

There are a lot of things that we need to consider when selecting a frame for the drones. Let's discuss the main ones:

- **Propeller Size** - Depending on the length of the arms of the frame, specific propeller sizes will be needed. Most common are 5" and 3" propellers, and drone frames usually support them well.

- **Usable Internal Space** - When selecting a frame, we need to consider the space available inside the frame for mounting the components. Does the frame have the right mounting-holes? Does it come with the right amount of space for all the components we will be putting into it (FC, ESC, Camera, battery, radio, antenna, etc)

- **Aerodynamics** - How well does the drone slice through the air? Bulky drones tend to meet with higher air resistance and will need more power to fly through the air. A thin nimble frame will cut through much easier and with lesser effort.

- **Strength** - A strong frame will survive many crashes before it breaks apart. A lightweight frame, on the other hand would break apart a bit more easily as they dont have the strength to withstand heavy crashes or drops. However, this can be a double-edged sword - a stronger drone would be heavier, and would need more power to fly. So a balance would need to be struck between strength and weight. Frames with 4mm thick plates are pretty durable and strong (but slightly heavier too). Also, 3mm thick frames are also available but will not be quite as strong.

- **Additional Features** - Some well designed frames come with some extra features. For example, some come with overarching support rungs that protect the camera in case of a head-on collision. Others come with capabilities to mount additional cameras like GoPros. Yet others come with power distribution boards that allow you to properly distribute power from the ESC to the motors.

**_We recommend beginners to go with freestyle 4mm thick 5" frames instead of thinner racing-style frames, for obvious reasons_**

## Power Distribution Board (PDB)

Power Distribution Boards (or PDBs) are circuit boards that help pass power from the drone battery to the various components of the drone. While these were very popular in recent times, many modern Flight Controllers (FC) come with a PDB inbuilt into the circuit, making a separate PDB unnecessary.

**_In our build, we use a Flight Controller that already has an integrated PDB, and this component is not required._**

## Flight Controller (FC)

This is arguably one of the most critical parts of the drone. This is a piece of hardware that forms the heart of the drone. The FC is basically a mini computer that manages the way your drone flies. The flight controller usually has some firmware installed on it that allows it to make calculations and decisions by collecting telemetry and data from other parts of the drone and from sensors such as a gyro, GPS, accelerometers and more. The Flight Controller also connects to a radio receiver chip (RX) and accepts control input from the pilot who is flying the drone. It uses these radio signals from the RX to determine the way the pilot wants the drone to move, and makes it fly that way.

The processing power of a flight controller determines the capabilities of the drone. An F4 is a common processor class that is a standard we see in many Flight Controllers today (example, the Mamba F405 comes with an F4 processor). F7 and H7 processor classes are more powerful and rapidly becoming the norm (example, Mamba F722 comes with a F7 processor).

### Categories of Flight Controllers

The Flight Controllers come in various categories and are used for specific applications:

- Made for multi-rotors
- Made for fixed-wing RC Planes &
- Multipurpose FCs (Used for both winged RC planes as well as multi-rotors)

### All In One Flight Controllers

Modern flight controllers typically come with many essential capabilities which would otherwise be separate components which we would need to connect together with cables. Known as All-in-One (AIO) Flight controllers, these come with PDB inbuilt (as explained before) and are capable of connecting with multiple different sensors and components.

### UARTS

UARTS are basically universal ports that allow the Flight Controllers to control or work with more components or sensors. For instance, a UART can be used to connect and control a camera. A UART can also be used to connect a GPS chip or other sensors that can enhance the capabilities of the drone.

## Electronic Speed Controller (ESC)

## Motors

## Propellers

## Battery & Pigtail

## Camera (FPV Camera)

## Video Transmitter (VTX)

## FPV Goggles

FPV Goggles are an integral part of the FPV drone racing setup. The drone pilot needs to use one of these goggles in order to successfully connect to the visual feed provided by a drone's video transmitter (VTX). Through these googles, the user would see what the drone's camera sees during flight, making FPV drone flying an immersive and addictive experience like never before.

## Radio Receiver (RX)

## Radio Transmitter (TX)

The radio transmitter is one of the main components of FPV Drone flying. This is the device we use to communicate with the drones. It transmits our inputs into radio signals that are picked up by the radio receivers that are present in the drones. These radio signals are then fed to the flight controller, which determines what the input was and how to follow this input order. These transmitters and receivers work in the 2.4GHz frequency range (considerable range) or 900MHz (very high range) and
come in many sizes and form factors.

## Antenna
