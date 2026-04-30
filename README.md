# Self-Balancing-Robot-


### Overview and Objectives
The project explores the practical application of the inverted pendulum principle, a naturally unstable system that requires continuous real-time correction to remain upright[cite: 1]. The document outlines several core objectives, presented in a mix of English and Roman Urdu, which include:
*   Building a compact, Arduino-based chassis and control system
*   Utilizing an MPU6050 gyroscope to measure tilt angles for real-time balance control
*   Applying feedback control (PID) concepts to maintain stability
*   Studying how weight distribution impacts mechanical stability.

### System Design and Hardware
The mechanical structure was built using a custom cylindrical chassis cut from a 6-inch water drain pipe[cite: 1]. The robot weighs approximately 370 grams and uses a three-tiered layered arrangement for optimal weight distribution:
*   Bottom Plate: Holds two battery cells.
*   Middle Section: Houses the main controller (Arduino Uno) and the L298N motor driver.
*   Top Plate: Mounts the MPU6050 gyroscope for accurate tilt detection.
*   Mobility: Driven by two DC gear motors equipped with wheels.

### **Control Logic and Mathematics**
To maintain balance, the system relies on a closed-loop Proportional-Integral-Derivative (PID) controller, which processes data from the gyroscope to adjust motor movement, reduce steady-state error, and minimize oscillations. The report provides the mathematical foundation for this mechanism:

### Challenges and Conclusion
During development, the team encountered and resolved several engineering challenges, including sensor calibration, noise reduction, precise weight distribution, and motor delay. The report concludes that the project was a success, with the robot demonstrating stable self-balancing behavior and effectively responding to external disturbances.
