# Configure VRRP

## Cisco NX-OS
### VRRP with VLAN Interface
```
conf t
interface <vlan id>
vrrp 101
ip address <virtual router IP>
priority <priority value>
authentication <auth value>
no preempt
end
```

**Validation**
```
show vrrp
```

