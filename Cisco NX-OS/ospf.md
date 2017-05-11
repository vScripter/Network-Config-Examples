<!-- Cisco NX-OS -->

# Configure OSPF
```
conf t
router ospf <ospf process id>
network <network-address> <wildcard-mask> <ospf-area-id>
end
```

**Validation**
```
sho ip ospf
```