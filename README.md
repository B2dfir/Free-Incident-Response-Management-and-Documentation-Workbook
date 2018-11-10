# Free-Incident-Response-Management-and-Documentation-Workbook
A free incident response management and documentation Microsoft Excel workbook.

For more information, please see my blog:
https://b2dfir.blogspot.com/2018/11/free-incident-response-management-and.html

If you are planning ahead for an incident and have capacity to manage an incident response management platform, I would recommend looking at TheHive Project instead.

https://thehive-project.org/

## Overview
To give you a quick overview of the workbook, it contains the following worksheets which I will walk through in the remainder of this blog post:

Dashboard   
1.1 Identification   
1.2 Evidence   
1.3 Analysis   
1.4 IOCs   
2.0 Containment   
2.1 Containment Monitoring   
3.0 Remediation   
3.1 Remediation Monitoring   
4.0 Recovery   
4.1 Recovery Monitoring   
5.0 Lessons Learnt   
6.0 Communications 


### Dashboard
Tracks administration information about an incident such as the incident name, date, team members and a resolution summary (so you can easily remember what happened when referring to the workbook at a later date)

![Dashboard](https://1.bp.blogspot.com/-HK7lYjtR7LY/W-X8ACnxCoI/AAAAAAAAhuM/U0jiXK5Gcr0H2xu8a7xQOd3xcqALAJyKwCLcBGAs/s1600/Dashboard.PNG)

### 1.1 Identification
The purpose of 'Identification' is to capture details of who, what, when and where the incident was identified. This worksheet should also capture any initial response steps which were conducted with or without knowledge of the Incident Response team.

![Identification](https://2.bp.blogspot.com/-aBlW9RV_Ip4/W-Xtny_Ie8I/AAAAAAAAhsQ/ZVptsnIp5zgAz_5-eG6sSy-qoCX3ZJ2DwCLcBGAs/s1600/1.1%2BIdentification.PNG)

### 1.2 Evidence
The purpose of 'Evidence' is to capture details of what, when and where evidence was collected. This worksheet should not replace comprehensive acquisition notes or chain of custody forms, but rather provide a one page view of evidence acquired throughout the incident response.

![Evidence](https://2.bp.blogspot.com/-Ak2w9rrNJv0/W-XuNClQMsI/AAAAAAAAhsY/W_22Mz00u7srVqK9qXjKNNrHn65C5MpEgCLcBGAs/s1600/1.2%2BEvidence.PNG)

### 1.3 Analysis
The purpose of 'Analysis' is to capture details of analysis activities performed throughout the incident response. Example activities could include:
Review autorunsc.exe output for suspicious persistence entries.
Run psxview in volatility to identify suspicious processes

![Analysis](https://4.bp.blogspot.com/-W_tfkqOiBIk/W-XvcJ-pHaI/AAAAAAAAhsk/UF_UgKsiSnkWfiHfX4Ej0y0fV265nOFAQCLcBGAs/s1600/1.3%2BAnalysis.PNG)

### 1.4 IOCs
The purpose of 'Indicators of Compromise' (IOCs) is to capture details of IOCs identified throughout the incident. These can then be used for analysis activities and reference material. IOCs can fall into three categories:
Atomic: Data which cannot be broken down in to smaller parts (in the context of the intrusion). E.g. IP Addresses, email header info, domain names, strings.
Computed: Computational values identified in the context of the incident. E.g. Hash
Behavioural: Trends identified in actions/operations of the incident. E.g. Attacks occur during the hours of 12:00am and 02:00am.

![IOCs](https://2.bp.blogspot.com/-Ve7jwjy9UMk/W-Xv7I3f0MI/AAAAAAAAhss/SB4JAZyedAkL1BwhU-I2djgpAz_tP8fRACLcBGAs/s1600/1.4%2BIOCs.PNG)

### 2.0 Containment
The purpose of 'Containment' is to capture details of approvals and activities performed in order to limit the spread of an incident. Containment steps should be performed only once a reasonable understanding of the incident has been obtained. An ideal containment phase should lock an attacker/malware out of the IT environment (including backdoors, lateral movement and persistence mechanisms).

![Containment](https://4.bp.blogspot.com/-usZ1TD6hdlc/W-Xw9BLzIlI/AAAAAAAAhs4/4ejhYLybkAojLC4mhS1YDTAECuBYNBxoQCLcBGAs/s1600/2.0%2BContainment.PNG)

### 2.1 Containment Monitoring
The purpose of 'Containment Monitoring' is to capture details of monitoring performed in order to confirm the effectiveness of containment activities.

![Containment Monitoring](https://4.bp.blogspot.com/-Flj8b0FFmNk/W-XycvpxCrI/AAAAAAAAhtE/6aKA9IxQmeAUNXTZ9jFYED_QJuInSdPggCLcBGAs/s1600/2.1%2BContainment%2BMonitoring.PNG)

### 3.0 Remediation
The purpose of 'Remediation' is to capture details of approvals and activities performed in order to remove threats from the incident environment. This step should be performed after containment activities. Remediation steps should be planned and executed effectively over a short time frame, in order to completely remove presence of the threat from the environment (including backdoors, lateral movement and persistence mechanisms).

![Remediation](https://3.bp.blogspot.com/-rppzEPxKMok/W-Xy2uNzI3I/AAAAAAAAhtM/E8uLJ2X_X5ox1Xf9moEBqn97KTR2dE_NQCLcBGAs/s1600/3.0%2BRemediation.PNG)

### 3.1 Remediation Monitoring
The purpose of 'Remediation Monitoring' is to capture details of monitoring performed in order to confirm the effectiveness of remediation activities.

![Remediation Monitoring](https://1.bp.blogspot.com/-lz0Da83NhO4/W-XzbQtPHAI/AAAAAAAAhtY/z3clOSjfvK4V_N73PvI1sdjrq9XYkzT5wCLcBGAs/s1600/3.1%2BRemediation%2BMonitoring.PNG)

### 4.0 Recovery
The purpose of 'Recovery' is to capture details of approvals and activities performed in order restore the IT Environment to business as usual (BAU) functionality following containment and remediation steps.

![Recovery](https://3.bp.blogspot.com/-KcMCvmT_4qg/W-XzyG_FJvI/AAAAAAAAhtg/Wtv81CEMWiYdgJ0C87jkxkcu4sIIk7mxACLcBGAs/s1600/4.0%2BRecovery.PNG)

### 4.1 Recovery Monitoring
The purpose of 'Recovery' is to capture details of monitoring performed in order to confirm the effectiveness of recovery activities.

![Recovery Monitoring](https://)

### 5.0 Lessons Learnt
The purpose of 'Lessons Learnt' is to capture details of process, procedure and control improvements identified throughout the incident. New controls should also be assigned responsibility to ensure they are implemented.

![Lessons Learnt](https://3.bp.blogspot.com/-rGNoepbF_hE/W-X0h1s2u6I/AAAAAAAAhtw/vrUD7uDVUzMGOniyFcpHwWsrzgf-D_DFACLcBGAs/s1600/5.0%2BLessons%2BLearnt.PNG)

### 6.0 Communications
The purpose of 'Communications' is to capture details of internal and external communications issued by the Information Security team and/or company

![Communications](https://4.bp.blogspot.com/-yEPTZrMhZTM/W-X03_v96aI/AAAAAAAAht4/y7dZWbZK9QwjrchXwl3tqledgt6TjqkaACLcBGAs/s1600/6.0%2BCommunications.PNG)

