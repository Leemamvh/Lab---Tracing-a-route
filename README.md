# Lab---Tracing-a-route
The lab involves verifying network connectivity, tracing network paths using both command-line and web-based tools, and comparing geographical hops in traceroute outputs.
Objectives
Part 1: Verifying Network Connectivity Using Ping
Part 2: Tracing a Route to a Remote Server Using Traceroute
Part 3: Trace a Route to a Remote Server Using Web-Based Traceroute Tool
Background
Tracing a route will list each routing device that a packet crosses as it traverses the network from source to
destination. Route tracing is typically executed at the command line as:
tracert <destination network name or end device address>
(Microsoft Windows systems)
or
traceroute <destination network name or end device address>
(Unix and similar systems)
The traceroute (or tracert) tool is often used for network troubleshooting. By showing a list of routers
traversed, it allows the user to identify the path taken to reach a particular destination on the network or
across internetworks. Each router represents a point where one network connects to another network and
through which the data packet was forwarded. The number of routers is known as the number of "hops" the
data traveled from source to destination.
The displayed list can help identify data flow problems when trying to access a service such as a website. It
can also be useful when performing tasks such as downloading data. If there are multiple websites (mirrors)
available for the same data file, one can trace each mirror to get a good idea of which mirror would be the
fastest to use.
Two trace routes between the same source and destination conducted some time apart may produce different
results. This is due to the "meshed" nature of the interconnected networks that comprise the internet and the
Internet Protocols’ ability to select different pathways over which to send packets.
Command-line-based route tracing tools are usually embedded with the operating system of the end device.
Scenario
Using an internet connection, you will use two route tracing utilities to examine the internet pathway to
destination networks. First, you will verify connectivity to a website. Second, you will use the traceroute utility
on the Linux command line. Third, you will use a web-based traceroute tool (https://gsuite.tools/traceroute).
Required Resources
• CyberOps Workstation VM
• Internet access
