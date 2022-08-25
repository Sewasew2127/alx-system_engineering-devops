# Networking Basics 2

## What is localhost
localhost is a hostname that refers to the current device used to access it. It is used to access the network services that are running on the host via the loopback network interface. Using the loopback interface bypasses any local network interface hardware
	### Loopback
	The local loopback mechanism may be used to run a network service on a host without requiring a physical network interface, or without making the service accessible from the networks the computer may be connected to. For example, a locally installed website may be accessed from a Web browser by the URL http://localhost to display its home page.

	The name localhost normally resolves to the IPv4 loopback address 127.0.0.1, and to the IPv6 loopback address

## What is 0.0.0.0
In the Internet Protocol Version 4, the address 0.0.0.0 is a non-routable meta-address used to designate an invalid, unknown or non-applicable target. This address is assigned specific meanings in a number of contexts, such as on clients or on servers.
In the context of servers, 0.0.0.0 can mean "all IPv4 addresses on the local machine". If a host has two IP addresses, 192.168.1.1 and 10.1.2.1, and a server running on the host is configured to listen on 0.0.0.0, it will be reachable at both of those IP addresses.

## What is the hosts file
The hosts file is a plain text file that all operating systems use to translate hostnames (also known as web addresses or URLs) into IP addresses.

It is a single file on a computer that serves as a small gateway between the computer and the web. It's called the hosts file. 
 If you need to block websites or create personalized web shortcuts on Linux, you can just add or tweak a few lines in the file.

On Linux, you can find the hosts file under /etc/hosts. 
	$ sudo nano /etc/hosts
## Netcat examples


# Files in this repo
* 0-change_your_home_IP -  a Bash script that configures an Ubuntu server with the below requirements.

	Requirements:

		* localhost resolves to 127.0.0.2
		* facebook.com resolves to 8.8.8.8.

		coution-> If you’re running this script on a machine that you’ll continue to use, be sure to revert localhost to 127.0.0.1. Otherwise, a lot of things will stop working!
* 1-show_attached_IPs - a Bash script that displays all active IPv4 IPs on the machine it’s executed on.