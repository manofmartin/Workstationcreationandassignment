<h1>Workstation Creation And Assignment</h1>

<h2>Description</h2>
In this demonstartaion we will be creating and assigning a workstation to our Active Directory server

<h2>List of Tools</h2>
- <b>KVM is my hypervisor of choice!</b></br>
- <b>Windows Server 2022 Domain</b>

<h2>Let's Begin!</h2>

<p align="center">
After launching KVM and creating a workstation instance we begin installing the workstation Windows OS: <br/>
<img src="https://i.imgur.com/Bprcll1.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/tvOLNNa.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/WkYv6dB.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Check the network configuration using ipconfig /all command against the Domain: <br/>
<img src="https://i.imgur.com/8Lfnxlz.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/YAd3oJN.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Change network configuration to match the Domain:<br/>
<img src="https://i.imgur.com/ctXBdbh.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/nLMt87N.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/ZQWR8iY.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
We will change the computer name settings to add the machine to the Domain:<br/>
<img src="https://i.imgur.com/sHLPrTw.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/st0wlgI.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/W6AmOe8.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
Now we can login as the Administrator and verify we are on the Domain:<br/>
<img src="https://i.imgur.com/ATfvcOO.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/MgVrkHx.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/gOfJINA.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/4noSHCV.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/B28LO1E.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/P6RgLue.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<img src="https://i.imgur.com/RLEy85y.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
There we have it! A workstation has been added to our Domain!
<img src="https://i.imgur.com/GdKPNPQ.png" height="80%" width="80%" alt="Windows 2022 KVM"/>
<br />
<br />
</p>





