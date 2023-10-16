DISCLAIMER:



The scripts available in this GitHub repository are designed to automate functions of the aircrack-ng suite. Their primary intent is for educational purposes and legal, ethical use, specifically to facilitate security assessments of wireless networks to which you have explicit authorization.

DEFINITIONS:
Ethical Use refers to the use of these scripts in manners that do not harm, exploit, or intrude on the privacy or rights of others.
Legal Authorization refers to having explicit permission from the rightful owner or administrator of the wireless network to conduct security assessments using these scripts.

1. LEGAL USE ONLY: These scripts must only be employed on networks where you have explicit legal authorization. Unauthorized access to wireless networks is illegal and punishable by law. Comply with all local, state, and international laws when using these scripts.
2. EDUCATIONAL PURPOSE: These scripts are shared with an educational objective, aimed at helping individuals to understand wireless network security and protect their own networks through legal and ethical hacking practices.
3. NO WARRANTY: These scripts are provided as is, without any guarantees. The creator disclaims any liabilities or damages that might arise from the use or misuse of these scripts.
4. RESPONSIBLE REPORTING: If your use of these scripts uncovers vulnerabilities, you are encouraged to report these findings responsibly to the appropriate parties to enhance network security rather than exploiting them for malicious purposes.
5. MODIFICATION: Users are allowed to modify the scripts but must retain this disclaimer and any original attribution. Distributing or selling these scripts without explicit permission from the creator is prohibited.
6. JURISDICTION: Users are responsible for understanding and adhering to all laws and regulations in their respective countries or regions.
7. INDEMNIFICATION: Users agree to indemnify the creator against any claims, losses, or damages resulting from their use or misuse of these scripts.
8. CONTACT: For queries or concerns related to this disclaimer or the scripts, contact Andrew Lobenstein at andrew@lobenstein.org
9. LIMITATION OF LIABILITY: In no event shall the creator be liable for any damages whatsoever resulting from the use or inability to use these scripts.
10. OPEN SOURCE LICENSE: These scripts are open source under the GNU Affero General Public License v3.0. Users must comply with the terms of this license in all uses of the scripts.
11. REVISION DATE: This disclaimer was last updated on October 1, 2023.

By accessing, downloading, or using these scripts, you affirm that you have read, understood, and agreed to these terms. If not in agreement, refrain from using these scripts.

The creator reserves the right to update or modify this disclaimer without prior notice.



DESCRIPTION:


Bash Script that can be run on Kali Linux, to set up a wireless access point. Once the access point is set up, the user can connect to the WiFi network and proceed to capturing the and cracking the WPA handshake, using a wireless interface, followed by a dictionary attack on the captured handshake. This script requires 2 wireless interfaces - one for the wireless network and another for capturing the WPA handshake. This script can be run on a VM or a physical device, such as a raspberry pi. 
