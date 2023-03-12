1. install adb tools on Debian based distros
` sudo apt-get install android-tools-adb `
2. uninstall google chrome via adb command
` adb uninstall --user 0 com.android.chrome `
3. uninstall google chrome via adbshell 
`pm list packages |grep chrome` 
`pm uninstall --user 0 com.android.chrome `
