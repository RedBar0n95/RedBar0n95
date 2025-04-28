## Hi there 👋

I’m currently working on using Azure, AWS, then GCS to setup Wazuh with MISP as an IoC database feed. I intend on taking the following actions:
- Next, I'm going to add logic to cycle through MISP, VirusTotal and AbuseIPDB sequentially in an effort to look for a match to what an agent has detected.
    - Next is to integrate Wazuh alerts with firewall connections so that DDOS attempts are dropped and black listed permanently after four(?) atempts. A geolocation filter will be activated to immediately exclude
    - entire countries from approaching the network firewall.
    - I'll figure out a way to collect metrics as to which feed has the highest match percentile. After a short period, I'll rearrange the order of the the IoC databases to promote the most effective feed.
    - I'll setup a test bench with earlier versions of Windows 10 and Linux, which will be internet-facing images, then I'll install the corresponding agents for log collection.
    - My next step is to download a large set of virii (200?) to test detection capability and IoC lookup function. I'll create a script to dacompress and execute them one by one.
    - Next, I'll activate the active response (XDR) function so that the above-mentioned compromises can be addressed with no human intervention.
    - What I need to figure out after that is some sort of case managment integration so that the event can be logged, populated sufficiently with information as to the Who, What, Where, When, Why and How of a given     - event.
    - I'm considering which integration(s) should be used to alert the proper people. High on the list is Slack along with email.
    - What would be great is an automation/integration that would reduce or cutoff network access of an infected machine if the SOAR function fails. Do I terminate the connection from the workstation side or the         - switch? Will Netbox or something else be able to handle this?
    - I will configure Wazuh to add every malicious source IP to its black list.
    - I have thought of setting up honeynets on other cloud providers to gather data on new or shifting attackers. Then use automation to feed their source IP to the Wazuh black list.
    - Long story short, I want to enable a system that will not only be extremely hard to slip by, but it will be bolstered to deal automatically so that no one has to run to the office or their remote system 
    - because the solution would have either eliminated or somehow effectively contained the threat.
    - The next step would be to carefully deploy the solution in phases. Document any anomalies, address them, then continue to the next target(s).
    - Have I missed something in my overall plan? I'd be interested to get feedback on what that could be. I love to keep up with the latest news, attacks, and breaches.
    
🌱 I’m currently learning Azure Funamentals. My long term goal is to become a Senior Cloud Engineer. I'm also weighing how I will integrate AI/ML into my function and the virtual infrastructure that I will be
    - managing.
    I'm also intent on taking TryHackMe's courses on SOC1 threat detection, correlation and remediation. Other courses I have interest in are for OWASP, WAF, and SQL attacks. They should make me more effective at
    - spotting threats and their blast radius. In the future, I intend on getting CompTIA Security+ and CISSP/CISA/CISM.

- 👯 I’m looking to collaborate on Qualys, Nessus, Splunk, Syslog, SNMP v2/v3, and Greylog.
- 🤔 I’m looking for help with threat detection and my studies as I've laid out above.
- ⚡ Fun fact: I used to work at the Wendy's location that was transformed into McDowell's in the film 'Coming To America!'
- 📫 How to reach me: Soon, I'll setup a Discord channel/group. Stay tuned!
- 
<!--
**RedBar0n95/RedBar0n95** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

## 🔭 I’m currently working on using Azure, AWS, then GCS to setup Wazuh with MISP as an IoC database feed. I intend on taking the following actions:
    - Next, I'm going to add logic to cycle through MISP, VirusTotal and AbuseIPDB sequentially in an effort to look for a match to what an agent has detected.
    - Next is to integrate Wazuh alerts with firewall connections so that DDOS attempts are dropped and black listed permanently after four(?) atempts. A geolocation filter will be activated to immediately exclude
    - entire countries from approaching the network firewall.
    - I'll figure out a way to collect metrics as to which feed has the highest match percentile. After a short period, I'll rearrange the order of the the IoC databases to promote the most effective feed.
    - I'll setup a test bench with earlier versions of Windows 10 and Linux, which will be internet-facing images, then I'll install the corresponding agents for log collection.
    - My next step is to download a large set of virii (200?) to test detection capability and IoC lookup function. I'll create a script to dacompress and execute them one by one.
    - Next, I'll activate the active response (XDR) function so that the above-mentioned compromises can be addressed with no human intervention.
    - What I need to figure out after that is some sort of case managment integration so that the event can be logged, populated sufficiently with information as to the Who, What, Where, When, Why and How of a given     - event.
    - I'm considering which integration(s) should be used to alert the proper people. High on the list is Slack along with email.
    - What would be great is an automation/integration that would reduce or cutoff network access of an infected machine if the SOAR function fails. Do I terminate the connection from the workstation side or the         - switch? Will Netbox or something else be able to handle this?
    - I will configure Wazuh to add every malicious source IP to its black list.
    - I have thought of setting up honeynets on other cloud providers to gather data on new or shifting attackers. Then use automation to feed their source IP to the Wazuh black list.
    - Long story short, I want to enable a system that will not only be extremely hard to slip by, but it will be bolstered to deal automatically so that no one has to run to the office or their remote system 
    - because the solution would have either eliminated or somehow effectively contained the threat.
    - The next step would be to carefully deploy the solution in phases. Document any anomalies, address them, then continue to the next target(s).
    
🌱 I’m currently learning Azure Funamentals. My long term goal is to become a Senior Cloud Engineer. I'm also weighing how I will integrate AI/ML into my function and the virtual infrastructure that I will be
    - managing.
    I'm also intent on taking TryHackMe's courses on SOC1 threat detection, correlation and remediation. Other courses I have interest in are for OWASP, WAF, and SQL attacks. They should make me more effective at
    - spotting threats and their blast radius. In the future, I intend on getting CompTIA Security+ and CISSP/CISA/CISM.
- 👯 I’m looking to collaborate on Qualys, Nessus, Splunk and Greylog. 
- 🤔 I’m looking for help with threat detection and my studies as I've laid out above.
- 💬 Ask me about ...
- 📫 How to reach me: Soon, I'll setup a Discord channel/group. Stay tuned!
- 😄 Pronouns: ...
- ⚡ Fun fact: I used to work at the Wendy's location that was transformed into McDowell's in the film 'Coming To America!'
-->
