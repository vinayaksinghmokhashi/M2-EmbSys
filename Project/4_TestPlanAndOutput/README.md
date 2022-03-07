## Table 1

## High Level Test plan

|Test id| Description| Exp I/P | Exp O/P |Actual O/P | Test type| Status |
|-------|------------|---------|---------|-----------|----------|--------|
| 1| Rotation of the motors |Power on | Motor motion |Motor motion| Technical base |✅ |
|2| Controlling the speed of motion | Change in potentiometer value | Change in motor speed |Change in motor speed | Technical base | ✅ |
|3| Controlling the direction of motor | Toggling push button | Change in direction of motion |Change in direction of motion |Technical base|✅ |

## Table 2

## Low Level Test plan for HLTP_1

|Test id| Description| Exp I/P | Exp O/P |Actual O/P |Status |
|-------|------------|---------|---------|-----------|-------|
|1 |Powering the circuit |Power supply |Motor motion|Motor motion|✅ |
|2|Powering the circuit| Power off | No motion|No motion|✅ |

## Low Level Test plan for HLTP_2

|Test id| Description| Exp I/P | Exp O/P |Actual O/P |Status |
|-------|------------|---------|---------|-----------|-------|
|1|Speed of the motion|Potentiometer value set at 1000 ohm|Speed at 1X|Speed at 1X|✅ |
|2|Speed of the motion|Potentiometer value set at 2000 ohm|Speed at 2X|Speed at 2X|✅ |
|3|Speed of the motion|Potentiometer value set at 10000 ohm|Speed at max|Speed at max|✅ |

## Low Level Test plan for HLTP_3

|Test id| Description| Exp I/P | Exp O/P |Actual O/P |Status |
|-------|------------|---------|---------|-----------|-------|
|1|Direction control|Noramal mode| Clock wise rotation|Clock wise rotation|✅ |
|2|Direction control|Toggle switch| Anti clock wise rotation|Anti clock wise rotation|✅ |
|3|Direction control|Toggle switch again| Clock wise rotation|Clock wise rotation|✅ |
