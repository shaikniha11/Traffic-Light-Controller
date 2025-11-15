# Traffic-Light-Controller
This project implements a realistic traffic light control system commonly found at intersections. The controller manages three traffic signals (Green, Yellow, Red) with precise timing control and smooth state transitions, designed using Moore FSM architecture for predictable behavior.
- 3-State Moore FSM: GREEN → YELLOW → RED → GREEN cycle
- Parameterized Timing Control:

- Green: 30 clock cycles (configurable)
- Yellow: 10 clock cycles (configurable)
- Red: 40 clock cycles (configurable)


- Synchronous Counter-Based Logic: Accurate timing using clock-synchronized counters
- Asynchronous Reset: Immediate system initialization to safe state (RED)
- One-Hot State Encoding: Optional for faster state transitions
- Glitch-Free Outputs: Registered outputs prevent signal hazards
- Scalable Design: Easy parameter adjustment for different timing requirements
