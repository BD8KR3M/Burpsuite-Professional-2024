# Burp Suite Professional Version 2024 #

* Install BurpSuite Pro ✔ (Win/linux/mac)
* You Can Make .EXE file ✔
* BurpSuite Full Version ✔
* Make .bat To .exe ✔


## Okay Follow Me Step By Step For Installation:<br>

1.    [Download](https://codeload.github.com/BD8KR3M/Burpsuite_Professional_2024/zip/refs/heads/main) or Clone This GitHub. 
2.    Download and Install Java and JDK.

      * [JAVA](https://javadl.oracle.com/webapps/download/AutoDL?BundleId=244068_89d678f2be164786b292527658ca1605)
      * [JDK](https://www.oracle.com/java/technologies/downloads/#jdk21-windows)
3. Download BurpSuite Pro Form Official WebSite. [Click Here](https://portswigger.net/burp/releases/download?product=pro&version=&type=Jar)
                                            
    Or, Download Burp Suite Pro--> 
    *  https://portswigger.net/burp/releases/download?product=pro&version=&type=Jar
4. Then Follow My Video 😂
    * Link: 

# If You Get Any Error:
 * Open CMD With Run As Administrator.
 * Then Execute This Command:

    ```  rd /s /q "%userprofile%\AppData\Roaming\BurpSuite\" ```

    ```reg delete "HKEY_CURRENT_USER\SOFTWARE\JavaSoft\Prefs\burp" /f ```

# Making .bat File  
``` 
@echo off
"[Your PATH]C:\Program Files\Java\jdk-21\bin\java.exe" ^
    "--add-opens=java.desktop/javax.swing=ALL-UNNAMED" ^
    "--add-opens=java.base/java.lang=ALL-UNNAMED" ^
    "--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED" ^
    "--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED" ^
    "--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED" ^
    "-javaagent:[YOUR PATH]D:\All app\Burp-Suite-Pro-main\burploader.jar" ^
    "-noverify" ^
    "-jar" ^
    "[YOUR PATH]D:\All app\Burp-Suite-Pro-main\burpsuite_pro_v2023.11.1.3.jar"
```
* Copy This Command
* Create New Empty Text File & Paste This Command 
* Save As (Burp) .bat Name

# Build .bat To .exe 
* Download Icon img file [Formet: .ico] For Using Burp.exe
* Download " Advanced BAT to EXE Converter" Software
    * [Download](https://www.battoexeconverter.com/)


## Follow Me 💋:
[<img src="https://github.com/dheereshagrwal/colored-icons/blob/master/public/icons/facebook/facebook.svg" alt="Facebook" width="32"/>](https://www.facebook.com/bd8kr3m) &nbsp;
[<img src="https://github.com/dheereshagrwal/colored-icons/blob/master/public/icons/instagram/instagram.svg" alt="Instagram" width="32"/>](https://www.instagram.com/Abm_Mujahid) &nbsp;
[<img src="https://github.com/dheereshagrwal/colored-icons/blob/master/public/icons/youtube/youtube.svg" alt="YouTube" width="39"/>](https://www.youtube.com/AbmMujahid) &nbsp;
[<img src="https://github.com/dheereshagrwal/colored-icons/blob/master/public/icons/linkedin/linkedin.svg" alt="LinkedIn" width="36"/>](https://www.linkedin.com/in/abmmujahid/)
