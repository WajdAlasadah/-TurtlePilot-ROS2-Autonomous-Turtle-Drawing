🐢 TurtlePilot – ROS2 Autonomous Turtle Control
A simple Python project using ROS2 to autonomously control the turtlesim turtle, drawing various shapes like circles, squares, and stars ⭐️. The project sends velocity commands (geometry_msgs/msg/Twist) to smoothly move the turtle inside the simulator.

Built for ROS2 Humble on Ubuntu 22.04, this project is perfect for beginners looking to learn how to create custom Python nodes and automate robot motion in an easy and visual way 👩‍💻🐢.

✨ Features
🚀 Automatic turtle movement using velocity commands

🔄 Circle drawing by controlling linear and angular velocity

🎨 Easy to customize for other shapes by adjusting speed parameters

🐍 Simple Python implementation using the rclpy library

⚙️ Setup & Usage
📂 Clone or copy the package into your ROS2 workspace (~/ros2_ws/src).

🏗️ Build your workspace:

bash
Copy
Edit
colcon build
source install/setup.bash
🐢 Run the turtlesim simulator:

bash
Copy
Edit
ros2 run turtlesim turtlesim_node
▶️ In a new terminal, run the turtle drawer node:

bash
Copy
Edit
ros2 run turtle_drawer turtle_drawer
👀 Watch the turtle start drawing shapes automatically!

🔧 Customization
You can modify the parameters inside turtle_drawer.py to try different shapes and behaviors:

python
Copy
Edit
msg.linear.x = 2.0      # Forward speed
msg.angular.z = 1.0     # Rotation speed
Experiment with different values to draw squares, stars, or even spirals!
