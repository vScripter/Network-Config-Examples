# Configure VRRP

### VRRP with VLAN Interface
```
conf t
interface <vlan id>
vrrp 101
ip address <virtual router IP>
priority <priority value>
authentication <auth value>
no preempt
```

