# Develop By : Dinesh M
# Reg No : 212222043002
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
# PROGRAM - ARP
## Client:
![Screenshot 2024-05-09 070505](https://github.com/MDINESH220305/2c.ARP_RARP_PROTOCOLS/assets/162429215/63ca55ce-da86-46bf-8a60-b3f4cb0ef194)

 
## OUPUT - ARP
![cn2c1](https://github.com/MDINESH220305/2c.ARP_RARP_PROTOCOLS/assets/162429215/f1ac8cd8-59f2-4a57-9f90-c4f6296a4f44)


## PROGRAM - RARP
![Screenshot 2024-05-09 070553](https://github.com/MDINESH220305/2c.ARP_RARP_PROTOCOLS/assets/162429215/29064de4-6a63-4f0e-a74e-efa6efe80754)



## OUPUT -RARP
![cn2c2](https://github.com/MDINESH220305/2c.ARP_RARP_PROTOCOLS/assets/162429215/b06de8dc-18ce-4045-b969-661b9a8823f1)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
