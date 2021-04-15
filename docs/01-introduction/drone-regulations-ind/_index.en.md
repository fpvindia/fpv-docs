# Drone Regulations in India

Before we get into the basics of Drone Building, we need to understand what the Indian government thinks about it.
Let's take a look at the hobby drone-flying scene in India:

## What you should know

The following rules apply irrespective of the category of the drone.

1. If you own a drone (defined as an RPAS or Remotely Piloted Aircraft System on the site), you need to register it with the Government of India. This is a mandatory requirement, and is not optional. This applies to custom-made drones and to commercial drones as well.

2. Drone regulations differ based on the total weight of your drone. Each drone category comes with it's own set of rules and regulations that we need to abide by (Scroll down to see a list of drone categories and their weight classifications).

3. Registration can be done by logging-on to the [DGCA Digital Sky WebSite](https://digitalsky.dgca.gov.in).

4. If you are planning to build a drone, or have a drone that you have built yourself, it still needs to be registered. Theres a section below that covers this scenario.

5. At the moment, the drone regulations in India are being formulated. While some of the regulations are already in place, there are still loopholes and scenarios that have not been covered in detail. For instance, custom-built drones like the ones we build in this document do not comply with NPNT and DGCA recognizes them as non-NPNT drones. Pilots cannot request for a UIN for these drones at the moment. The best course of action in this scenario is to stay as compliant as logically possible. Scroll down for more details on this specific scenario.

## Drone Categories

The following are the different categories recognized by the DGCA as of this time of writing:

| Category | Weight Classification                                  |
| :------: | :----------------------------------------------------- |
|   Nano   | Less than or equal to 250 grams.                       |
|  Micro   | Greater than 250 grams and less than or equal to 2 kg. |
|  Small   | Greater than 2 kg and less than or equal to 25 kg.     |
|  Medium  | Greater than 25 kg and less than or equal to 150 kg.   |
|  Large   | Greater than 150 kg.                                   |

## Primary Regulations

Here are the main rules that you need to be aware of:

1. Drone pilots need to register their drones before they attempt to fly them.
2. Drones must not be flown higher than 200ft vertically off the ground.
3. Drone pilots must always maintain line-of-sight with their drones when flying them.
4. Drones cannot be flown in no-fly zones or controlled airspace (mostly places of national importance, military locations, airports, LoCs and so on).
5. Drones should not be used to violate the privacy of others or to harm others in any way.

Refer to this image for clarity (Taken from [DGCA home Page](https://digitalsky.dgca.gov.in/home)):
![DGCA Directive for nano and micro drones](../../images/DGCA-micro-nano.png)

### In short, Regular Micro drones require UIN and the pilots need to adhere to the do's-and-dont's of flying RPAs. Nano pilots do not even need a UIN to fly.

## Nano drones

These are drones with All Up Weight (AUW) of 250 grams or less. AUW includes any payload that the drone may be carrying.
At the time of writing, Nano drones do not have any restrictive rules governing its use in India. These drones do not
need to be registered. Note that a nano drone will be bumped up to the micro category if it's speed exceeds 15 meters
per second or if it can fly farther than 100m from the pilot. The drone will also be bumped up to Micro category if it
can fly higher than 15 feet off the ground level.

Since we are primarily focused on Micro drones, this document focuses on that category alone.

## Micro Drones

### UIN Number

To fly micro drones, you need to register the drone as mentioned above, and you need to obtain a UIN (Unique
Identification Number) for the drone. This UIN number needs to be clearly indicated on the body of the drone.

### NPNT

This drone needs to comply with NPNT rule. NPNT stand for No Permission No TakeOff, which is a system that allows a
drone to fly only if the drone pilot has been granted permission for a flight. This is a complicated requirement that
requires your drone to have a GPS GLONASS chip and a SIM, allowing the drone be tracked and monitored. This particular
regulation is pretty hard to achieve for us, and we will be attempting this compliance only after large-scale adoption
and support for this requirement in the drone building world.

### RTH System & GeoFencing Capabilities

Drones in the Micro category need to be equipped with the automated capability to return back to the pilot if they enter
restricted airspace (also known as Controlled Airspace) or places that they are not supposed to be flown into. This too
is a complicated requirement for us to achieve and we will be attempting this compliance only after large-scale adoption
and support for this requirement in the drone building world.

### Flight Records and Logbooks

Drone pilots are required to maintain clear and concise records of their flight sessions, including information about
flight locations, flight time, and other flight metrics. This is a manual requirement that each pilot needs to adhere to
and is not in scope for our document.

## What about a drone that you build yourself

We intend to build our own drones instead of buying RTF (ready-to-fly) drones. In our case, our drone build is going to
be in the micro category. The DGCA Digital Sky platform recognizes us as a drone manufacturer, and we need to register
by operating under this assumption. Since we build our own drones, we will provide our own serial numbers for each
drone we register. Thankfully, this is allowed and perfectly legal to do so.

### Custom-made Micro Drones & the Regulations that currently govern them

Drones that fall under the micro category need to be enlisted in the drone enlistment site, and as mentioned above, need
to have a UIN. However, custom-built micro drones do not have the ability today to be NPNT compliant. As on 15th of April
2021, pilots cannot apply for a UIN for these drones. This is a temporary state-of-affairs that we expect to change soon.

However, what can be done about this situation? When asked, the DGCA response has been as under:

!!! note ""

    **Please be informed that as your drone is self-made drone it comes under non-NPNT drone, so enlistment is the only
    process for non-NPNT drone. We would request you to do the enlistment. Then you will get an OAN (Owner Acknowledgement
    Number) and DAN(Drone Acknowledgement Number). And for the next process wait for further announcement from DGCA.**

=== "Nano Drones"

    - You do **NOT** need a UAOP License
    - You do **NOT** need a UIN number for your drone
    - You **DO** need to enlist your drone

=== "Micro Drones"

    - You do **NOT** need a UAOP-1 License in uncontrolled airspace below 200ft AGL
    - You **DO** need a UIN number for your drone
    - You **DO** need to enlist your drone

## UK's Drone-code

Other countries have their own rules and regulations. Here's a simple way UK's government advocates safety and rules:

- **D**on't fly near airports or airfields
- **R**emember to stay below 400 feet and at least 150 feet away from buildings and people
- **O**bserve your drone at all times
- **N**ever fly near aircraft
- **E**njoy responsibly
