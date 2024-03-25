# Linux-interview-questions
Useful Interview Questions for Linux Engineer

Source for the questions: https://www.reddit.com/r/linuxquestions/comments/11tynim/interview_questions_for_linux_engineer/

* What is the difference between Linux and Unix?

* How do you troubleshoot a server that is running slowly?
  * Check the server resources CPU, memory, disk and network.
     * top - show all running processes
     * iostat - monitor system input/output devices (physical and logical) by detecting the time for which these devices are active.
     * check cpu infomation - lscpu, cat/proc/cpuinfo
     * mpstat - report processor related statistics
     * sar - show cpu utilization | sar -u - show cpu usage
     * free -m - check memory status in mb
     * sar -r - show memory usage historically
     * df -h - show disk space in human readable format
     * fdisk -l - capacity of our hard disk, the partitions within it, and their respective sizes
     * lsblk - show all the available block devices connected to the system, except RAM.
     * ipaddr - check ip address 
     * ifconfig - show current configuration for network interface from here also we can get ip address
     * traceroute - trace path network packets take from source to destination host
     * netstat - statistics about active connections
     * You can terminate unnecessary processes, increase the memory size, defragment the disk, or use a faster network adapter based on the investigation.
  * Analyze the server logs - We can use journalctl, syslog commands
  * Test the server functionality which can help you verify if the server is performing as expected and delivering the desired results. You can use tools like Ping, Traceroute, or Telnet to test the server's connectivity, latency, and availability.
  * Review the server configuration - You can use tools like Nmap, Wireshark, or Netstat to monitor and analyze the server's network traffic and ports. you can check for firewall rules, proxy settings, encryption protocols, or authentication methods.
  * Update the server software or Seek professional help

* How do you configure a network interface in Linux?

* What is the difference between a process and a thread?

* How do you check the available disk space in Linux?
   * By typing df (disk-free) will show the disk usage details for every file system on your Linux machine. df -h will show the output in a human-readable format.

* What is the role of the superuser in Linux?
   * It's like admin access. It has unrestricted access to all commands, files, directories, and resources.

* What is the difference between a hard link and a symbolic link?

* How do you check the status of a service in Linux?

* How do you set up a firewall in Linux?

* What is SELinux and how do you configure it?

* What is the difference between a soft link and a hard link in Linux?

* How do you find all files modified in the last 24 hours in Linux?

* How do you mount a file system in Linux?

* What is the difference between RAID 0, RAID 1, RAID 5 and RAID 10?

* What is a cron job in Linux and how do you set one up?

* What is the difference between TCP and UDP?

* How do you change the ownership of a file in Linux?

* How do you add a user to a group in Linux?

* What is SSH and how do you use it to connect to a remote server?

* How do you check the system load average in Linux?

* What is the purpose of the /etc/passwd file in Linux?

* How do you check the system uptime in Linux?

* What is the difference between a process and a daemon in Linux?

* How do you set up a static IP address in Linux?

* What is the purpose of the /var/log directory in Linux?

* How do you check the kernel version in Linux?

* How do you check the status of a network interface in Linux?

* What is the purpose of the /etc/fstab file in Linux?

* How do you troubleshoot a service that is not starting in Linux?

* What is the purpose of the crontab file in Linux?

RH

What is the difference between Red Hat Enterprise Linux and Fedora?

How do you install packages using yum in Red Hat?

What is the purpose of the /etc/sysconfig/network-scripts directory in Red Hat?

How do you configure SELinux in Red Hat?

How do you upgrade a Red Hat system to a newer release?

How do you configure networking in Red Hat using the nmcli command?

What is the purpose of the /etc/yum.repos.d directory in Red Hat?

How do you set up a LAMP stack (Linux, Apache, MySQL, PHP) in Red Hat?

What is the purpose of the /etc/shadow file in Red Hat?

How do you configure NTP (Network Time Protocol) in Red Hat?

How do you create a software RAID in Red Hat?

What is the purpose of the /etc/sysconfig directory in Red Hat?

How do you configure a static IP address in Red Hat using the nmcli command?

What is the purpose of the /etc/httpd directory in Red Hat?

How do you configure SELinux to allow or deny specific actions in Red Hat?
