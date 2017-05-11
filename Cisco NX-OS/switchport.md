# Switchport Configurations

### Basic Hypervisor/Host Trunk Port
```
spanning-tree port type edge
spanning-tree bpduguard enable
spanning-tree bpdufilter enable
switchport mode trunk
switchport trunk allowed vlan <vlan list>
no shut
```

> Validation
>> `show interface switchport`