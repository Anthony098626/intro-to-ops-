# VirtualBox Network Setting: Complete guide
    
 Virtual Network Adapters 

    - eash virtualbox vm can use up to 8 virtual network adapters. 4 of witch that can be configured in the Vbox GUI.
## Reading notes questions
    1) Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?
        - The newtwork mode that can be used to emulate unplugging the eathernet cable from the network is "Internal Netwrok".

    2) Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?
        - The network mode that would be best if you wnated to run a server in a VM that would be fully accessible from my physical locla area netwrok would be "Bridged mode"
    
    3) What are the three options of promiscuous mode and what does each do?
        - Deny: This option will only recieve network packets that are addressed to it. 
        - Allow VM's: This option will recieve all netwrok packets that are sent on the physical network. 
        -Allow All: This option will accept all packets that are sent on the physical network. 

    4) What is Port Forwarding?
        - Port forwarding is used to allow external devices to access services or applications running on a specific port on a local network device, such as a computer or a router.

Sources/ https://www.nakivo.com/blog/virtualbox-network-setting-guide/

chatgbt.com