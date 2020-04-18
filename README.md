# Weeks 10 & 11 Project: Honeypot

Harrison Luu

- GCP is set up with firewall setup
![GCP is set up](https://user-images.githubusercontent.com/43581439/79606489-ae52eb00-80bf-11ea-8428-5d74db2ea602.png)




- Setting up MHN
![MHN admin is set up](https://user-images.githubusercontent.com/43581439/79612958-a1d48f80-80cb-11ea-904b-496f90fca78f.png)

![MHN setup details](https://user-images.githubusercontent.com/43581439/79612964-a39e5300-80cb-11ea-9af0-dd8a17a5a963.png)




- MHN-admin is successfully set up!
![SSH fingerprint](https://user-images.githubusercontent.com/43581439/79612972-a7ca7080-80cb-11ea-91c9-b424d95a1fab.png)



- Honeypot-1 is successfully set up!
![honeypot-1 is set up](https://user-images.githubusercontent.com/43581439/79612952-9ed99f00-80cb-11ea-9c5b-8e0cdc8ac5cc.png)

![honeypot-1 is set up2](https://user-images.githubusercontent.com/43581439/79612954-a00acc00-80cb-11ea-8c56-cc9ef4fcac5f.png)



- MHN server webapp is successfully set up, but unable to login

![MHN server web app](https://user-images.githubusercontent.com/43581439/79625542-bfb7e980-80f7-11ea-858e-f69c86d53eb4.png)

![MHN server web map](https://user-images.githubusercontent.com/43581439/79625543-c0508000-80f7-11ea-8c19-9ae6a6822e97.png)




Honeypots deployed: Dionaea over HTTP

Issues encountered: 
  - Needed to be in administrator mode for GCP
  - Needed to set up a billable account for GCP free trial
  - Needed to be in administrator mode for MHN admin
  - Unable to log into MHN browser (I used my real email the first time I tried to get MHN running but it didnt work for either the login nor the password recovery feature. I attempted the manual python reset explained in pwnlandia's README for MHN but that didn't work either for my system.)
  
  Troubleshooting process/Confirmation of correct setup
 
- Celery is running so password retrieval should work but it doesn't for unspecified reason.
![celery is running](https://user-images.githubusercontent.com/43581439/79625537-be86bc80-80f7-11ea-832f-a53a80b6d7f1.png)

- Everything is running as it should be so why can't I log into the MHN web app

![making sure everything is working](https://user-images.githubusercontent.com/43581439/79625540-bfb7e980-80f7-11ea-8511-eef72fd9ead9.png)

- After hours of starting over and research over a few days, I decided to settle for partial credit from Overview & Setup.

![cleanup](https://user-images.githubusercontent.com/43581439/79625539-bf1f5300-80f7-11ea-9ce4-0d70a7b61099.png)  
  
Summary of data collected:

  - Number of attacks: 0
  - Number of malware samples: 0


Unresolved questions raised by data collected:
  - Why was I unable to login and why was the password retrieval tool not working despite celery-worker actively running?
