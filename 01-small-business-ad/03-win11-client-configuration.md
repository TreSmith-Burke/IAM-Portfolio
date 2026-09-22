## Windows 11 Client Configuration

1. Sign into your Local account with password after going through previous screens.
2. Change the name of the computer so its recognizable on the DC (Ex: Client 1).
   - You will be prompted to restart the computer so it applies the changes.
3. Once the computer powers back on, navigate to Network and Internet settings.
   - Configure the network settings but only edit the Preferred DNS.
   - This should match the same DNS as your DC.
   - Apply settings.
4. You can confirm settings are correct by pinging the IP of the DC and DNS.
5. From there, right click the start menu on the taskbar, then select System.
   - Scroll down to the option that says Domain and Workgroup.
   - Select Change.
   - In the Computer Name/Domain Changes dialog, select the Domain radio button.
6. Enter the domain name that you used to create the DC (e.g. `yourlab.local`).
7. You will be prompted to enter administrator credentials.
8. A dialog will confirm that the client is now added to the domain. A restart is required to complete the domain join.
