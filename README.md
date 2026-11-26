# netpractice

> Ten hands-on levels of **TCP/IP networking**: IP addressing, subnet masks, routing and getting small networks to talk to each other.

![Networking](https://img.shields.io/badge/topic-TCP%2FIP-0A66C2?style=flat)

## About

NetPractice is a set of exercises in a browser-based simulator. Each level shows a broken network of hosts,
switches and routers, and the goal is to fill in the missing IP addresses, masks and routes so that
every required connection works. No code, just networking fundamentals.

## Topics covered

- IPv4 addresses and the difference between network, host and broadcast addresses
- subnet masks and CIDR notation (`/24`, `/30`, ...), splitting networks into subnets
- public vs. private address ranges
- switches vs. routers, default gateways and routing tables
- the special case of reaching the internet from a private network

## Contents

[`level1.json`](level1.json) … [`level10.json`](level10.json) are the saved solutions exported from the simulator.
They can be loaded back into the NetPractice training interface with its import option.

---

<sub>Part of the <a href="https://www.codam.nl/">Codam</a> (42 network) curriculum.</sub>
