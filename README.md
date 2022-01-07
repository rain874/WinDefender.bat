# WinDefender.bat
Windows 10 Defender starten und nach fullScan runterfahren


```start cmd.exe /k "C: && cd \Program Files\Windows Defender && MpCmdRun.exe -SignatureUpdate && MpCmdRun.exe Scan -ScheduleJob -ScanTrigger 55 -IdleScheduledJob && shutdown.exe /s /t 00"```
