# classic-windowstaskmanager
The Classic Windows Task Manager from Windows 11 22H2's recovery partition. This is identical to the one used in Windows 7.

## How can I get myself the copy of the same files in this repository?
It is super easy!
<br>
<br>
1.) Go into Settings and go to System>Restore>Advance Startup option then click the "Restart Now" twice.
<br>
2.) Wait and then click Troubleshooting then click Command Prompt.
<br>
3.) Then input the following codes:
<br>
<br>
C:
<br>
copy X:\windows\system32\taskmgr.exe
<br>
md en-us
<br>
cd en-us
<br>
copy X:\windows\system32\en-us\taskmgr.exe.mui
<br>
4.) Then type exit and press Continue to return to Windows.
<br>
5.) Find the executable (taskmgr.exe) on the root directory (C:/).
