
<img title="powerwiggle" alt="powerwiggle" src="https://github.com/K3rn4lP4nic/PowerWiggle/blob/main/PowerWiggle.png">

                                                                                          
# Powerwiggle
PowerWiggle is a simple PowerShell script that can be helpful for simulating a jiggler by using dummy keystrokes on the keyboard without the need to install any third-party applications.

## Usage
Open PowerShell and paste the script below. Then, press Enter.

```powershell
$wsh = New-Object -ComObject WScript.Shell; while (1) {$wsh.SendKeys('+{F15}'); Start-Sleep -seconds 59}
```
That's it! It will start running, and whenever you need to exit the script, press **CTRL+C**.

## How does it work?
The script is designed to continually simulate the pressing of the "Shift + F15" key combination at intervals of 59 seconds, without any apparent termination condition for the loop.
