# Technical Reconnect Pre-Course Assessment

>[!KNOWLEDGE] During this 60 minute assessment you will attempt to complete a number of tasks to assess your ability to follow high level instructions and basic usage skills of Windows, Linux.  At certain points there is a check button which needs to be pressed once the previous instruction has been completed.

## Hyper-V configuration tasks

1. [] Using the credentials on the Resources tab above log onto the machine
2. [] Using the Windows Turn Features On tool install Hyper-V

@lab.Activity(901)
3. [] Using the Hyper-v Manager import two virtual machines.  The source VM's can be found in **C:\Assessment**
- An Ubuntu Linux Virtual Machine
- A Windows 10 Virtual Machine
===
## Virtual Machine configuration tasks
@lab.Activity(910)
4. [] Start the Ubuntu virtual machine
5. [] The Windows 10 VM machine has not been connected to a network.  Connect the VM to the CORP network by using the Settings tool in the Hyper-V Manager
6. [] Start the Windows 10 VM
7. [] The Windows 10 VM does not have an ipaddress.  Connect and login into the Windows 10 VM using the credentials on the resources tab above.  Once logged in configure the ipaddress 172.31.0.200/24

@lab.Activity(909)
8. [] Open a web browser in the Windows Client VM and in the web browser navigate to +++http://www.techreconnect.co.uk+++
@lab.Activity(932)

9. [] Connect to the Ubuntu VM and login using the credentials on the resources tab above.
10. [] Create the following folder /home/alice/folder1

@lab.Activity(933)
11. [] Close both the Windows Client VM and the Ubuntu VM Virtual Machine Connection windows
===
## Wireshark installation and usage tasks
12. [] From the **C:\Assessment** folder install **Wireshark**
13. [] Open the **Wireshark** application
13. [] In **Wireshark** open the PCAP file **C:\Assessment\Sample.pcap**

@lab.Activity(934)