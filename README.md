# 3vilGu4rd
This is a daemon process which make a programe runing all time.

![image](https://github.com/PDWR/3vilGu4rd/blob/main/images/logo.png)

3vilGu4rd is a permission maintenance tool. It is written in VBS and packaged into a binary file with a VBE suffix. In theory, all systems after xp can run. After testing, the permissions can be maintained normally in win7, win server 2008, win2019, win10 and win11.

![image](https://github.com/PDWR/3vilGu4rd/blob/main/images/1.png)


You can upload it to the victim's host when you get the host permission, run the program, and specify the backdoor Trojan or other commands to maintain the permission.
The operation method is as follows:
1. Upload the daemon 3vilGu4rd.vbe to the target host, and then upload the Trojan to the victim host (remote.exe, custom path)
2. Use CS shell to remotely call 3vilGu4rd.vbe to guard our Trojan program.

   3vilGu4rd.vbe (absolute path to Trojan) [process name]

When using the tool, be sure to use the absolute path of the Trojan. Failure to do so will result! ! !
![image](https://github.com/PDWR/3vilGu4rd/blob/main/images/2.png)

3. Double-click to run the program or use the shell to directly call the program, and the usage and precautions of the program will pop up. Do not execute directly in actual combat

![image](https://github.com/PDWR/3vilGu4rd/blob/main/images/3.png)

## This is the vedio about the trojan re-online after user log out!!!
[![3vilGu4rd -- re-online after log out](https://i.ytimg.com/vi/BjFGJIWzoQg/sddefault.jpg)](https://www.youtube.com/watch?v=BjFGJIWzoQg)


## This is the vedio about the trojan re-online after user restart machine!!!
[![3vilGu4rd -- re-online after restart machine](https://i.ytimg.com/vi/3sJ7Tt6wLhs/sddefault.jpg)](https://www.youtube.com/watch?v=3sJ7Tt6wLhs)


## Tool Features:
1. "Mother-child" type daemon process, the mother program has no shellcode or malicious code, reducing the risk of the mother program being discovered
2. The subroutine has a single function, reducing the detection of malicious programs caused by heuristic detection
3. Dynamic generation, using the "avalanche effect", the Hash value of each generated file is different
4. The program self-destructs, the program will self-destruct after executing the function, leaving no trace
5. The Trojan will restart when the user log out or restart the machine 
6. VBE format, good versatility, in theory, the system after XP can be used. VBE format is the encrypted version of VBS, the program code and encryption are relatively difficult to crack
7. At present, it can bypass the detection of do


stic anti-software (non-Trojan programs)


## This program is one of the 3vil-toolboxes, and subsequent programs will be updated through GitHub. The other tools you can follow my github or contact me.
## Submit [Issues](https://github.com/PDWR/3vilGu4rd/issues) on GitHub if you have any questions!
