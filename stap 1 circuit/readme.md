De readme.md vind je in de hoofdmap van deze repo.

Sensoren:
1. Ultrasonic

Actuator:
1. TB6612FNG dual H-bridge motor driver
2. Joystick


Pinnen:

motor:
#define  PWMA  5  //Left Motor Speed pin (ENA)
#define  AIN2  A0  //Motor-L forward (IN2)
#define  AIN1  A1  //Motor-L backward (IN1)
#define  PWMB  6  //Right Motor Speed pin (ENB)
#define  BIN1  A2  //Motor-R forward (IN3)
#define  BIN2  A3  //Motor-L backward(IN4)

ultrasonic:

raging:
#define ECHO   2
#define TRIG   3

infrarood obstacle avoiding:
#define PWMA   6           //Left Motor Speed pin (ENA)
#define AIN2   A0          //Motor-L forward (IN2).
#define AIN1   A1          //Motor-L backward (IN1)
#define PWMB   5           //Right Motor Speed pin (ENB)
#define BIN1   A2          //Motor-R forward (IN3)
#define BIN2   A3          //Motor-R backward (IN4)
#define ECHO   2
#define TRIG   3

#define Addr  0x20

obstacle avoiding without infrared:
#define PWMA   6           //Left Motor Speed pin (ENA)
#define AIN2   A0          //Motor-L forward (IN2).
#define AIN1   A1          //Motor-L backward (IN1)
#define PWMB   5           //Right Motor Speed pin (ENB)
#define BIN1   A2          //Motor-R forward (IN3)
#define BIN2   A3          //Motor-R backward (IN4)
#define ECHO   2
#define TRIG   3


