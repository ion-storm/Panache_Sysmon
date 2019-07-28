# Panache_Sysmon

Just another sysmon config:

1. Sysmon schemaversion "4.1"
2. Main_Template.xml contains configuration of the less noisy sysmon event categories (i.e. WMI EventSubscription) and can be merged with any of the other event specific configuration files (i.e. Merge Main_Template.xml with ProcessCreate_config.xm to monitor process creation only).
3. Panache config covers more than 150 different attack techniques and also logs important and must to have events that can be processed at the SIEM end.
4. Example of evtx that are a result of testing Panache_Sysmon can be found in the ATT&CK EVTX repository.

                                                   Happy Hunting
