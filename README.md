# RedLab
An automated platform for ethical red-teaming exercises in controlled, vulnerable environments
-----------------------------------------------------------------------------------------------
The main objective of RedLab is to create controlled environments within which will be possible to deploy containers connected through an isolated network following a client-host structure, in which the host will have a vulnerable API and the clients will act as the attackers. This will be possible through a DinD (Docker in Docker) system, in which the host will always have the same characteristics, and there can be any number of clients, although initially it will be limited to just one. 
