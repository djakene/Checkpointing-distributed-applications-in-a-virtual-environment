# Checkpointing-distributed-applications-in-a-virtual-environment
pour faire le checkpointing des applications distribuées, on a mis en place un environnement virtuel reposant sur u
n cluster physique.
Le cluster physique est constitué de 4 machines physiques:
- N1 constitue de 16 coeurs donc chacun a 2GHz
- N2 constitue de 16 coeurs donc chacun a 2GHz
-N3 constitue de 8 coeurs donc chacun a 2GHz
- N4 constitue de 16 coeurs donc chacun a 2GHz
Sur chaque Ni sauf N3, on a quatre machines virtuelles qui sont:
- NiV1 ayant 4 coeurs de 2GHz
- NiV2 ayant 4 coeurs de 2GHz
- NiV3 ayant 4 coeurs de 2GHz
- NiV4 ayant 4 coeurs de 2GHz
