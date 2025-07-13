[5]
A. Create a Vnet, 2 Subnets Subnet-1: Linux VM, WindowsVM Subnet-2: SQL DB.
B. Create 4 VNets 1. Management Vnet (HUB) 2. Production Vnet 3. Testing Vnet 4. Developing Vnet And Configure Hub and Spoke Architecture and verify it's working by launching VM in each VNet and ping from Managemnent VM to every other VM


**✅ Task A: Create 1 VNet with 2 Subnets**
🎯 Goal:
VNet: MainVNet

Subnet-1: Host Linux & Windows VMs

Subnet-2: Host Azure SQL Database
=======================================================================================================================================

**✅ Task B: Hub and Spoke Architecture with 4 VNets**
🎯 Goal:
Management VNet → HUB

Production, Testing, Development → Spokes

Configure Peering from Hub ↔ Each Spoke

Deploy VMs in each, and test ping from Management VM
