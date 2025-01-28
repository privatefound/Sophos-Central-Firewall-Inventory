# Sophos-Central-Firewall-Inventory
Automated Python script for exporting firewall list from Sophos Central into custom Excel spreadsheets

Script Setup and configuration <br/>
<ol>
  <li>Log into your sophos central customer</li><br/>

![image](https://github.com/user-attachments/assets/98191389-2513-4cf6-9bd3-c1f26aba1465)

  <li>Create an API Token from the central</li><br/>

![image](https://github.com/user-attachments/assets/b25ba994-551a-478a-81a3-ec377dca2d5d)

![image](https://github.com/user-attachments/assets/2a6b9e9b-604e-4432-b357-0a6e2c6bd43d)

![image](https://github.com/user-attachments/assets/600ac056-13e6-48e7-af57-ab4fd9535ff6)

  <li>Edit the script</li>
    - Then edit the script by adding <strong>client id and client secret</strong> at line 10 and 11
<br/><br/>
  <li>Install dependencies</li>
    - <code>pip3 install openpyxl</code>
  <br/><br/>
  <li>Run the script</li>
    - <code>python3 script.py</code>
</ol><br/>

Sources: 
- https://developer.sophos.com/docs/firewall-v1/1/overview
- https://community.sophos.com/sophos-central-api/f/recommended-reads/120745/authenticating-to-sophos-central-apis
- https://developer.sophos.com/intro
