leodotcloud/network-manager:9700 

Native Container
  - Without label, without net 
    Docker+Bridge+Network+Mode, 172.17.0.3
  
  - Without label (none, host) 
    Docker None network mode, no ip 
    No existing network uuid, 127.0.0.1
  
  - With label --net (host, none, nothing)
    Docker Host Network Mode 127.0.0.1 ~~why label?~~ (always label) [Syncing]. 
    ipsec 
    ipsec
    
 
UI 
  - Without label, host
    Docker Host Network Mode 127.0.0.1 
    
  - With label, --net(host) 
    Docker Host Network Mode 127.0.0.1  no label 
    
  - With label, --net(none) 
    Docker None Network Mode 
  
