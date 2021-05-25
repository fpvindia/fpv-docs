# Drone Build Guide - Part 1

## Getting it all together

This is a comprehensive drone build guide where we will go step-by-step to build a 5-inch freestyle drone. The drone will be capable of a 3-5 minute flight time with a 1300mah LiPo battery and a GoPro attached.

## The Parts

For this build we will use the following parts:

- **TBS Source One v3 Frame** - This is a sturdy frame that is tested and used by a lot of FPV pilots. Comes with 5mm thick arms and a simple yet effective design. While we have multiple options available, this one is a good starter frame with support for 20x20 and 30x30

- **TMotor Pacer v2 2207 1950KV motors** - TMotor makes some of the best brushless DC motors out there and their Pacer v2 lineup will do well for our build. Since this is a freestyle 6S build, we are going with these 1950KV motors.

- **Aikon F7 2020 v3 HD Flight Controller** - One of the best FCs out there, the AIkon F7 HD v3 comes with an F7 processor, 5 UARTs, dedicated LED pads (although we wont be using those in this build), On-board high overhead voltage regulators (50V Peak voltage) and a JST connector dedicated to the CaddX Vista or DJI Air Unit (hence the HD tag). All of this comes in a small 20x20 form factor.

- **Aikon AK32 Pro 50A 4-in-1 ESC** - With an Aikon FC chosen for this build, its only natural to go for an ESC made by Aikon. This is a powerful 50A ESC, and works well with the AIkon FC we have chosen. This is a 6S capable ESC, and comes with BLHeli_32 firmware & programmable PWM frequency up to 96KHz.

- **CaddX Vista Nebula Pro Kit** - For a freestyle drone that we intend to use in relatively close range sessions, a full sized Air Unit may not be the best idea. The Vista Nebula Pro kit comes with the Nebula Pro camera and is lighter and suits our requirements well. The Source One Frame has enough space at the back to accommodate the Vista. This back-placement works well for us as we want to mount the Vista's antenna at the back of the frame. The iFlight mini 5.8GHz Antenna (slightly better than the Cherry/CaddX stock antenna that comes with the Vista) is what we will go with for this build.

- **TBS CrossFire Nano Rx** - The famed CrossFire protocol is one of the best long-distance protocols out there today. The Nano Rx receiver paired with an immortal-T antenna will ensure that the drone will never failsafe in the short distances (1-2 Km) that we intend to fly with this drone.

!!! warning end

    **IMPORTANT**
    _If you have a DJI controller, you should be aware that the DJI Air Unit & the CaddX Vista are capable of transmitting Video AND control Signals between your controller and the drone. In other words, your drone can be controlled through the Air Unit/Vista without needing a dedicated receiver. If you have the DJI controller, you do not need a dedicated Rx for your drone like the one we are using here (the TBS CrossFire Nano Rx)_

    **This however, does not mean that you cannot use CrossFire if you want to. If you like, you can build the drone the way we will in this guide, with the CrossFire Nano Rx receiver. However, you will need a different controller (with a CrossFire Module) as the DJI version wont work with CrossFire.**

- **TBS CrossFire Nano Rx** -
