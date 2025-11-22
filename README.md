# 🛰️ Data Center Interconnection Using BGP with EVE-NG

This repository contains a simulation of **interconnected data centers using Border Gateway Protocol (BGP)** across three different Autonomous Systems (AS).  
The project uses **Cisco 7206 routers** running inside **EVE-NG**.

## 📘 Overview
This project aims to understand how BGP can be implemented in data center interconnection to achieve efficient and scalable routing between multiple Autonomous Systems (AS).

The topology consists of **five routers**, divided into **three data centers**:
- **Data Center 1:** Router 1 (RTR-AS100-DC1)
- **Data Center 2:** Router 2, 3, 4 (RTR-1-AS200-DC2, RTR-2-AS200-DC2, RTR-3-AS200-DC2)
- **Data Center 3:** Router 5 (RTR-AS300-DC3)

Simulation is performed using **EVE-NG Community Edition** with **Cisco IOS 7206VXR** virtual routers.

## ⚙️ Configuration Summary
Each router is configured with:
- Loopback interfaces for Router-ID and BGP Prefix advertisement
- OSPF for internal routing within AS200
- BGP for inter-AS communication
- IPv4 addressing only

## 🧩 Tools Used
- VMware Workstation Pro 17  
- EVE-NG Community Edition v6.0.1-12  
- WinSCP, PuTTY, and Windows Client Pack  

## 🧠 Key Learning Outcomes
- Implementation of iBGP and eBGP in multi-AS topology
- Router configuration for data center interconnection
- Verifying connectivity through ping and BGP table inspection

## 📂 Repository Structure
