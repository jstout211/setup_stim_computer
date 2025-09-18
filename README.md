# setup_stim_computer
Recipe to setting up task delivery computer

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
Install psychopy: https://www.psychopy.org/download.html <br>
Requires Git:  
```
conda create -n psychopy pip python=3.11   #currently highest supported py version (09/25)
conda activate psychopy
pip install psychopy 
```

### Install Mobaxterm for file transfer


### Install filezilla





