# toviscsapat-ev3-mindstorms-blocks
LEGO EV3 Mindstorms custom blocks created for FIRST LEGO League teams and a collection of useful applications you can add to youe EV3 brick - EV3 main app menu, under the third tab.

## TovisBlocks
Custom blocks created for FIRST LEGO League teams

TovisBlocks enables advanced use of some functions possible with EV3 Mindstorms.

- Sensor and Motor name detection
- Tiny font and
- Tilt mode on new gyros.

Download [TovisBlocks.ev3b](TovisBlocks.ev3b) and import the .ev3b block under the menu `Tools | Block Import | Browse | TovisBlocks.ev3b | Open | Import`

Sharing is important - so have fun, use it freely - and please reference in your documentation and code - TövisBlocks, Toviscsapat Robotics Club, toviscsapat.hu.

Additional credits go for [OFDL EV3 Developer Mode Config Tool](https://ofdl.tw/en/technical/ev3-developer-tools/) for helping development and research.

![tovisblocks1](https://github.com/user-attachments/assets/e643bb23-836d-431d-8d5e-0f39d645076d)

## EV3 Brick Applications

A collection of useful applications you can add to youe EV3 brick - EV3 main app menu, under the third tab.

Install app with the EV3BrickMagic command line tool.
Download the [EV3BrickMagic](https://s3.eu-west-3.amazonaws.com/ev3brickmagic/ev3brickmagic-win-x86.zip) command line tool, then with e.g. USB connection execute
`EV3BrickMagic.exe -p=USB install <zipname>`

The source zip file shall contain a single directiory containing all files (rbf, rgf, rsf)

__IRDrive app: Motor control with speed adjustment and IR Control.__

Adding fine motor control from the brick and remote testing of a robot before programming.
Download [IRDrive](IRDrive.zip) EV3 application as a zip file and install `EV3BrickMagic.exe -p=USB install IRDrive.zip`

Functions
- Motor control with adjustable speed 10-50
- Infrared remote controlled drive on B+C
- Infrared remote controlled fine motor control on A, D

Modes, set with middle button
- Mode1: motor control: B+C, A, D with IR remote
- Mode2: speed setting: B+C, A, D with arrows
- Mode3: IR sensor port, color sensor port, reveresed B+C motor

![ev3apps](https://github.com/user-attachments/assets/257d6e6a-c0ba-4387-9ab8-9a7a0d7b4cd2)
![irdrive](https://github.com/user-attachments/assets/5fca626a-32c3-4ba6-a2a2-652d27810bc8)
