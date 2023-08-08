# pshell

# Compile
`C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe  /reference:"C:\Windows\Microsoft.Net\assembly\GAC_MSIL\System.Management.Automation\v4.0_3.0.0.0__31bf3856ad364e35\System.Management.Automation.dll" /out:pshell.dll pshell.cs`

# Run 
`C:\Windows\Microsoft.NET\Framework64\v4.0.30319\InstallUtil.exe /logfile= /LogToConsole=false /U pshell.dll`
# Reference
This was taken virtually in entirety from here. The only modification that was done was the addition of an AMSI bypass. 
https://gist.github.com/addenial/0319ae7837c8d3d9701a
