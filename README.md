# Awesome-SmartGrid: A curated list of awesome Smart Grid and IoT frameworks, libraries, and software

## Tools & Platforms
* [Power System Block](https://www.powsybl.org), [GitHub](https://github.com/powsybl) The open source set of Power System Blocks in Java, dedicated to grid analysis and simulation
* [Matpower](https://matpower.org) Free, open-source tools for electric power system simulation and optimization for MATLAB and Octave
* [FUXA](https://github.com/frangoteam/FUXA) Web-based Process Visualization (SCADA/HMI/Dashboard) software
* [GridAPPSD](https://github.com/GRIDAPPSD) GridAPPS-D’s visualization application displays the topology of selected distribution model with highlighted capacitors and regulators.
* [LF Energy](https://www.lfenergy.org) is an open source foundation focused on the power systems sector, hosted within The Linux Foundation.
* [Dynaωo](https://dynawo.github.io) is an hybrid C++/Modelica open source suite of simulation tools for power systems.
* [SmartGrid](https://www.smartgrid.gov) Department of Energy's Advanced Grid Research and Development activities accelerate discovery and innovation in electric transmission and distribution technologies and create "next generation" devices, software, tools, and techniques to help modernize the electric grid.
* [Fledge IoT](https://github.com/fledge-iot) An open source platform for the Industrial Internet of Things, it acts as an edge gateway between sensor devices and cloud storage systems.
* [FledgePower](https://github.com/fledge-power) FledgePower is a multi-protocol translation gateway for power systems based on the industrial IoT LF Edge project Fledge.
* [OpenDSS](https://www.epri.com/pages/sa/opendss), [GitHub](https://github.com/tshort/OpenDSS) is an electric power distribution system simulator (DSS) designed to support distributed energy resource (DER) grid integration and grid modernization.
* [DNET](https://github.com/takemaru/dnet) Distribution Network Evaluation Tool is an analysis tool that works with power distribution networks for efficient and stable operation such as loss minimization and verification.
* [FLISR](https://github.com/PVKonovalov/flisr) Fault Location, Isolation, and Service Restoration service can automate power restoration in seconds, automatically isolating faults and restoring power to disconnected feeders.
* [Open SCADA/DMS](https://github.com/robidev/open_scada_dms) An open source project for a basic ems/dms scada system.
* [GElectrical](https://github.com/manuvarkey/GElectrical) is a free and opensource electrical system analysis software for LV/MV electrical distribution networks.
* [SOGNO](https://github.com/sogno-platform) The LF Energy project Service-based Open-source Grid automation platform for Network Operation.
* [Openremote](https://github.com/openremote/openremote) 100% open-source IoT Platform - Integrate your devices, create rules, and analyse and visualise your data.
* [PMU Connection Tester](https://github.com/GridProtectionAlliance/PMUConnectionTester) is an application used to validate, test and trouble‐shoot connections and data streams from phasor measurement (IEEE C37.118.2) devices as well as graphically visualize their synchophasor data in real‐time.

## Frameworks and libraries
* [GridCal](https://www.advancedgridinsights.com/gridcal), [GitHub](https://github.com/SanPen/GridCal) A cross-platform power systems solver written in Python with user interface and embedded python console.
* [Pandapower GitHub](https://github.com/e2nIEE/pandapower), [Pandapower site](https://www.pandapower.org) Convenient Power System Modelling and Analysis based on PYPOWER and pandas.
* [TopoGrid](https://github.com/PVKonovalov/topogrid) Package topogrid contains implementations of basic power grid algorithms based on the grid topology.
* [Power Grid Model](https://github.com/PowerGridModel) Python/C++ library for distribution power system analysis.
* [PyPSA](https://github.com/PyPSA/PyPSA) Python for Power System Analysis.

## Industrial protocols
### DNP-3
* [OSS related](https://github.com/dnp3) to the DNP3 protocol
* [Rust implementation](https://github.com/stepfunc/dnp3) of DNP3 (IEEE 1815) with idiomatic bindings for C, .NET, C++, and Java.
### MQTT
* [paho.mqtt.golang](https://github.com/eclipse/paho.mqtt.golang) Golang MQTT library.
* [EMQX](https://www.emqx.com/en/downloads-and-install/broker) The most popular open source MQTT broker with a high-performance real-time message processing engine, powering event streaming for IoT devices at massive scale.
### SNMP
* [GoSMNP](https://github.com/gosnmp/gosnmp) GoSNMP is an SNMP client library fully written in Go. 
* [GoSNMPServer](https://github.com/slayercat/GoSNMPServer) SNMP server library fully written in Go.
* [Python SNMP MIB browser](https://github.com/markkuleinio/python-snmp-mib-browser) Small program to show MIB file OIDs in a list.
### Modbus (Yes it's still alive)
* [GoModbus](https://github.com/grid-x/modbus) Fault-tolerant, fail-fast implementation of Modbus protocol in Go.
* [Modbus](https://github.com/stephane/libmodbus) A Modbus library for Linux, Mac OS, FreeBSD and Windows
* [Rust implementation](https://github.com/stepfunc/rodbus) of Modbus with idiomatic bindings for C, C++, .NET, and Java.
* [M31config](https://github.com/PVKonovalov/m31config) Console application for configuration M31-AAAX4440G Modbus module
### OPC UA
* [GoOPCUA](https://github.com/gopcua/opcua) A native Go implementation of the OPC/UA client library.
* [open62541](https://github.com/open62541/open62541) Open source implementation of OPC UA (OPC Unified Architecture) aka IEC 62541 licensed under Mozilla Public License v2.0
* [OPC UA](https://reference.opcfoundation.org) Online reference
### IEC 60870
* [EC 60870-5-104 simulator](https://github.com/FreyrSCADA/IEC-60870-5-104) RTU Server Simulator, Master Client Simulator, Windows and Linux POSIX ARM, IEC104 Source Code in C, C++, C# .NET Programming
* [IEC 60870](https://github.com/mz-automation/lib60870) Official repository for lib60870 an implementation of the IEC 60870-5-101/104 protocol
* [Control commands](https://github.com/PVKonovalov/iec104_client_control) testing tool.
### IEC 61850
* [IEC 61850](https://github.com/mz-automation/libiec61850) Official repository for libIEC61850, the open-source library for the IEC 61850 protocols
* [GoLang IEC61850 library](https://github.com/wendy512/iec61850) Cgo version of IEC 61850 library, reference [libiec61850](https://github.com/mz-automation/libiec61850)
* [IEC 61850 open server](https://github.com/robidev/iec61850_open_server) An open source implementation of an IEC61850 IED using lib61850
* [IEC61850bean](https://github.com/beanit/iec61850bean) Java IEC 61850 MMS stack for clients and servers.
* [Fuzzy IEC61850 Simulator](https://github.com/st-ing/61850-sim) This simulator is a helpful tool that can be used for testing of various IED integration scenarios.
* [Open Substation Communication Designer](https://github.com/openscd/open-scd) A substation configuration description editor for projects using SCL IEC 61850-6 Edition 2 or greater
* [News on IEC 61850 and related Standards](https://blog.nettedautomation.com) IEC 61850, IEC 61400-25, IEC 61970 (CIM), IEC 60870-5, DNP3, IEC 62351 (Security), ...
* [IEDExplorer](https://sourceforge.net/projects/iedexplorer) EDExplorer is an IEC 61850 client tool written for testing and educational purposes (Windows/Linux Mono)
* [CoMPAS](https://github.com/com-pas)  - (Co)nfiguration (M)odules for (P)ower industry (A)utomation (S)ystems. This project is to develop open source software components related to IEC 61850 model.

## Single Line Diagram editors
* [QElectroTech](https://qelectrotech.org) is a free software to create electric diagrams.

## Common Information Model - CIM
* [CIMDraw](https://github.com/danielePala/CIMDraw) is a Web application to view IEC CIM files. Editing is also possible, with some limitations.
* [CIMpy](https://github.com/sogno-platform/cimpy) Import and export CGMES/CIM IEC-61970 files in the XML/RDF format
* [CimBios.Core](https://github.com/Cimbios/CimBios.Core) DotNET library designed for reading, writing, and editing models in the CIM standard format
* [CimBios.Gost58651](https://github.com/Cimbios/CimBios.Gost58651) DotNET CimBios.Core type library based on IEC-61970, 61968 + GOST-58651 extensions

## Outage Management System (OMS)
* [Adaptive Design Algorithms, Models & Systems (ADAMS) Lab.](https://github.com/adamslab-ub/Real-Time-Outage-Management-Active-DNR-GRL) Real-Time Outage Management in Active Distribution Networks Using Reinforcement Learning over Graphs
