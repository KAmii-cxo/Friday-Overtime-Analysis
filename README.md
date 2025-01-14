# Friday Overtime Analysis VM
	
1. Start the vm. We can open Docintel platform using credential below
	
	![image](https://github.com/user-attachments/assets/5ebfa7be-92cb-4531-ac1d-ad314bdbf765)

	
2. Once login, we are in the dashboards. We can see the name Erica Tracy, files and document attachment for analysis.
	
	![image](https://github.com/user-attachments/assets/8d690778-9a21-4d1a-bf48-c8f124770915)

	
3. Click on the title Urgent: … Read the details, and download the samples too.
	
	![image](https://github.com/user-attachments/assets/5355b424-2db8-4a16-a931-23a942538c29)

	
4. After download, go to File Manager and open with Archive Manager. The password is Panda321. I did hands-on labs on malware analysis before. So this is standard practice during analysis to enter the password given by other teams. 
	
	![image](https://github.com/user-attachments/assets/ceb28e1c-0c9c-48dc-9d85-ad3f503e7ff8)

	
5. Before we dive into answering this, let's explore some details first. Here, we know that the malware infected over 9000 systems and it's huge. So be smart, don't dig into it longer than needed because it must be other researchers did the analysis. So be smart.
	
	![image](https://github.com/user-attachments/assets/581186ab-d9bb-4797-be94-3cb1d3ca8869)

	Here the first answer. The sample is from Oliver Bennett.
	
	![image](https://github.com/user-attachments/assets/994448e5-eb40-4228-808e-0db363cc5c55)

	
6. Go to the terminal and command sha1sum pRsm.dll (this is the file name) 
	
	![image](https://github.com/user-attachments/assets/8ee11678-76d1-43e5-8931-e38bfeacf595)

7. Let's dig some more information. The malware framework utilizes there DLLS is MgBot
	
	![image](https://github.com/user-attachments/assets/0ec1b658-ebce-4b34-9394-31f9a7ce48f6)

	
8. T1123 is the MITRE ATT&CK technique attack linked to the malware.
	
	![image](https://github.com/user-attachments/assets/3ba09250-dc10-4991-8c80-fdad3c828e6e)

	
9. Now let's find CyberChef defanged URL. Answer: hxxp[://]update[.]browser[.]qq[.]com/qmbs/QQ/QQUrlMgr_QQ88_4296[.]exe
	
	![image](https://github.com/user-attachments/assets/6820d64e-eae8-4eaa-8181-e9b59fa11397)

	
10. First copy the IP address and go to Cyberchef. The defanged IPaddress 122[.]10[.]90[.]12
	
	![image](https://github.com/user-attachments/assets/cf1a0a60-b452-4b0e-b863-66d6200a4c96)

	![image](https://github.com/user-attachments/assets/e8fb93b9-4ccb-4d76-8a95-5999cf0d5637)

	
11. Go to the VirusTotal. On relations tab, go to Communication Files - Android. The, go to details to look at sha1
	
	![image](https://github.com/user-attachments/assets/827bf4dd-50a3-4617-8124-291ce1f6791e)

	![image](https://github.com/user-attachments/assets/b7e3244b-fac5-4120-8bcf-4c10c33daa5c)

	## Congrats! We complete the Friday Overtime Room!! 
