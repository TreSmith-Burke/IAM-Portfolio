## Windows 11 Client Configuration

*Note: Before continuing ensure your DC is online as you will need it so the client can connect to it.*

1. Go through the setup screens. When you reach the edition selection screen, choose **Windows 11 Pro**.
	- Choosing Windows 11 Pro will allow the client to be able to connect to the domain.

 ![Windows 11 Pro Setup](images/15-%20Windows%2011%20Pro%20Setup.png)

2. Sign into your Local account with a password after completion of previous screens.
3. Once the computer powers back on, navigate to **Network and Internet** settings.
	- Locate **DNS server assignment** and click **Edit**
	- Enter the DNS settings. This should match 
	- This should match the same DNS as your DC.
	- Save settings.
	- You can confirm settings are correct by pinging the IP of the DC and DNS.

![Configured DNS Settings](images/16-Configured%20DNS%20Settings.png)

4. Right-click the start menu on the taskbar, then select System.
   - Scroll down to the option that says Domain and Workgroup.
   - Select Change.
   - In the **Computer Name/Domain Changes** window, select the Domain radio button.
5. Enter the domain name that you used to create the DC (e.g. `yourlab.local`).
	- You will be prompted to enter administrator credentials.
	- A dialog box will confirm that the client is now added to the domain. A restart is required to complete the domain join.

![Welcome to the Domain](images/17-Welcome%20to%20Domain.png)

6. Post domain join verification: 
- `ipconfig /all`

![ipconfig](images/18-ipconfig.png)

- `nslookup`

![nslookup](images/19-nslookup.png)

- On the DC: **Server Manager > Tools > Active Directory Users and Computers**, then expand your root domain (e.g., `lab.local`).
- Click the **Computers** container (this is where domain-joined computers live).
	- You'll see that the client is now added to the domain.

![ADUC](images/20-ADUC.png)
