# MQTT_to_BACnet_Server
Subscribes to MQTT topics and created BACnet objects for values.
Has persistent object storage loaded at startup.
Valid MQTT JSON payload:
{
  'name': 'environment_data', 
  'device': 'ESP32-Device', 
  'location': 'Livingroom', 
  'temperature': 73.4, 
  'temperature_unit': '°F', 
  'humidity': 61.4, 
  'humidity_unit': '%', 
  'enthalpy': 50.48, 
  'enthalpy_unit': 'kJ/kg'
 }
