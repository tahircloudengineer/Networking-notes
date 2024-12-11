Hi this is just a test file
# Basic LAN Setup Using Cisco Packet Tracer

## **Objective**
This project demonstrates how to design and configure a basic Local Area Network (LAN) using Cisco Packet Tracer. The aim is to connect two PCs via a switch and verify connectivity using IP address configuration and ping commands.

---

## **Project Details**

- **Network Devices Used:**
  - 2 PCs (`PC-0` and `PC-1`)
  - 1 Switch (`Switch-0`)
- **IP Address Configuration:**
  - `PC-0`: 192.168.1.1
  - `PC-1`: 192.168.1.2
- **Subnet Mask:**
  - 255.255.255.0 (same for both PCs)

---

## **Steps to Recreate**

### **1. Design the Network**
- Open Cisco Packet Tracer.
- Drag and drop:
  - Two PCs (`PC-0` and `PC-1`).
  - One switch (`Switch-0`).
- Connect the PCs to the switch using **Copper Straight-Through Cables**.

### **2. Configure IP Addresses**
- On `PC-0`:
  - Go to `Desktop > IP Configuration`.
  - Set:
    - **IP Address:** 192.168.1.1
    - **Subnet Mask:** 255.255.255.0
- On `PC-1`:
  - Repeat the steps above, using:
    - **IP Address:** 192.168.1.2
    - **Subnet Mask:** 255.255.255.0

### **3. Test Connectivity**
- On `PC-0`:
  - Go to `Desktop > Command Prompt`.
  - Run the command: `ping 192.168.1.2`.
- You should receive a reply, indicating successful communication between the PCs.

---

## **How to Test the Project**
1. Open the `.pkt` file in Cisco Packet Tracer.
2. Use the **Command Prompt** on `PC-0` or `PC-1` to test connectivity using the `ping` command.

---

## **Files in This Project**
- `Basic_LAN.pkt`: The Cisco Packet Tracer project file.

---

## **Future Improvements**
- Extend the network to include additional PCs or routers.
- Configure dynamic IP allocation using DHCP.
- Add VLANs to segment traffic.

---

## **Credits**
This project was created for practice and learning purposes as part of my networking studies.

