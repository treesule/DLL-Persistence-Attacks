# DLL-Search-order-Hijacking

Place a malicious DLL file ahead of original DLL in search order<br />
Dll search order <br />
•	Application Installed Directory <br />
•	System Directory (C:\Windows\System32) <br />
•	16-bit System Directory (C:\Windows\System) <br />
•	Windows Directory (C:\Windows) <br />
•	Directories listed in %PATH% (Environment Variables) <br />

Based on the above DLL search order, for example test.exe needs to load ippsec.dll from Windows Directory (C:\Windows) but attacker place malicious ippsec.dll before Windows Directory (C:\Windows) i.e., at 16-bit System Directory (C:\Windows\System) so in this example test.exe loads malicious ippsec.dll from 16-bit System Directory (C:\Windows\System) as per Dll search order this is called DLL Search order Hijacking..<br />

Different testoutputs: <br />

![](images/Picture1.png) <br />
![](images/Picture2.png) <br />
![](images/Picture3.png) <br />
![](images/Picture4.png) <br />
![](images/Picture5.png) <br />
![](images/Picture7.png) <br />
