#  Secure Network Design with Cisco Packet Tracer

## Introduction

For this portfolio project, my objective is to construct a secure network infrastructure using Cisco Packet Tracer. The primary focus will be on establishing the network layout, implementing authentication protocols across switches and routers, facilitating inter-VLAN communication, setting up DHCP services on the router, and fortifying switch ports against potential security breaches.
<br />
<br />

## Objectives

- Build a network topology with Cisco Packet Tracer.
- Apply authentication to switches and routers.
- Enable communication between devices in different VLANs.
- Configure DHCP on the router.
- Secure switch ports from attacks.
  <br />
<br />

## Tools and Technologies

- Cisco Packet Tracer: A network simulation tool used to design, configure, and troubleshoot network topologies.
  <br />
<br />

## Steps

### 1. Setting up Cisco Packet Tracer

- Download and install Cisco Packet Tracer from the official website.
- Launch Cisco Packet Tracer and create a new project.

<br />
  <img width="1280" alt="Capture1" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/3fd4c0c1-78fd-4ea1-8f86-054ce2244b50">

<br />
<br />

### 2. Building the Network Topology

- Open Cisco Packet Tracer and drag PCs, switches, and routers onto the workspace.
- Connect the devices using appropriate cables and arrange them in the desired topology layout.

<br />
  <img width="1280" alt="Capture" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/bbffe885-62a8-4cee-956c-783908bbd3c3">
<br />
<br />

### 3. Applying Authentication to Switches and Routers

- Configure passwords for privileged EXEC mode on switches and routers.
- Encrypt passwords using the `enable secret` command.


<br />
  <img width="1280" alt="Capture2" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/20a8fad9-a4d7-4562-842f-df2aba29613d">

<br />
<br />

  <img width="1280" alt="Capture5" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/0371ac61-b921-44f3-bb55-28971a51af67">

<br />
<br />

- Verify authentication configurations using the `show running-config` command.

  <br />
<br />

  <img width="1280" alt="Capture3" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/ae533e67-a077-45a5-9665-8cb4a879deb1">
<br />
<br />

### 4. Enabling Communication Between Devices in Different VLANs

- Configure VLANs on the switches.
- Assign IP addresses to devices in different VLANs.
- Configure trunk links between switches and routers.
- Configure subinterfaces on the router for each VLAN.
- Test communication between devices in different VLANs.

<br />
<img width="1280" alt="Capture6" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/93620694-c496-4d34-b406-48524a609c2d">
<br />
<br />
<img width="1280" alt="Capture7" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/f311fa69-b3dd-4498-a895-c70a9b423802">
<br />
<br />
<img width="1280" alt="Capture8" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/155e65ac-abf3-4869-b322-9dac89bf7984">


<br />
<br />

### 5. Configuring DHCP on the Router

- Create a DHCP pool on the router.
- Specify the IP address range and subnet mask for the DHCP pool.
- Verify DHCP configurations using the `show ip dhcp pool` command.
- Configure PCs to obtain IP addresses dynamically using DHCP.

<br />
<img width="1280" alt="Capture9" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/1cd7e566-99f5-484e-af21-1a9d1cc77bd4">
<br />
<br />

### 6. Securing Switch Ports from Attacks

- Enable port security on switch ports.
- Set maximum allowed MAC addresses per port.
- Configure violation actions to shut down ports.
- Enable sticky MAC address learning on switch ports.


<br />
<img width="1280" alt="Capture11" src="https://github.com/Pranavnathan23/Secure-Network-Design-Packet-Tracer/assets/163876627/ff76bb54-045f-4f66-81c3-3e4afbd2f17e">
<br />
<br />

### 7. Testing and Verification

- In the network testing phase, it's crucial to assess connectivity between devices by sending test packets and verifying successful communication. Additionally, DHCP functionality should be validated by reviewing 
  IP address assignments to ensure that dynamic address allocation is working as expected. Lastly, to assess the effectiveness of security measures, attempts should be made to gain unauthorized access to switch  
  ports. This helps identify any vulnerabilities and ensures that appropriate security protocols are in place to safeguard the network infrastructure.
<br />
<br />

## Conclusion

In this portfolio project, I embarked on the task of crafting a secure network infrastructure using Cisco Packet Tracer. The endeavor encompassed various pivotal stages: commencing with the setup of the network topology, establishing stringent authentication protocols, facilitating seamless inter-VLAN communication, configuring DHCP services for IP allocation, and fortifying switch ports against potential security threats. Through meticulous execution of these steps, I honed my skills in network design and security, augmenting my proficiency in Cisco technologies while ensuring the resilience of the network environment against potential vulnerabilities.
