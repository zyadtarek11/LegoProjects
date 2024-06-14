# **Sending Messages using WeDo Kit**
Program Description \
The program works as follows:    \

When the 'A' button is pressed on the keyboard, the program will wait until the tilt position changes to the right or to the left. \
If the tilt is to the left, the program will run a certain sound indicating a certain character and wait until the tilt returns to its horizontal state. \
The program will then wait for the tilt to change its position either to the left or to the right. \
If the tilt is to the right this time, it will run a certain sound indicating another character and wait until the tilt returns to its horizontal state. \
This process continues, alternating between left and right tilts, each time running a specific sound to indicate different characters. \
#Pseudocode:
START    \
WHILE true <br />
    IF 'A' button is pressed THEN <br />
        WAIT until tilt position changes (left or right) <br />
        IF tilt is LEFT THEN \
            RUN sound indicating Character 1 \
            WAIT until tilt returns to horizontal \
        ELSE IF tilt is RIGHT THEN \
            RUN sound indicating Character 2    \
            WAIT until tilt returns to horizontal    \
        END IF    \
    END IF    \
END WHILE    \
END    \
This pseudocode provides a basic structure for the program.
