# DHT22-with-NodeMCU-over-MQTT
Connecting DHT22 Temperature sensor with nodeMCU . Sending its Collecting its  Data with  the help of MQTT protocol
Firstly You need to add your Wifi's Name and Password 
Secondly put the IP address for MQTT broker.
Thridly there are three topics published viz: 1.) sensor/Humidity 2.) sensor/temp_c  3.)sensor/temp_f
In order to get the values of the humidity, temperature in celcius and temperature in fereh. you have to subscribe those topics
