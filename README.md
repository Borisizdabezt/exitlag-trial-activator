# exitlag-trial-activator-beta


(reinstalling windows iz better than this)
(only work on GPT disk, exitlag must be installed on C:\)

How to use:
0. Remember to create a recovery point or u will have bsod (dont panik)
1. Create a new Exitlag account
2. Use YourUninstall or RevoUninstall to uninstall Exitlag
3. Open https://www.uuidgenerator.net/ and use Bulk Version 4 UUID Generation by generate 1 HWID and copy it
4. Go to "Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlS et\Control\IDConfigDB\Hardware Profiles\0001"
5. Open HwProfileGuid and paste the new HWID between { }
6. Then go to "Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Cryptography"
7. Open MachineGuid and paste the same HWID that we copy before.
8. Run CMD as admin
9. Open ( https://guidgenerator.com/ ) and Generate some GUIDs and copy the result
10. Type "Diskpart" --> Type "list disk" --> Type "select disk ( write disk number )" --> Type "uniqueid disk" --> Type "uniqueid disk id=(your guid at step 9)" no space after id= --> Type "exit"
11. Type "bcdedit /default "your hwid in step 9""
12. Type "bcdboot C:\Windows" to be sure that the windows boot thru the new HWID
13. Reboot and then choose "Windows 10 on volume 'x'" (do not choose windows 10 without on volume "x" or bsod)
14. Download Exitlag
15. Install Exitlag on C:\
16. Login with your exitlag account at step 1
17. Enjoy!



Contact me kostyliev-boris@mail.ru for bugs!
