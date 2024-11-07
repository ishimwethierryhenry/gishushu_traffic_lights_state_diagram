SOFTWARE MODELLING AND DESIGN ASSIGNMENT ON GISHUSHU TRAFFIC LIGHT STATE DIAGRAM
.................................................................................

NAMES:ISHIMWE Thierry Henry
ID:25319
GROUP:E
                                             
                                             
                                             GISHUSHU TRAFFIC LIGHTS STATES DIAGRAM SPECIFICATIONS
                                             =====================================================

                                             
Gishushu is a neighborhood located in Kigali, Rwanda. It is known for its quiet residential areas, businesses, and amenities.The traffic lights in Gishushu appear to be standard three-color traffic lights (red, yellow, and green).

State Diagram and Specification of Gishushu Traffic Lights[Is attached in the screenshot section]

Specification (Narration):

The Gishushu traffic lights operate in a cyclical manner, transitioning between three states: Red, Yellow, and Green.

=>Red Light State:

Function: Signals vehicles to stop.
Transition: After a set period, the system moves to the Yellow state, allowing vehicles to prepare to move.

The traffic light displays a red light, indicating that vehicles must stop.
After a predetermined duration, the light transitions to the Yellow Light state.


=>Yellow Light State:

Function: Indicates to drivers to slow down, preparing for a transition to the next state.
Transition: After a short duration, it can either:
Move to the Green Light state (for vehicles to proceed).
Or move back to the Red Light state if pedestrian crossing is detected or no vehicle traffic is present.

The traffic light displays a yellow light, indicating that vehicles should prepare to stop or proceed with caution.
The light can either transition to the Green Light state after a brief period, or it can return to the Red Light state if no vehicles are crossing.


=>Green Light State:

Function: Allows vehicles to proceed through the intersection.
Transition: After a set duration, it changes back to the Yellow state, warning vehicles to prepare to stop as it transitions to Red.
Pedestrian Crossing Signal

Function: Intervenes in the cycle based on pedestrian requests to cross.
Operation: Activates “WALK” and “DON’T WALK” indicators and modifies the vehicle traffic light cycle as needed.
Vehicle Sensors

Function: Monitors the presence of vehicles at the intersection.
Operation: Adjusts the traffic light timing based on detected traffic volume, allowing for a more adaptive system.

The traffic light displays a green light, indicating that vehicles may proceed through the intersection.
After a specific duration, the light transitions back to the Yellow Light state, preparing for the next cycle.
Additional Considerations:

Pedestrian Signals: The traffic lights in Gishushu may also include pedestrian signals with "WALK" and "DON'T WALK" indications to regulate pedestrian crossings.
Vehicle Sensors: The traffic lights may be equipped with sensors to detect the presence of vehicles, allowing for adaptive timing adjustments to optimize traffic flow.
Traffic Light Controller: A central traffic light controller manages the timing and sequencing of the traffic lights, ensuring smooth and safe traffic movement.

                     
Specification (Narration) for Gishushu Traffic Lights
The Gishushu traffic light system operates with a cyclic transition between Red, Yellow, and Green states, with added support for pedestrian crossings and vehicle sensors. The system functions as follows:

Red Light State:

The traffic light turns red, indicating that all vehicles must come to a complete stop.
Pedestrians may be allowed to cross during this time if they request a "WALK" signal.
After a specific duration, the system transitions to the Yellow Light state, indicating to vehicles that they will soon be able to move.
Yellow Light State:

The traffic light shows yellow, instructing vehicles to prepare to stop or proceed cautiously.
The yellow light remains active briefly, and based on conditions, it can transition to:
Green Light State: if traffic flow needs to resume.
Red Light State: if there is a pedestrian crossing request or if no vehicles are detected.
If no other triggers occur, the system typically transitions from Yellow to Green.
Green Light State:

The traffic light displays green, allowing vehicles to proceed through the intersection.
Pedestrian crossings are not permitted during the Green Light state.
After a predetermined duration, the system transitions to the Yellow Light State, signaling vehicles to prepare to stop.
Pedestrian Crossing Signal:

Pedestrian requests trigger a crossing signal, which changes the vehicle lights to red, giving pedestrians safe passage.
The pedestrian signal alternates between "WALK" and "DON'T WALK" indications to guide pedestrians safely.
Once the pedestrian has crossed, the light resumes the normal vehicle traffic cycle.
Vehicle Sensors:

Vehicle sensors detect the presence and volume of vehicles waiting at the intersection.
If traffic is particularly heavy, the green light duration may extend to allow more vehicles to pass, optimizing traffic flow.
If there are no vehicles detected, the system can skip the Green state or shorten its duration, saving time and prioritizing other directions or pedestrian crossings.
Traffic Light Controller:

A central controller manages the entire operation, ensuring that traffic flows smoothly and safely. This controller processes inputs from vehicle sensors and pedestrian requests and makes real-time adjustments to the traffic lights.
This model describes a basic but adaptive traffic light system, designed to manage the flow of vehicles and pedestrians at Gishushu efficiently. The system provides a clear flow between states, ensuring safety and minimizing congestion based on real-time traffic conditions.                                                                              



This state diagram provides a clear structure for understanding the basic flow and conditions of the Gishushu traffic light system, taking into account both vehicle traffic and pedestrian requests.

BELOW ARE THE SCREENSHOT FOR BOTH StarUML and draw.io:

![StarUML](https://github.com/user-attachments/assets/1072058f-61d9-44a3-9114-e5a81bec4f75)
![StateDiagram](https://github.com/user-attachments/assets/b92de8f1-e03d-49af-ae8f-d645a7eb3ab2)
