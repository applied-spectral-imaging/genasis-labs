## Configuring ASI Lab hosts in local hosts file
To use ASI Lab, clients hosts entries must be added to the local machine host file.

### Manually configuring hosts file on Windows or MAC:
Add the following lines to hosts file:

```
# ASI - GenASIS Citrix Hosts
173.196.148.155                     INC-CTX-VDA1.genasis.local
173.196.148.156                     INC-CTX-VDA2.genasis.local
```

Instructions on how to manually configure hosts file: [How to modify the hosts file on Windows and Mac](https://www.godaddy.com/resources/skills/how-to-modify-the-hosts-file-on-windows-and-mac) 

### Configuring hosts file on Windows or MAC using ASI Lab scripts:
1. Download ASI Lab scripts
1. Download zip archive from: [https://github.com/applied-spectral-imaging/genasis-labs/releases/download/1.0/asi-lab.zip](https://github.com/applied-spectral-imaging/genasis-labs/releases/download/1.0/asi-lab.zip)
1. Extract zip archive to a local directory

### Windows
In extracted directory double click and execute ‘run-asi-host.bat’.
On successful configuration tool will output:
```
Setting ASI Lab hosts in local hosts file completed successfully
Press any key to continue...
```

### MAC
In extracted directory execute:
```
chmod +x run-asi-host-mac.sh
run-asi-host-mac.sh
```
For more information on how to execute shell scripts on mac:
- [How to Run Shell Script on Mac](https://techwiser.com/run-shell-script-mac/)
- [Intro to shell scripts in Terminal on Mac](https://support.apple.com/en-il/guide/terminal/apd53500956-7c5b-496b-a362-2845f2aab4bc/mac)
- [Run a script in Script Editor on Mac](https://support.apple.com/en-il/guide/script-editor/scpedt1069/mac)
