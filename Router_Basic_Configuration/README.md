# Router Basic Configuration

## Description
This project demonstrates how to configure a router to connect two different subnets and enable communication between them.

## Network Design
- **Subnet 1**: 192.168.10.0/24
  - Router Interface: 192.168.10.1
  - Device: PC-0 (192.168.10.2)
- **Subnet 2**: 192.168.20.0/24
  - Router Interface: 192.168.20.1
  - Device: PC-1 (192.168.20.2)

## Configuration Steps
1. Configure the router interfaces:
   - `FastEthernet0/0` - 192.168.10.1
   - `FastEthernet0/1` - 192.168.20.1
2. Assign IP addresses to the PCs.
3. Test connectivity using the `ping` command.

## Testing
- Ping the router from each PC.
- Verify communication between PC-0 and PC-1.

## Expected Output
- All pings should be successful.

## Files Included
- `Router_Basic_Configuration.pkt`: The Packet Tracer file for the network setup.
