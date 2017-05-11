# Switchport Configurations

## Cisco NX-OS
### Basic Hypervisor/Host Trunk Port
```
conf t
spanning-tree port type edge
spanning-tree bpduguard enable
spanning-tree bpdufilter enable
switchport mode trunk
switchport trunk allowed vlan <vlan list>
no shut
end
```

**Validation**
```
show interface switchport
```