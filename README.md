# UBUNTU SERVER


## Objective

>This Ubuntu server is a project to upload files and other media, learn how to configure a server and how start from the hardware to the end product.

### Skills Learned

>PC Hardware Setup: Assembled a custom PC from individual components for use as a home server.

>Troubleshooting: Diagnosed and resolved hardware and software issues to ensure proper server functionality.

>Operating System Installation: Installed and configured Ubuntu Server, tailoring it for server-specific operations.

>Server GUI Configuration: Set up and managed a web-based GUI for streamlined server management via a browser.

>Linux Navigation and Configuration: Navigated through the Linux file system and edited configuration files to ensure accurate user permissions and system functionality.

>Custom File Permissions: Configured server settings to allow specific users write access while maintaining security.

>Samba File Sharing: Installed and configured Samba for seamless file sharing across the network.

>SMB Feature Activation: Enabled and configured SMB features on Windows PCs for full compatibility with the server.

>Firewall Management: Configured the Uncomplicated Firewall (UFW) to open required ports securely and allow necessary traffic.

>Network Integration: Set up a secure and functional SMB client-server environment for networked file access.

>Linux Server Administration: Gained experience in administering a Linux server, including user permissions, software installation, and network services configuration.

### Tools Used

>Rufus - creates bootable media

>Ubuntu Server - OS

>UFW - firewall configuration tool

>Cockpit - GUI interface over browser

>Podman - Container software

>Samba - file sharing and user access control between Linux and Windows systems

## Steps

Installed a Ryzen 5 1400 CPU onto the motherboard, 16GB RAM, and CPU cooler with thermopaste.


<a href="https://imgur.com/H1pFuOn"><img src="https://i.imgur.com/H1pFuOnl.jpg" title="source: imgur.com" /></a>

Installed motherboard onto a NZXT case along with a 500W power supply, GTX 1650 GPU, and a 1TB HDD 

<a href="https://imgur.com/JIzbnBs"><img src="https://i.imgur.com/JIzbnBsl.jpg" title="source: imgur.com" /></a>

Downloaded OS and created a bootable Drive with RUFUS

<a href="https://imgur.com/nOPptI2"><img src="https://i.imgur.com/nOPptI2l.png" title="source: imgur.com" /></a>

Followed the prompts and finished installing Ubuntu Server OS

<a href="https://imgur.com/tRHvRQi"><img src="https://i.imgur.com/tRHvRQil.jpg" title="source: imgur.com" /></a>

Enabled Uncomplicated Firewall (UFW) 

<a href="https://imgur.com/IehzCBU"><img src="https://i.imgur.com/IehzCBUl.png" title="source: imgur.com" /></a>

Configured firewall to allow port 22(ssh)

<a href="https://imgur.com/sHTmilw"><img src="https://i.imgur.com/sHTmilwl.png" title="source: imgur.com" /></a>

Started SSH on personal windows pc to verify functionality

<a href="https://imgur.com/4vTgdfj"><img src="https://i.imgur.com/4vTgdfj.png" title="source: imgur.com" /></a>

Enabled cockpit for GUI interface on browser

<a href="https://imgur.com/SlSH8oU"><img src="https://i.imgur.com/SlSH8oUl.png" title="source: imgur.com" /></a>

Added rule to firewall 

<a href="https://imgur.com/SrUztor"><img src="https://i.imgur.com/SrUztorl.png" title="source: imgur.com" /></a>

Verified GUI in Browser 

<a href="https://imgur.com/Rt8V9sS"><img src="https://i.imgur.com/Rt8V9sSl.png" title="source: imgur.com" /></a>

Added Users to server and configured permissions

<a href="https://imgur.com/XvEDXEJ"><img src="https://i.imgur.com/XvEDXEJl.png" title="source: imgur.com" /></a>

Verified user in cockpit

<a href="https://imgur.com/3I4Hb7n"><img src="https://i.imgur.com/3I4Hb7nl.png" title="source: imgur.com" /></a>

Installed samba

<a href="https://imgur.com/KvPiWTA"><img src="https://i.imgur.com/KvPiWTAl.png" title="source: imgur.com" /></a>

Configured samba files

<a href="https://imgur.com/5IOELR0"><img src="https://i.imgur.com/5IOELR0l.png" title="source: imgur.com" /></a>

Restarted service and verifying its operational 

<a href="https://imgur.com/mPfBae7"><img src="https://i.imgur.com/mPfBae7l.png" title="source: imgur.com" /></a>

Added users to smb

<a href="https://imgur.com/qDR134O"><img src="https://i.imgur.com/qDR134Ol.png" title="source: imgur.com" /></a>

Verified it's operating 

<a href="https://imgur.com/Tmhatvs"><img src="https://i.imgur.com/Tmhatvsl.png" title="source: imgur.com" /></a>

Added application to android to transfer files to server through smb 

<a href="https://imgur.com/VRz7d3u"><img src="https://i.imgur.com/VRz7d3ul.jpg" title="source: imgur.com" /></a>



## Troubleshooting 

<a href="https://imgur.com/6lFz1Vj"><img src="https://i.imgur.com/6lFz1Vjl.png" title="source: imgur.com" /></a>


Was having a difficult time with PC getting access to server and found smb client was not enabled on Windows PC and had to add user with 
syntax sudo smbpasswd -a umb12eon
