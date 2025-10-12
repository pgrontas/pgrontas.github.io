---
title: "Load Balancing in Distributed Object Systems"
collection: publications
category: theses
permalink: /publication/2000-01-01-Distributed-object-systems
date: 2000-01-01
venue: 'BSc Thesis. University Of Piraeus'
citation: 'Panagiotis Grontas. Load Balancing in Distributed Object Systems. Piraeus 2014.'
excerpt: ' The project focused on developing a load distribution system for object-oriented environments based on RMI and CORBA. Its main goal was to create an application capable of dynamically allocating computational load among multiple distributed objects (servers) within an Object Web framework. The system was designed so that client machines could also perform server-side operations, improving resource utilization and decentralizing processing tasks. Communication initially uses HTTP only to download the Java applet, while subsequent interactions occur via JRMP or IIOP protocols, depending on the implementation.
The system’s architecture follows a fully object-oriented model, where user interaction occurs through a Java applet, and specialized server-side objects execute the algorithmic computations. One of the project’s key innovations is leveraging Java’s mobile code feature, allowing certain operations traditionally executed on the server to be transferred and executed on the client host. This approach effectively transforms the classical client-server model into a truly distributed system, where processing responsibilities are shared dynamically between clients and servers.
Additionally, the project attempts to achieve dynamic load management—distributing problem-solving requests evenly so that all system components contribute equally to computation. Each incoming task is assigned to a server based on its current workload policy, although the study did not manage to extract measurable performance indicators (such as server utilization levels). Nevertheless, transferring part of the computation to the client side helps reduce the load on central servers, improving scalability and flexibility in distributed applications.'
---