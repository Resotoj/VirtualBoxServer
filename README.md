<h1>Server 2019 on VirtualBox</h1>




<h2>Description</h2>
I've created a few envirnoments in VirtualBox such as Ubuntu, Windows 10, Windows 8.1 (I dont know why 8.1..) but I never created a server. I wanted an environment to be able to manage all my clients from a central location. Eventually, I will like to control all my IoT from it, but in the mean time, I have it running as a lab enviroment for my Ubuntu and Windows 10 clients. The network set up took me way longer than I wanted. <br>
I set up the Server to run as a NAT, with two NIC (one facing out and one facing in). Setting up the DHCP, NAT, and Domain seemed pretty straight forward. Once I got the first client to connect however, I ran into a small issue.<br>
<br>
unfortunately, I didn't screenshot, as I was fairly frustrated, but I couldn't get the client to ping a FQDN. IP addresses were fine, but the darn FQDN was not working. I tried to reconfigure my routing settings, but it wasn't working. After a lot of poking around, I discovered my mistake. a simple typo on the DNS. <br>
I will next be attempting to connect the Ubuntu client and setting up shared files.
<br />
<br />






<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
