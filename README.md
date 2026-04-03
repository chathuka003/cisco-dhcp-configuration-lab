# DHCP Configuration Lab using Cisco Packet Tracer

## 📌 Overview

This project demonstrates the configuration of **Dynamic Host Configuration Protocol (DHCP)** using Cisco Packet Tracer. The lab focuses on automating IP address assignment within a network, reducing manual configuration, and improving network efficiency.

## 🎯 Objectives

* Understand the working principle of DHCP
* Configure a DHCP server on a Cisco device
* Assign IP addresses dynamically to client devices
* Verify and troubleshoot DHCP configuration

## 🛠️ Tools & Technologies

* Cisco Packet Tracer
* Networking concepts (IP addressing, subnetting, DHCP)

## 🧪 Lab Setup

The network topology includes:

* 1 Router (configured as DHCP server)
* 1 Switch
* Multiple PCs (DHCP clients)

## ⚙️ Configuration Steps

### 1. Configure Router Interface

* Assign IP address to the router interface
* Enable the interface

### 2. Exclude IP Addresses

* Reserve a range of IP addresses to avoid dynamic allocation

### 3. Create DHCP Pool

* Define pool name
* Configure:

  * Network address
  * Default gateway
  * DNS server

### 4. Configure Clients

* Set PCs to obtain IP address automatically

### 5. Verification

* Use commands like:

  * `ipconfig` (on PCs)
  * `show ip dhcp binding`
  * `show ip dhcp pool`

## ✅ Expected Output

* PCs should receive IP addresses automatically from the DHCP server
* Successful communication between devices

## ⚠️ Troubleshooting Tips

* Ensure interfaces are up (`no shutdown`)
* Check correct network and subnet configuration
* Verify DHCP pool settings
* Confirm clients are set to DHCP mode

## 📚 Learning Outcomes

* Practical understanding of DHCP configuration
* Hands-on experience with Cisco Packet Tracer
* Improved troubleshooting skills in networking

## 👤 Author

* Chathuka Wishmith Siriwardana

## 📄 License

This project is for educational purposes only.
