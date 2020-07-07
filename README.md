# hydroponic
IoT automation for hydroponic system.
The system should:
1. Measure temperature of the water
2. Measure PH level of water
3. Measure TDS in water
When needed the system should automatically add furtilizer and acid.
The system should eventually send messages to MQTT broker/Blynk/email/dedicated cloud.

The system consists of 2 controllers which communicate with each other:
1. Arduino nano to measure the readings from sensor
2. NodeMCU ESP8266 for communicating via Wifi
