# windows-setup
How to set up Windows 10

## Windows
- O&O ShutUp10: https://www.oo-software.com/en/shutup10
- Windows 10 Decrapifier: https://community.spiceworks.com/scripts/show/4378-windows-10-decrapifier-18xx-19xx-2xxx
- YES _ Windows 10: Cortana deinstallieren: https://www.netzwelt.de/anleitung/180485-windows-10-cortana-deinstallierenso-gehts.html
- Cortana vollständig deinstallieren: https://praxistipps.chip.de/cortana-vollstaendig-deinstallieren-so-gehts_44689
- Windows 10 OneDrive entfernen: https://www.netzwelt.de/tutorial/163642-windows-10-so-deinstalliert-onedrive.html
- OneDrive deinstallieren: https://www.heise.de/tipps-tricks/OneDrive-deinstallieren-so-geht-s-4975944.html
- WhyNotWin11: https://github.com/rcmaehl/WhyNotWin11

## Programs
- Mozilla Firefox: https://www.mozilla.org/en-US/firefox/all/
- Mozilla Thunderbird: https://www.thunderbird.net/en-US/thunderbird/all/
- Adobe Acrobat Reader DC: https://get.adobe.com/reader/otherversions/
- PDF24 Creator: https://tools.pdf24.org/en/creator
- VLC Media Player: https://www.videolan.org/vlc/#download
- Microsoft Office: https://www.office.com/
- LibreOffice: https://www.libreoffice.org/download/download/
- Google Chrome: https://www.google.com/intl/en-US/chrome/
- Notepad++: https://notepad-plus-plus.org/downloads/

## System tools
- Sysinternals Process Explorer: https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer
- Sysinternals Autoruns: https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns
- Greenshot: https://getgreenshot.org/downloads/ and https://github.com/greenshot/greenshot
- 7-Zip: https://www.7-zip.org/download.html

## Video telephony
- Microsoft Teams: https://www.microsoft.com/en-us/microsoft-teams/download-app
- Zoom: https://zoom.us/download
- Cisco Webex Meetings: https://www.webex.com/downloads.html

## WhyNotWin11
- Achitecture: 64bit instead of 32bit (CPU + OS)
- Boot method: UEFI instead of Legacy
- Disk partition type: GPT instead of MBR

## Uninstall Cortana
- Go to the Windows Desktop by pressing `Win` + `D`
- Right click on the Windows icon in the bottom left
- Click on `Windows PowerShell (Administrator)`
- Copy the following command:

```
Get-AppxPackage -allusers Microsoft.549981C3F5F10 | Remove-AppxPackage
```

- Paste it in the Windows PowerShell by pressing `Right click`
- Press Enter
