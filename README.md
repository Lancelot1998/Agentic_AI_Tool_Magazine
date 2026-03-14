# Agentic_AI_Tool_Magazine

The tutorial for establishing an MCP server can be found at: https://github.com/Hornzolen/mcp-weather

## Representative communication/networking tools (MCP)

Despite such progress, the number of professional communication tools remains significantly scarce compared to the abundance of web- and user-centric tools.

### Category 1: Wireless, Drones, & Software Defined Radio (SDR)

| Tool Name | Optimized Description | Category | Link / Source |
|---|---|---|---|
| **FlytBase MCP** | Allow AI agents to query drone status (battery, GPS), manage missions, and access flight data/media. | UAV | [@flytbase/mcp-server](https://www.npmjs.com/package/@flytbase/mcp-server) |
| **GNU Radio MCP** | Integrate GNU Radio flowgraphs, allowing LLMs to autonomously create, modify, and execute signal processing pipelines for SDR. | Signal processing | [gnuradio-mcp-server](https://github.com/K-CEPT/gnuradio-mcp-server) |
| **WiFi MCP** | Provide real-time Wi-Fi information. Tools include scanning, connecting, disconnecting, and querying status. | Wireless networking | [wifi-mcp-server](https://github.com/borisyal/wifi-mcp-server) |
| **Bluetooth MCP** | Control Bluetooth devices and manage connections (discovery, pairing, audio controls) using natural language commands. | Wireless comm. | [bluetooth-mcp-server](https://github.com/semioz/bluetooth-mcp-server) |

### Category 2: Network Diagnostics & Management

| Tool Name | Optimized Description | Category | Link / Source |
|---|---|---|---|
| **Globalping** | Run network diagnostic commands, such as `ping`, `traceroute`, and DNS resolve. | Network diagnostics | [globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) |
| **Wireshark MCP** | Expose packet capture and protocol analysis capabilities to AI agents for traffic monitoring and diagnostics. | Network analysis | [wireshark-mcp](https://github.com/V-3/wireshark-mcp) |
| **Netdata** | Provide network observability. Integrates metrics, logs, containers, and network connections for root cause analysis. | Network operations | [Netdata MCP](https://learn.netdata.cloud/docs/netdata-ai/mcp) |
| **OPNSense MCP** | Enable firewall and routing management for OPNSense devices via its API, allowing agents to manage network security rules. | Network security | [opnsense-mcp-server](https://github.com/j-Soma/opnsense-mcp-server) |
| **NetBox MCP** | Manage the NetBox database, such as configuring a company's IP addresses and physical data center equipment. | Network inventory | [netbox-mcp-rw](https://github.com/alexkiwi1/netbox-mcp-rw) |

### Category 3: Internet of Things (IoT) & Protocols

| Tool Name | Optimized Description | Category | Link / Source |
|---|---|---|---|
| **Home Assistant** | Expose all connected smart home entities (lights, sensors, etc.) as tools for AI agents. | Smart home | [Home Assistant MCP Server](https://www.home-assistant.io/integrations/mcp_server/) |
| **ZigBee2MQTT** | Discover all Zigbee devices, exposing their capabilities (e.g., switch and brightness). | Zigbee | [zigbee2mqtt-mcp-server](https://github.com/ichbinder/MCP2ZigBee2MQTT) |
| **ESP RainMaker** | Control and manage ESP32/ESP8266 devices connected to the ESP RainMaker cloud. | IoT | [esp-rainmaker-mcp](https://github.com/espressif/esp-rainmaker-mcp) |
| **Apache IoTDB** | Manage Apache IoTDB time-series database, allowing agents to query and analyze IoT sensor data using SQL. | IoT database | [iotdb-mcp-server](https://github.com/apache/iotdb-mcp-server) |
