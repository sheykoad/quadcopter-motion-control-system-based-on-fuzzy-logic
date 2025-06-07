# quadcopter-motion-control-system-based-on-fuzzy-logic
The work presents the development of a height stabilization system and a linear motion system for a quadcopter based on a fuzzy controller and a fuzzy PID controller, as well as simulation results of trajectory tracking under various wind disturbances
The objective of this study is to improve the quality of quadcopter motion control along reference trajectories under wind disturbances.
The object of the study is a quadcopter represented by a mathematical model in the form of a system of differential equations.
The subjects of the study are:
1.	A fuzzy logic-based controller used for quadcopter control under disturbing influences.
2.	A fuzzy PID controller used for quadcopter control under disturbing influences

Simulations were conducted for two trajectories (vertical circle and helical path) under the following wind disturbances according to the Beauport scale: Moderate wind (5.6 m/s), Strong wind (11.2 m/s), Very strong wind (18 m/s).
The mean-square error (MSE) was used as a quantitative measure of trajectory tracking accuracy.
A comparison was made with a PID-based control system from prior research.
Table 4 presents the MSE values for each control method and trajectory under varying wind conditions.
Moderate Wind (5.6 m/s): the fuzzy PID controller and PID controller exhibit similar accuracy for both trajectories. The fuzzy controller outperforms them by an order of magnitude in z-axis precision.
Strong Wind (11.2 m/s): the PID and fuzzy PID controllers shows comparable performance. The fuzzy controller maintains significantly higher accuracy (order of magnitude better).
Very Strong Wind (18 m/s): the PID controller fails to track the reference trajectories. The fuzzy PID controller succeeds only for the vertical circle, but with reduced accuracy. The fuzzy controller remains operational for both trajectories, demonstrating superior robustness.

