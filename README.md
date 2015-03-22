Standalone Executable to check for simple privilege escalation vectors on Windows systems

Windows-privesc-check is standalone executable that runs on Windows systems (tested on XP, Windows 7 only so far).  It tries to find misconfigurations that could allow local unprivileged users to escalate privileges to other users or to access local apps (e.g. databases).  

It is written in python and converted to an executable using pyinstaller so it can be easily uploaded and run (as opposed to unzipping python + other dependencies).  It can run either as a normal user or as Administrator (obviously it does a better job when running as Administrator because it can read more files).

Ignore the main branch.  See https://github.com/pentestmonkey/windows-privesc-check/tree/wpc-2.0

Also see: http://pentestmonkey.net/tools/windows-privesc-check/ (coming soon).
