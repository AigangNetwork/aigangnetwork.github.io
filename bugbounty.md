[back](https://aigangnetwork.github.io)  
  
# Aigang.Network Bug Bounty
2018-11-01 - 2018-11-30

## About

We are Aigang Team and we are targeting to build next-generation insurance product.

## Policy

We will evaluate reported security issues, bugs, features based on the impact to our users and the Aigang ecosystem.

This bounty brief describes the rules of the Aigang bug bounty program, as well as the eligibility of vulnerabilities and the rewards.

## Reward

Rewards will be paid out in AIX (Aigang Token). Once your submission is accepted the Aigang team will ask for your email address associated with your wallet to send your payment. 

Aigang may award an additional reward bonus for exceptional reports, or double up your reward if you submit a pull request with issue fix.
 
LEVEL 1  Critical: **$500 - $1000**    
LEVEL 2  Severe:   **$250 - $500**   
LEVEL 3  Moderate: **$60 - $150**     
LEVEL 4  Low:      **$0 - $60**     
 
*Please note that the TEAM will decide which level will be assigned for the issue and what reward will be paid.*  

*We created the form where you can register for reward: //TODO: Add Link*  

## Testing Targets
  
**website** - [https://testplatform.aigang.network/](https://testplatform.aigang.network/)  
**api** - [https://testapi.aigang.network/swagger/](https://testapi.aigang.network/swagger/)  
**android app** - [https://github.com/AigangNetwork/aigang-insurance-app/tree/master/android](https://github.com/AigangNetwork/aigang-insurance-app/tree/master/android)  
**insurance contracts** - [https://github.com/AigangNetwork/aigang-platform-contracts-insurance](https://github.com/AigangNetwork/aigang-platform-contracts-insurance)  
**prediction market contracts** -  [https://github.com/AigangNetwork/aigang-platform-contracts-predictions](https://github.com/AigangNetwork/aigang-platform-contracts-predictions)  

## Preparation For testing:

**Ropsten test network ETH**. You can generate them using Metamask browser extension ([https://metamask.io/](https://metamask.io/))  
**TESTAIX tokens** you can generate them using our faucet ([https://aigangnetwork.github.io/testaix/](https://aigangnetwork.github.io/testaix/))  
**Android device**  
**Valid user** registered on ([https://testplatform.aigang.network/](https://testplatform.aigang.network/))  
  
Whitelist your device ID in ([https://github.com/AigangNetwork/aigang-platform-web/issues/86](https://github.com/AigangNetwork/aigang-platform-web/issues/86)) to get more functionality for easier testing  

## Scenario:

 We setup:
- 1 datasheet with our model: 
-- Data - https://testplatform.aigang.network/data/2b6e482338504b0fa7f1d5bcf3874e02/
-- Model - https://testplatform.aigang.network/data/2b6e482338504b0fa7f1d5bcf3874e02/models/bb93ed105c9f4a2498ac981792c5d20f/
- 3 predictions with initial balances:
--// TODO Link to 1 prediction
--// TODO Link to 2 prediction
--// TODO Link to 3 prediction
- 1 Android battery insurance product
--// TODO Link to insurance product

## Bugs Registration  

All bugs should be registered here: [https://github.com/AigangNetwork/aigang-platform-web/issues](https://github.com/AigangNetwork/aigang-platform-web/issues) or by email: team@aigang.network  

Please note that only vulnerabilities with a working proof of concept that shows how it can be exploited or reproduced will be considered eligible for monetary rewards! Not reproducible or duplicate issues will be not rewarded.  

## Actions to avoid  

Testing on accounts other than those that you own  
Excessive request attempts  
Destruction of data  

## Ineligible issues  

Theoretical vulnerabilities without actual proof of concept  
Email verification deficiencies, expiration of password reset links, and password complexity policies  
Invalid or missing SPF (Sender Policy Framework) records (incomplete or missing SPF/DKIM/DMARC)  
Clickjacking/UI redressing with minimal security impact  
Email enumeration - For example, the ability to identify emails via password reset.  
Information disclosure with minimal security impact (stack traces, path disclosure, directory listings)  
Internally known issues, duplicate issues, or issues which have already been made public  
Tab-nabbing  
Vulnerabilities only exploitable on out-of-date browsers or platforms  
Vulnerabilities related to auto-fill web forms  
Use of known vulnerable libraries without actual proof of concept  
Lack of security flags in cookies  
Issues related to unsafe SSL/TLS cipher suites or protocol version  
Content spoofing  
Cache-control related issues  
Missing security headers that do not lead to direct exploitation  
CSRF with negligible security impact  
Vulnerabilities that require root/jailbreak  
Vulnerabilities that require physical access to a user's device  

## Communication Channels  
  
**Developers** - [https://gitter.im/AigangNetwork/Lobby](https://gitter.im/AigangNetwork/Lobby)  
**Telegram (community)** - [https://t.me/aigangnetwork](https://t.me/aigangnetwork)  
**Email** - team@aigang.network


## Extra information
Developers wiki page https://aigangnetwork.github.io/  [https://aigangnetwork.github.io/  ](https://aigangnetwork.github.io/   "https://aigangnetwork.github.io/  ")  
AIX faucet (Ropsten network)	[https://aigangnetwork.github.io/testaix/](https://aigangnetwork.github.io/testaix/ "https://aigangnetwork.github.io/testaix/")  
Documentation	[https://aigang.readthedocs.io/en/latest/](https://aigang.readthedocs.io/en/latest/ "https://aigang.readthedocs.io/en/latest/")  


*Company reserves the right, in its sole discretion, to modify this Program rules at any time.*

[back](https://aigangnetwork.github.io)  