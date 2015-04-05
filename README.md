## Standalone Executable to Check for Simple Privilege Escalation Vectors on Windows Systems

Windows-privesc-check is standalone executable that runs on Windows systems.  It tries to find misconfigurations that could allow local unprivileged users to escalate privileges to other users or to access local apps (e.g. databases).  

It is written in python and converted to an executable using pyinstaller so it can be easily uploaded and run (as opposed to unzipping python + other dependencies).  It can run either as a normal user or as Administrator (obviously it does a better job when running as Administrator because it can read more files).

The latest version of the code is in the master branch.

