<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Diagnose and Fix a Broken Windows PC

**Project Link:** [View Project](https://nextwork.ai/projects/c36a769f-5c05-48ec-8533-39be6745932f)

**Author:** Inga Nguse  
**Email:** inganguse09@gmail.com

---

![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_7fhhqfd8)

## Acting as IT Support: Diagnosing a Slow PC

### Project overview and role

In this project, I'm acting as a level 1 IT Support technician responding to a support ticket using built in Windows tools to diagnose a PC layer by layer and write a proffesional support ticket documenting all my findings

## Setting Up the Diagnostic Workspace

### Preparing the environment

In this step, I am launching my diagnostic tools: Windows Command Prompt to run diagnostic commands and Task Manager to monitor system resources and performance in real time.

![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_fdv335bu)

### System hardware details

My computer has 16 276 MB of Total Physical Memory and is running Microsoft Windows 11 Pro

## Investigating CPU and Memory Performance

### Approach to performance analysis

In this step, I am investigating the computer's CPU and memory usage in Task Manager so that I can determine whether hardware resource limitations are causing the PC's slow performance.

![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_zhl1nm00)

### Top resource-consuming process

Top process: Microsoft Edge (20) at 2.7% CPU usage. Hardware is not the bottleneck because CPU and memory usage are within normal ranges.

## Reading System Health with Event Viewer

### Why Event Viewer matters

In this step, I'm checking the Windows System logs in Event Viewer so that I can determine whether any recent errors or warnings are causing the PC to perform slowly.


![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_b9hmt6mu)

### Findings from system logs

Event Viewer showed no Warning or Error events in the System log within the last hour, indicating that the system is operating normally with no recent issues detected.


## Diagnosing Network Connectivity

### Network investigation approach

In this step, I'm checking my network configuration and testing internet connectivity so that I can determine whether the website issue is being caused by my PC, the local network, or a problem beyond the router.


![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_svcbupzg)

### Connectivity findings

I found that my IPv4 address is 192.168.2.17, with a subnet mask of 255.255.255.0, a default gateway of 192.168.2.1, and a DNS server of 192.168.2.1. My ping to 8.8.8.8 showed 4 successful replies with 0% packet loss, and my ping to the default gateway (192.168.2.1) also showed 4 successful replies with 0% packet loss. The network layer is healthy because both local network and internet connectivity are working correctly.

## Isolating the Root Cause: DNS or Network?

### Testing DNS vs. network layer

In this step, I'm testing DNS resolution and the network route to a website so that I can determine whether the website loading issue is caused by DNS problems or a connectivity issue along the network path.

### nslookup and tracert results

I ran nslookup and saw that google.com successfully resolved to the IP address 142.251.216.142, confirming that DNS resolution is working correctly. Then tracert showed a route of 10 hops to reach the destination, which tells me that network traffic is successfully passing through the required routers and reaching the website. Overall, the network appears to be healthy, with no DNS or connectivity issues detected.

## Writing a Professional Support Ticket

### Documenting findings professionally

In this step, I'm writing a support ticket that documents all of my diagnostic findings so that I can provide a clear and complete record of the investigation for other technicians or a Level 2 engineer to review.

![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_7fhhqfd8)

### Root cause conclusion

Based on my findings, I concluded that the issue was likely browser-related or temporary because the computer's hardware was performing normally, no system errors were detected, network connectivity was working correctly, and DNS resolution was successful. All diagnostic tests passed, indicating that the problem was not caused by the hardware, operating system, or network infrastructure.

## Bonus: Flushing DNS and Verifying the Fix

![Image](https://nextwork.ai/proud_blue_vibrant_quince/uploads/c36a769f-5c05-48ec-8533-39be6745932f_3k6l5ygx)

### Resolution documented in support ticket

In this project extension, I documented the before state, which showed that google.com already had a cached DNS record when I ran ipconfig /displaydns | findstr /i google. The action I took was running ipconfig /flushdns, which successfully cleared the DNS Resolver Cache and displayed the confirmation message "Successfully flushed the DNS Resolver Cache." The after state confirmed that a fresh lookup of google.com resolved to IP address 192.178.54.14 and that a new DNS cache entry for google.com was created when I ran ipconfig /displaydns | findstr /i google again.

## Reflections and Key Takeaways

### Tools and concepts learned

The key tools I used include Command Prompt, Task Manager, DNS diagnostic commands (ipconfig, ping, and nslookup), and Notepad for documenting troubleshooting steps in a support ticket.
Key concepts I learnt include how to diagnose Windows network issues, view and clear the DNS cache, verify network connectivity using ping, perform DNS lookups with nslookup, monitor system processes with Task Manager, and document troubleshooting activities by recording the before state, actions taken, and after state for support purposes.

### Time and challenges

This project took me approximately one day and a few hours to complete. The most challenging part was troubleshooting the DNS-related issues, understanding how the DNS cache works, and verifying that the cache was successfully cleared and rebuilt using the appropriate Windows diagnostic commands while accurately documenting the process in the support ticket.

### Looking ahead

I did this project today to learn how to diagnose and troubleshoot a broken Windows PC using built-in tools such as Command Prompt, Task Manager, ping, nslookup, and ipconfig, as well as how to document troubleshooting steps in a professional support ticket.
Another skill I want to learn is advanced Windows system administration, including event log analysis, network troubleshooting, Active Directory management, and automated system maintenance using PowerShell.

---

*Built with [NextWork](https://nextwork.ai) - [View this project](https://nextwork.ai/projects/c36a769f-5c05-48ec-8533-39be6745932f)*
