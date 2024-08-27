# Creating a Basic LAN

## Goal:
In this activity, you will create a simple local area network (LAN) by adding devices, cabling them up, assigning IP addresses, and testing connectivity.

## Instructions:

### 1. Create the Network:
Create the network displayed in **Figure 1**. Make sure that the device models and names match the ones in the diagram.

<br />

<P align="center">
<img src="https://github.com/user-attachments/assets/541bdb3a-0c26-46ad-a6f9-f68830bd19a6" height="100%" width="100%" alt="" />
</P>

<br />

*In this step, I set up the network according to **Figure 1**. I made sure that each device model and name matched the diagram to ensure a proper setup.*

<br />

<P align="center">
<img src="https://github.com/user-attachments/assets/22c6ec2f-48a0-4b18-bf61-d0c59a047430" height="100%" width="100%" alt="" />
</P>

<br />

### 2. Refer to Connection Table:
Before connecting the cables, refer to **Connection Table 1** that specifies how to make the connections.

*Next, I consulted **Connection Table 1** to correctly establish the connections between each device and the switch. This ensured that all devices were properly linked.*

| From Device | Interface          | To Device | Interface          |
|-------------|--------------------|-----------|--------------------| 
| Switch0     | GigabitEthernet0/1 | Switch1   | GigabitEthernet0/1 |
| PC0         | Ethernet           | Switch0   | FastEthernet0/1    |
| PC1         | Ethernet           | Switch0   | FastEthernet0/2    |
| PC2         | Ethernet           | Switch1   | FastEthernet0/1    |
| PC3         | Ethernet           | Switch2   | FastEthernet0/2    |

*Connection Table 1: Device Connections*

<br />

<P align="center">
<img src="https://github.com/user-attachments/assets/e92b2590-5750-467f-a11b-4442c0ed4ca4" height="100%" width="100%" alt="" />
</P>


### 3. Assign IP Addresses:
Click on each PC, select the **Desktop** tab, and the **IP Configuration** applet. Assign IP addresses to the PCs as specified in **Table 2**. Close the IP Configuration applet when you are done.

*I then assigned IP addresses to each PC by accessing the **IP Configuration** applet. I used **Table 2** to input the correct IP addresses for each device.*

| Computer | IP Address     |  Subnet Mask |
|----------|----------------| -------------|
| PC0      | 192.168.1.1    | 255.255.255.0|
| PC1      | 192.168.1.2    | 255.255.255.0|
| PC2      | 192.168.1.3    | 255.255.255.0|
| PC3      | 192.168.1.4    | 255.255.255.0|

*Table 2: IP Address Assignments*
<br />

<P align="center">
<img src="https://github.com/user-attachments/assets/01fba140-27b0-4e64-bb35-2a3367b05afe" height="100%" width="100%" alt="" />
</P>

<P align="center">
<img src="https://github.com/user-attachments/assets/a8e6540d-1716-44fd-831c-8bc73bcbc713" height="100%" width="100%" alt="" />
</P>

<P align="center">
<img src="https://github.com/user-attachments/assets/1e60009c-662b-4475-907b-5211adbfea08" height="100%" width="100%" alt="" />
</P>

<P align="center">
<img src="https://github.com/user-attachments/assets/ae346254-cfd3-4cc5-9111-59f1cd29712d" height="100%" width="100%" alt="" />
</P>

<br />


> **Note:** For this activity, you do not need to provide an IP address for the Default Gateway or DNS Server.

### 4. Test Connectivity:

*Finally, I tested the network connectivity by using the **Command Prompt** on **PC0**. I pinged PC1, PC2, and PC3 to verify that all devices could communicate with each other.*

<P align="center">
<img src="https://github.com/user-attachments/assets/1402f3fc-6ead-40ad-b1d7-4d90620dd0c4" height="100%" width="100%" alt="" />
</P>



