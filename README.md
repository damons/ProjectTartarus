# ProjectTartarus
Overture
As per Greek mythology Tartarus refers to an oubliette or dungeon, possibly like Hades, where the evil and wicked were sent to be tormented. The name has also been used to refer to a primordial force or deity [Source: Wiki]. In our world, Tartarus refers to a Multi-Agent platform which can take in your problems and churn out solutions. Tartarus is the new version of Typhon and is built using SWI-Prolog.

Introduction
Written in SWI-Prolog, Tartarus, facilitates users to create overlay sort of network of nodes comprising either a single PC/laptop/embedded system or several such devices connected as a LAN (wired/wireless) and then program both static and mobile agents. Agents in Tartarus are basically programs written in Prolog. They can be programmed to perform tasks autonomously at select nodes and even migrate to others in the network they inhabit. Such agents can even be programmed to clone (copy and multiply) on-the-fly and then move around the network and execute tasks concurrently, providing a distributed and decentralized processing environment. These agents can also carry programs as payloads. Payloads could be written in Prolog or Python and executed at desired nodes. One could try out using other languages as well. Agents can communicate amongst one another and also with programs at a node. As of now, Tartarus can be run on Windows, Ubuntu and Raspbian operating systems.
Tartarus can run on the Raspberry Pi. It can be used to sense the sensors on-board and also control the actuators (motors, relays, etc.) connected to the board.

***Tartarus - Some salient features***

* Multi-threading: Tartarus allows for threaded execution of agents so that they all function concurrently. These threads are managed by its core engine thereby ridding the developers of comprehending the complexities of implementing mutual exclusion.

* Heterogeneity: Tartarus supports both Windows, Ubuntu and Raspbian and can thus be installed in most hardware which run these operating systems. Agents running on top of any of these operating systems can communicate with one another providing cross platform interchange.

* Hardware-in-the-loop: Tartarus can be ported on embedded boards such as the Raspberry Pi. It also comes with an interface for the LEGO MINDSTORM NXT robots. These special interfaces allow developers to access and control the underlying hardware, thus making it easier for a developer to build applications with hardware-in-the-loop.

* Distributed Control: Multi-Agent Systems (MAS) provide for ideal solutions for applications that demand distributed computations and communications among heterogeneous entities. Tartarus agents can share information between nodes, migrate amongst them and even execute the code at a destination/remote node.

* Mobility & Cloning: Agents can also be mobile and can migrate from one node to another in a network they inhabit. They can also clone as and when required contributing to a degree of parallelism in the network.

* Payloads: A mobile agent within Tartarus can carry a set of programs/data as payload to be either executed at the destination node or be downloaded for use at some node. Agents can also be programmed to either upload/download/offload these payloads at specific nodes or based on an event. Changing a payload can thus facilitate the altering of the behaviour of an agent even in run time.

* Security: Security implemented for the agents in Tartarus. Mobile agents can enter a node only if they possess a key (provided to them a priori). This key should match with the one in the platform installed at the node; else entry is rejected. Developers can put in a bit of effort to provide for a more sophisticated security arrangement based on their application.
