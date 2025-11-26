# Awesome Network Automation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Network Automation is a cross between the discipline of [Network Infrastructure](https://github.com/sindresorhus/awesome#networking) and the discipline of Programming. This list was created to serve as a one-stop shop for information related to Network Automation.

- [Awesome Network Automation ](#awesome-network-automation-)
- [Community](#community)
- [Events / Meetup](#events--meetup)
- [Training](#training)
- [Presentations](#presentations)
- [Blogs](#blogs)
- [Programming Topics](#programming-topics)
  - [Structured Data](#structured-data)
    - [YAML](#yaml)
    - [JSON](#json)
    - [XML](#xml)
    - [YANG](#yang)
    - [Jinja2](#jinja2)
  - [API](#api)
    - [RESTCONF](#restconf)
    - [NETCONF](#netconf)
  - [Python](#python)
  - [Go](#go)
  - [Vendor API Docs](#vendor-api-docs)
  - [Git](#git)
  - [RegEx](#regex)
- [Open Source Projects](#open-source-projects)
  - [Ansible](#ansible)
  - [Arista](#arista)
  - [Batfish](#batfish)
  - [Chef](#chef)
  - [Clixon](#clixon)
  - [Puppet](#puppet)
  - [Salt](#salt)
  - [StackStorm](#stackstorm)
  - [SuzieQ](#suzieq)
  - [Products](#products)
  - [Library](#library)
  - [Non-Core Ansible Modules](#non-core-ansible-modules)
  - [Pre-written Salt States (Formulas)](#pre-written-salt-states-formulas)
  - [Vendor Abstraction Library](#vendor-abstraction-library)
  - [Tools](#tools)
  - [Network Telemetry](#network-telemetry)
  - [Online Parser](#online-parser)
    - [Jinja2](#jinja2-1)
    - [TextFSM](#textfsm)
    - [TTP](#ttp)
- [Hypervisors and Containers](#hypervisors-and-containers)
- [Network Emulators](#network-emulators)
- [Network Simulators](#network-simulators)
- [Backups](#backups)
- [IPAM](#ipam)
- [Configuration Management](#configuration-management)
- [Books](#books)
- [Vendor Agnostic Products](#vendor-agnostic-products)
- [Network Vendor Products](#network-vendor-products)
- [Podcasts](#podcasts)
  - [Podcasts Feeds](#podcasts-feeds)
  - [Podcasts Episodes](#podcasts-episodes)
- [Contributing](#contributing)
- [License](#license)

# Community

- [Ansible Google Groups](https://groups.google.com/forum/#!forum/ansible-project) - Ansible's mailing list and forum!
- [IRC Ansible](https://docs.ansible.com/ansible/community.html#irc-channel) - Ansible IRC Channels.
- [Chef Community](https://community.chef.io/) - The complete offical list of Chef Community resources.
- [Network Automation Forum](https://networkautomation.forum/) - A conference focused on Network Automation.
- [Network to Code Slack](http://slack.networktocode.com) - The NTC Slack is a vendor and product agnostic home/pseudo-home to many popular Network Automation solution repositories, such as Nautobot, NAPALM, Netmiko, Nornir, NSoT, and so on. Over 17,000 members meet here to discuss topics related to Network Automation.
- [Puppet Community](https://puppet.com/community/) - The complete offical list of Puppet Community resources.
- [Salt Formulas](https://groups.google.com/forum/#!forum/salt-formulas) - The SaltStack formulas working group.
- [Salt Networks](https://groups.google.com/forum/#!forum/salt-networks) - A centralized group for talking about network device automation with SaltStack.
- [Salt Users](https://groups.google.com/forum/#!forum/salt-users) - The official forum of the Salt community.
- [SaltStack Community Slack ](https://saltstackcommunity.slack.com/) - The official Slack of Saltstack Project.

# Events / Meetup

- [AWS Reinvent](https://reinvent.awsevents.com/) - AWS re:Invent Central is designed to facilitate connections between sponsors and attendees.
- [Ansible Fest](https://www.ansible.com/ansiblefest) - AnsibleFest is a day-long conference bringing together Ansible users, developers and industry partners to share best practices, case studies and Ansible news.
- [Ansible NYC Meetup](https://www.meetup.com/Ansible-NYC/) - Local NYC Ansible user meetup.
- [Chef Summits](https://www.chef.io/summits/) - Chef community summit schedule.
- [London Network Automation Meetup](https://www.meetup.com/London-Network-Automation-Meetup/) - A community of network engineers, who have interest in the new buzz of network automation.
- [Minnesota Network User Group](https://www.meetup.com/mn-nug/) - Minnesota Network User Group, quarterly meetup of network users.
- [NANOG](https://www.nanog.org) - North American Network Operators' Group with fair share of automation presentations/discussions.
- [Network to Coders Meetup](https://www.meetup.com/Network-to-Coders/) - Maybe this can pressure NTC to finally setup an event for the 140+ NTC meetup members.
- [Puppetize Live](https://puppet.com/puppetizelive) - A 24-hour global event including community discussions, presentations, and training. Formerly PuppetConf.
- [SaltStack NYC Meetup](https://www.meetup.com/SaltStack-NYC/) - Local NYC SaltStack user meetup.
- [Tech Field Day](https://techfieldday.com/) - Field Day events bring together innovative IT product vendors and independent thought leaders to share information and opinions in a presentation and discussion format.
- [SaltConf](https://saltconf.com/) - 4 days event including two days of SaltStack customer case studies and SaltStack technical deep dives.

# Training

- [CML - Training videos @ learningnetwork.cisco.com](https://learningnetwork.cisco.com/s/cml-training-videos) - Learning and Certifications at Cisco has created a series of in-depth training videos to assist users with installing and operating Cisco Modeling Labs (CML). This video series also provides a few videos on some of the more advanced features that CML offers.
- [DevNet Academy](https://devnet-academy.com) - Self-paced e-learning with theory, exercises and quizzes for the Cisco Certified DevNet Expert exam by Luca Gubler.
- [DevNet Expert Training](https://www.devnetexperttraining.com) - Training resources targeting the Cisco Certified DevNet Expert exam topics, including bootcamp courses by Andreas Baekdahl.
- [GNS3 Academy - Instructor David Bombal](https://academy.gns3.com/courses/author/12794) - Offers an inexpensive set of introductions to Ansible and Python for Network Engineers, among other courses.
- [ipSpace.net](https://www.ipspace.net/Training) - Numerous courses, webinars, and videos covering SDN, network automation, cloud computing, virtualization technologies, IPv6, VPNs, and much more.
- [Network to Code](https://www.networktocode.com/training/) - Network Automation Training including Python, Ansible, DevOps, and much more.
- [Network Programmability Basics - Cisco](https://developer.cisco.com/video/net-prog-basics/) - Jumpstart your journey into network programmability with this expert-led video course by Cisco DevNet.
- [Nick Russo study resources](http://njrusmc.net/jobaid/jobaid.html) - Collection of DevNet certification study resources, such as study plans and Postman collections.
- [Python for Network Engineers](https://pynet.twb-tech.com/class.html) - Learn skills that make you better at network automation and that improve your capability to use programming to scale your work.

# Presentations

|            Title            |            Details            |            Year            |
|-----------------------------|-------------------------------|----------------------------|
| [Python, Go and Rust for Network Automation](https://www.youtube.com/watch?v=hx1JCsQKkns) | Claus Töpke, NANOG | 2024 |
| [Text Parsing Strategies for Network Devices](https://www.youtube.com/watch?v=3ael6w4a948) | Ruairi Carroll, DKNOG | 2023 |
| [Nautobot Overview](https://www.youtube.com/watch?v=_vq-rtTRLRk&list=PLinuRwpnsHadCKcgqwnikyMZEWZX1raMB&index=16) | Network to Code, Network Field Day 24 | 2021 |
| [Automation without Config Deployment](https://www.youtube.com/watch?v=qw6jKa7yLBQ) | Ken Celenza, NANOG | 2021 |
| [Cisco DevNet Day 2020](https://developer.cisco.com/events/devnetday20/) | Todd Nightingale (Cisco SVP/GM) | 2020 |
| [Interop Network Automation track](https://www.youtube.com/watch?v=5qTC3lZYX34&list=PLjA0bhxgryJ35D79ZRrNLMaZNaL3NAvEa) | Network to Code hosted Interop event | 2020 |
| [NetBox Day](https://www.youtube.com/watch?v=ZHH0Kjx55LM&list=PLjA0bhxgryJ3VcbLIZqY2F2QfUcdRhxZS) | Network to Code hosted event | 2020 |
| [Network Automation: The Hype vs. Reality](https://youtu.be/fFHL2o033Zc) | Jonah Kowall, NANOG | 2020 |
| [Network Automation Architecture](https://youtu.be/VlDCYmItkzE) | John Anderson, Network Field Day 21 | 2019 |
| [Network Automation Journey - Part 1](https://youtu.be/6wl2suubMIQ) | Damien Garros, Network Field Day 21 | 2019 |
| [Network Automation Journey - Part 2](https://youtu.be/u0mYDbxH5-s) | Damien Garros, Network Field Day 21 | 2019 |
| [Managing Network Device Properties as Code](https://youtu.be/dqzy7wyi1M4) | Damien Garros, NANOG 75 | 2019 |
| [Powering Your Automation: A Single Source of Truth](https://youtu.be/_ad-DUGBNiw) | Tim Schreyack, NANOG 77 | 2019 |
| [Bart Dworak AnsibleFest Keynote](https://www.ansible.com/bart-dworak-keynote-microsoft) | Bart Dworak, AnsibleFest | 2019 |
| [Greenfielding Network and Systems Automation in a Large and Highly Dynamic Public Transit Network](https://www.ansible.com/greenfielding-network-and-systems-automation-in-a-large-and-highly-dynamic-public-transit-network) | Logan Best, AnsibleFest | 2019 |
| [Using Ansible as a Catalyst for Digital Transformation](https://www.ansible.com/using-ansible-as-a-catalyst-for-digital-transformation) | Bart Dworak, AnsibleFest | 2019 |
| [Securing Network Automation](https://www.youtube.com/watch?v=EXvJMv13t3A) | Ivan Pepelnjak, Troopers [slide deck](https://www.troopers.de/downloads/troopers17/TR17_Securing_Network_Automation.pdf).  | 2017 |
| [Network automation at scale](https://www.youtube.com/watch?v=99jHvkVM0Dk) | Mircea Ulinic, NANOG 69, [slide deck](https://www.nanog.org/sites/default/files/1_Ulinic_Network_Automation_At_v1.pdf). | 2017 |
| [Experiences with network automation at Dyn](https://www.youtube.com/watch?v=a4s15nmjDkE) | Carlos Vicente, NANOG 67 | 2016 |
| [Abstract all the things](https://www.youtube.com/watch?v=Ym5kFJhCLJc) | David Barroso, SDN and Network Automation Meetup, Stockholm [presentation](https://www.dravetech.com/presos/abstraction.html). | 2016 |
| [How Facebook Learned to Stop Worrying and Love the Network](https://ripe71.ripe.net/archives/video/152/) | Jose Leitao, David Rothera, RIPE71 [slide deck](https://ripe71.ripe.net/wp-content/uploads/presentations/4-DR-NMS-ng-v2.pdf). | 2015 |
| [NAPALM](https://www.youtube.com/watch?v=93q-dHC0u0I) | David Barroso, Elisa Jasinska, NANOG 64 [slide deck](https://www.nanog.org/sites/default/files/meetings/NANOG64/1043/20150601_Jasinska_Network_Automation_And_v1.pdf). | 2015 |
| [What Is NetDevOps](https://ripe71.ripe.net/archives/video/154/) | Leslie Carr, RIPE71, [slide deck](https://ripe71.ripe.net/wp-content/uploads/presentations/54-LeslieCarr_What_is_NetDevOps_Why_RIPE71.pdf). | 2015 |


# Blogs

- [Benoît Claise blog](https://www.claise.be/) - The Network Automation thoughts of Benoît Claise.
- [Coding Packets](https://codingpackets.com/blog/) - The Network Automation thoughts of Brad Searle.
- [dravetech.com](https://www.dravetech.com) - The Network Automation thoughts of David Barroso.
- [Eric Chou - PythonicNetneg](https://blog.pythonicneteng.com/) - The Network Automation thoughts of Eric Chou.
- [IPEngineer - David Gee](http://ipengineer.net) - Network automation, software-networking and musings from David Gee.
- [ipSpace.net - Ivan Pepelnjak](https://blog.ipspace.net/tag/automation.html) - Network automation blog posts by Ivan Pepelnjak.
- [Jason Edelman](http://www.jedelman.com/) - The Network Automation thoughts of Jason Edelman.
- [Josh-V](https://josh-v.com/) - The Network Automation thoughts of Josh VanDeraa.
- [Mircea Ulinic](https://mirceaulinic.net/) - Random thoughts of Mircea Ulinic. May include event-driven network automation, vendor bashing or machine learning (TBD).
- [MTU Ninja](https://vincent.bernat.ch/en/blog#tag-network-automation) - The Network Automation thoughts of Vincent Bernat.
- [Napalm-automation](https://napalm-automation.net/blog/) - News and updates about the NAPALM project.
- [Network to Code](https://blog.networktocode.com/) - Network to Code's blog sharing thoughts, ideas, and tips all about network automation.
- [Networklore](https://networklore.com/blog) - The Network Automation thoughts of Patrick Ogenstad.
- [Network OP](https://networkop.co.uk/) - The Network Automation thoughts of Michael Kashin.
- [NWMichl Blog](https://nwmichl.net/) - The Network Automation thoughts of Michael Schön.
- [Open-Source Routing and Network Simulation - Brian Linkletter](https://www.brianlinkletter.com/) - Blog about the open-source network emulation and network simulation tools by Brian Linkletter.
- [Packet Coders](https://packetcoders.io/tag/blog) - The Network Automation thoughts of Rick Donato.
- [Packet Life](http://packetlife.net/) - The Network Automation thoughts of Jeremy Stretch.
- [Python for Network Engineers](https://pynet.twb-tech.com/blog/) - Articles on Netmiko, NAPALM, and Ansible by Kirk Byers.
- [Scott Lowe](https://blog.scottlowe.org) - The Network Automation thoughts of Scott Lowe.
- [Wim Wauters](https://blog.wimwauters.com/categories/all/) - The Network Automation thoughts of Wim Wauters.

# Programming Topics

## Structured Data

### YAML

 - [Getting Started and Basics](http://www.yaml.org/start.html) - Introduction to YAML
 - [Online Validator](https://yaml-online-parser.appspot.com/) - Online YAML Parser.
 - [Sample YAML documents describing common data structures](https://github.com/ipspace/NetOpsWorkshop/tree/master/YAML) - YAML examples courtesy of Ivan Pepelnjak.
 - [YAML Data Validation with JSON Schema](https://infrastructureascode.ch/yaml_validation.html) - Explains how JSON schema can be used to validate YAML files and how syntax highlighting can be added to the IDE for the YAML files.
 - [YAML syntax validator](https://yamllint.readthedocs.io/en/latest/) - YAML online parser.
 - [YAML idiosyncrasies](https://docs.saltstack.com/en/latest/topics/troubleshooting/yaml_idiosyncrasies.html) -- Document with the most common YAML idiosyncrasies, hosted under the SaltStack docs, but not specific to Salt or any other tool.

### JSON

 - [Awesome JSON](https://github.com/burningtree/awesome-json) - A curated list of awesome JSON libraries and resources.
 - [Getting Started and Basics](https://www.codecademy.com/courses/javascript-beginner-en-xTAfX/0/1) - JSON Basics.
 - [JSON diff](https://extendsclass.com/json-diff.html) - An online JSON diff tool.
 - [JSON 2 YAML](https://www.json2yaml.com/) - An online JSON to YAML conversion tool.

### XML

 - [XML to JSON converter online](http://www.utilities-online.info/xmltojson/) - XML to JSON and JSON to XML converter online.

### YANG

 - [Cisco Labs YANG Introduction](https://developer.cisco.com/learning/lab/intro-yang/step/1) - Introducing YANG Data Modeling for the Network.
 - [IETF RFC](https://tools.ietf.org/html/rfc6020) - The IETF RFC on YANG.
 - [YANG for dummies](https://napalm-automation.net/yang-for-dummies/) - NAPALM YANG introduction.
 - [YANG fundamentals](https://www.devnetexperttraining.com/devnet-articles/yang-fundamentals) - A walkthrough video on how to build your own YANG model.

### Jinja2

 - [Documentation](http://jinja.pocoo.org/docs/2.10/templates/) - Base documentation for Jinja2.
 - [Sample Jinja2 templates](https://github.com/ipspace/NetOpsWorkshop/tree/master/Jinja2) - Jinja examples courtesy of Ivan Pepelnjak.

## API

### RESTCONF

 - [RESTCONF requests for IOS-XE](https://www.devnetexperttraining.com/articles/restconf-operations) - How to combine HTTP path, method and payload for IOS-XE restconf operations.

### NETCONF

 - [NETCONF message layers](https://www.devnetexperttraining.com/articles/netconf-anatomy) - A view into the payload of NETCONF XML documents and layers.

## Python

 - [Awesome Python](https://github.com/vinta/awesome-python) - A curated list of awesome Python frameworks, libraries, software and resources.
 - [Learn Python the Hard Way](https://learnpythonthehardway.org) - Learn Python The Hard Way takes you from absolute zero to able to read and write basic Python, giving you the tools to understand other documentation and books about Python.
 - [Python at Codecademy](https://www.codecademy.com/learn/learn-python-3) - Learn Python by Codecademy.
 - [Python data structures](https://www.devnetexperttraining.com/articles/python-looping) - Examples on how to access data in nested structures of lists and dicts.
 - [Python Programming Guides and Tutorials - Python Central](https://pythoncentral.io/) - Experienced Python programmers and enthusiasts from around the world that are eager to share their experience.
 - [Real Python](https://www.realpython.com) - Real Python is a leading provider of online Python education. They regularly publish new articles, books, courses, and videos of basic to advanced Python concepts.

## Go

 - [Awesome Go](https://github.com/avelino/awesome-go) - A curated list of awesome Go frameworks, libraries, software and resources.
 - [Getting Started and Basics](https://tour.golang.org/welcome) - Introduction to programming with Go.
 - [JSON-to-Go](https://mholt.github.io/json-to-go/) - This tool instantly converts JSON into a Go type definition.
 - [YAML-to-Go](https://zhwt.github.io/yaml-to-go/) - This tool instantly converts YAML into a Go type definition.

## Vendor API Docs

 - [Arista EAPI](https://eos.arista.com/arista-eapi-101/) - The Arista Command eAPI is a simple and complete API that allows you to configure and monitor your Arista switches.
 - [Cisco DNA Center Platform API](https://developer.cisco.com/docs/dna-center/) - Online documentation of Cisco DNA Center Platform API.
 - [Cisco IOS XE CSR1000V](https://www.cisco.com/c/en/us/td/docs/routers/csr1000/software/restapi/restapi/RESTAPIintro.html) - Cisco IOS XE REST API Management Reference Guide.
    - [IOS-XE Programmability](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/prog/configuration/177/b_177_programmability_cg.html) - Documentation for Plug and Play, Guestshell, Python API, EEM, NETCONF, RESTCONF, gNMI/gNOI, gRPC and Application Hosting.
 - [Cisco IOS-XR](https://www.cisco.com/c/en/us/td/docs/ios_xr_sw/iosxr_r4-1/xml/programming/guide/xl41apidoc.html) - Cisco IOS-XR API Docs only.
   - [XR-Docs](https://xrdocs.github.io) - Documentation Blogs and Tutorials on all things IOS-XR An Open, Extensible and Stable Cloud-Scale Network Operating System.
   - [NX_API Coming soon]() - Coming Soon.
   - [Cisco NX-API](https://developer.cisco.com/site/nx-api/) - Main DEVNET page for NX-API docs.
 - [Checkpoint Management API](https://sc1.checkpoint.com/documents/latest/APIs/#web/) - Checkpoint Management REST API docs.
 - [Cumulus Networks HTTP API](https://docs.cumulusnetworks.com/cumulus-linux/System-Configuration/HTTP-API/) - Cumulus Networks REST API docs.
 - Extreme Networks:
   - [EXOS REST API](https://github.com/extremenetworks/EXOS_Apps/tree/master/REST) - Documentation and examples for ExtremeSwitching ExtremeXOS RESTCONF API.
   - [EXOS JSONRPC Interface](https://github.com/extremenetworks/EXOS_Apps/tree/master/JSONRPC) - Documentation and examples for ExtremeSwitching ExtremeXOS JSONRPC API.
   - [EXOS Python API](https://api.extremenetworks.com/EXOS/ProgramInterfaces/PYTHONAPI/?_ga=2.86707664.93471558.1615766490-270125121.1613692686) - Documentation for writing Python applications that run on ExtremeXOS based switches.
 - [F5](https://devcentral.f5.com/d/icontrolr-rest-api-user-guide-version-1300-241) - REST API User Guide, Version 13.0.0.
 - [Infoblox Perl API](https://demogm1.infoblox.com/api/doc/) and [Infoblox REST API](https://demogm1.infoblox.com/wapidoc/)
 - [Juniper JUNOS API](https://www.juniper.net/documentation/en_US/junos/information-products/pathway-pages/rest-api/rest-api.html) - JUNOS REST API Guide.
 - [Meraki Dashboard API](https://dashboard.meraki.com/api_docs) - Manage network environments within Meraki's cloud management tools.
   - [Meraki Dashboard API What's New](https://create.meraki.io/whats-new/) - Documentation of changes to API endpoints.
 - [Palo Alto Networks PAN-OS API](https://www.paloaltonetworks.com/documentation/80/pan-os/xml-api) - PAN-OS 8.0 XML API Reference.

 ## Git

- [Learn Git Branching](https://learngitbranching.js.org/) - Learn Git Branching helps learn Git concepts through a series of small interactive lessons in which the learner is able to actually execute the git commands inside of the shell in the browser and visually observe the results of the commands.
- [Learn Git Branching Sandbox](https://learngitbranching.js.org/?NODEMO) - This is a sandbox for practicing any git concepts you desire. Provides a shell and visual feedback of the results of your git commands.

## Regex

- [Regular Expressions 101](https://regex101.com/r/KtD6ib/1) - Regular Expressions 101 provides tools for developing and testing any regex you need in whatever language you select. A regex sandbox is provided to help you see the results of your regex.
- [W3 Schools Python RegEx](https://www.w3schools.com/python/python_regex.asp) - W3 Schools Python RegEx section is a straightforward and easy cheatsheet for developing regexes.

# Open Source Projects

## Ansible

 - [Getting Started with the ios_config Ansible Module](https://www.youtube.com/watch?v=WXLUgDmvHDI) - YouTube video by Jason Edelman of NetworkToCode introducing the ios_config Ansible module
 - [Sample network automation Ansible playbooks](https://github.com/ipspace/ansible-examples) - Ansible playbooks geared towards network engineers, courtesy of Ivan Pepelnjak.

## Arista

 - [Arista Validated Designs](https://avd.arista.com/stable/index.html) - AVD is an extensible data model that defines Arista’s Unified Cloud Network architecture as “code”.
 - [Arista Network Test Automation](https://anta.arista.com/stable/) - ANTA is a Python framework that automates tests for Arista devices.

## Batfish
 - [Home Page](https://bit.ly/2R0Mefx) - Batfish.org home page with tutorials, talks and technical papers detailing the research behind Batfish.
 - Getting Started with Batfish
    - [Documentation](https://batfish.readthedocs.io) - Getting Started Documentation for Batfish.
    - [Jupyter Notebook](https://github.com/batfish/pybatfish/tree/master/jupyter_notebooks) - Jupyter Notebooks showing how to use Batfish for configuration, ACL, routing, forwarding, etc... analysis.
    - [Video](https://www.youtube.com/playlist?list=PLUXUN_5CNTWJeMUqbUFcdi2qPnm_2mit3) - YouTube videos explaining how to use Batfish.

## Chef

 - [Using Chef Client with Cisco NX-OS](https://www.cisco.com/c/en/us/td/docs/switches/datacenter/nexus9000/sw/7-x/programmability/guide/b_Cisco_Nexus_9000_Series_NX-OS_Programmability_Guide_7x/b_Cisco_Nexus_9000_Series_NX-OS_Programmability_Guide_7x_chapter_01110.html) - Using Chef Client with Cisco NX-OS

## Clixon

 - [Clixon Home Page](https://clicon.org) - Clixon home page with links to the different projects with code and documentation.
 - [Clixon Code](https://github.com/clicon/clixon) - Clixon provides an interactive CLI, NETCONF, and RESTCONF configuration interface for a YANG-based device. 
 - [Clixon Controller Code](https://github.com/clicon/clixon-controller) - The Clixon controller is an open-source tool for network automation of devices based on NETCONF and YANG.

## Infrahub

- [Infrahub GitHub Repo](https://github.com/opsmill/infrahub) - Infrahub - A new approach to Infrastructure Management.
- [Infrahub Documentation](https://docs.infrahub.app/) - Including overview, getting started, and FAQ.

## Puppet

 - [Managing a Cisco switch with Puppet](http://www.scottyob.com/2012/12/08/my-experiences-of-managing-a-cisco-switch-with-puppet/) - My experiences of managing a Cisco switch with Puppet.

## Salt

 - [Napalm-Salt Repository](https://github.com/napalm-automation/napalm-salt) - The NAPALM-Salt Repository.
 - [salt-nornir](https://github.com/dmulyalin/salt-nornir) - proxy minion to manage network with SaltStack and Nornir using Netmiko, NAPALM, Scrapli, Ncclient, PyGNMI, PyATS based plugins to name a few.
 - [salt-sproxy](https://github.com/mirceaulinic/salt-sproxy) - Salt plugin to automate the management and configuration of (network) devices at scale, without running (Proxy) Minions.
 - [Salt in 10 minutes](https://docs.saltstack.com/en/latest/topics/tutorials/walkthrough.html) - Salt in 10 minutes.
 - [Salt high availability and fault tolerance](https://docs.saltstack.com/en/latest/topics/highavailability/index.html) - Salt high availability and fault tolerance.
 - [Salt RIPE-74](https://ripe74.ripe.net/presentations/18-RIPE-74-Network-automation-at-scale-up-and-running-in-60-minutes.pdf) - Event-driven network automation using Salt: up and running in 60 minutes.
 - [Salt 2016.11](https://docs.saltstack.com/en/develop/topics/releases/2016.11.0.html#network-automation-napalm) - Salt 2016.11 (Carbon) release notes.
 - [Salt 2017.7](https://docs.saltstack.com/en/develop/topics/releases/2017.7.0.html#network-automation) - Salt 2017.7 (Nitrogen) release notes.
 - [SaltStack fundamentals](https://docs.saltstack.com/en/getstarted/fundamentals/) - Getting Started Guide walks you through the fundamental concepts you need to learn as you start using SaltStack.
 - [SaltStack configuration management](https://docs.saltstack.com/en/getstarted/config/) - SaltStack Configuration Management.
 - [SaltStack Network Automation](https://docs.saltstack.com/en/develop/topics/network_automation/index.html) - SaltStack Network Automation Overview.
 - [Using Salt at scale](https://docs.saltstack.com/en/latest/topics/tutorials/intro_scale.html) - Using Salt at scale.

## StackStorm
 - [StackStorm Repository](https://github.com/StackStorm/st2) - StackStorm (aka "IFTTT for Ops") is event-driven automation commonly used for auto-remediation, security responses, facilitated troubleshooting, complex deployments, and more. Includes rules engine, workflow, 1800+ integrations, native ChatOps and so forth.
 - [StackStorm Installer](https://docs.stackstorm.com/install/index.html) - Ready to install StackStorm? Here’s an overview of how to get your system up and running.
 - [StackStorm Youtube](https://www.youtube.com/channel/UCColc5CuBJ8-1SnALnkDz8Q) - Various intro, marketing, interviews, and technical product talks.
 - [Stackstorm Docs](https://docs.stackstorm.com) - Documentation repository for latest version of StackStorm.
 - [StackStorm Intro on Software Gone Wild](https://blog.ipspace.net/2016/11/stackstorm-101-on-software-gone-wild.html) - SGW team talk with StackStorm (including Matt Oswalt) to discuss StackStorm.
 
 ## SuzieQ

 - [SuzieQ Documentation](https://suzieq.readthedocs.io/en/latest/) - All official documentation including project overview, quick start, configuration guide, etc.
 - [SuzieQ Repository](https://github.com/netenglabs/suzieq) - Open-source code for the SuzieQ project.
 - [SuzieQ Youtube](https://www.youtube.com/@suzieqproject7168) - Official youtube home of the SuzieQ project providing community meetups and demonstrations of the project in action.

## Products

 - [eNMS](https://github.com/afourmy/eNMS) - A vendor-agnostic NMS for carrier-grade network visualization and network automation.
 - [Nautobot](https://github.com/nautobot/nautobot) - Nautobot is a Network Source of Truth and Network Automation Platform.
 - [netpalm](https://github.com/tbotnz/netpalm) - netpalm is a ReST broker and abstraction layer for NAPALM, Netmiko, NCCLIENT or a Python Script.
 - [NSoT](https://github.com/dropbox/nsot) - Network Source of Truth (NSoT) is a source of truth database and repository for tracking inventory and metadata of network entities to ease management and automation of network infrastructure.
 - [Rundeck](https://rundeck.org/) - Job scheduler and runbook (and Ansible playbook) automation.

## Library

 - [Aerleon](https://github.com/aerleon/aerleon) - Multi-platform ACL generation system with plugin support, YAML-based config, and a Python API. Fork of Capirca.
 - [Capirca](https://github.com/google/capirca) - Multi-platform ACL generation system; can output Juniper/IOS/etc ACLs from the same policy.
 - [Cisco Genie Parsers](https://pubhub.devnetcloud.com/media/genie-feature-browser/docs/#/parsers) - Genie Parsers by Cisco
 - [ciscoconfparse](https://github.com/mpenning/ciscoconfparse) - Parse, Audit, Query, Build, and Modify Cisco IOS-style configurations.
 - [Cisco virl2_client](https://developer.cisco.com/docs/virl2-client/) - Documentation for the VIRL 2 (aka CML) API Client. Use this library to create Python scripts to interact with CML.
 - [EasySNMP](https://github.com/kamakazikamikaze/easysnmp) - Easy to use and very fast SNMP library that uses Net-SNMP.
 - [FreeZTP](https://github.com/PackeTsar/freeztp) - FreeZTP is an open-source Zero-Touch Provisioning system for Cisco IOS campus switches and routers.
 - [gNMIc](https://gnmic.kmrd.dev) - gNMI CLI client and collector.
 - [Hierarchical Configuration](https://github.com/netdevops/hier_config) - Hierarchical Configuration is a Python library that is able to take a running configuration of a network device, compare it to its intended configuration, and build the remediation steps necessary bring a device into spec with its intended configuration.
 - [inet-henge](https://github.com/codeout/inet-henge) - Generate d3.js based Network Diagram from JSON data.
 - [Jinja2](http://jinja.pocoo.org/) - A full-featured template engine for Python.
 - [NAPALM](https://github.com/napalm-automation/napalm) - NAPALM (Network Automation and Programmability Abstraction Layer with Multivendor support) is a Python library that implements a set of functions to interact with different router vendor devices using a unified API.
 - [Need To Graph](https://github.com/dmulyalin/N2G) - A library to generate diagrams in yWorks GraphML, diagrams.net/draw.io or JSON formats using structured data or show commands output.
 - [netaddr](https://github.com/drkjam/netaddr) - Network address manipulation that supports a number of techniques (supernetting and subnetting).
 - [Netmiko](https://github.com/ktbyers/netmiko) - Multi-vendor library to simplify Paramiko SSH connections to network devices.
 - [Netutils](https://github.com/networktocode/netutils) - A Python library that is a collection of functions that are used in the common network automation tasks.
 - [Nornir](https://github.com/nornir-automation/nornir) - Nornir is a pure Python automation framework intended to be used directly from Python.
 - [NUTS](https://github.com/network-unit-testing-system) - Network Unit Testing System is a Pytest plugin enabling writing network tests with YAML files.
 - [PyGNMI](https://github.com/akarneliuk/pygnmi) - Pure Python implementation of gNMI client to interact with network functions.
 - [SEC - Simple Event Correlator](https://simple-evcorr.github.io/) - SEC is an event correlation tool for advanced event processing which can be harnessed for event log monitoring, for network and security management, for fraud detection, and for any other task which involves event correlation.
 - [Template Text Parser](https://github.com/dmulyalin/ttp) - CLI tool and Python module for parsing semi-structured text into structured data. Similar syntax to Jinja templating, but in reverse. TTP Templates [collection](https://github.com/dmulyalin/ttp_templates).
 - [TextFSM](https://github.com/google/textfsm) - Python module for parsing semi-structured text into Python tables.
 - [YAPYANG](https://github.com/nomios-opensource/yapyang) - Python package that helps translate YANG data models to Python.


## Non-Core Ansible Modules

 - [ansible-junos-stdlib](https://github.com/Juniper/ansible-junos-stdlib) - Junos OS modules for Ansible.
 - [ansible-mysql-query](https://github.com/zauberpony/ansible-mysql-query) - Ansible module to modify MySQL database records.
 - [ara](https://github.com/openstack/ara) - Ansible Runtime Analysis.
 - [FortiManager-Ansible](https://github.com/networktocode/fortimanager-ansible) - Ansible module to work with FortiManager.
 - [Infoblox-Ansible](https://github.com/infobloxopen/infoblox-ansible) - Ansible module to work with Infoblox.
 - [IP Infusion OcNOS Ansible module](https://github.com/IPInfusion/OcNOS) - Ansible module, SNMP MIB files, and YANG files for OcNOS.
 - [Napalm-Ansible](https://github.com/napalm-automation/napalm-ansible) - Collection of Ansible modules that use napalm to retrieve data or modify configuration on networking devices.
 - [Netscaler-Ansible](https://github.com/networktocode/netscaler-ansible) - Ansible module to work with Netscalers.
 - [NTC Ansible](https://github.com/networktocode/ntc-ansible) - Multi-vendor Ansible modules for Network Automation.
 - [pan-os-ansible](https://github.com/PaloAltoNetworks/pan-os-ansible) - Ansible modules for working with Palo Alto Networks PAN-OS.

## Pre-written Salt States (Formulas)

 - [napalm-install-formula](https://github.com/saltstack-formulas/napalm-install-formula) - Salt formula to simplify the installation of the necessary packages and system dependencies for NAPALM.
 - [napalm-ntp-formula](https://github.com/saltstack-formulas/napalm-ntp-formula) - Formula to manage the NTP configuration on network devices, following the OpenConfig system YANG model.

## Vendor Abstraction Library

 - [clicrud](https://github.com/davidjohngee/clicrud) - Brocade specific (MLX/VDX/ICX/CER/CES) CLI driver (Telnet & SSH).
 - [cvprac](https://github.com/aristanetworks/cvprac) - Python library for Arista CVP.
 - [dnacentersdk](https://github.com/cisco-en-programmability/dnacentersdk) - Python library for Cisco DNA Center Platform API.
 - [f5-common-python](https://github.com/F5Networks/f5-common-python) - Python SDK for configuration and monitoring of F5 BIG-IP devices via the iControl REST API.
 - [Infoblox Python Module](https://github.com/infobloxopen/infoblox-client) - Python wrapper for REST API
 - [Infoblox Go Client](https://github.com/infobloxopen/infoblox-go-client) - Go wrapper for REST API
 - [pan-python](https://github.com/kevinsteves/pan-python) - Multi-tool set for Palo Alto Networks PAN-OS, Panorama, WildFire and AutoFocus.
 - [pandevice](https://github.com/PaloAltoNetworks/pan-os-python) - Device framework for interacting with Palo Alto Networks devices.
 - [pyeapi](https://github.com/arista-eosplus/pyeapi) - Python library for Arista EOS.
 - [pyfg](https://github.com/spotify/pyfg) - Python library for Fortinet.
 - [pyiosxr](https://github.com/fooelisa/pyiosxr) - Python library for Cisco IOSXR.
 - [pyntc](https://github.com/networktocode/pyntc) - Python library focused on tasks related to device level and OS management.
 - [py-junos-eznc](https://github.com/Juniper/py-junos-eznc) - Python library for Junos automation.

## Tools

- [Batfish](https://github.com/batfish/batfish) - Open-source network validation application. Multi-vendor configuration parser with a detailed modeled based simulation to analyze all aspects of network behavior (routing, forwarding, security, etc...).
- [D2](https://d2lang.com/) - Create beautiful diagrams in minutes. Simple syntax. Endlessly customizable. D2 is the fastest and easiest way to get a mental model from your head onto the screen, then make edits with your team.
- [Drawthe.net](https://github.com/cidrblock/drawthe.net) - Draw network diagrams described in YAML files.
- [IS-IS Watcher](https://github.com/Vadims06/isiswatcher) - Tracks IS-IS topology changes by establishing a GRE tunnel with network devices via a history diagram.
- [napalm-logs](https://github.com/napalm-automation/napalm-logs) - Cross-vendor normalisation for network syslog messages, following the OpenConfig and IETF YANG models.
- [Network-Conditions-Emulator](https://github.com/marty90/Network-Conditions-Emulator) - Artificially limit bandwidth, delay and loss rate on selected interfaces.
- [netconan](https://github.com/intentionet/netconan) - Network Configuration Anonymizer
- [NetCopa](https://github.com/cidrblock/netcopa) - Network device configuration parser ("industry standard" -> YAML converter).
- [NetTowel](https://github.com/InfrastructureAsCode-ch/nettowel) - Collection of useful network automation functions for the CLI.
- [OSPF Watcher](https://github.com/Vadims06/ospfwatcher) - Tracks OSPF topology changes by establishing a GRE tunnel with network devices via a history diagram.
- [Topolograph](https://github.com/Vadims06/topolograph) - Python-based Web tool for visualisation of OSPF/ISIS topologies and making a prediction of network behaviour in case of network's outage.

## Network Telemetry

- [InfluxDB](https://www.influxdata.com/) - Made for developers to build time-series-based applications quickly and at scale.
- [Prometheus](https://prometheus.io/) - Prometheus is an open-source systems monitoring and alerting toolkit originally built at SoundCloud.
- [Telegraf](https://www.influxdata.com/time-series-platform/telegraf/) - Telegraf is the open source server agent to help you collect metrics from your stacks, sensors, and systems.
- [Grafana](https://grafana.com/) - An open source observability platform.

## Online Parser

### Jinja2

 - [J2Live - TTL255](https://j2live.ttl255.com/) - Online Jinja2 parser. Additional support for Ansible and Salt filters.
 - [Jinja 101](https://jinja101.infrastructureascode.ch/) - Online Jinja2 parser with Ansible, SaltStack and Stackstorm filter support. Jinja2 environment settings can be configured.
 - [TD4a](https://td4a.codethenetwork.com/) - Advanced online rendering tool.
 - [textfsm.nornir.tech](https://textfsm.nornir.tech/) - Online development tool for Jinja2 templates and more.

### TextFSM

 - [textfsm.nornir.tech](https://textfsm.nornir.tech/) - Online development tool for TextFSM templates and more.
 - [TextFSM 101](https://textfsm101.infrastructureascode.ch/) - Simple online TextFSM parser with examples.


### TTP

 - [textfsm.nornir.tech](https://textfsm.nornir.tech/) - Online development tool for TTP templates and more.
 - [TTP 101](https://ttp101.infrastructureascode.ch/) - Simple TTP online parser with easy examples.

# Hypervisors and Containers

 - [Docker](https://www.docker.com/) - Docker is a software technology providing operating system-level virtualization also known as containers, promoted by the company Docker, Inc.
 - [KVM](https://www.linux-kvm.org/page/Main_Page) - KVM (Kernel-based Virtual Machine) is a full virtualization solution build into the Linux Kernel
 - [Proxmox](https://www.proxmox.com/en/proxmox-ve) - Proxmox is an open source virtualization platform that provides an easy web interface (and REST API) for KVM and LXC.
 - [QEMU](https://www.qemu.org/) - QEMU is a generic and open source machine emulator and virtualizer. When using KVM, QEMU can virtualize x86, server and embedded PowerPC, 64-bit POWER, S390, 32-bit and 64-bit ARM, and MIPS guests.
 - [Vagrant](https://www.vagrantup.com/) - Vagrant enables users to create and configure lightweight, reproducible, and portable development environments.
 - [VirtualBox](https://www.virtualbox.org/) - VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.
 - [Vmware ESXi](https://www.vmware.com/products/esxi-and-esx.html) - VMware ESXi is a purpose-built bare-metal hypervisor that installs directly onto a physical server.

# Network Emulators

 - [CML](https://www.cisco.com/c/en/us/products/cloud-systems-management/modeling-labs/index.html) - Cisco Modeling Labs (CML), which replaces VIRL, is a network emulator with both an API and GUI frontend.
 - [Container-Lab](https://github.com/srl-wim/container-lab) - Containerlab provides a framework for orchestrating networking labs with containers. It starts the containers, builds a virtual wiring between them to create lab topologies of users choice and manages labs lifecycle.
 - [EVE-NG](http://www.eve-ng.com/) - The Emulated Virtual Environment for Network, Security and DevOps professionals.
 - [FakeNOS](https://fakenos.github.io/fakenos/) -  Simulate network operating systems in a programmatic and easy way.


 - [GNS3](https://www.gns3.com/) - Graphical Network Simulator-3.
 - [Mininet](http://mininet.org/) - Mininet creates a realistic virtual network, running real kernel, switch and application code, on a single machine (VM, cloud or native), in seconds, with a single command.
 - [netlab](https://github.com/ipspace/netlab) - Brings infrastructure-as-code concepts to networking labs. You'll describe your high-level network topology and routing design in a YAML file, and the tools in this repository will create configs for VirtualBox/libvirt/containerlab, Ansible inventory, IPv4/v6 addressing, VLANs and VRFs, OSPF, EIGRP, IS-IS, BGP, BFD, MPLS, MPLS/VPN, VXLAN, EVPN and Segment Routing.
 - [UNetLab](https://www.routereflector.com/unetlab/) - Unified Networking Lab.
 - [VRNetLab](https://github.com/plajjan/vrnetlab) - Run your favourite virtual routers in docker for convenient labbing, development and testing.

# Network Simulators

 - [Batfish](https://github.com/batfish/batfish) - Batfish provides a model-based simulation for multi-vendor networks, that enables routing, forwarding, security, compliance, and what-if scenario analysis of a network (or proposed change to a network).
 - [Cisco WAN Automation Engine](https://www.cisco.com/c/en/us/products/routers/wae-planning/index.html) - Cisco WAE, formerly known as Cariden MATE, provides a multi-vendor network simulation that enables capacity planning and what-if scenario analysis for carrier networks.
 - [Forward Networks](https://forwardnetworks.com) - Forward Enterprise documents, searches, verifies, and predicts the behavior of your network by creating an always-accurate software copy of your entire network infrastructure for both on-prem and cloud.
 - [Juniper WANDL](https://www.juniper.net/us/en/products-services/sdn/wandl/) - Juniper WANDL provides traffic engineering
models that enable capacity planning, network optimization and what-if scenario analysis for carrier networks.
 - [SuzieQ](https://github.com/netenglabs/suzieq) - SuzieQ is a agentless, multi-vendor network observability application.

# Backups

- [Cidr](https://github.com/renard/cidr) - Cidr Is not as Dumb as Rancid.
- [fetchconfig](https://github.com/udhos/fetchconfig) - fetchconfig is a Perl script for retrieving configuration of multiple devices.
- [Gerty](https://github.com/ssinyagin/gerty) - Universal framework for device management automation. Eventually a replacement for RANCID... and much more.
- [Jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple devices, similar to rancid, fetchconfig, oxidized, Sweet.
- [Oxidized](https://github.com/ytti/oxidized) - Oxidized is a network device configuration backup tool. It's a RANCID replacement!
- [RANCID](https://www.shrubbery.net/rancid) - RANCID monitors a router's (or more generally a device's) configuration, including software and hardware (cards, serial numbers, etc) and uses CVS (Concurrent Version System), Subversion or Git to maintain history of changes.
- [Sweet](https://github.com/AppliedTrust/sweet) - Network device configuration backups and change alerts for the 21st century - inspired by RANCID!
- [Unimus](https://unimus.net) - Configuration backup with an easy to use Web GUI. From nothing to backing-up 1000 routers in 15 minutes.

# IPAM
- [bluecat](https://bluecatnetworks.com/adaptive-dns/bluecat-integrity/) - BlueCat provides network intelligence and insight into the relationship between devices, users and IP addresses that can be put into action to improve security and ensure reliable, always-on business connectivity.
- [Device42](https://www.device42.com) - Automatically maintain an up-to-date inventory of your physical, virtual, and cloud servers and containers, network components, software, services, applications, and their inter-relationships and inter-dependencies. Integrations, REST APIs and webhooks to automate your workflows with a modern CMDB as a single source of truth. Comes with powerful Data Center Infrastructure Management, IP Address Management and Application Mappings.  Mostly leverages SNMP or vendor provided APIs that are well adopted/documented.
- [Infoblox](https://www.infoblox.com/) - Industry leader in DNS, DHCP, and IP address management, the category known as DDI.
- [NetBox](https://github.com/netbox-community/netbox) - NetBox is an IP address management (IPAM) and data center infrastructure management (DCIM) tool.
- [nipap](https://spritelink.github.io/NIPAP/) - nipap is a sleek, intuitive and powerful IP address management system built to handle large amounts of IP addresses.
- [NSoT](https://github.com/dropbox/nsot) - Network Source of Truth is an open source IPAM and network inventory database.
- [phpIPAM](https://phpipam.net/) - phpIPAM is an open-source web IP address management application (IPAM). Its goal is to provide light, modern and useful IP address management.
- [TeemIP](https://sourceforge.net/projects/teemip/) - TeemIp is an open source, WEB based, IP Adress Management (IPAM) tool that provides comprehensive IP Management capabilities. It allows you to manage your IPv4 and IPv6 spaces through a simple and powerful user interface: track user requests, discover and allocate IPs, manage your IP plan and your subnet space in accordance with best in class IP Management practices.

# Configuration Management
- [Jerikan](https://github.com/jerikan-network/cmdb) - Network wide CMDB combining single source of truth in YAML, configs in Jinja2 and deployment with Ansible.
- [ManageEngine](https://www.manageengine.com/network-configuration-manager/) - Network Configuration Manager is a multi vendor network change, configuration and compliance management (NCCCM) solution for switches, routers, firewalls and other network devices.
- [NetMRI](https://www.infoblox.com/products/netmri/) - Vendor Agnostic NCCM tool with with policy engine and multi-vendor device lifecycle/vulnerability management. (Infoblox product)
- [Rconfig](https://www.rconfig.com/) - Free, open source network device configuration management tool, customizable to your needs!
- [Solarwinds](https://www.solarwinds.com/network-configuration-manager) - Automated network configuration and compliance management.
- [Unimus](https://unimus.net) - Network-wide configuration search and config diff over time in an easy to use web GUI.

# Books

- [Ansible for DevOps](https://www.ansiblefordevops.com/) - Learn Ansible concepts from an industry leading Ansible expert, with associated Vagrant files for ease of learning
- [Ansible: Up and Running](https://shop.oreilly.com/product/0636920035626.do) - Automating Configuration Management and Deployment the Easy Way.
- [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) - Automate the Boring Stuff with Python is an excellent introduction to programming concepts with a focus on Python. The concepts are made easier to learn by practicing them with hands on real world examples and projects.
- [Cloud Native Data Center Networking](https://www.oreilly.com/library/view/cloud-native-data/9781492045595/) - If you want to study, build, or simply validate your thinking about modern cloud native data center networks, this is your book. Whether you’re pursuing a multitenant private cloud, a network for running machine learning, or an enterprise data center, author Dinesh Dutt takes you through the steps necessary to design a data center that’s affordable, high capacity, easy to manage, agile, and reliable.
- [Effective DevOps](https://www.amazon.com/Effective-DevOps-Building-Collaboration-Affinity/dp/1491926309/) - Learn cultural and organizational best practices on how to make a good DevOps team
- [Git Pocket Guide](http://chimera.labs.oreilly.com/books/1230000000561) - This pocket guide is the perfect on-the-job companion to Git, the distributed version control system. It provides a compact, readable introduction to Git for new users, as well as a reference to common commands and procedures for those of you with Git experience.
- [Infrastructure as Code](https://www.amazon.com/Infrastructure-Code-Managing-Servers-Cloud/dp/1491924357) - Learn the Infra as Code principles and design patterns (examples are for Compute not network though)
- [Mastering Python Networking Second Edition (August 2018)](https://amzn.to/2PkMRiZ), [First Edition (June 2017 with more SDN-related topics)](https://amzn.to/2NBjlVM) - Become an expert in implementing advanced, network-related tasks with Python.
- [Network Programmability and Automation](https://shop.oreilly.com/product/0636920042082.do) - Skills for the Next-Generation Network Engineer.
- [Network Programmability with YANG](https://www.oreilly.com/library/view/network-programmability-with/9780135180471/) - The Structure of Network Automation with YANG, NETCONF, RESTCONF, and gNMI.
- [Network Automation at Scale](https://www.oreilly.com/webops-perf/free/network-automation-at-scale.csp) - An introduction and practical look at using Salt to automate your network at scale, in a free ebook from O'Reilly.
- [Open Source Network Management](https://leanpub.com/opensourcenetworkmanagement/) - Step by step guide for getting started with Open Source Network Management tools such as Nautobot, Hashicorp Vault, Telegraf, and Prometheus.
- [Site Reliability Engineering and The Site Reliability Workbook](https://landing.google.com/sre/book.html) - Learn concepts of automating and operating at scale from Google experts.
- [Seeking SRE: Conversations About Running Production Systems at Scale](https://www.amazon.com/Seeking-SRE-Conversations-Running-Production/dp/1491978864) - Learn from the best practices of SRE practitioners who are not working at Google.
- [The DevOps Handbook](https://itrevolution.com/book/the-devops-handbook/) - Learn the concepts of Agile and DevOps principles.
- [The Phoenix Project](https://itrevolution.com/book/the-phoenix-project/) - See the concepts of Agile and DevOps in this fiction story about a typical IT Org.
- [The Unicorn Project](https://itrevolution.com/the-unicorn-project/) - See the concepts of Agile and DevOps following a Developer viewpoint.

# Vendor Agnostic Products
- [Anuta Networks ATOM](https://www.anutanetworks.com/anuta-atom-overview/) - Monitoring & Closed-Loop Automation for Multi-Vendor Networks.
- [Apstra](https://www.apstra.com/products/) - The Apstra Operating System (AOS) is a vendor-agnostic distributed operating system for the data center network that enables business agility, dramatically scales operational efficiency, and reduces downtime.
- [Cisco NSO](https://cisco.com/go/nso) - NSO (former Tail-f NCS) is a multi-vendor automation and orchestration platform for physical and virtual networks for over 80+ vendors. NSO provides YANG-based programmability through a wide variety of interfaces including CLI, RESTCONF, NETCONF, Java, Python and web UI.
 - [Forward Networks](https://forwardnetworks.com) - Forward Enterprise documents, searches, verifies, and predicts the behavior of your network by creating an always-accurate software copy of your entire network infrastructure for both on-prem and cloud.
- [Glue](http://gluenetworks.com/about-us-the-glue-team/) - With Gluware, the Glue Networks vision and team are continuing to trail-blaze at the forefront of the networking industry with multi-vendor orchestration solutions for Data Center, WAN and LAN networks.
- [Intentionet](https://www.intentionet.com/) - Intentionet provides a hosted or on-premise network validation software solution based on [Batfish](http://www.batfish.org). Intentionet Sage's model-based network simulation enables pre-commit validation for all network changes, ensuring only correct changes are pushed to the network, thereby reducing outages and breaches while improving network agility.
- [IP Fabric](https://ipfabric.io/) - Network assurance tool with vendor agnostic network discovery, inventory, modelling and mapping of on-prem and cloud networks.  Snapshots create a point-in-time view to verify that network behaves as intended after changes. GUI supports your network documentation with accurate, live network representation, and API used to keep all your SoT, automation tooling and monitoring up to date.
- [NetMRI](https://www.infoblox.com/products/netmri/) - Vendor Agnostic NCCM tool with with policy engine and multi-vendor device lifecycle/vulnerability management. (Infoblox product)
- [NetYCE](https://netyce.com/) NetYCE lets you be in control of any and all of your networks, using its unique Design Driven Networking approach. Not stopping at network devices, but orchestrate end-to-end including firewalls, DDI (DNS, DHCP, IPAM) and other 3rd party tooling. Deploy your networks as Designed.
- [PacketFront](https://pfsw.com/) - PacketFront BECS and BBE is a vendor-agnostic network, service and resource orchestration system for residential, enterprise and data center networks.
- [SuzieQ Enterprise Edition](https://stardustsystems.net) - The enterprise edition of the [suzieq](#suzieq) open source project.

# Network Vendor Products

- [Arista CloudVision](https://www.arista.com/en/products/eos/eos-cloudvision) - CloudVision is Arista’s modern, multi-domain management platform that leverages cloud networking principles to deliver a simplified NetOps experience.
- [Cisco DNA Center](https://developer.cisco.com/dnacenter/) - Cisco DNA Center automates campus networks for faster workflows, faster troubleshooting through more visibility, and policy-driven security (inc. [SDA](https://www.cisco.com/c/en/us/solutions/enterprise-networks/software-defined-access/index.html)).
- [Cisco Meraki](https://meraki.cisco.com/) - Cisco Meraki is the leader in cloud controlled WiFi, routing, and security. Secure and scalable, Cisco Meraki enterprise networks simply work.
- [Cisco Viptela](http://viptela.com/) - Viptela provides Software-Defined Wide Area Network (SD-WAN) technology that allows global companies to build cost-effective WANs.
- [Cumulus Networks NetQ](https://cumulusnetworks.com/products/netq/) - Cumulus NetQ is a highly-scalable, modern network operations tool set that provides visibility into your overlay and underlay networks in real-time. NetQ delivers actionable insights and operational intelligence about the health of your data center — from the container, virtual machine, or host, all the way to the switch and port, enabling a NetDevOps approach.
- [Oracle Talari](https://www.oracle.com/industries/communications/enterprise-communications/products/talari-platforms.html) - Talari Networks SD-WAN technology.

# Podcasts

## Podcasts Feeds

- [Network to Code](https://networkcollective.com/category/episodes/network-to-code/) - Network to Code automation podcast on the Network Collective feed.
- [Packet Pushers Full Stack](https://packetpushers.net/series/full-stack-journey/) - The Journey To Full Stack.
- [Software Gone Wild](https://www.ipspace.net/Podcast/Software_Gone_Wild) - Software Gone Wild is focusing on architectures, solutions and technologies that real networking engineers use in production networks.

## Podcasts Episodes

- [Network Collective EPISODE 10](https://thenetworkcollective.com/2017/08/ep10-grassroots-automation/) - GRASSROOTS AUTOMATION.
- [Network Collective Infrastructure as Code 101](https://networkcollective.com/2019/09/infrastructure-as-code/) Introduction to Infrastructure as Code with Damien Garros and Ken Celenza.
- [Packet Pushers Datanauts 80](https://packetpushers.net/podcast/podcasts/datanauts-080-network-automation-telemetry/) - The Current State Of Network Automation & Telemetry.
- [Packet Pushers Day Two Cloud 043](https://packetpushers.net/podcast/day-two-cloud-043-git-for-ops-people/) - Git For Ops People with Damien Garros.
- [Packet Pushers Heavy Networking #445](https://packetpushers.net/podcast/heavy-networking-445-an-introduction-to-the-nornir-automation-framework/) - David Barroso, Kirk Byers, and Dmitri Figol on Nornir.
- [Packet Pushers Heavy Networking #498](https://packetpushers.net/podcast/heavy-networking-498-creating-a-single-source-of-truth-for-network-automation/) - Creating A Single Source Of Truth For Network Automation with Tim Schreyack.
- [Packet Pushers PQ Show 81](https://packetpushers.net/podcast/podcasts/pq-show-81-network-testing-todd/) - Network Testing With ToDD.
- [Packet Pushers PQ Show 99](https://packetpushers.net/podcast/podcasts/pq-show-99-netmiko-napalm-network-automation/) - Netmiko & NAPALM For Network Automation.
- [Packet Pushers PQ Show 116](https://packetpushers.net/podcast/podcasts/pq-show-116-practical-yang-network-automation/) - Practical YANG For Network Automation.
- [Packet Pushers PQ Show 135](https://packetpushers.net/podcast/podcasts/pq-135-mastering-python-networking-book/) - Mastering Python Networking – The Book.
- [Packet Pushers PQ Show 198](https://packetpushers.net/podcast/podcasts/show-198-kirk-byers-network-automation-python-ansible/) - Kirk Byers on Network Automation with Python & Ansible.
- [Packet Pushers Show 176](https://packetpushers.net/podcast/podcasts/show-176-intro-to-python-automation-for-network-engineers/) - Intro to Python & Automation for Network Engineers.
- [Packet Pushers Show 333](https://packetpushers.net/podcast/podcasts/show-333-orchestration-vs-automation/) - Automation & Orchestration In Networking.
- [Packet Pushers Show 351](https://packetpushers.net/podcast/podcasts/show-351-design-build-13-network-orchestration-salt/) -  Design & Build 13: Network Orchestration with Salt.
- [Packet Pushers Show 353](https://packetpushers.net/podcast/podcasts/show-353-business-impact-network-automation/) - The Business Impact Of Network Automation.
- [Packet Pushers Show 368](https://packetpushers.net/podcast/podcasts/show-368-radical-change-devops-automation/) - Show 368: Radical Change, DevOps & Automation.
- [Packet Pushers Show 402](https://packetpushers.net/podcast/weekly-show-402-building-a-network-automation-framework/) - Show 402 - Building A Network Automation Framework
- [Packet Pushers Show 532](https://packetpushers.net/podcast/heavy-networking-532-scrapli-is-a-netmiko-alternative/) - Scrapli Is A Netmiko Alternative - Show 532 with Carl Montanari and Dmitry Figol.
- [Packet Pushers Show 537](https://packetpushers.net/ansible-or-terraform-choose-one/) - Ansible Or Terraform: Choose One with Josh VanDeraa and Ned Bellavance.
- [Podcast__init Episode 117](https://www.podcastinit.com/napalm-with-david-barosso-and-mircea-ulinic-episode-117/) - NAPALM with David Barroso and Mircea Ulinic.
- [Podcast__init Episode 232](https://www.pythonpodcast.com/enms-network-automation-episode-232/) - Network Automation At Enterprise Scale With Python - Episode 232 with Antoine Fourmy.
- [Talk Python to me #128](https://talkpython.fm/episodes/embed_details/128) - Pythonic Networks with NAPALM.
- [Talk Python to me #175](https://talkpython.fm/episodes/show/175/teaching-python-to-network-engineers) - Teaching Python to network engineers

# Contributing

Contributions about network automation are most welcome!

This list is just getting started, please contribute to make it super awesome.

# License

[![CC4](https://mirrors.creativecommons.org/presskit/cc.srr.primary.svg)](https://creativecommons.org/licenses/by/4.0/legalcode)

Licensed under the Creative Commons 4.0 License, see LICENSE file for more detail.
