# setup_stim_computer
Recipe to setting up task delivery computer <br>
Open a bplogix ticket for IT excemptions <br>

### Matlab
Download matlab: https://www.mathworks.com/downloads/ <br>
Install using nimh email address w/ sitewide license <br>

#### Psychtoolbox for matlab: 
http://psychtoolbox.org/download.html#Windows  <br>
may need to use mobaxterm for gstreamer download - required install for display to work w/ psychopy <br>
wget https://gstreamer.freedesktop.org/data/pkg/windows/1.22.12/msvc/gstreamer-1.0-msvc-x86_64-1.22.12.msi <br>
```
cd <<InstallDir>>
SetupPsychoToolbox   #Links gstreamer and some java utilities
```


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

### Eprime
Inst
Requires `.NET SP1 3.5 `


### Psychopy 
Install psychopy: https://www.psychopy.org/download.html <br><br>
Requires Git:  https://gitforwindows.org/ <br>
&nbsp;&nbsp;Use git bash / unix<>win conversions / add to all shells / use system certificate <br>
Requires C++ build tools: https://visualstudio.microsoft.com/downloads/#title-build-tools-for-visual-studio-2022 <br>
&nbsp;&nbsp;Download installer and add C++ / .NET and possibly other build tools <br>


```
conda create -n psychopy pip python=3.11   #currently highest supported py version (09/25)
conda activate psychopy
pip install psychopy 
```
##### Install parallel port drivers
Look up brand and model (startech seems to work reliably for us), download driver <br>
Install drivers >> manual >> find path to driver <br>

##### Find parallel port address (for pcie based ppt card)
control panel >> multifunction adapters >> Controller >> resources Tab >> Setting (first number in range)

##### Install drivers into the conda environment
pyschopy will complain about the parrallel port <br>
Download inpout from: https://www.highrez.co.uk/scripts/download.asp?package=InpOutBinaries   <br>
Copy those files into the conda/env/<<MYENV>>/bin  folder    <br>
Additional troubleshooting was discussed here: https://discourse.psychopy.org/t/parallel-port-issues-w-windows-11/45464/15

### Install Presentation (neurobehavioral systems)
https://neurobs.com/ <br>
Check email for software licenses from Brad

### Install Mobaxterm for file transfer


### Install filezilla





