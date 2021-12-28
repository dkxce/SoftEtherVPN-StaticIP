## Custom Build (Server) with Static IP for Clients

**SoftetherVPN Server v4.38 Build 9765** (Dec 28, 2021) by [Milok Zbrozek](https://github.com/dkxce) with predefined static IP (IPv4) for users - **rtm stable**

Build with MSVS 2008 SP1 on XP win32 for Windows OS    
Tested on XP, Vista, Windows Server 2003 & Windows 10    

## Changes and Features Added:

Only Server Changes:

* **Static IPv4 for users by User Name**

    [vpnserver-with-static-IPs-L-x86.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-L-x86.exe) - L Build 9762 (Login) - Static IP by User Login    
    [vpnserver-with-static-IPs-L-x64.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-L-x64.exe) - L Build 9762 (Login) - Static IP by User Login
	
        How to set:
            - Static IP can be set as user name (example: 10.0.0.1)   
		
        How to use:
			1) Install Original Softether VP Server (v4.38-9760, link below)
			2) Stop SoftEther VPN Server (SEVPNSERVER) service
			3) Replace original vpnserver.exe file in C:\Program Files\SoftEther VPN Server with selected from above
			4) Run SoftEther VPN Server (SEVPNSERVER) service
			5) That's All	
		
* **Static IPv4 for users by User Note**

    [vpnserver-with-static-IPs-N-x86.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-N-x86.exe) - N Build 9763 (Note) - Static IP by User Note    
    [vpnserver-with-static-IPs-N-x64.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-N-x64.exe) - N Build 9763 (Note)  - Static IP by User Note
		
        How to set:
            - Static IP can be set as user note (example: IPv4: 10.0.0.1) 
		
        How to use:
			1) Install Original Softether VP Server (v4.38-9760, link below)
			2) Stop SoftEther VPN Server (SEVPNSERVER) service
			3) Replace original vpnserver.exe file in C:\Program Files\SoftEther VPN Server with selected from above
			4) Run SoftEther VPN Server (SEVPNSERVER) service
			5) That's All	

* **Static IPv4 for users by User Name or User Note**
		
    [vpnserver-with-static-IPs-LN-x86.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-LN-x86.exe) - LN Build 9761 (Login-Note) - Static IP by User Login (firstly) and Note    
    [vpnserver-with-static-IPs-LN-x64.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-LN-x64.exe) - LN Build 9761 (Login-Note) - Static IP by User Login (firstly) and Note
	
        How to set:
            - Static IP can be set as user name (example: 10.0.0.1)   
            - Static IP can be set as user note (example: IPv4: 10.0.0.1) 
            * IP sets from User Name, if User Name is not IP then try to set from User Note
		
        How to use:
			1) Install Original Softether VP Server (v4.38-9760, link below)
			2) Stop SoftEther VPN Server (SEVPNSERVER) service
			3) Replace original vpnserver.exe file in C:\Program Files\SoftEther VPN Server with selected from above
			4) Run SoftEther VPN Server (SEVPNSERVER) service
			5) That's All	

    [vpnserver-with-static-IPs-NL-x86.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-NL-x86.exe) - NL Build 9764 (Note-Login) - Static IP by User Note (firstly) and Login    
    [vpnserver-with-static-IPs-NL-x64.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-NL-x64.exe) - NL Build 9764 (Note-Login) - Static IP by User Note (firstly) and Login
	
        How to set:
            - Static IP can be set as user name (example: 10.0.0.1)   
            - Static IP can be set as user note (example: IPv4: 10.0.0.1) 
            * IP sets from User Note, if User Note is empty IP will try to set from User Name
		
        How to use:
			1) Install Original Softether VP Server (v4.38-9760, link below)
			2) Stop SoftEther VPN Server (SEVPNSERVER) service
			3) Replace original vpnserver.exe file in C:\Program Files\SoftEther VPN Server with selected from above
			4) Run SoftEther VPN Server (SEVPNSERVER) service
			5) That's All	

* **Static IPv4 for users from file or by User Name or User Note:**
		
    [vpnserver-with-static-IPs-FNL-x86.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-FNL-x86.exe) - FNL Build 9765 (File-Note-Login) - Static IP from file, if no from Note (firstly) and Login    
    [vpnserver-with-static-IPs-FNL-x64.exe](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/vpnserver-with-static-IPs-FNL-x64.exe) - FNL Build 9765 (File-Note-Login) - Static IP from file, if no from Note (firstly) and Login
	
        How to set:
            - Static IP can be set by user name in staticip.ini file
            - Static IP can be set as user name (example: 10.0.0.1)   
            - Static IP can be set as user note (example: IPv4: 10.0.0.1) 
            * IP sets from staticip.ini file; if file has no records or empty - ip will set from from User Note, then from User Name
            * staticip.ini file loads at first user login
		
        How to use:
			1) Install Original Softether VP Server (v4.38-9760, link below)
			2) Stop SoftEther VPN Server (SEVPNSERVER) service
			3) Replace original vpnserver.exe file in C:\Program Files\SoftEther VPN Server with selected from above
			4) Copy staticip.ini to C:\Program Files\SoftEther VPN Server folder and edit records in it
			5) Run SoftEther VPN Server (SEVPNSERVER) service
			6) That's All		
			
* **Full Archive**

    [softether-vpnserver_vpnbridge-v4.38-9761-with-static-ip-by-Milok-Zbrozek.rar](https://github.com/dkxce/SoftEtherVPN_Stable/releases/download/v4.38-9761/softether-vpnserver_vpnbridge-v4.38-9761-with-static-ip-by-Milok-Zbrozek.rar)

* **Original SofteherVPN**

    [SoftetherVPN v4.38-9760 rtm stable](https://github.com/dkxce/SoftEtherVPN_Stable/releases/tag/v4.38-9760-rtm)    
    [SoftetherVPN v4.38-9760 rtm stable](https://github.com/SoftEtherVPN/SoftEtherVPN_Stable/releases/tag/v4.38-9760-rtm)

**В данной версии добавлена поддержка статических IP для пользователей**

    - Логин (имя) пользователя может быть использовано как статический IP (версии L, LN, NL) (например, 10.0.0.1)
    - Заметка (примечания, Note) пользователя может быть использована как статический IP (версии N, LN, NL) (например, IPv4: 10.0.0.1)
    - В версии L: IP адрес назначается если он указан как имя (логин) пользователя   
    - В версии N: IP адрес назначается если он указан в примечании пользователя 
    - В версии LN: IP адрес сперва назначается из имени пользователя, а если имя пользователя не является адресом - исходя из примечания   
    - В версии NL: IP адрес сперва назначается из примечания, а если в примечании не указан -то из имени пользователя
    - В версии FNL: IP адрес задается в файле staticip.ini, если он пуст или в нем нет записей, то обрабатывается сперва примечание, а если в примечании IP не указан - то IP берется из имени пользователя (файл загружается при первом подключении пользователя)

<img src="https://raw.githubusercontent.com/dkxce/SoftEtherVPN_Stable/master/src/bin_modified/HOWTO_A.png" />   
<img src="https://raw.githubusercontent.com/dkxce/SoftEtherVPN_Stable/master/src/bin_modified/HOWTO_B.png" />   
<img src="https://raw.githubusercontent.com/dkxce/SoftEtherVPN_Stable/master/src/bin_modified/HOWTO_C.png" />   
<img src="https://raw.githubusercontent.com/dkxce/SoftEtherVPN_Stable/master/src/bin_modified/HOWTO_D.png" />   
<img src="https://raw.githubusercontent.com/dkxce/SoftEtherVPN_Stable/master/src/bin_modified/HOWTO_E.png" />   

Tags: Softether, VPN, SoftetherVPN, Static, Static IP, IP, DHCP, Predefined
