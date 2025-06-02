Maze Navigation Robot using CoppeliaSim and Jupyter Notebooks
This project features a series of workshops that guide the development of a robot capable of navigating maze environments using CoppeliaSim (V-REP) and Python in Jupyter notebooks. The robot used in later workshops is the dr20, equipped with ultrasonic sensors, a front-facing laser sensor, and a camera.

Project Structure
🧠 Workshop 02 - Basic Robot Programming
This notebook introduces basic robot programming concepts and simulates simple movements using CoppeliaSim.

🧠 Workshop 03 - Intermediate Control
Building on Workshop 02, this notebook expands robot control using sensor feedback to create more reactive behavior.

🧠 Workshop 05 - Introducing the dr20 and Maze Navigation
You will begin using the dr20 robot in a short curvy maze environment. The notebook focuses on:

Accessing ultrasonic and laser sensor data

Writing logic to navigate through a walled maze

Recognizing when the robot has exited the maze

💾 Ensure you have sim.py, simConst.py (or vrepConst.py), remoteApi.dll, and the short_path_vrep.ttt scene in your working directory.

🧠 Workshop 06 - Enhanced Maze Navigation
Continues from Workshop 05 with improvements in:

Path-following accuracy

Better sensor usage

More robust logic for detecting maze completion

🧠 Workshop 07 - Sign Detection Maze
Uses a more complex maze (02_Maze_scene_vrep.ttt) with straight lines and signposts. Objectives include:

Capturing signpost images at junctions using the dr20’s camera

Preparing data for future training of a neural network to autonomously solve the maze

💾 Required files: sim.py, simConst.py, remoteApi.dll, and 02_Maze_scene_vrep.ttt.

Requirements
Python 3.x

Jupyter Notebook

CoppeliaSim (V-REP)

pyzmq, numpy, and other standard Python libraries

How to Run
Launch CoppeliaSim and load the corresponding .ttt scene file.

Start the simulation.

Open the desired Jupyter notebook and run the cells sequentially.

Observe robot behavior and sensor feedback in real-time.
