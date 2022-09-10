# virus threat protection

[![virus threat protection](gett-stateed.png)](https://github.com/softwarelaab/virus.threat.protection/)

Virus & threat protection in Windows Security helps you scan for threats on your device. You can also run different types of scans, see the results of your previous virus and threat scans, and get the latest protection offered by Microsoft Defender Antivirus.

## How do I fix Virus threat protection?

* Complete the following steps to update your antivirus definitions.
* Select the Start menu.
* In the search bar, type Windows Security. Select the matching result.
* Select Virus & threat protection.
* Under Virus & threat protection updates, select Check for updates.

## Hide the Virus & threat protection section

* On your Group Policy management machine, open the Group Policy Management Console, right-click the Group Policy Object you want to configure and click Edit.
* In Group Policy Management Editor, go to Computer configuration and click Administrative templates.
* Expand the tree to Windows components > Windows Security > Virus and threat protection.
* Open the Hide the Virus and threat protection area setting and set it to Enabled. Click OK.
* Deploy the updated GPO as you normally do.

## Virus threat protection not working on Windows 11/10

**_If virus and threat protection not working on your Windows, follow the below suggestions:_**

* Run SFC and DISM
* Turn on Virus and threat protection settings
* Repair & Reset Windows Security
* Restart Windows Security Service
* Check your Date and Time settings
