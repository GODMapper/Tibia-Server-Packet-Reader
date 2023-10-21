# Tibia-Server-Packet-Reader
Read packets sent to server This is a c# program that intercept packet sent to server by tibia via dll injection.

Today I bring you a packet reader to get packets the client send to the server. This is done by hooking send packet function.
It's functional for Tibia 10.78 and can be easily updated to any version. This addresses are in 0x400000 base, so if you have aslr you'll have to do the math.
