# windows-productivity

## PowerToys

#### Pin windows to be always on top

  
  `Ctrl+Win+T`


#### PowerToys Runner for app search

  
  `Win+Space`

## Process explorer

https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer

## Keys setup

#### Disable Win+L

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\System
In the right pane, right-click and opt to create a new DWORD 32-bit value. Once you have done this, name it DisableLockWorkstation. Next, double-click on it, and in the Value Data space provided, give it a value of 1, Hexadecimal. Click OK.

## Git setup


    git config --global user.name "My Name"
    git config --global user.email "my-name@chromium.org"
    git config --global core.autocrlf false
    git config --global core.filemode false
    git config --global branch.autosetuprebase always

## Display settings

#### Color adjust

#### Turn off sensor monitoring

* Save the settings through clicking Apply and then OK
If you don’t find an Adaptive Display setting, your device might not have a built-in ambient light sensor.
* If you followed the instructions but the adaptive brightness didn’t change your auto-brightness setting, you’ll need to turn off the Sensor Monitoring service by pressing Win + R and typing services.msc. Then press Enter
* In the services window, click on the Sensor Monitoring Service which will lead to the service settings window
* Click Stop and select Disabled from the drop-down menu found next to the Startup type
