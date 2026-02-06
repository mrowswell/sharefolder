<h1>JShare Folder</h1>

<h2>Description</h2>
Step by step demonstration how to have a shared folder on a domain network.
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Create a new folder in desired drive: <br/>
<img src="https://imagur.org/i/dTofcL1e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click > properties: <br/>
<img src="https://imagur.org/i/IKdiVlsR" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select sharing tab > click share:  <br/>
<img src="https://imagur.org/i/rAI0M3cY" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter Domain Users > Add: <br/>
<img src="https://imagur.org/i/GYMlBCz4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select read / write permissions:  <br/>
<img src="https://imagur.org/i/0H3KTiBf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter credentials:  <br/>
<img src="https://imagur.org/i/Iza7P8vw" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Folder has been shared:  <br/>
<img src="https://imagur.org/i/MJgv9Lzm" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Let's see if we can find the folder on the domain. Launch run: <br/>
<img src="https://imagur.org/i/NB1PEKml" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the domain:  <br/>
<img src="https://imagur.org/i/esfSFTdk" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right  click "this pc" > map network drive: <br/>
<img src="https://imagur.org/i/PoQbjsaD" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select desired drive > enter file path:  <br/>
<img src="https://imagur.org/i/YSDAiMrc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Shows the shared folder (it is empty):  <br/>
<img src="https://imagur.org/i/Db1i7RSV" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go back to this PC, see the shared folder:  <br/>
<img src="https://imagur.org/i/aD0Yjm6K" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login with another user on the domain to verify access:  <br/>
<img src="https://imagur.org/i/X0cAL3W9" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Shared folder is here:  <br/>
<img src="https://imagur.org/i/57jrntGf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
