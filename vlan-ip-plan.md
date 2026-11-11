
# VLAN and IP Address Plan

This is a sample VLAN and IP plan for a small office network.

## VLAN Plan

| VLAN ID | Name | Purpose | Network |
|---|---|---|---|
| 10 | USERS | Employee computers | 192.0.2.0/27 |
| 20 | SERVERS | Server connections | 198.51.100.0/27 |
| 30 | PRINTERS | Network printers | 203.0.113.0/27 |
| 99 | MANAGEMENT | Network device management | 192.0.2.64/27 |

## Sample Device IP Addresses

| Device | VLAN | IP Address |
|---|---|---|
| User PC | 10 | 192.0.2.10 |
| Windows Server | 20 | 198.51.100.10 |
| Network Printer | 30 | 203.0.113.10 |
| Cisco Switch | 99 | 192.0.2.70 |

## Things I Check

- Correct VLAN assignment
- IP address and subnet mask
- Default gateway
- Switch port status
- Trunk VLAN configuration
- Network connectivity

## Note

These IP addresses are reserved for documentation examples. This is not a production network plan.
