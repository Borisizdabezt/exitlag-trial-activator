# exitlag-trial-activator-beta
Sorry gatolouco!

pip (or pip3) install tqdm (i forgot to put it on :(( )
How to use: (only work on GPT disk, exitlag must be installed on C:\)
0. Remember to create a recovery point or u will have bsod (dont panik)
1. Create a new Exitlag account
2. Use YourUninstall or RevoUninstall to uninstall Exitlag
3. Open https://www.uuidgenerator.net/ and use Bulk Version 4 UUID Generation by generate 1 HWID and copy it
4. Go to "Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlS et\Control\IDConfigDB\Hardware Profiles\0001"
5. Open HwProfileGuid and paste the new HWID between the parentheses { }
6. Then go to "Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Cryptography"
7. Open MachineGuid and paste the same HWID that we copy before.
8. Run CMD as admin
9. Open ( https://guidgenerator.com/ ) and Generate some GUIDs and copy the result
10. Type "bcdedit /default {"your hwid in step 9"}"
11. Type "bcdboot C:\Windows" to be sure that the windows boot thru the new HWID
12. Reboot and then choose "Windows 10 on volume 'x'" (do not choose windows 10 without on volume "x" or bsod)
13. Download Exitlag
14. Install Exitlag on C:\
15. Login with your exitlag account at step 1
16. Enjoy!



Contact me kostyliev-boris@mail.ru for bugs!
