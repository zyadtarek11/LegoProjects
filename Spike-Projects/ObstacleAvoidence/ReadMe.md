# Basic Obstacle Avoidance Robot
When the program starts, the motor speed will be set to half, 
and the robot will start moving forward. 
If the distance sensor detects an obstacle within 15 cm, the robot will stop and rotate to the right. 
If it doesn't detect anything within the range, it will keep going; otherwise, it will rotate to the left, and so on.
# Pseudocode: 

START
SET motor_speed TO half
MOVE_FORWARD(motor_speed)
LOOP forever
    distance = READ_DISTANCE_SENSOR()
    IF distance < 15 cm THEN
        STOP()
        ROTATE_RIGHT()
        MOVE_FORWARD(motor_speed)
    ELSE
        MOVE_FORWARD(motor_speed)
    ENDIF
ENDLOOP
END
