# IO-Link

PoC Python implementation of IO-Link volume flow sensors via TCP/IP JSON with an ifm IO-Link Master.

## Usage

IP-address from IO-Link Master is 192.168.1.250.

SD-Sensor is connected to port 1 of the master.

```
from sd054x_iolink_REST import PBCo_IOLink_SDSensor

sensor = PBCo_IOLink_SDSensor(ipadr='192.168.1.250', port=1)

sensor.get_process_data()
```
