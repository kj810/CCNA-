# Ethenet LAN Switching

Review OSI physical layer, data link layer.

Review PDUs(Protocol Data Units)
  - data
  - segment
  - packet
  - frame

## Ethernet Frame

Eth. header + Packet + Eth. trailer

  - Eth. header
    - Preamble(7)/SFD(1)/Destination(6)/Source(6)/Type(2)
  - Eth. Trailer
    - FCS(4)
  = 26 bytes (header + trailer)
  
 ## MAC Adress
    - 6 byte (48bit) physical address assigned to the device when it is made
    - A.K.A 'Burned-In Address' (BIA)
    - is globally unique
    - The first 3 bytes are the OUI (Organizationally unique Identifier), which is assigned to the company making the device
    - The last 3 bytes are unique to the device itself
    - Written as 12 **hexadecimal** characters
    
### Decimal
  Uses 10 possible digits: 0,1,2,3,4,5,6,7,8,9
  
  ## hexadecimal
    Uses 16 Possible digits: 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F
    
    
    
    
https://youtu.be/u2n762WG0Vo
    
