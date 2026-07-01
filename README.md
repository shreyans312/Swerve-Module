# Swerve Rover Module
Building a custom swerve drive because normal wheels don’t rotate enough.

## List of Components
1. AS5600 Magnetic Encoder Sensor Module (https://robu.in/product/magnetic-encoder-sensor-module-as5600/)
2. RMCS-3001 BLDC Motor Drive (Quantity: 2)
3. RMCS-2070 BLDC Motor

## Way Forward
1. Mechanical: Reprint of parts which were either weak or faulty in dimensions
   - Strengthening of main case, and change of dimensions to incorporate tolerance
   - Change in radius of circular disc
   - Reprint of big bevel gear
   - Still thinking about the coupler
    
2. Electronics: Figuring out the circuit diagram
   - Decide on the power supply
   - Understand the role of different components and sketch out the connections
   - We will have to make a ROS package for swerve drive control. Full gazebo simulation is not needed, just basic Rviz simulation. This is for good working simulation for control of 4 wheel swerve. 
   - For the time being, we use our own PC & send commands to esp32 via bluetooth (like rpm etc).
   - Later, we might use Raspberry Pi. 
