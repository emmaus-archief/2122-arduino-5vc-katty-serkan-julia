De readme.md vind je in de hoofdmap van deze repo.

Sensoren:
1. ST188: reflective infrared photoelectric sensor, for obstacle avoiding
2. ITR20001/T: reflective infrared photoelectric sensor, for line tracking
3. IR receiver

Actuator:
1. Potentiometer for adjusting obstacle avoiding range ??
2. TB6612FNG dual H-bridge motor driver
3. N20 micro gear motor reduction rate 1:30, 6V/600RPM ??
4. WS2812B: true-color RGB LEDs
5. AlphaBot2 control interface: for connecting AlphaBot2-Base
6. Arduino expansion header: for connecting Arduino shields
7. Arduino interface: for connecting Arduino compatible controller
8. Xbee connector: for connecting dual-mode Bluetooth module, remotely control the robot via Bluetooth ??
9. PC8574: I/O expander, SPI interface ??
10. Joystick
11. Speakers

Pinnen:

motor:
#define  PWMA  5  //Left Motor Speed pin (ENA)
#define  AIN2  A0  //Motor-L forward (IN2)
#define  AIN1  A1  //Motor-L backward (IN1)
#define  PWMB  6  //Right Motor Speed pin (ENB)
#define  BIN1  A2  //Motor-R forward (IN3)
#define  BIN2  A3  //Motor-L backward(IN4)
