# Threat Hunting with Panache_Sysmon Config

0. Named Panache (see refreshing photo below) cuz it's a mix of a lot of APT reports, tested hacking tools, analyzed malwares, blog posts and MITRE ATT&CK framework.  
1. Sysmon schemaversion "4.1"
2. Main_Template.xml contains configuration of the less noisy sysmon event categories (i.e. WMI EventSubscription) and can be merged with any of the other event specific configuration files (i.e. Merge Main_Template.xml with ProcessCreate_config.xm to monitor process creation only).
3. Panache config covers more than 150 different attack techniques (including advanced ones) and also logs important and must to have events that can be processed at the SIEM end.
4. Example of evtx that are a result of testing Panache_Sysmon can be found in the ATT&CK EVTX repository (i.e. already tested against RedCanary Atomic RedTeam automated testing framework) 
5. Remember, exclude configuration section always depend on your own environment (so make sure to add to it any observed false positives)

                                            Let's Go Hunting, Maybe it's your day!


![alt text](https://raw.githubusercontent.com/sbousseaden/Panache_Sysmon/master/panache.jpg)
