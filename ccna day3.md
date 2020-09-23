# OSI model & TCP/IP suite

### What is a networking model?
  - Networking models categorize and provide a structure for networking protocols and standards.
    (protocols : A set of logical rules defining how network devices and software should work.[not pyshical standard!])

# OSI Model
 - 'Open Systems Interconnection' model
 - A conceptual model that categorizes and standardizes the different functions in a network.
 - Created by the 'interntational Organization for Standardization' (ISO).
 - Functions are divided int 7 'Layers'.
 - These layers work together to make the network work.

 ### 7. Application 
  - This layer is closest to the end user.
  - Interacts with software applications, for example your web browser (Brave, Firefox, Chrome, etc)
  - HTTP and HTTPS are Layer 7 Protocols (https://www.cisco.com)
   Fuctions of Layer 7 include:
    - Identifying communication partners
    - Synchronizing communication
    
 ### 6. Presentation
  - Data in the application layer is in 'application format'.
  - It needs to be 'translated' to a different format to be sent over the network.
  - The Presentation Layer's job is to trandlate between application and network formats.
  - For example, encryption of data as it is sent, and decryption of data as it is received.
  - Also, translates between different Application-Layer formats.
  Summarize : The presentation layer trandlates data to the appropriate format.
  
 ### 5. Session
  - Controls dialogues (sessions) between communicating hosts.
  - Establishes, manages, and terminates connections between the local application (for example, your web browser) and the remote application (for example, YouTube).

## 5, 6, 7 layers = Top 3 layers. 
 - Network engineers don't usually work with the top 3 layers.
 - Application developers work with the top layers of the OSI model to connect their applications over networks.
 
 4. Transport
  - Segment and reassembles data for communications between end hosts.
  - Breaks large pieces of data into smaller segments which can be more easily sent over the network and are less likely to cause transmission problems if errors occur.
  - Provide host-to-host communcation. (end-to-end)
  
 3. Network
  - Provides connectivity between end hosts on different networks (ie. outside of the LAN).
  - Provides logical addressing (IP addresses).
  - Provides path selection between source and destination.
  - Routers operate at Layer 3.
  
 2. Data Link
  - Provides node-to-node connectivity and data transfer (for example, PC to switch, switch to router, router to router).
  - Defines how data is formatted for transmission over a physical medium (for example, copper UTP cables)
  - Detects and (possily) corrects Physical Layer errors.
  - Uses Layer 2 addressing, separate from Layer 3 addressing
  - Switches operate at Layer 2.
  
 1. Physical
  - Defines physical characteristics of the medium used to transfer data between devices.
  - For example, voltage levels, maximum transmissioin distances, physical connectors, cable specifications, etc.
  - Digital bits are converted into electrical (for wired connections) or radio (for wireless connections) signals.
  - All of the information in day 2(cables, pin, layouts, etc.) is related to the Physical layer.
  
  ### PDUs (Protocol Data Units)
  1. Data (top 3 layers)
  2. Segment L4
  3. Packet L3
  4. Frame L2
   Layer 1 PDU = Bit
   
  
  # TCP/IP Suite
    - Conceptual model and set of communications protocols used in the internet and other networks.
    - Known ad TCP/IP because those are two of the foundational protocols in the suite.
    - Deloped by the United States Department of Defense through DARPA(Defense Advanced Research Projecks Agency)
    - Simmilar structure to the OSI Model, but with fewer layers.
    - This is the model actually in use in modern networs.
    - NOTE : The OSI model still influences how network engineers think and talk about networks.
   
   4. Application
    - OSI Top 3 layers. = TCP/IP Suite Applycation layer.
    
   3. Transport
   2. Internet
    - OSI Network layer
   1. Link
    - OSI Data Link, Physical layers = TCP/IP Suite Link layer.
  
