# ArduinoProject

Reference:

Connecting simple devices to IoT Central
https://sandervandevelde.wordpress.com/2019/04/06/connecting-simple-devices-to-iot-central/

Key generation

Visit the GitHub page of the Azure IoT DPS Symmetric Key Generator. There you find the tooling to derive a connection string from the device administration in IoT Central:

afd06

First, you get the code from GitHub and compile it using:

git  clone https://github.com/Azure/dps-keygen.git
cd dps-keygen
npm i -g dps-keygen
Then, you generate the key using:

dps-keygen -di:deviceidhere -dk:devicekeyhere -si:scopeidhere
