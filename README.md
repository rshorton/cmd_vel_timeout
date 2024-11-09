# cmd_vel_timeout 

This package wraps the cmd_vel_timeout node from Linorobot2 by Juan Miguel Jimeno.

The cmd_vel_timeout node monitors the cmd_vel topic and publishes a cmd_vel message to stop the robot after not receiving a new message without a configured duration.