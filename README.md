![image](https://github.com/user-attachments/assets/fdfc6117-b0e2-4b18-b9d4-1221bd003d70)# MQTT
A repository aimed at reaserching MQTT and similar technologies.


## Topic structure
![image](https://github.com/user-attachments/assets/a312e8f2-22fe-4881-a061-639fa2d38004)

## User structure
| User                 | Permisions                                       |
|----------------------|--------------------------------------------------|
| Housemaster          | Read/Write: root/home/#                          |
| Status Tracker       | Read-only: root/home/+/+/+/+/status              |
| Sensor Monitor       | Read-only: root/home/+/+/sensors/#               |
| Sensor Control       | Read/Write: root/home/+/+/sensors/#              |
| Smart Device Control | Read/Write: root/home/+/+/devices/#              |
| Guest (Bedroom2)     | Read-only: root/home/floor2/bedroom2/sensors/+/# |


## Related repositories:
[sensor_simulation](https://github.com/ITIS-TEAM-7/sensor_simulation)

## Related software:
[MQTT Explorer](https://mqtt-explorer.com/)
[Node-RED](https://nodered.org/)

## Useful introduction information
[MQTT Version 3.1.1 OASIS Standard](https://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.pdf)

[Great beginner __basics__ tutorial](https://youtube.com/playlist?list=PLRkdoPznE1EMXLW6XoYLGd4uUaB6wB0wd&si=foSOxoWVDRMRlZ_u)

[MQTT.js](https://github.com/mqttjs)

## For further work
[MQTT-SN](https://groups.oasis-open.org/higherlogic/ws/public/document?document_id=66091)
[TLS](https://datatracker.ietf.org/doc/html/rfc8446)
