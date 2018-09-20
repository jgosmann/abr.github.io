---
title: Adaptive manipulators
slug: adaptive-manipulators
img: control.png
pitch: >
  We have implemented nonlinear adaptive control
  with a learning spiking neural network
  to control a 6-DOF Kinova Jaco<sup>2</sup> robotic arm.
  Provably more effective than PID control,
  and running on neuromorphic hardware,
  we have demonstrated increased accuracy, speed,
  and orders of magnitude lower-power than using conventional hardware.
  This opens the door to efficient,
  adaptive, embedded robotic systems.
---

As a step towards developing human-friendly robotics,
directly controlling the force
applied by each motor to the robot
allows for safe, compliant robotic movement.

<iframe width="100%" height="400" src="https://www.youtube.com/embed/muaG2VETgHU?list=PL0Xs4sfQU-Q1MeTNaizzFWYv1Xz3ua7ZA" frameborder="0" allowfullscreen></iframe>

To effectively implement force controllers, however,
accurate models of the system dynamics are required.
Nonlinear adaptive control methods
provide means of compensating for inaccurate models online,
and are provably stable
and at least as effective as standard PID control.

Our research has shown how nonlinear adaptive control
can be implemented in neural networks
to control robotic simulations.
We applied this control on the Kinova Jaco<sup>2</sup> robotic arm
by first developing a force-control interface to the arm
(available publicly on GitHub),
and then building a hybrid implementation
of adaptive neural control using Nengo
(which we have also made available publicly)
and neuromorphic hardware.
Our demonstration shows the system
adapting to unexpected forces acting upon the arm
in real-time, showcasing the utility of
low-power, adaptive, embedded robotic systems.

- [Demo videos](https://www.youtube.com/watch?v=muaG2VETgHU&list=PL0Xs4sfQU-Q1MeTNaizzFWYv1Xz3ua7ZAs&index=1)
- [ABR Control code](https://github.com/abr/abr_control)

<!-- TODO: Add link to paper (eventually) -->