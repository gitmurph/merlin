# Learn Routing
| VRF | Address Family | Route | Active | Metric | Next Hop Index | Next Hop | Outgoing Interface | Route Preference | Source Protocol | Source Protocol Code |
| --- | -------------- | ----- | ------ | ------ | -------------- | -------- | -------------------| ---------------- | --------------- | -------------------- |
| default | ipv4 | 192.168.210.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/1.1 | N/A | local | L |
| default | ipv4 | 192.168.210.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/1.1 | N/A | connected | C |
| default | ipv4 | 192.168.202.200/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.202 | N/A | local | L |
| default | ipv4 | 192.168.202.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.202 | N/A | connected | C |
| default | ipv4 | 192.168.201.200/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.200 | N/A | local | L |
| default | ipv4 | 192.168.201.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.200 | N/A | connected | C |
| default | ipv4 | 192.168.128.130/32 | True | N/A | N/A | N/A | GigabitEthernet0/0 | N/A | local | L |
| default | ipv4 | 192.168.128.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0 | N/A | connected | C |
| default | ipv4 | 192.168.101.100/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.100 | N/A | local | L |
| default | ipv4 | 192.168.101.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.100 | N/A | connected | C |
| default | ipv4 | 172.1.0.112/32 | True | N/A | N/A | N/A | Loopback0 | N/A | connected | C |
| default | ipv4 | 12.12.12.12/32 | True | 2 | 1 | 10.0.0.1 | N/A | 110 | ospf | O |
| default | ipv4 | 10.33.33.33/32 | True | N/A | N/A | N/A | Loopback22 | N/A | local | L |
| default | ipv4 | 10.33.33.0/24 | True | N/A | N/A | N/A | Loopback22 | N/A | connected | C |
| default | ipv4 | 10.10.190.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.190 | N/A | local | L |
| default | ipv4 | 10.10.190.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.190 | N/A | connected | C |
| default | ipv4 | 10.10.180.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.180 | N/A | local | L |
| default | ipv4 | 10.10.180.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.180 | N/A | connected | C |
| default | ipv4 | 10.10.160.11/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.160 | N/A | local | L |
| default | ipv4 | 10.10.160.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.160 | N/A | connected | C |
| default | ipv4 | 10.10.140.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.140 | N/A | local | L |
| default | ipv4 | 10.10.140.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.140 | N/A | connected | C |
| default | ipv4 | 10.10.130.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.130 | N/A | local | L |
| default | ipv4 | 10.10.130.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.130 | N/A | connected | C |
| default | ipv4 | 10.10.120.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.120 | N/A | local | L |
| default | ipv4 | 10.10.120.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.120 | N/A | connected | C |
| default | ipv4 | 10.10.110.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.110 | N/A | local | L |
| default | ipv4 | 10.10.110.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.110 | N/A | connected | C |
| default | ipv4 | 10.0.0.2/32 | True | N/A | N/A | N/A | GigabitEthernet0/1 | N/A | local | L |
| default | ipv4 | 10.0.0.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/1 | N/A | connected | C |
| default | ipv4 | 0.0.0.0/0 | True | 0 | 1 | 192.168.128.2 | N/A | 254 | static | S* |