# Android-ImGui-Mod-Menu
Android Internal ImGui Mod Menu Template with remap hide

# Features
- [x] Any Android Version
- [x] Any Game Supported
- [x] Arm64 Support
- [x] x86 Support
- [x] Test UI Without having to implement into game 

# Implementation
1. Build the APK in Android Studio
2. Open the APK in the zip program of your choice
3. Copy all the files from /lib/arm64-v8a/ to /lib/arm64-v8a of the game
   ![image](https://github.com/reveny/Android-ImGui-Mod-Menu/blob/main/img/264991616-75554869-54d2-4c18-b89b-70958246d300.png)
4. Find the games launcher activity and place the following code in the onCreate method
   ```
    const-string v0, "Loader"
    invoke-static {v0}, Ljava/lang/System;->loadLibrary(Ljava/lang/String;)V
   ```
   ![image](https://github.com/reveny/Android-ImGui-Mod-Menu/blob/main/img/264992884-d8e57355-6f62-427f-97b0-db6aa04f30fb.png)
5. Recompile the apk


# Credits
FIXED 15 ANDROID BY BLITCHCORE <br />
ImGui by ocornut: https://github.com/ocornut/imgui <br />
DobbyHook by jmpwes: https://github.com/jmpews/Dobby <br />
KittyMemory by MJx0: https://github.com/MJx0/KittyMemory <br />
OpenGL Test by JimSeker: https://github.com/JimSeker/opengl/tree/master <br />
ImGui Touch by fedes1to: https://github.com/fedes1to/Zygisk-ImGui-Menu <br />

# Contact
Telegram Group: https://t.me/reveny1 <br>
Telegram Contact: https://t.me/revenyy

# Preview
 ![image](https://github.com/reveny/Android-ImGui-Mod-Menu/blob/main/img/ezgif.com-video-cutter%20(1).gif)
