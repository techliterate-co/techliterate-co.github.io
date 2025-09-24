+++
date = '2025-09-23T14:16:46-06:00'
draft = true
title = 'Computer Networking Quiz'
linkTitle = 'Quiz'
weight = 99

[params]
  menuPre = '<i class="fa-solid fa-question"></i> '
+++

{{< quizdown >}}

---
primary_color: dodgerblue
secondary_color: lightgray
text_color: black
shuffle_questions: true
---

## What is an IP Address?

---
shuffle_answers: true
---

What is the primary function of an IP (Internet Protocol) address?

> Think of it as a unique identifier for a device on a network.

- [ ] To encrypt data sent over the internet.
- [ ] To provide power to network devices.
- [ ] To measure network speed.
- [x] To uniquely identify a device on a network.

## Dynamic vs. Static

---
shuffle_answers: true
---

What is the main difference between DHCP and a static IP address?

> Consider how the IP address is assigned to a device.

- [ ] DHCP is used for wireless connections, while static is for wired.
- [x] DHCP assigns an IP address automatically, while a static IP is manually configured.
- [ ] DHCP is more secure than a static IP.
- [ ] Static IPs change frequently, while DHCP addresses are permanent.

## Default Route

---
shuffle_answers: false
---

In computer networking, what is the purpose of a **default route**?

> It's a key concept for communication outside the local network.

- [ ] To assign IP addresses to devices.
- [ ] To act as a security firewall.
- [ ] To manage network traffic within a subnet.
- [x] To specify where to send data packets when the destination is not on the local network.

## Understanding Subnets

---
shuffle_answers: true
---

What does a **subnet** allow you to do with a large network?

> Subnets are used to break up networks into smaller, more manageable parts.

- [ ] Increase the overall speed of the network.
- [ ] Connect to the internet wirelessly.
- [x] Divide it into smaller, more efficient logical segments.
- [ ] Prevent viruses from spreading.

## Ping Command

---
shuffle_answers: true
---

What is the purpose of the `ping` command in a command-line interface?

> This command is used for testing connectivity.

- [ ] To change your IP address.
- [ ] To encrypt network traffic.
- [x] To test the reachability of a host on a network.
- [ ] To display a list of all devices connected to the network.

## A Subnet Mask

---
shuffle_answers: false
---

A subnet mask is used to determine which part of an IP address represents the network and which part represents the host.

> Think about the role of the subnet mask in network routing.

- [x] True
- [ ] False

## Network Bottleneck

---
shuffle_answers: true
---

What is a common cause of a network bottleneck?

> A bottleneck is a point of congestion in a network.

- [ ] The use of Wi-Fi instead of a wired connection.
- [x] A device with a low bandwidth capacity.
- [ ] Using a static IP address instead of DHCP.
- [ ] Having too few devices on the network.

## The Role of a Gateway

---
shuffle_answers: true
---

In a typical home network, the router often serves as the **default gateway**. What is its primary function in this role?

> It's the point of entry and exit for data to and from the internet.

- [ ] To provide power to connected devices.
- [x] To act as a path for data to leave the local network and reach other networks (like the internet).
- [ ] To assign IP addresses to all devices.
- [ ] To store data from all connected devices.

## The DHCP Process

---
shuffle_answers: true
---

Which of the following describes the correct order of the DHCP process when a device connects to a network?

> The process has four steps, often remembered by the acronym DORA.

- [ ] Discover, Offer, Request, Access
- [x] Discover, Offer, Request, Acknowledge
- [ ] Discover, Obtain, Request, Accept
- [ ] Download, Offer, Request, Acknowledge

## Network Layers

---
shuffle_answers: false
---

Which layer of the OSI model is responsible for logical addressing and routing of packets?

> This is a key layer for network-to-network communication.

- [ ] Physical Layer
- [ ] Transport Layer
- [ ] Data Link Layer
- [x] Network Layer

{{< /quizdown >}}
