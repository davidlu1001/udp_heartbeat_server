# udp_heartbeat_server
UDP Heartbeat Server &amp; Client

UDP Heartbeat Server: Simulates packet loss and supports user defined value for the port number

    usage="./svr.py [--port] N  [--packetloss] N [-h/--help]"
  
UDP Heartbeat Client: Simulates sending and receiving packets to and from the server

    usage"./cli.py --serverip ip --serverport port [--vif vif_interface]"
    e.g. ./cli.py --serverip 10.10.10.2 --serverport 12000 --vif vif2.0
