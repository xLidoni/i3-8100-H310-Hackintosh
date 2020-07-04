# i3-8100 H310I Hackintosh OpenCore Catalina

OpenCore 0.5.9 Catalina for CoffeLake Architecture 

<b>Configuration</b>

Components    | Product Code
------------- | -------------
CPU           | I3 8100
MOTHERBOARD   | H310I-M Asus Prime
RAM           | Patriot Viper 3000MHz
GPU           | RX 580 Sapphire
SSD           | Silicon Power 500GB NVMe


<h4>What works?</h4>
<br>1. Audio </br>
<br>2. Keyboard & Mouse </br>
<br>3. Video with dedicated Graphics Card. </br>
<br>4. Apple Services</br>
<br>5. iGPU (I'm working on it) </br>

<h3>To modify the config.plist use this tool for windows or mac os:</h3>

https://github.com/corpnewt/ProperTree

<h3>Use integrated graphics or dedicated graphics</h3>
In my case i used dGPU (RX460) , so in <strong>ig-platform-id</strong> there is <strong>0300923E</strong> this is used when the Desktop iGPU is <strong>only</strong> used for computing tasks and doesn't drive a display.

<img src="https://dortania.github.io/OpenCore-Desktop-Guide/images/config/config.plist/coffeelake/DeviceProperties.png" width="400">

If you want use only iGPU you have to put this <strong>07009B3E</strong>

<h3>SMBIOS</h3>
For setting up the SMBIOS info, use CorpNewt's <a href ="https://github.com/corpnewt/GenSMBIOS">GenSMBIOS</a> application.


<h3>To create a vanilla hackintosh from scratch, you can follow this guide:</h3>

https://www.youtube.com/watch?v=6KGuINOyHh0

<img src="https://scontent-fco1-1.xx.fbcdn.net/v/t1.0-9/106893723_2823160104573775_8625142720928313998_o.jpg?_nc_cat=107&_nc_sid=09cbfe&_nc_ohc=5FXfChBFgr4AX_jiIaO&_nc_ht=scontent-fco1-1.xx&oh=ae019e5fd783a543ba9c2f1ab7354367&oe=5F24870C" width="400" >


