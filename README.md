# Wireshark
<h1>Description </h1>
 Utilize Wirehsark to capture packets and use filters to observe website traffic.  </h1>

<br />


<h2>Utilities Used</h2>

- <b>Ubuntu</b>
- <b>Wireshark</b>


<h2>Program walk-through:</h2>

<p align="center">
Step 1: Add user to Wirehsark group<br/>
<img src="https://i.imgur.com/7Z2pUY8.png" height="80%" width="80%" alt="Add User"/>
<br />
<br />
Step 2: Start a packet capture on an ethernet port and save it to a file <br/>
<img src="https://i.imgur.com/8aouJDZ.png" height="80%" width="80%" alt="Capture"/>
<br />
<img src="https://i.imgur.com/6Rg7bzM.png" height="80%" width="80%" alt="Save"/>
<br />
<br />
Step 3: Use a display filter to detect HTTPS packets<br/>
<img src="https://i.imgur.com/DOcX7YJ.png" height="80%" width="80%" alt="Display filter https/443"/>
<br />
<br /> 
Step 4: Visit a web page and detect its IP address using a display filter <br/>
<img src="https://i.imgur.com/S3Jh0by.png" height="80%" width="80%" alt="enable DHCP"/>
<br />
<br />
Step 5: Locate all HTTPS packets from a capture not containing a certain IP address<br />
<img src="https://i.imgur.com/WLrNPu9.png" height="80%" width="80%" alt="enable DHCP"/>  
<br />
</p>
