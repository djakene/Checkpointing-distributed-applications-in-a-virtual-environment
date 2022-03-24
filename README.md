# Checkpointing-distributed-applications-in-a-virtual-environment
To checkpoint distributed applications, we set up a virtual environment based on a physical cluster.
The physical cluster consists of 4 physical machines:
- N1: 16 cores of 2GHz each, 12 GB of RAM and 401 GB of hard disk  
- N2: 16 cores of 2GHz each, 12 GB of RAM and 637 GB of hard disk  
- N3: 8 cores of 2GHz each, 6GB RAM and 122GB hard drive  
- N4: 16 cores of 2GHz each, 8GB of RAM and 158GB of hard disk 

For the physical node N1, we have 4 Virtual nodes which are:
- N1V1 with 4 cores of 2GHz
- N1V2 with 4 cores of 2GHz
- N1V3 having 4 cores of 2GHz
- N1V4 having 4 cores of 2GHz

For the physical node N2, we have 4 Virtual nodes which are:
- N2V1 having 4 cores of 2GHz
- N2V2 having 4 cores of 2GHz
- N2V3 having 4 cores of 2GHz
- N2V4 having 4 cores of 2GHz

For the physical node N3, we have 3 Virtual nodes which are:
- N3V1 having 4 cores of 2GHz
- N3V2 having 4 cores of 2GHz
- N3V3 having 4 cores of 2GHz

For the physical node N4, we have 4 Virtual nodes which are:
- N4V1 having 4 cores of 2GHz
- N4V2 having 4 cores of 2GHz
- N4V3 having 4 cores of 2GHz
- N4V4 having 4 cores of 2GHz

In each virtual node in the physical nodes N1, N2, N3 and N4, we have 4 containers of 4 virtual processors
