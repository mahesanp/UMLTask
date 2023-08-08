# HLDTask
# Online Shopping system


## Distributed File Storage System

## Main Components:

The main components of the Distributed File Storage System are as follows:
* Client
* Authorization factor
* Load Balancer
* Name Node
* Meta Data
* Data Node
* Data Center

## Interactions:

The client interacts with the name noder to store the data. The namenode acts as a main linkage between various data nodes. The data center contains the data nodes. The name node is responsible to manage all the details and file storage about the data nodes. The data of the name node will be stored as Meta Data.

## Data Flow:
The data flows in such a way starting from client to name node via load balancer to the data node where the data being replicated in various nodes for replicability ensuring a copy of data being present always in the data center.

![HLD Diagram](https://github.com/mahesanp/UMLTask/blob/master/HLD/HLD%20Diagram.png)