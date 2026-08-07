# Enterprise IP Matrix & Architecture Plan

## 1. WAN / ISP Link Subnets (Point-to-Point /30 links)
* **ISP Backbone Network:** 100.1.0.0/16
  * **Ottawa HQ to ISP Link:** 100.1.1.0/30
    * ISP Interface: 100.1.1.1
    * Ottawa-HQ Interface (Gig0/0/0): 100.1.1.2
  * **Calgary Branch to ISP Link:** 100.1.2.0/30
    * ISP Interface: 100.1.2.1
    * Calgary Router Interface: 100.1.2.2
  * **Toronto Branch to ISP Link:** 100.1.3.0/30
    * ISP Interface: 100.1.3.1
    * Toronto Router Interface: 100.1.3.2

## 2. Local Area Networks (LAN Subnets)
* **Ottawa HQ LAN:** 192.168.10.0/24 (Gateway: 192.168.10.1)
* **Calgary Branch LAN:** 192.168.20.0/24 (Gateway: 192.168.20.1)
* **Toronto Branch LAN:** 192.168.30.0/24 (Gateway: 192.168.30.1)

## 3. Loopback Interfaces (Router IDs / Stability)
* **Ottawa HQ Loopback 0:** 10.1.1.1/32
* **Calgary Loopback 0:** 10.1.2.1/32
* **Toronto Loopback 0:** 10.1.3.1/32
EOFcat << 'EOF' > documentation/ip_matrix.md
# Enterprise IP Matrix & Architecture Plan

## 1. WAN / ISP Link Subnets (Point-to-Point /30 links)
* **ISP Backbone Network:** 100.1.0.0/16
  * **Ottawa HQ to ISP Link:** 100.1.1.0/30
    * ISP Interface: 100.1.1.1
    * Ottawa-HQ Interface (Gig0/0/0): 100.1.1.2
  * **Calgary Branch to ISP Link:** 100.1.2.0/30
    * ISP Interface: 100.1.2.1
    * Calgary Router Interface: 100.1.2.2
  * **Toronto Branch to ISP Link:** 100.1.3.0/30
    * ISP Interface: 100.1.3.1
    * Toronto Router Interface: 100.1.3.2

## 2. Local Area Networks (LAN Subnets)
* **Ottawa HQ LAN:** 192.168.10.0/24 (Gateway: 192.168.10.1)
* **Calgary Branch LAN:** 192.168.20.0/24 (Gateway: 192.168.20.1)
* **Toronto Branch LAN:** 192.168.30.0/24 (Gateway: 192.168.30.1)

## 3. Loopback Interfaces (Router IDs / Stability)
* **Ottawa HQ Loopback 0:** 10.1.1.1/32
* **Calgary Loopback 0:** 10.1.2.1/32
* **Toronto Loopback 0:** 10.1.3.1/32
