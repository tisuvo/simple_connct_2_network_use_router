# simple_connct_2_network_use_router
Here have two diffterent network
one part are 192.168.10.0 to 192.168.10.64
another 192.168.10.65 to 192.168.10.128

i connct this network using router 
few line cmd use

enable
config terminal
interface GigabitEthernet0/0
Router(config-if)#ip address 192.168.10.1 255.255.255.192
Router(config-if)#no shutdown

Router(config)#interface GigabitEthernet0/1
Router(config-if)#ip address 192.168.10.65 255.255.255.192
Router(config-if)#no shutdown



