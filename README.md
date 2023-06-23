
*BCDEDIT Timer Settings*
bcdedit /set useplatformclock no
bcdedit /set useplatformtick yes
bcdedit /set disabledynamictick yes

*Changes to BCDEdit take effect after reboot*
*Reminder to disable HEPT in your BIOS.  If it's not there, it should already be off!*

*Remove BCDEDIT Timer Settings*
bcdedit /deletevalue useplatformclock
bcdedit /deletevalue useplatformtick
bcdedit /deletevalue disabledynamictick

*Changes to BCDEdit take effect after reboot*
*If you disabled HPET in your BIOS, you can re-enable it*

