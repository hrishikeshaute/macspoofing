# macspoofing
Developed a command-line tool to modify MAC addresses on Windows and Linux. Features include auto-revert, random generation, and registry-based spoofing for Windows interfaces. Useful for privacy testing, penetration testing, and system analysis.
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

MAC Spoofing Tool is used to:

Change the MAC address of a network interface temporarily or permanently.

Enhance privacy/anonymity (e.g., avoid device tracking on public Wi-Fi).

Bypass MAC-based network filters or restrictions.

Test network access controls in cybersecurity/ethical hacking contexts.
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
My Novelty
✅ Cross-platform (Windows & Linux) support.

✅ Automatic MAC reversion after a delay (--revert flag).

✅ Random MAC generation.

✅ Registry manipulation on Windows to support actual MAC spoofing (which many tools skip).

✅ CLI-based, user-friendly interface for scripting/integration.

✅ Clean Python-based implementation — easier to audit or extend.
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$4
first step is to open powershell and run it as admin 
check the first original mac address by ( Get-NetAdapter)
# Run as Administrator
1. python macspoofing.py -i "Wi-Fi" --random
2. python macspoofing.py -i "Ethernet" --mac 00:11:22:33:44:55 --revert  10
   any issue free to contact me
   www.linkedin.com/in/hrishikeshautepatil
