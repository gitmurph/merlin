# Learn Routing
| VRF | Address Family | Route | Active | Metric | Next Hop Index | Next Hop | Outgoing Interface | Route Preference | Source Protocol | Source Protocol Code |
| --- | -------------- | ----- | ------ | ------ | -------------- | -------- | -------------------| ---------------- | --------------- | -------------------- |
| default | ipv4 | 192.168.128.129/32 | True | N/A | N/A | N/A | GigabitEthernet0/0 | N/A | local | L |
| default | ipv4 | 192.168.128.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0 | N/A | connected | C |
| default | ipv4 | 192.168.87.100/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.875 | N/A | local | L |
| default | ipv4 | 192.168.87.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.875 | N/A | connected | C |
| default | ipv4 | 172.16.85.100/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.975 | N/A | local | L |
| default | ipv4 | 172.16.85.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/2.975 | N/A | connected | C |
| default | ipv4 | 172.1.0.112/32 | True | 2 | 1 | 10.0.0.2 | N/A | 110 | ospf | O |
| default | ipv4 | 168.10.129.1/32 | True | N/A | N/A | N/A | GigabitEthernet0/4.1000 | N/A | local | L |
| default | ipv4 | 168.10.129.0/30 | True | N/A | N/A | N/A | GigabitEthernet0/4.1000 | N/A | connected | C |
| default | ipv4 | 147.225.225.101/32 | True | N/A | N/A | N/A | GigabitEthernet0/2.675 | N/A | local | L |
| default | ipv4 | 147.225.225.100/30 | True | N/A | N/A | N/A | GigabitEthernet0/2.675 | N/A | connected | C |
| default | ipv4 | 30.30.30.30/32 | True | N/A | N/A | N/A | Null0 | N/A | static | S |
| default | ipv4 | 22.22.22.22/32 | True | N/A | N/A | N/A | Loopback12 | N/A | connected | C |
| default | ipv4 | 20.20.20.20/32 | True | N/A | N/A | N/A | Null0 | N/A | static | S |
| default | ipv4 | 12.12.12.12/32 | True | N/A | N/A | N/A | Loopback0 | N/A | connected | C |
| default | ipv4 | 11.11.11.11/32 | True | N/A | N/A | N/A | Loopback11 | N/A | connected | C |
| default | ipv4 | 10.33.33.33/32 | True | 2 | 1 | 10.0.0.2 | N/A | 110 | ospf | O |
| default | ipv4 | 10.10.10.10/32 | True | N/A | N/A | N/A | Loopback10 | N/A | connected | C |
| default | ipv4 | 10.0.0.1/32 | True | N/A | N/A | N/A | GigabitEthernet0/1 | N/A | local | L |
| default | ipv4 | 10.0.0.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/1 | N/A | connected | C |
| default | ipv6 | FF00::/8 | True | N/A | N/A | N/A | Null0 | N/A | local | L |