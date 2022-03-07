# tcp-timestamp-vulnerability

♦ Disable the TCP timestamp response on Linux.


To set the value of net.ipv4.tcp_timestamps to 0, run the sysctl -w net.ipv4.tcp_timestamps=0 command.

    $sysctl -w net.ipv4.tcp_timestamps=0
    
Add the net.ipv4.tcp_timestamps=0 value in the default sysctl.conf file.

    $nano /etc/sysctl.conf


#reference
shorturl.at/mptF5
