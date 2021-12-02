#[Quadcopter Simulation in Python](https://github.com/hbd730/quadcopter)

The project simulates a quadcopter in 3D environment. It contains a basic quadcopter dynamcis model, hover controller, trajectory generator, visulization toolkit and a top level scheduler which runs each module at a specific rate. 

![alt tag](https://github.com/hbd730/quadcopter-simulation/blob/master/sim.gif)

Motivation
-----
I have been playing and studying quadcopter in my spare time since 2014 when I first bought a crazyflie. There are many interesting projects around already, like vison-based SLAM, hover control and advance manoeuvre,etc. However, there are very few open source quadcopter simulator which helps a beginner to overcome the mental barrier of understanding the underlying physics. There are a lot of research papers on the topic of quadcopter control and autonomous application, but none of those can be made possible without a decent simulation tool. This project aims to address that. Thanks to Coursera's online course Aerial Robotics by Professor Vijay Kumar, which presents quadcopter's motion equations in detail, I was then inspired and finally able to write this from scratch.

To Run
-----
The simulator only uses matplotlib and scipy. You can simply run the following:
``` 
make
python runsim.py
``` 

Future Work
-----
Here is my current plan:

* Add state history plots.
* Develop a helix or way points trajectory.
* Kalman filter based sensor fusion: height estimation by accelerometer and barometer.

Contribution
-----
Any contribution are welcome if you are interested in the project, but please let me know.

Contact
-----
Peter Huang

Email: hbd730@gmail.com
