[IN PROGRESS]

# Netpractice

This project is your first introduction to networking at 42 School.
You will need to solve 10 levels of network exercises and submit your solutions. During the evaluation, you’ll be asked to solve 3 random levels in front of the evaluator.

When I started this project, I studied everything related to the subject: TCP/IP, private and public networks, subnet masks, loopback addresses, switches, and more. Once I felt confident enough in my theoretical understanding, I decided to tackle the exercises.

That’s when I realized why it’s called Netpractice—because you really need to practice, my friend. Maybe you already have some networking knowledge, or perhaps you’ll find it easy. That wasn’t the case for me. Even though I thought I understood the theory, I struggled to solve the exercises without seeing how others approached them.

In this README, I’ll break down the networking theory needed to solve each exercise—so you can tackle the problems yourself. People learn in different ways, and maybe this will help someone else.

<!-- <details> <summary> So let's start! </summary>
HEYY
</details> -->


Before we start there are some concepts you need to understand: **TCP**,  **IP**, and **subnet masks**

Click here to see a video about "[How the Internet Works](https://www.youtube.com/watch?v=sMHzfigUxz4)".

### TCP: Transmission Control Protocol
Responsible for **reliable data transfer**. It achieves this by:

- Breaking information into small **packets**
- Sending them across the network
- Ensuring they arrive in the **correct order** at the destination

TCP guarantees delivery, making it essential for error-free communication.

### IP: Internet Protocol (IPv4)
There are two types of IP addresses: **IPv4** and **IPv6**. In this project, we only use **IPv4**, so this README focuses on it.

Every device connected to a network has a unique **IPv4 address**, which identifies and locates it (e.g., your computer, phone, or smart devices).

An **IPv4 address** consists of two parts:

1) **Network portion**: Identifies the network
2) **Host portion**: Identifies the specific device on that network

### TCP/IP
This combination forms the foundation of internet communication:

- **IP** handles addressing and routing.
- **TCP** ensures reliable data delivery.

Together, they use a subnet mask to separate the network and host portions of an IP address.

### Subnet Masks
A subnet mask is a **32-bit number** that:

- Divides an **IP address** into network and host sections.
- Determines which part of the **IP** belongs to the network and which identifies the device.

For example, in 192.168.1.10/24, the /24 (or subnet mask 255.255.255.0) means:

The first 24 bits represent the network.

The remaining 8 bits identify the host.


## Level 1
[image1]
