# RoboCAD_Visualizer
 This project demonstrates the process of using CAD models to create a Unified Robot Description Format (URDF) file and visualizing the model in RViz using ROS2.

Overview:
1. Convert CAD models (e.g., from SolidWorks) into STL files.
2. Define a URDF file referencing the STL files.
3. Launch the model in RViz using ROS2 tools for visualization.

To launch RViz with your URDF model, use the following command:
ros2 launch urdf_tutorial display.launch.py model:=/absolute/path/to/your/urdf/file.urdf 
