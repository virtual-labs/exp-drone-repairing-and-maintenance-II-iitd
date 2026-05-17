### Definition of Drone Motors and ESCs

In a quadcopter or multirotor drone, *Brushless DC (BLDC) motors* are
used to spin the propellers and generate thrust. Each motor is
controlled by an *Electronic Speed Controller (ESC)*, which regulates
the motor's speed and direction. Together, motors and ESCs are the core
propulsion system of the drone.

A drone's stable flight relies on all motors and ESCs functioning
properly---failure of even one motor or ESC can lead to imbalance and
possible crashes.

------------------------------------------------------------------------

### Principle of Motor and ESC Operation

-   *Motors (BLDC):* Work on the principle of electromagnetic
    induction. The ESC sends a 3-phase alternating signal to the motor
    coils, creating a rotating magnetic field that spins the rotor.

-   *ESCs:* Convert the drone's battery DC power into 3-phase AC
    signals, and regulate motor speed based on flight controller inputs.

-   *Pitch/Roll Control:* Achieved by increasing or decreasing speed
    of opposite motors.

-   *Yaw Control:* Achieved by creating torque differences between
    clockwise (CW) and counterclockwise (CCW) motors through ESC
    commands.

------------------------------------------------------------------------

### Components Involved in Motor and ESC Issues

### 1. Drone Motor (BLDC Motor)

The motor is responsible for generating thrust by rotating the
propellers.

*Functions:*
- Produces lift by spinning propellers.
- Provides stability during flight through precise speed control.
- Works continuously under high loads.

*Common Issues:*
- Motor not spinning (damaged winding, short circuit).
- Overheating due to excess current or friction.
- Unusual noise/vibration from bent shafts or worn bearings.
- Reduced thrust from partial winding burn.

*User Checks:*
- Test motor windings using a multimeter (continuity test).
- Inspect bearings, shafts, and propeller fittings.
- Smell or discoloration check (burnt windings).
- Spin the motor by hand to feel resistance or grinding.

------------------------------------------------------------------------

### 2. Electronic Speed Controller (ESC)

The ESC acts as a power regulator and motor driver, converting DC from
the battery into signals that run BLDC motors.

*Functions:*
- Supplies correct 3-phase current to motors.
- Controls motor speed, direction, and braking.
- Receives signals from the flight controller to adjust motor thrust.

*Common Issues:*
- ESC not responding (burnt MOSFETs, faulty firmware).
- Motor jerking/stuttering due to timing mismatch.
- ESC overheating from excess current.
- Loose/burnt connectors.

*User Checks:*
- Measure ESC output voltage with a multimeter.
- Swap faulty ESC with a working one to confirm issue.
- Inspect solder joints, power wires, and connectors.
- Calibrate ESC with the flight controller if necessary.

------------------------------------------------------------------------

### 3. Wiring and Soldering Connections

Proper wiring ensures stable power delivery between ESC, motor, and
battery. Weak or broken connections can interrupt operation.

*Common Problems:*
- Cold solder joints (dull or cracked).
- Loose bullet connectors.
- Burnt PCB tracks from short circuits.

*Solution:*
- Re-solder using proper flux and heat.
- Replace damaged wires or connectors.

------------------------------------------------------------------------

### 4. Physical Damage

Drone crashes can damage motor shafts, bend propellers, or break ESC
boards. Physical wear and tear directly affects performance.

------------------------------------------------------------------------

### Troubleshooting Approach

1.  *Visual Inspection* -- Check motors, ESC boards, and wires.
2.  *Continuity Test* -- Use multimeter for motor windings and ESC
    output.
3.  *Component Swapping* -- Replace suspected faulty ESC/motor with a
    working one.
4.  *Re-soldering* -- Repair loose joints.
5.  *Replacement* -- Replace damaged motors or ESCs if not repairable.