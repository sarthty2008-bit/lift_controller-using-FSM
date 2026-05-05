
# 3-floor lift controller using FSM 
The objective of this project is to design and verify a Finite State Machine (FSM) for a 3-floor elevator system capable of handling multiple floor requests, controlling movement direction, and managing door operations with timing.

This project evaluates:

Correctness of state transitions

Scheduling and prioritization logic

Sequential control (movement + door timing)

# Problem Statement
Design an elevator controller with the following floors:

Floor 0

Floor 1

Floor 2

# Functional Behavior
Elevator must respond to multiple requests

Requests should be stored and served efficiently

Fairness: all requests must eventually be served

# Movement Logic
Move UP if lower floor request exists

Move DOWN if upper floor request exists

Stay IDLE if no pending requests

# Door Operation
Open door when elevator reaches requested floor

Keep door open for fixed cycles (timer-based)

Close door before moving

# included in Testbench 

Clock generation

Reset logic

Apply multiple request patterns

Use display for outputs
