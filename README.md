# Flight Mechanics
All rights reserved.
The software is a limited demo of the flight mechanics simulator that will be released in a future update, together with the source code.
The simulation is based on the first-year TU Delft course 'Introduction to Aerospace Engineering' so certain behaviors (such as realistic stall) are missing.

The flight model of the aircraft is that of an F-16 Viper, despite the visual model being that of a business jet.
This was chosen, because the final goal of the project is to simulate an aircraft parametrically, from a json file, without regard for visuals.
The program also simulates a landing gear and tire contact which allow for take-off and landing, however, those are not visible since they do not have visual models yet.

The demo calculates and displays a number of parameters that are significant for aircraft handling:
- Angle of Attack
- Load Factor (g)
- Instantaneous Turn Rate
- True (TAS) and Equivalent (EAS) Airspeeds
- Mach number
- Minimum speed (VMIN)
- Best speed for max rate of climb (ROC)
- Best speed for max endurance i.e. time flown (END)
- Best speed for max range i.e. distance flown (RNG)

# Controls
Throttle: W/S
Elevator: Mouse Y (down is up)
Aileron: Mouse X
Rudder: A/D, reset to neutral with Q
Flaps: H to lower, Y to retract
Landing Gear: G
Ground Brakes: Up/Down arrow
Spectator Camera: X
Quit: Escape
