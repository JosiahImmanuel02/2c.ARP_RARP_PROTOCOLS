# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2024-10-15 143501](https://github.com/user-attachments/assets/ab71e25a-f17c-4cb7-a503-7a7e057ed3e8)

## OUPUT - ARP
![2c arp](https://github.com/user-attachments/assets/37077134-fea1-4aea-8aa9-85031d977eb2)


## PROGRAM - RARP
![Screenshot 2024-10-15 143451](https://github.com/user-attachments/assets/399f4174-2c1f-4dd1-9107-d75f18d96aaa)

## OUPUT -RARP
![2c rarp](https://github.com/user-attachments/assets/96fff07d-7823-4942-bb48-ffaf8f6e1ddd)


## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
