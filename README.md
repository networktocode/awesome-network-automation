# Awesome Network Automation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome about Network Automation

- [Awesome Network Automation](#awesome-network-automation)
  - [Community](#community)
  - [Training](#training)
  - [Events / Meetup](#events--meetup)
  - [Blogs](#blogs)
  - [Programming Topics](#programming-topics)
  - [Open Source Projects](#open-source-projects)
  - [Hypervisor's](#hypervisors)
  - [Backups](#backups)
  - [IPAM](#ipam)
  - [Configuration Management](#configuration-management)
  - [Books](#books)
  - [Vendor Agnostic Products](#vendor-agnostic-products)
  - [Network Vendor Products](#network-vendor-products)
  - [Podcasts](#podcasts)
  - [Contributing](#contributing)
  - [License](#license)

# Community

- [Ansible Google Groups](https://groups.google.com/forum/#!forum/ansible-project) - Welcome to Ansible's mailing list / forum!
- [IRC Ansible](http://docs.ansible.com/ansible/community.html#irc-channel) - Ansible IRC Channels
- [Network to Code Slack](http://slack.networktocode.com) - NTC Slack is the home/pseudo-home to many popular repo's (NAPALM/netmiko/netbox/nsot) and over 3000 members around Network Automation.
- [Salt Formulas](https://groups.google.com/forum/#!forum/salt-formulas) - The SaltStack formulas working group.
- [Salt Networks](https://groups.google.com/forum/#!forum/salt-networks) - The goal of this group is to have a central place to communicate goals about network device automation with SaltStack.
- [Salt Users](https://groups.google.com/forum/#!forum/salt-users) - The official forum of the Salt community.

# Events / Meetup

- [AWS Reinvent](https://reinvent.awsevents.com/) - AWS re:Invent Central is designed to facilitate connections between sponsors and attendees.
- [Ansible Fest](https://www.ansible.com/ansiblefest) - AnsibleFest is a day-long conference bringing together Ansible users, developers and industry partners to share best practices, case studies and Ansible news.
- [London Network Automation Meetup](https://www.meetup.com/London-Network-Automation-Meetup/) - A community of network engineers, who have interest in the new buzz of network automation.
- [Tech Field Day](http://techfieldday.com/) - Field Day events bring together innovative IT product vendors and independent thought leaders to share information and opinions in a presentation and discussion format.
- [SaltConf](http://saltconf.com/) - A 4 days event including two days of SaltStack customer case studies and SaltStack technical deep dives.

# Training

- [IP Space](http://www.ipspace.net/Training) - On ipSpace.net you'll find numerous courses, webinars, and videos covering SDN, network automation, cloud computing, virtualization technologies, IPv6 and VPNs.
- [Network to Code](http://networktocode.com/products/training/) - Network Automation Training including Python, Ansible, DevOps, and much more.
- [Mircea Ulinic](http://mirceaulinic.us14.list-manage1.com/subscribe?u=4d3e65e9c470a62dc341ce797&id=bd27d97b29) - Learn more about cross-vendor event-driven network automation and orchestration.
- [Python for Network Engineers](https://pynet.twb-tech.com/class.html) - You will learn skills that make you better at network automation and that improve your capability to use programming to scale your work.

# Blogs

- [cidrblock](https://cidrblock.github.io) - The Network Automation thoughts of Bradley A. Thornton
- [Coding Networker](https://codingnetworker.com) - The Network Automation thoughts of Henry Ölsner
- [Coding Packets](https://codingpackets.com) - The Network Automation thoughts of Brad Searle
- [Jason Edelman](http://www.jedelman.com/) - The Network Automation thoughts of Jason Edelman
- [IPEngineer - David Gee](http://ipengineer.net) - Network automation, software-networking and musings from David Gee
- [ipSpace.net - Ivan Pepelnjak](https://blog.ipspace.net/search/label/Automation) - Network automation blog posts by Ivan Pepelnjak
- [Mircea Ulinic](https://mirceaulinic.net/) - Random thoughts of Mircea Ulinic. May include event-driven network automation, vendor bashing or machine learning (TBD).
- [Napalm-automation](https://napalm-automation.net) - News and updates about the NAPALM project
- [Networklore](https://networklore.com/blog) - The Network Automation thoughts of Patrick Ogenstad
- [Networker and Coder](https://networkerandcoder.wordpress.com/) - The Network Automation thoughts of Csilla Bessenyei
- [Network OP](http://networkop.co.uk/) - The Network Automation thoughts of Michael Kashin
- [Packet Life](http://packetlife.net/) - The Network Automation thoughts of Jeremy Strech
- [Project 10](https://projectme10.wordpress.com) - The Network Automation thoughts of Gabriele Gerbino
- [Scott Lowe](http://blog.scottlowe.org) - The Network Automation thoughts of Scott Lowe

# Programming Topics

## Structured Data

### YAML

 - Getting Started and Basics
 - [Online Validator](http://yaml-online-parser.appspot.com/) - An Online YAML Parser
 - [Sample YAML documents describing common data structures](https://github.com/ipspace/NetOpsWorkshop/tree/master/YAML)
 - Examples

 - Advanced and Tools
   - [YAML syntax validator](https://yamllint.readthedocs.io/en/latest/)

### JSON

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

### XML

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

### YANG

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

 ### Jinja2

 - [Documentation]()
 - [Online rendering tool](http://jinja2test.tk/)
 - [Sample Jinja2 templates](https://github.com/ipspace/NetOpsWorkshop/tree/master/Jinja2)

## API

### RestConf

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

### NETCONF

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

## Python

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

## Go

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

## Vendor API Docs

 - [Arista EAPI](https://eos.arista.com/arista-eapi-101/) - The Arista Command eAPI is a simple and complete API that allows you to configure and monitor your Arista switches
 - [Cisco IOS-XR](https://www.cisco.com/c/en/us/td/docs/ios_xr_sw/iosxr_r4-1/xml/programming/guide/xl41apidoc.html) - Cisco IOS-XR API Docs only
   - [XR-Docs](https://xrdocs.github.io) - Documentation Blogs and Tutorials on all things IOS-XR An Open, Extensible and Stable Cloud-Scale Network Operating System
 - [F5](https://devcentral.f5.com/d/icontrolr-rest-api-user-guide-version-1300-241) - REST API User Guide, Version 13.0.0
 - [Infoblox](https://ipam.illinois.edu/api/doc/) - Externally hosted Infoblox API docs

# Open Source Projects

## Ansible

 - Getting Started and Basics
 - [Sample network automation Ansible playbooks](https://github.com/ipspace/ansible-examples)
 - Advanced and Tools

## Salt

 - [Napalm-Salt Repository](https://github.com/napalm-automation/napalm-salt) - The Napalm-Salt Repository
 - [Salt in 10 minutes](https://docs.saltstack.com/en/latest/topics/tutorials/walkthrough.html) - Salt in 10 minutes
 - [Salt high availability and fault tolerance](https://docs.saltstack.com/en/latest/topics/highavailability/index.html) - Salt high availability and fault tolerance
 - [Salt RIPE-74](https://ripe74.ripe.net/presentations/18-RIPE-74-Network-automation-at-scale-up-and-running-in-60-minutes.pdf) - Event-driven network automation using Salt: up and running in 60 minutes
 - [Salt 2016.11](https://docs.saltstack.com/en/develop/topics/releases/2016.11.0.html#network-automation-napalm) - Salt 2016.11 (Carbon) release notes
 - [Salt 2017.7](https://docs.saltstack.com/en/develop/topics/releases/2017.7.0.html#network-automation) - Salt 2017.7 (Nitrogen) release notes
 - [SaltStack fundamentals](https://docs.saltstack.com/en/getstarted/fundamentals/) - Getting Started Guide walks you through the fundamental concepts you need to learn as you start using SaltStack.
 - [SaltStack configuration management](https://docs.saltstack.com/en/getstarted/config/) - SaltStack Configuration Management
 - [SaltStack Network Automation](https://docs.saltstack.com/en/develop/topics/network_automation/index.html) - SaltStack Network Automation Overview
 - [Using Salt at scale](https://docs.saltstack.com/en/latest/topics/tutorials/intro_scale.html) - Using Salt at scale

## Puppet

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

## Chef

 - Getting Started and Basics
 - Examples
 - Advanced and Tools

## Products

 - [NSOT](https://github.com/dropbox/nsot) - Network Source of Truth (NSoT) a source of truth database and repository for tracking inventory and metadata of network entities to ease management and automation of network infrastructure
 - [ToDD](https://github.com/toddproject/todd) - ToDD is an extensible framework for providing natively distributed testing on demand.
 - [Nuts](https://github.com/HSRNetwork/Nuts) - Network Unit Testing System automates tests in the network similar to unit tests.
 - [Trigger](https://github.com/trigger/trigger) - Trigger is a robust network automation toolkit written in Python that was designed for interfacing with network devices and managing network configuration and security policy.
 - [pyNMS](https://github.com/afourmy/pyNMS) - pyNMS is a vendor-agnostic Network Management System for network visualization, inventory and graphical automation.
 - [Rundeck](http://rundeck.org/) - Job scheduler and runbook (and Ansible playbook) automation

## Library

 - [Capirca](https://github.com/google/capirca) - Multi-platform ACL generation system; can output Juniper/IOS/etc ACLs from the same policy
 - [ciscoconfparse](https://github.com/mpenning/ciscoconfparse) - Parse, Audit, Query, Build, and Modify Cisco IOS-style configurations
 - [Condoor](https://github.com/kstaniek/condoor) - This is a python module providing access to Cisco devices over Telnet and SSH
 - [EasySNMP](https://github.com/kamakazikamikaze/easysnmp) - Easy to use and very fast SNMP library that uses Net-SNMP
 - [JINJA2](http://jinja.pocoo.org/) - Jinja2 is a full featured template engine for Python
 - [Napalm](https://github.com/napalm-automation/napalm) - NAPALM (Network Automation and Programmability Abstraction Layer with Multivendor support) is a Python library that implements a set of functions to interact with different router vendor devices using a unified API.
 - [netaddr](https://github.com/drkjam/netaddr) - Network address manipulation that supports a number of techniques (supernetting and subnetting)
 - [Netmiko](https://github.com/ktbyers/netmiko) - Multi-vendor library to simplify Paramiko SSH connections to network devices
 - [TextFSM](https://github.com/google/textfsm) - Python module for parsing semi-structured text into python tables.

## Non-Core Ansible Modules

 - [ansible-junos-stdlib](https://github.com/Juniper/ansible-junos-stdlib) - Junos modules for Ansible
 - [ansible-mysql-query](https://github.com/zauberpony/ansible-mysql-query) - Ansible module to modify MySQL database records
 - [ara](https://github.com/openstack/ara) - Ansible Runtime Analysis
 - [Fortimanager-Ansible](https://github.com/networktocode/fortimanager-ansible) - Ansible Module to work with Fortimanager
 - [Infoblox-Ansible](https://github.com/infobloxopen/infoblox-ansible) - A new Ansible Module to work with Infoblox.
 - [Napalm-Ansible](https://github.com/napalm-automation/napalm-ansible) - Collection of ansible modules that use napalm to retrieve data or modify configuration on networking devices.
 - [Netscaler-Ansible](https://github.com/networktocode/netscaler-ansible) - Ansible Module to work with Netscalers
 - [NTC Ansible](https://github.com/networktocode/ntc-ansible) - Multi-vendor Ansible Modules for Network Automation

## Pre-written Salt States (Formulas)

 - [napalm-install-formula](https://github.com/saltstack-formulas/napalm-install-formula) - Salt formula to simplify the installation of the necessary packages and system dependencies for NAPALM.
 - [napalm-ntp-formula](https://github.com/saltstack-formulas/napalm-ntp-formula) - Formula to manage the NTP configuration on network devices, following the OpenConfig system YANG model.

## Vendor Abstraction Library

 - [clicrud](https://github.com/davidjohngee/clicrud) - Brocade specific (MLX/VDX/ICX/CER/CES) CLI driver (Telnet & SSH)
 - [f5-common-python](https://github.com/F5Networks/f5-common-python) - Python SDK for configuration and monitoring of F5 BIG-IP devices via the iControl REST API.
 - [infoblox](https://github.com/infobloxopen/infoblox-client) - Python library for Infoblox
 - [pandevice](https://github.com/PaloAltoNetworks/pandevice) - Python library for Palo Alto
 - [pyeapi](https://github.com/arista-eosplus/pyeapi) - Python library for Arista EOS
 - [pyfg](https://github.com/spotify/pyfg) - Python library for Fortinet
 - [pyiosxr](https://github.com/fooelisa/pyiosxr) - Python library for Cisco IOSXR
 - [pynxos](https://github.com/networktocode/pynxos) - Python library for Cisco NXOS
 - [py-junos-exnc](https://github.com/Juniper/py-junos-eznc) - Python library for Junos automation

## Tools

- [BGP-Dashboard](https://github.com/rhicks/bgp-dashboard) - BGP Dashboard and Monitoring Web Application
- [Drawthe.net](https://github.com/cidrblock/drawthe.net) - Draw network diagrams described in YAML files
- [napalm-logs](https://github.com/napalm-automation/napalm-logs) - Cross-vendor normalisation for network syslog messages, following the OpenConfig and IETF YANG models.
- [Net-Config](https://github.com/SLAC/net-config/) - Automation framework for network devices
- [NetCopa](https://github.com/cidrblock/netcopa) - Network device configuration parser ("industry standard" -> YAML converter)
- [NetSpark-Scripts](https://github.com/admiralspark/NetSpark-Scripts) - Netmiko-based scripts to assist the Network Administrators and Engineers of the world!
- [NetTools](https://github.com/crisponions/NetTools) - Simple network python scripts
- [Network-CI](https://github.com/networkop/network-ci) - Proof of Concept of CI/CD methodology applied to traditional non-SDN network topologies
- [NetGrph](https://github.com/yantisj/netgrph) - Network graph modeling database

# Hypervisor's

 - Docker
 - Vagrant
 - Kubernetes
 - Marathon
 - VirtualBox
 - ESX

# Backups

- [Cidr](https://github.com/renard/cidr) - Cidr Is not as Dumb as Rancid
- [Gerty](https://github.com/ssinyagin/gerty) - A universal framework for device management automation. Eventually a replacement for RANCID... and much more
- [Jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple devices, similar to rancid, fetchconfig, oxidized, Sweet.
- [Oxidized](https://github.com/ytti/oxidized) - Oxidized is a network device configuration backup tool. It's a RANCID replacement!
- [RANCID](www.shrubbery.net/rancid) - RANCID monitors a router's (or more generally a device's) configuration, including software and hardware (cards, serial numbers, etc) and uses CVS (Concurrent Version System), Subversion or Git to maintain history of changes
- [Sweet](https://github.com/AppliedTrust/sweet) - Network device configuration backups and change alerts for the 21st century - inspired by RANCID!
- [Unimus](https://unimus.net) - Configuration backup with an easy to use Web GUI. From nothing to backing-up 1000 routers in 15 minutes.

# IPAM

- [bluecat](https://www.bluecatnetworks.com/products/ip-address-management/) - BlueCat provides network intelligence and insight into the relationship between devices, users and IP addresses that can be put into action to improve security and ensure reliable, always-on business connectivity.
- [haci](http://haci.larsux.de/) - HaCi is an IP Address / Network Administration (IPAM) Tool with IPv6 support.
- [infoblox](https://www.infoblox.com/) - Industry leader in DNS, DHCP, and IP address management, the category known as DDI
- [netbox](https://github.com/digitalocean/netbox) - NetBox is an IP address management (IPAM) and data center infrastructure management (DCIM) tool.
- [nipap](http://spritelink.github.io/NIPAP/) - nipap is a sleek, intuitive and powerful IP address management system built to handle large amounts of IP addresses.
- [NSoT](https://github.com/dropbox/nsot) - Network Source of Truth is an open source IPAM and network inventory database.
- [phpipam](https://phpipam.net/) - phpipam is an open-source web IP address management application (IPAM). Its goal is to provide light, modern and useful IP address management.

# Configuration Management

- [Solarwinds](www.solarwinds.com/network-configuration-manager) - Automated network configuration and compliance management
- [ManageEngine](https://www.manageengine.com/network-configuration-manager/) - Network Configuration Manager is a multi vendor network change, configuration and compliance management (NCCCM) solution for switches, routers, firewalls and other network devices
- [Rconfig](http://www.rconfig.com/) - A free, open source network device configuration management tool, customizable to your needs!
- [Unimus](https://unimus.net) - Network-wide configuration search and config diff over time in an easy to use web GUI.

# Books

- [Ansible: Up and Running](http://shop.oreilly.com/product/0636920035626.do) - Automating Configuration Management and Deployment the Easy Way
- [Mastering Python Networking](https://www.packtpub.com/networking-and-servers/mastering-python-networking?utm_source=github&utm_medium=repository&utm_campaign=9781784397005) - Become an expert in implementing advanced, network-related tasks with Python.
- [Network Programmability and Automation](http://shop.oreilly.com/product/0636920042082.do) - Skills for the Next-Generation Network Engineer

# Vendor Agnostic Products

- [Apstra](http://www.apstra.com/products/) - The Apstra Operating System (AOS) is a vendor-agnostic distributed operating system for the data center network that enables business agility, dramatically scales operational efficiency, and reduces downtime.
- [Glue](http://gluenetworks.com/about-us-the-glue-team/) - With Gluware, the Glue Networks vision and team are continuing to trail-blaze at the forefront of the networking industry with multi-vendor orchestration solutions for Data Center, WAN and LAN networks.

# Network Vendor Products
- [Cisco Merkai](https://meraki.cisco.com/) - Cisco Meraki is the leader in cloud controlled WiFi, routing, and security. Secure and scalable, Cisco Meraki enterprise networks simply work
- [Cisco Viptela](http://viptela.com/) - Viptela provides Software-Defined Wide Area Network (SD-WAN) technology that allows global companies to build cost-effective WANs
- [Talari](https://www.talari.com/) - Talari Networks SD-WAN technology

# Podcasts

## Podcasts Feeds

- [Packet Pushers Full Stack](http://packetpushers.net/series/full-stack-journey/) - The Journey To Full Stack
- [Software Gone Wild](https://www.ipspace.net/Podcast/Software_Gone_Wild) - Software Gone Wild is focusing on architectures, solutions and technologies that real networking engineers use in production networks.

## Podcasts Episodes

- [Network Collective EPISODE 10](http://thenetworkcollective.com/2017/08/ep10-grassroots-automation/) - GRASSROOTS AUTOMATION
- [Packet Pushers Datanauts 80](http://packetpushers.net/podcast/podcasts/datanauts-080-network-automation-telemetry/) - The Current State Of Network Automation & Telemetry
- [Packet Pushers Show 176](http://packetpushers.net/podcast/podcasts/show-176-intro-to-python-automation-for-network-engineers/) - Intro to Python & Automation for Network Engineers
- [Packet Pushers Show 333](http://packetpushers.net/podcast/podcasts/show-333-orchestration-vs-automation/) - Automation & Orchestration In Networking
- [Packet Pushers Show 353](http://packetpushers.net/podcast/podcasts/show-353-business-impact-network-automation/) - The Business Impact Of Network Automation
- [Packet Pushers PQ Show 81](http://packetpushers.net/podcast/podcasts/pq-show-81-network-testing-todd/) - Network Testing With ToDD
- [Packet Pushers PQ Show 99](http://packetpushers.net/podcast/podcasts/pq-show-99-netmiko-napalm-network-automation/) - Netmiko & NAPALM For Network Automation
- [Packet Pushers PQ Show 116](http://packetpushers.net/podcast/podcasts/pq-show-116-practical-yang-network-automation/) - Practical YANG For Network Automation
- [Packet Pushers PQ Show 198](http://packetpushers.net/podcast/podcasts/show-198-kirk-byers-network-automation-python-ansible/) - Kirk Byers on Network Automation with Python & Ansible
- [Podcast__init Episode 117](https://www.podcastinit.com/napalm-with-david-barosso-and-mircea-ulinic-episode-117/) - NAPALM with David Barroso and Mircea Ulinic
- [Talk Python to me #128](https://talkpython.fm/episodes/embed_details/128) - Pythonic Networks with NAPALM

# Contributing

Contributions about network automation are most welcome!

This list is just getting started, please contribute to make it super awesome.

# License

Licensed under the Apache License, Version 2.0, see LICENSE file for more detail

