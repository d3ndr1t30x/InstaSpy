PASSWORD FOR ZIP FILE: infected

Pre-Install Procedures

You MUST disable Windows Defender for a smooth install. The best way to accomplish this is through Group Policy.

In Windows versions 1909 and higher, Tamper Protection was added. Tamper Protection must be disabled first, otherwise Group Policy settings are ignored.

    Open Windows Security (type Windows Security in the search box)
    Virus & threat protection > Virus & threat protection settings > Manage settings
    Switch Tamper Protection to Off

    It is not necessary to change any other setting (Real Time Protection, etc.)

    Important! Tamper Protection must be disabled before changing Group Policy settings.

To permanently disable Real Time Protection:

    Make sure you disabled Tamper Protection
    Open Local Group Policy Editor (type gpedit in the search box)
    Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Antivirus > Real-time Protection
    Enable Turn off real-time protection
    Reboot

    Make sure to reboot before making the next change

To permanently disable Microsoft Defender:

    Make sure you rebooted your machine
    Open Local Group Policy Editor (type gpedit in the search box)
    Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Antivirus
    Enable Turn off Microsoft Defender Antivirus
    Reboot

PASSWORD FOR ZIP FILE: infected
