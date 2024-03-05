# CSE-366-3---2021-2-60-097

In the robot simulation, we made changes to better manage its battery while it moves. Now, every time the robot moves, its battery level drops by 10%. If the battery level hits 0%, the robot automatically charges back up to 100%. These changes help the robot navigate a 10x10 grid with obstacles efficiently, making sure it stays operational. We also updated the simulate function to consider energy use when planning the robot's path. This ensures the robot navigates while taking into account both safety and energy efficiency.
