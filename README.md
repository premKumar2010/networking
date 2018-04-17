# Networking
Learn basic networking, how the internet works and http,ping

# Commands:
 1. `ping -c3 8.8.8.8`
    ### -c3:
    This is used to send the number of packets to the server and receive the packets fromm the server and then quite `-c3` send three         packets
    ### 8.8.8.8 (or) www.google.com ###
    This is the server `ip` or `domain name`
    ### ping ###
    Ping is the command which not intract with the server instead it intreact with the operating system where the server presents.
  2. `printf 'HEAD / HTTP/1.1\r\nHost: en.wikipedia.org\r\n\r\n' | nc en.wikipedia.org 80`
     ### |
     https://askubuntu.com/questions/349058/what-does-the-vertical-bar-character-mean-in-a-terminal-command
     ### nc
     https://www.computerhope.com/unix/nc.htm
    
# HTTP vs Ping
  ### HTTP ###
  HTTP makes the request to the server through `Get` or `post` request and gets the response back to the server.
  ### Ping
  Instead ping speaks to the operating system where the server presents.its just like an `echo` command from the server operating system.
