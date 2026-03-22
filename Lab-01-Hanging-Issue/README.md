Lab 01: Windows Hanging Issue
📌 Problem
The computer was freezing and very slow. Disk usage was reaching 100%.

🔍 Investigation
Opened Task Manager
Found Disk usage at 100%
Checked running processes
Identified WMI Provider Host
Investigated further using Details tab
🛠 Solution
Opened Services (services.msc)
Found SysMain service
Stopped SysMain
✅ Result
Disk usage dropped to 4%
System performance improved
🧠 What I Learned
How to troubleshoot high disk usage
How to use Task Manager and Services
Importance of identifying root cause
