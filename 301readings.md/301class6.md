# Network Address Translation (NAT)

This is a way to share one internet connection between multiple devices in a private network.  With NAT, each device on the private network is given a unique IP address so they can communicate with the internet, but they all appear to have the same public IP address to the outside world. This allows multiple devices to share a single internet connection without each device needing its own public IP address.
## Reading questions
    1) What is the main purpose for implementing NAT on a network?
        - To enable multiple devices on a private network to share a single public IP address, while still being able to communicate with the internet.
    2) At what layer of the OSI model does NAT happen?
        -layer 3
    3) What happens to packets when NAT runs out of addresses in the pool of available IPs?
        - it can stop accepting new connections or may reject new requests
    4) What disadvantage does using NAT pose for routers?
        -it can introduce additional complexity and overhead into the network.
### sources
    1) https://www.geeksforgeeks.org/network-address-translation-nat/
    2) https://chat.openai.com/chat
