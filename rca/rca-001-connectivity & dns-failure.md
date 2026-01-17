RCA-001 Evidence Log
Title: DNS Resolution Failure / Connectivity Validation
Date: YYYY-MM-DD
Lab: Cisco Packet Tracer

============================================================
[1] TOPOLOGY / CONTEXT
- Devices: R1, R2, R3, DNS Server
- DNS Server IP: __________
- Test Hostname: __________

Screenshot Files:
- evidence/rca-001-topology.png
- evidence/rca-001-dns-gui.png

============================================================
[2] BEFORE STATE (SYMPTOMS)

Command(s):
ping <hostname>
Result:
<paste output here>

Command(s):
ping <DNS server IP>
Result:
<paste output here>

------------------------------------------------------------
[Interface Status]
Command(s):
show ip interface brief
Result:
<paste output here>

------------------------------------------------------------
[Routing Table Check] (optional)
Command(s):
show ip route
Result:
<paste output here>

------------------------------------------------------------
[DNS Client Config]
Command(s):
show run | include name-server|domain-lookup|domain-name
Result:
<paste output here>

============================================================
[3] FIX APPLIED

Command(s) used:
<type the commands you entered>

Notes:
- <what you changed and why>

============================================================
[4] AFTER STATE (VALIDATION)

Command(s):
ping <hostname>
Result:
<paste output here>

Command(s):
ping <destination IP>
Result:
<paste output here>

(Optional)
traceroute <destination IP>
Result:
<paste output here>

============================================================
[5] SUMMARY
- Root cause:
- Fix:
- Verification result:
============================================================
