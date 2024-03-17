# Intro-To-Network-Traffic-Analysis
<a href="https://academy.hackthebox.com/achievement/1195604/81"> <img src="https://img.shields.io/badge/Network_Traffic_Analysis-purple?style=for-the-badge&logo=Hack%20the%20box&logoColor=green" /> </a>

## Description
This project introduces network traffic analysis in a general sense for both offensive and defensive security practitioners, covering principles of NTA and the usage of traffic analysis tools such as Wireshark and tcpdump.


## Languages and Technologies Used

- <b>Wireshark</b>
- <b>TCPdump</b>
- <b>Tshark</b>

- <b>Bash Shell</b>

## Environments Used 

- <b>Parrot OS</b>
- <b>Windows 11</b> (23H2)

## Program walk-through
<p align="left">
First started by defining the network traffic analysis process and its key components, followed by the different types of analysis (Descriptive, Diagnostic, and Predictive) and their implementation on a basic workflow template as shown in the following example: <br/>

 ![NTA_Workflow](https://github.com/RodolfoMBD/Intro-To-Network-Traffic-Analysis/assets/163322012/62e2a712-ab62-489e-a678-58d5e29769c9)
<p>&nbsp;</p>

<p align="left">
Then moved over to TCPdump fundamentals and the process of capturing, analyzing, and identifying network traffic from different interfaces, as well as writing the captures to a .pcap file to read later for post-capture analysis, and applying basic TCPdump filters: <br/>

 ![2-NTA_TCPdump_StartCapture](https://github.com/RodolfoMBD/Intro-To-Network-Traffic-Analysis/assets/163322012/21965a65-aa21-470c-a06b-12919e8c3e49)
 
![3-NTA_TCPdump_Write ReadCapture](https://github.com/RodolfoMBD/Intro-To-Network-Traffic-Analysis/assets/163322012/2e22bb8f-cced-4d41-949c-7c843936c549)
<p>&nbsp;</p>

<p align="left">
Finally moved over to Wireshark and its CLI version Tshark, in which I practiced running captures, writing them to .pcap files, applying basic filters, exploring advanced plugins and functions, as well as packet inspection, and traffic dissection : <br/>

![4-NTA_Wireshark](https://github.com/RodolfoMBD/Intro-To-Network-Traffic-Analysis/assets/163322012/effd39e3-65d6-455a-874b-4002c6c02798)

![5-NTA_Wireshark](https://github.com/RodolfoMBD/Intro-To-Network-Traffic-Analysis/assets/163322012/97205342-920d-439f-ac46-e5eaae35cd26)
![6-NTA_Wireshark](https://github.com/RodolfoMBD/Intro-To-Network-Traffic-Analysis/assets/163322012/322870f5-6889-4411-8685-9dcbab12d998)

 
## Conclusion

This project covered network traffic analysis principles and discussed the implications for both blue team and red team personnel. Got hands-on experience using Wireshark, Tshark, and tcpdump to learn different ways of sniffing out  and filtering for sensitive related data transversing through the network. Also covered general network traffic analysis methods and the security implications of having no visibility into the network.
