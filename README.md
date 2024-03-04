# different-dds-demo

Connecting Cyclone DDS and Fast DDS powered ROS 2 nodes over the internet

## Quick Start

### Husarnet Setup

Create the `.env` file based on `.env.template` and paste your own Husarnet Join Code here

### Launching Demo

In two separate terminals (on the same or different hosts) run:

1. Terminal 1: launching listener node with FastDDS

```
docker compose -f compose.listener.yaml up
```

2. Terminal 2: launching talker node with CycloneDDS

```
docker compose -f compose.talker.yaml up
```
