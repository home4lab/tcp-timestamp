# tcp-timestamp-vulnerability

♦ Disable the TCP timestamp response on Linux.


    $echo 0 > /proc/sys/net/ipv4/tcp_timestamps
    
Fixes timestamp on every boot. Edit /etc/sysctl.conf and enter line below
net.ipv4.tcp_timestamps = 0

    $nano /etc/sysctl.conf
    $sysctl -p
    
    
    
    ==================
    $sysctl -w net.ipv4.tcp_timestamps=0
    
Add the net.ipv4.tcp_timestamps=0 value in the default sysctl.conf file.

    $nano /etc/sysctl.conf
    


#reference
shorturl.at/mptF5
