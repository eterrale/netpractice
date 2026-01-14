*This project has been created as part of the 42 curriculum by ekeisler.*

# NetPractice

## Description 📜

**NetPractice** is a pedagogical project designed to introduce the fundamental concepts of networking. The goal of the project is to configure small-scale networks to ensure communication between specific devices.

Through a series of levels, this project helps you understand how IP addressing works, how subnets are divided, and how routing tables dictate the flow of traffic across a network. It provides a practical, visual approach to mastering TCP/IP configuration.

## Instructions 🤓

### How to Run
This project runs entirely in a web browser using a static interface. No compilation is required.

1.  Clone this repository.
2.	Download the `net_practice.1.8.tgz` from the Intra and extract it.
3.  Open `index.html` with your Chrome browser.

### Usage
* **The Interface:** The screen displays a network topology with various devices (computers, routers, switches).
* **The Goal:** You must modify the IP addresses, subnet masks, and routing tables so that the requested devices (usually Client A and Client B) can communicate.
* **Exporting:** Once a level is solved (all connection indicators turn green), you must click the "Export" button to download the configuration file for that specific level.

### Submission Requirements
To validate the project, you must solve the required levels and export their configurations.

* **File Placement:** The exported configuration files must be placed directly at the **root** of the Git repository.
* **File Count:** You must include **10 configuration files** (one for each successfully solved level). These files must not be empty.
* **Naming Convention:** Ensure the files keep their original exported names (e.g., `level1.json`, etc., depending on the project version's export format).

## Resources 💻

### Networking Concepts Studied
To complete this project, the following core networking concepts were applied:
* **TCP/IP Addressing:** Understanding IPv4 structure and notation.
* **Subnet Masks & CIDR:** Calculating network ranges and host capacities.
* **Default Gateway:** Configuring the entry point for traffic leaving the local subnet.
* **Routers & Switches:** Understanding the difference between Layer 2 (switching) and Layer 3 (routing) forwarding.
* **Routing Tables:** Defining static routes and next-hop addresses.
* **OSI Model:** With a specific focus on Layer 3 (Network).

### Useful References
* [Youtube/NetworkChuck: What is an IP address // You Suck at Subnetting series](https://www.youtube.com/watch?v=5WfiTHiU4x8&list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P&index=16)
* [Cloudflare: What is an IP address ?](https://www.cloudflare.com/learning/dns/glossary/what-is-my-ip-address/)
* [Cloudflare: What is a packet ?](https://www.cloudflare.com/learning/network-layer/what-is-a-packet/)
* [Cloudflare: What is a router ?](https://www.cloudflare.com/learning/network-layer/what-is-a-router/)
* [Cloudflare: What is routing ?](https://www.cloudflare.com/learning/network-layer/what-is-routing/)
* [Cloudflare: What is a subnet ?](https://www.cloudflare.com/learning/network-layer/what-is-a-subnet/)
* [Cloudflare: What is a network switch ?](https://www.cloudflare.com/learning/network-layer/what-is-a-network-switch/)
* [Cloudflare: What are IP & TCP ?](https://www.cloudflare.com/learning/ddos/glossary/tcp-ip/)

### AI Usage 🤖
Generative AI (e.g., ChatGPT/Claude/Perplexity) was used for the following specific tasks:
* **Concept Clarification:** Asking for analogies to understand the difference between a Switch and a Router.
* **Math Verification:** Verifying binary-to-decimal conversions for subnet masks.
* **Readme Creation** Writing this README and learning the syntax for the first time.

#networking
#42school