<h1>Syetem Administration: Webserver and Backup Server (AWS)</h1>


<h2>Description</h2>
The purpose of this project is to create one virtual machine as a simple web server and another as an offsite back-up machine. The marketing team gets access to a web server, but they don’t need access to the back-ups or to be interfering with that.
<br />


<h2>Utilities Used</h2>

- <b>Amazon Web Services (AWS)</b> 
- <b>Linux: Ubuntu 20.0.04</b>
- <b>WordPress</b>
- <b>FireZilla</b>
- <b>Amazon S3</b>


<h2>Project walk-through:</h2>

<p align="center">
Creating and configuring Windows 10 VM: <br/>
<img src="https://i.imgur.com/49Bgf2F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Downloading Nessus:  <br/>
<img src="https://i.imgur.com/ovhNgMx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Disabling firewall on VM: <br/>
<img src="https://i.imgur.com/DtmSv82.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing uncredentialed Nessus Scan:  <br/>
<img src="https://i.imgur.com/hzQcijm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing credentialed Nessus Scan with no installed vulnerablities:  <br/>
<img src="https://i.imgur.com/sUPUStd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing vulnerable version of Firefox:  <br/>
<img src="https://i.imgur.com/UsAgeoz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nessus Scan with known vulnerabiltites:  <br/>
<img src="https://i.imgur.com/Q01PP0P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remediating Vulnerabilities (Uninstalling Firefox and updating Windows):  <br/>
<img src="https://i.imgur.com/d1blgKr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Performing last credential scan to ensure most critical vulnerabilties are remediated:  <br/>
<img src="https://i.imgur.com/2GgII9W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
