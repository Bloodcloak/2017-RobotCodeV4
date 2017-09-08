# 2017-RobotCodeV4
Our 4th itteration of our code. Based off of 2017-RobotCodeCommented and contains many organization improvements

# Some Features
) Table Based Autonomous where auton command sequence is relayed from Dashboard to the robot through Network Tables

) CMU Pixycam implementation though I2C

) Modular automated Aim and Shoot using Pixy

Note: NavX was NOT implemented for any orientation tracking this year due to dependency corruption caused by the library. It was planned to be reimplemented as we have found the cause of the corruption - we had to use the NavX main vi through the third party sensors palette rather than the dependency libary - but we never got back to it.
