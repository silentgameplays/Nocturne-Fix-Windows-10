# Nocturne-Fix-Windows-10
Nocturne Fix Windows 10

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support

1. Install Nocturne as Admin using this link: https://drive.google.com/drive/folders/1ThYlgFDNLV-hucyHvNGluROB1dBsCT1G?usp=sharing

2. Download/Copy/Paste all files from this preconfigured fix to the folder overwritting when necessary C:\Games\Terminal Reality\Nocturne

3. Change Compatibility on nocturne.exe to Windows XP SP 2>Run as Administrator

4. After Launching the game go to the settings Graphics and change Hardware mode to On if its not set

5. Set resolution to 640x480 (dont worry it is set to FHD in the Fix)

6. Run the game for the first time and configure keyboard settings (faster than waiting before running)
7. (Optional) Intro requires old indeo codec to play,but they dont display using the fix if you have VLC player use it to play the intro,location C:\Games\Terminal Reality\Nocturne\video
8.(Optional) On Windows Vista, Windows 7, Windows 8, Windows 8.1 and Windows 10, the Indeo video codec is integrated in the system but not registered. Open a command prompt ("Start" -> "Run..." -> type "cmd" or "command", click "OK") and execute the following commands :
# First change directory (64 bit Windows only): 
* cd C:\Windows\SysWOW64
# Register the .dll with this command : 
* regsvr32 ir50_32.dll


Enjoy the classic!
