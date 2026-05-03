# Network-Connectivity-Lab
## Objective

This project involved creating a basic network topology in Cisco Packet Tracer using a Cisco 3650 switch, laptops, and a server. The goal was to configure IP addresses, MAC addresses, default gateways, test device connectivity, troubleshoot an invalid IP address issue, and verify access to a simple web server across the network.

## Skills Learned

- Built a basic network topology using Cisco Packet Tracer.
- Added and configured end devices, including laptops and a server.
- Connected devices to a Cisco 3650 switch.
- Labeled network connections and interfaces.
- Configured IP addresses, MAC addresses, subnet masks, and default gateways.
- Used `ipconfig` to verify device network settings.
- Used `ping` to test connectivity between devices.
- Troubleshot a failed ping caused by an invalid IP address.
- Configured a basic server for web access.
- Tested web connectivity using a server IP address or hostname.

## Tools Used

- Cisco Packet Tracer
- Cisco 3650 Switch
- Laptops / End Devices
- Server
- Copper Straight-Through Cable — Used for all network connections between the switch, laptops, and server.
- Fast Ethernet
- Gigabit Ethernet
- Command Prompt
- `ipconfig`
- `ping`
- Basic HTML

## Steps

### 1. Added a Cisco 3650 Switch

I started the lab by adding a Cisco 3650 switch to the topology. The switch was used as the central networking device that allowed the laptops and server to communicate with each other.


### 2. Added End Devices

Next, I added end devices to the topology. In my case, I used laptops as the main devices in the network.


### 3. Labeled the Network Connections

I labeled the connections between the devices and the switch. In my case, the connections included:

- Fast Ethernet 1
- Gigabit Ethernet 1/0/1
- Gigabit Ethernet 1/0/2

I used copper straight-through cables for all of my connections. These cables were used to connect the laptops and server to the Cisco 3650 switch.
<img width="1920" height="1009" alt="Cisco Packet Tracer 5_1_2026 6_57_40 PM" src="https://github.com/user-attachments/assets/a05ca621-c06d-4c2a-8c72-93f9e78643a8" />
Labeling the connections made the topology easier to understand and helped with troubleshooting.


### 4. Configured the First Device

I clicked on the first laptop and configured its network settings, including:

- IP address
- MAC address
- Subnet mask
- Default gateway
<img width="1009" height="700" alt="Laptop0 5_1_2026 7_06_20 PM" src="https://github.com/user-attachments/assets/580dccdd-425f-4187-abe0-89ffa68f294c" />

These settings allowed the device to communicate on the local network.


### 5. Verified the Configuration with `ipconfig`

To make sure my changes went through correctly, I opened the command prompt on the device and typed: ipconfig
This command showed the device’s IP address, subnet mask, and default gateway.
<img width="832" height="798" alt="Laptop1 5_1_2026 7_20_51 PM" src="https://github.com/user-attachments/assets/5685fd76-0d31-4911-8c1e-99935772a05d" />


### 6. Labeled IP Addresses and Subnet Masks

I labeled the IP addresses and subnet masks in the topology. This helped make the network diagram easier to read and showed which IP address belonged to each device.


### 7. Tested Connectivity Between Laptops

I used the ping command from Laptop1 to ping Laptop0. This test was used to check if the two laptops could see each other and communicate across the network.


### 8. Identified a Failed Ping
<img width="832" height="475" alt="Laptop1 5_2_2026 10_53_35 PM" src="https://github.com/user-attachments/assets/c5936e46-96b2-4c81-98dc-b041532e2a6c" />
The first ping test did not receive a reply. This happened because one of the devices had an invalid IP address.
This showed how important correct IP addressing is when configuring devices on the same network.


### 9. Fixed the IP Address Issue

After correcting the invalid IP address, I tested connectivity again. This time, the ping was successful and I received 4 replies.
<img width="832" height="475" alt="Laptop1 5_2_2026 11_01_05 PM" src="https://github.com/user-attachments/assets/01637a0b-50da-47b9-a748-a2f4f1bdc4ea" />
This confirmed that the laptops were now able to communicate with each other.


### 10. Added a Server to the Topology

After confirming laptop-to-laptop communication, I added a server to the topology and connected it to the switch.
<img width="1920" height="1009" alt="Cisco Packet Tracer 5_3_2026 4_25_04 PM" src="https://github.com/user-attachments/assets/1285901a-dc38-4ae3-b342-e11dfe6fc34c" />
The server was added so the network could support a basic web service.


### 11. Configured the Server

I configured the server’s network settings, including:
IP address
MAC address
Subnet mask
Default gateway
Then, I opened the command prompt and typed: ipconfig
This confirmed that the server’s network configuration was applied correctly.


### 12. Tested Server Connectivity

To make sure the server was properly connected to the rest of the network, I pinged Laptop0 from the server.

<img width="832" height="475" alt="Server0 5_3_2026 5_18_35 AM" src="https://github.com/user-attachments/assets/6774f1a7-053f-49a9-9131-ed273970cc87" />

A successful reply confirmed that the server was communicating with the other devices on the network.


### 13. Created a Simple Web Page

With the network devices connected and communicating, I created a simple HTML page on the server.
This allowed the server to act as a basic web server in the Cisco Packet Tracer network.
<img width="832" height="475" alt="Server0 5_3_2026 1_17_51 PM" src="https://github.com/user-attachments/assets/f1b30395-dcc6-41d9-b083-127e7c52e6f4" />


### 14. Tested Web Access from Laptop1

To test the web server, I went to Laptop1 and opened the web browser.
I access the web I could have typed either: cisco, or the server’s IP address.
This allowed me to confirm that Laptop1 could access the web page hosted on the server.
<img width="832" height="466" alt="Laptop0 5_3_2026 4_24_28 PM" src="https://github.com/user-attachments/assets/413b4427-41a7-450e-92f8-37526e4cd8b1" />


### Troubleshooting Performed

During the lab, I ran into a connectivity issue where the laptops could not communicate at first. The ping test failed because one of the devices had an invalid IP address.

After correcting the IP address, the ping test returned 4 successful replies. This confirmed that the issue was fixed and that the devices could communicate properly.

## Outcome

By completing this lab, I gained hands-on experience with building a basic network in Cisco Packet Tracer. I practiced adding devices, connecting them to a switch, configuring IP settings, verifying configurations with ipconfig, troubleshooting connectivity with ping, and testing access to a basic web server.

This project helped reinforce important networking concepts such as IP addressing, subnet masks, default gateways, switch connectivity, device communication, and basic troubleshooting.
