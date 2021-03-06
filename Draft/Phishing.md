##Phishing



TOC

* [General](#general)
* [Phishing Frameworks](#framework)
* [Phishing Guides](#guides)
* [Phishing Writeups](#writeup)





### Cull

#### End cull













------------------
###<a name="general>General</a>
[Phishing - wikipedia](http://www.en.wikipedia.org/wiki/Phishing):
* “Phishing is the attempt to acquire sensitive information such as usernames, passwords, and credit card details (and sometimes, indirectly, money) by masquerading as a trustworthy entity in an electronic communication.”

[Post exploitation trick - Phish users for creds on domains, from their own box](https://enigma0x3.wordpress.com/2015/01/21/phishing-for-credentials-if-you-want-it-just-ask/)

[Tab Napping - Phishing](http://www.exploit-db.com/papers/13950/)

[Top 10 Email Subjects for Company Phishing Attacks](http://www.pandasecurity.com/mediacenter/security/top-10-email-subjects-phishing-attacks/)









###<a name="framework">Phishing Frameworks:</a>

[Phishing Frenzy](http://www.phishingfrenzy.com/)
* Phishing Frenzy is an Open Source Ruby on Rails application that is leveraged by penetration testers to manage email phishing campaigns. The goal of the project is to streamline the phishing process while still providing clients the best realistic phishing campaign possible. This goal is obtainable through campaign management, template reuse, statistical generation, and other features the Frenzy has to offer.

[sptoolkit](https://github.com/sptoolkit/sptoolkit)
* Simple Phishing Toolkit is a super easy to install and use phishing framework built to help Information Security professionals find human vulnerabilities

[sptoolkit-rebirth](https://github.com/simplephishingtoolkit/sptoolkit-rebirth)
* sptoolkit hasn't been actively developed for two years. As it stands, it's a brilliant peice of software, and the original developers are pretty damn awesome for creating it. But we'd like to go further, and bring sptoolkit up to date. We've tried contacting the developers, but to no avail. We're taking matters into our own hands now.

[KingPhisher](https://github.com/securestate/king-phisher)
* King Phisher is a tool for testing and promoting user awareness by simulating real world phishing attacks. It features an easy to use, yet very flexible architecture allowing full control over both emails and server content. King Phisher can be used to run campaigns ranging from simple awareness training to more complicated scenarios in which user aware content is served for harvesting credentials.











------------------
### Tools

[CatMyFish](https://github.com/Mr-Un1k0d3r/CatMyFish)
* Search for categorized domain that can be used during red teaming engagement. Perfect to setup whitelisted domain for your Cobalt Strike beacon C&C.  It relies on expireddomains.net to obtain a list of expired domains. The domain availability is validated using checkdomain.com

[PhishBait](https://github.com/hack1thu7ch/PhishBait)
* Tools for harvesting email addresses for phishing attacks
* [Email Address Harvesting for Phishing](http://www.shortbus.ninja/email-address-harvesting-for-phishing-attacks/)

[SimplyTemplate](https://github.com/killswitch-GUI/SimplyTemplate)
* Phishing Template Generation Made Easy. The goal of this project was to hopefully speed up Phishing Template Gen as well as an easy way to ensure accuracy of your templates. Currently my standard Method of delivering emails is the Spear Phish in Cobalt strike so you will see proper settings for that by default.

[MailRaider](https://github.com/xorrior/EmailRaider)
* MailRaider is a tool that can be used to browse/search a user's Outlook folders as well as send phishing emails internally using their Outlook client.





------------------
### Microsoft Outlook/Exchange Stuff

[How to bypass Web-Proxy Filtering](https://www.blackhillsinfosec.com/?p=5831)

[Malicious Outlook Rules](https://silentbreaksecurity.com/malicious-outlook-rules/)

[EXE-less Malicious Outlook Rules - BHIS](https://www.blackhillsinfosec.com/?p=5544)

[Outlook and Exchange for the Bad Guys Nick Landers](https://www.youtube.com/watch?v=cVhc9VOK5MY)

[Outlook and Exchange for the Bad Guys Nick Landers](https://www.youtube.com/watch?v=cVhc9VOK5MY)

[Microsoft Support and Recovery Assistant for Office 365](https://testconnectivity.microsoft.com/)

[Exchange Versions, Builds & Dates](https://eightwone.com/references/versions-builds-dates/)

[morphHTA - Morphing Cobalt Strike's evil.HTA](https://github.com/vysec/morphHTA)

[Outlook and Exchange for the Bad Guys Nick Landers - Derbycon6](https://www.youtube.com/watch?v=cVhc9VOK5MY)

[Malicious Outlook Rules - Nick Landers](https://silentbreaksecurity.com/malicious-outlook-rules/)


------------------
### MS Office

[Exploiting Office native functionality: Word DDE edition](https://www.securityforrealpeople.com/2017/10/exploiting-office-native-functionality.html)

[Next Gen Office Malware v2.0 - Greg Linares Dagmar Knechtel - Hushcon17](https://prezi.com/view/eZ3CSNMxPMOfIWEHwTje/)








------------------
### Writeups

[How do I phish? – Advanced Email Phishing Tactics - Pentest Geek](https://www.pentestgeek.com/2013/01/30/how-do-i-phish-advanced-email-phishing-tactics/)

[Real World Phishing Techniques - Honeynet Project](http://www.honeynet.org/book/export/html/89)









------------------
### Talks/Presentations

[Three Years of Phishing - What We've Learned - Mike Morabito](http://www.irongeek.com/i.php?page=videos/centralohioinfosec2015/tech105-three-years-of-phishing-what-weve-learned-mike-morabito)
* Cardinal Health has been aggressively testing and training users to recognize and avoid phishing emails. This presentation covers 3 years of lessons learned from over 18,000 employees tested, 150,000 individual phishes sent, 5 complaints, thousands of positive comments, and a dozen happy executives. Learn from actual phishing templates what works well, doesn,t work at all, and why? See efficient templates for education and reporting results.

[Ichthyology: Phishing as a Science - BH USA 2017](https://www.youtube.com/watch?v=Z20XNp-luNA&app=desktop)

[Modern Evasion Techniques Jason Lang - Derbycon7](https://www.irongeek.com/i.php?page=videos/derbycon7/t110-modern-evasion-techniques-jason-lang)
* As pentesters, we are often in need of working around security controls. In this talk, we will reveal ways that we bypass in-line network defenses, spam filters (in line and cloud based), as well as current endpoint solutions. Some techniques are old, some are new, but all work in helping to get a foothold established. Defenders: might want to come to this one.