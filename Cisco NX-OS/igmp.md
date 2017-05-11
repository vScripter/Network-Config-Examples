<!-- Cisco NX-OS -->

# Enable IGMP, Globally
```
conf t
ip igmp snooping
end
```

**Validation**
```
show ip igmp snooping
```

# Configure IGMP Querier for VLAN 100
* VLAN: `100`
* Subnet: `192.168.1.0/24`
* Querier IP: `192.168.1.253`
```
conf t
ip igmp snooping querier 192.168.1.253
end
```

**Validation**
```
show ip igmp snooping querier vlan 100
```