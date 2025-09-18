# setup_stim_computer
Recipe to setting up task delivery computer <br>
Open a bplogix ticket for IT excemptions <br>

### Matlab
Download matlab: https://www.mathworks.com/downloads/ <br>
Install using nimh email address w/ sitewide license <br>

### Install Miniconda 
Download miniconda .... <br>
Install for all users and make it systemwide py <br>
Open miniconda powershell <br>
<br>
In file browser share C:\ProgramData\miniconda3\.condarc  with logged in admin user <br>
Edit file with notepad: 
```
channels:
  - conda-forge

channel_priority: strict
```

### Psychopy 
Install psychopy: https://www.psychopy.org/download.html <br><br>
Requires Git:  https://gitforwindows.org/ <br>
&nbsp;&nbsp;Use git bash / unix<>win conversions / add to all shells / use system certificate <br>
Requires C++ build tools: https://visualstudio.microsoft.com/downloads/#title-build-tools-for-visual-studio-2022 <br>
&nbsp;&nbsp;Download installer and add C++ and other build tools (can't remember which ones) <br>


```
conda create -n psychopy pip python=3.11   #currently highest supported py version (09/25)
conda activate psychopy
pip install psychopy 
```

### Install Presentation (neurobehavioral systems)
https://neurobs.com/
Check email for software licenses from Brad

### Install Mobaxterm for file transfer


### Install filezilla





