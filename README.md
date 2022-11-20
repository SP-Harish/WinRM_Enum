# WinRM_Enum
PS-Remoting enumeration

Cyber trends tend to come and go, but one popular technique we’re seeing currently is the use of living-off-the-land binaries. The living off the land technique provides attackers with an opportunity to fly under the radar. A legitimate tool is less likely to raise suspicions, and they can avoid a lot of detection methods such as Hash Values, IOCs, and signatures. LotL TTPs are becoming increasingly accessible within open-source and popular hacking frameworks and tools, such as MetaSploit, PowerSploit, Exploit Pack and more. Not to mention, commodity malware, which can be rented or purchased for cheap, already includes LotL functionality when sold.

The detection and analysis of LotL being used in cyberattacks is no longer indication of an advanced threat actor group or robust malware. Nevertheless, detection and mitigation still prove to be difficult for most organizations and even security teams.

The tool can be used internally to detect any misconfiguration/privileged access that had enabled powershell remoting, therby mitigating the risk of adversary's lateral movement within the network.

