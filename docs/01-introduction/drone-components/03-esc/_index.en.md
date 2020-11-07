# Electronic Speed Controller (ESC)

The ESC connects the motor in a drone with the flight controller. The ESC is responsible for driving the motor in a drone, based on the power it gets from the battery and the signal that it gets from the flight controller. Since quadcopters need 4 motors and each motor needs an ESC, a single build would need 4 ESC modules. However, we also have an option where a single ESC can do the job of four ESCs - called four-in-one ESC.

**Here's a 4-in-1 ESC**:

![4-in-1 ESC](/images/4-in-1-esc.jpg)

As you can see, a 4-in-one ESC has enough connection pads to connect all 4 motors to it. This means that it manages the power distribution for each individual motor quite well.

**Here's an example of an individual ESC**:

![Individual ESC](/images/individual-esc.jpeg)

In this case, we will need four ESCs to drive the four motors of our Quadcopter (one for each).

In our builds, we usually go for a Flight Controller Stack (A pre-matched combination of a flight controller and an ESC). This decision has some advantages:

- We do not need to worry about compatibility issues between the FC and the ESC, as are already paired by the manufacturers.
- We do not need 4 separate ESCs to drive each motor.

## The Digital Shot (DShot) Protocol

An ESC communicates with the flight controller using a protocol called DShot. This protocol has many advantages over the earlier protocols (one shot and multi-shot), and has the capability to clean up signal data and prevent corrupted data from reaching the motor. For in-depth details on DShot, here's a [link](https://oscarliang.com/dshot/) to Oscar Liang's post on the same.
