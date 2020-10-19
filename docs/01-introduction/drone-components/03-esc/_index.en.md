# Electronic Speed Controller (ESC)

The ESC connects the motor in a drone with the flight controller. The ESC is responsible for driving the motor in a drone, based on the power it gets from the battery and the signal that it gets from the flight controller. Since quadcopters need 4 motors and each motor needs an ESC, a single build would need 4 ESC modules. However, we also have an option where a single ESC can do the job of four ESCs - called four-in-one ESC.

## The Digital Shot (DShot) Protocol

An ESC communicates with the flight controller using a protocol called DShot. This protocol has many advantages over the earlier protocols (one shot and multi-shot), and has the capability to clean up signal data and prevent corrupted data from reaching the motor. For in-depth details on DShot, here's a [link](https://oscarliang.com/dshot/) to Oscar Liang's post on the same.

##
