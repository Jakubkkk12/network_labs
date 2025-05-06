# 🧠 ENCOR: Layer 3 Forwarding – ARP, Routing, Adjacency & CEF

## 🧾 Commands used:

### 🔍 ARP Commands
- `show arp`
- `show arp 10.0.1.10`
- `show arp 10.0.1.10 detail`
- `show arp interface`
- `show arp summary`
- `show arp dynamic`
- `show arp incomplete`

### 📡 IP Interface and Routing
- `show ip interface brief | exclude unassigned`
- `show ip route | begin Gateway`
- `show ip route 192.168.50.0 longer-prefixes | begin Gateway`
- `show ip route 192.168.50.0 255.255.255.0`

### 🤝 Adjacency Table
- `show adjacency`
- `show adjacency gigabitEthernet0/1 detail`
- `show adjacency summary`
- `show adjacency encapsulation`
- `show adjacency link ipv4`

### ⚙️ Cisco Express Forwarding (CEF)
- `show cef fib`
- `show cef gigabitEthernet0/1`
- `show cef state`

## 📷 Screenshot

### 🔹 show arp
![show arp](screenshots/show_arp.png)

### 🔹 show arp 10.0.1.10
![show arp 10.0.1.10](screenshots/show_arp_10.0.1.10.png)

### 🔹 show arp 10.0.1.10 detail
![show arp 10.0.1.10 detail](screenshots/show_arp_10.0.1.10_detail.png)

### 🔹 show arp interface
![show arp interface](screenshots/show_arp_interface.png)

### 🔹 show arp summary
![show arp summary](screenshots/show_arp_summary.png)

### 🔹 show arp dynamic
![show arp dynamic](screenshots/show_arp_dynamic.png)

### 🔹 show arp incomplete
![show arp incomplete](screenshots/show_arp_incomplete.png)

### 🔹 show ip interface brief | exclude unassigned
![show ip int br | ex unassigned](screenshots/show_ip_int_br_ex_unassigned.png)

### 🔹 show ip route | begin Gateway
![show ip route | beg Gat](screenshots/show_ip_route_begin_gateway.png)

### 🔹 show ip route 192.168.50.0 longer-prefixes | begin Gateway
![show ip route 192.168.50.0 longer-prefixes | beg Gat](screenshots/show_ip_route_192.168.50.0_longer_prefixes.png)

### 🔹 show ip route 192.168.50.0 255.255.255.0
![show ip route 192.168.50.0 255.255.255.0](screenshots/show_ip_route_192.168.50.0_255.255.255.0.png)

### 🔹 show adjacency
![show adjacency](screenshots/show_adjacency.png)

### 🔹 show adjacency gigabitEthernet0/1 detail
![show adjacency g0/1 det](screenshots/show_adjacency_g0_1_detail.png)

### 🔹 show adjacency summary
![show adjacency summary](screenshots/show_adjacency_summary.png)

### 🔹 show adjacency encapsulation
![show adjacency encapsulation](screenshots/show_adjacency_encapsulation.png)

### 🔹 show adjacency link ipv4
![show adjacency link ipv4](screenshots/show_adjacency_link_ipv4.png)

### 🔹 show cef fib
![show cef fib](screenshots/show_cef_fib.png)

### 🔹 show cef gigabitEthernet0/1
![show cef g0/1](screenshots/show_cef_g0_1.png)

### 🔹 show cef state
![show cef state](screenshots/show_cef_state.png)
