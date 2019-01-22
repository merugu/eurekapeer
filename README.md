# eurekapeer
The idea is to have a backup for eureka instance.If one instance in 'x' cluster goes down. Zuul should be able to pick the another eureka instance 'y' 
To run Eurek Peer awareness in windows machine locally, please append the below code at the end of hosts file under C:\Windows\System32\drivers\etc:
below:

127.0.0.1       eureka-peer1
localhost       eureka-peer1
::1             eureka-peer1
127.0.0.1       eureka-peer2
localhost       eureka-peer2
::1             eureka-peer2
