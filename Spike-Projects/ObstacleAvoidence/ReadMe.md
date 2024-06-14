# Basic Obstacle Avoidance Robot
When the program starts, the motor speed will be set to half, <br />
and the robot will start moving forward. <br />
If the distance sensor detects an obstacle within 15 cm, the robot will stop and rotate to the right. <br />
If it doesn't detect anything within the range, it will keep going; otherwise, it will rotate to the left, and so on. <br />
# Pseudocode: 

START <br />
SET motor_speed TO half <br />
MOVE_FORWARD(motor_speed) <br />
LOOP forever <br />
   distance = READ_DISTANCE_SENSOR() <br />
    IF distance < 15 cm THEN <br />
        STOP() <br />
        ROTATE_RIGHT() <br />
        MOVE_FORWARD(motor_speed) <br />
    ELSE <br />
        MOVE_FORWARD(motor_speed) <br />
    ENDIF <br />
ENDLOOP <br />
END
