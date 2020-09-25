#Introduction to the Cisco IOS CLI

## what is a CLI?
  - Command-line interface.
  - The interface you use to configure Cisco devices.
  

## Modes
  - Router>         = user EXEC mode
  - Router#         = privileged EXEC mode
  - Router (config) #         = global configuration mode
  
## Command Review
  - Router>enable
      - used to enter privileged EXEC mode
      
  - Router#configuration terminal
      - used to enter global configuration mode
      
  - Router (config) #enable password /password/
      - configures a password to protect privileged exec mode
      
  - Router (config) #service password-encryption
      - encrypts the enable password (and other passwords)
      
  - Router (config) #enable secret /password/
      - configures a more secure, always-encrypted enable password
      
  - Router (config) #run privileged-exec-level-command
      - executes a privileged-exec level command from global configuration mode
      
  - Router (config) #no command
      - removes the command
      
  - Router (config) #show running-config
      - displays the current, active configuration file
  - Router (config) #show startup-config
      - diplays the saved configuration file which will be loaded if the device is restarted
      
  - Router (config) #write
      - saves the configuration  
  - Router (config) #write memory
      - saves the configuration
  - Router (config) #copy running-config startup-config
      - saves the configutraion

https://youtu.be/IYbtai7Nu2g
  
