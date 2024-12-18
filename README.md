
<p align="center">
  <a href="#"><img src="https://raw.githubusercontent.com/MelonixLoader/MelonixLoader.Installer/master/Resources/ML_Icon.png"></a>
  <a href="#"><img src="https://raw.githubusercontent.com/MelonixLoader/MelonixLoader.Installer/master/Resources/ML_Text.png"></a>
</p>

---

<p align="center">
	<a href="https://github.com/MelonixLoader/MelonixLoader/releases/latest"><img src="https://img.shields.io/github/v/release/MelonixLoader/MelonixLoader?label=latest&style=for-the-badge"></a>
	<a href="https://github.com/MelonixLoader/MelonixLoader/releases"><img src="https://img.shields.io/github/downloads/MelonixLoader/MelonixLoader/total.svg?style=for-the-badge"></a>
	<a href="https://github.com/MelonixLoader/MelonixLoader/graphs/contributors"><img src="https://img.shields.io/github/contributors/MelonixLoader/MelonixLoader?style=for-the-badge"></a>
	<a href="https://discord.gg/MNBMv8uvmS"><img src="https://img.shields.io/discord/1318707388936884276?label=discord&style=for-the-badge&color=blueviolet"></a>
</p>

---

## GENERAL INFORMATION:

- Debug Mode is for Development Purposes.  
Use it to help Develop and Debug MelonixLoader, Plugins, and Mods.
<br></br>
- All Logs are made in the created `MelonixLoader/Logs` folder in your Game's Installation Folder.
- All Plugins get placed in the created `Plugins` folder in your Game's Installation Folder.
- All Mods get placed in the created `Mods` folder in your Game's Installation Folder.
<br></br>
- [The Official Wiki](https://melonwiki.xyz)
<br></br>
- [Proxies](#proxies)
- [Launch Options](#launch-options)
- [Debugging](https://melonwiki.xyz/#/modders/debugging)
<br></br>
- [Linux Support (__WINE / STEAM PROTON / NATIVE__)](https://melonwiki.xyz/#/README?id=linux-instructions)
- [Android & Oculus Quest Support (__WIP__)](https://melonwiki.xyz/#/android/general)
<br></br>

| Usage Guides: |
| - |
| [INSTALLER](#how-to-use-the-installer) |
| [MANUAL USE](#how-to-manually-use-MelonixLoader) |

| Example Projects: |
| - |
| [TestPlugin](https://github.com/MelonixLoader/TestPlugin) |
| [TestMod](https://github.com/MelonixLoader/TestMod) |

| Nightly Builds: |
| - |
| [master](https://nightly.link/MelonixLoader/MelonixLoader/workflows/build/master) |
| [alpha-development](https://nightly.link/MelonixLoader/MelonixLoader/workflows/build/alpha-development) |
| [universality](https://nightly.link/MelonixLoader/MelonixLoader/workflows/build/universality) |

---

## ❤️ SPECIAL THANKS TO OUR WONDERFUL PATRONS ❤️

- **Givo**  
- **Florian Fahrenberger**  
- **Python**  
- **SirCoolness**  
- **SlidyDev**  

---

## REQUIREMENTS:

- [.NET Framework 3.5 Runtime](https://www.microsoft.com/en-us/download/details.aspx?id=21)
- [.NET Framework 4.7.2 Runtime](https://dotnet.microsoft.com/download/dotnet-framework/net472)
- [.NET Framework 4.8 Runtime](https://dotnet.microsoft.com/download/dotnet-framework/net48)
- [.NET 6.0 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/6.0#runtime-6.0.15)
- Microsoft Visual C++ 2015-2019 Re-distributable [[x86](https://aka.ms/vs/16/release/vc_redist.x86.exe)] [[x64](https://aka.ms/vs/16/release/vc_redist.x64.exe)]

---

## HOW TO USE THE INSTALLER:

1. Follow the Instructions in one of the Guides linked below.

| Installer Guides: |
| - |
| [INSTALL](https://github.com/MelonixLoader/MelonixLoader.Installer/blob/master/README.md#how-to-install-re-install-or-update-MelonixLoader) |
| [UPDATE](https://github.com/MelonixLoader/MelonixLoader.Installer/blob/master/README.md#how-to-install-re-install-or-update-MelonixLoader) |
| [RE-INSTALL](https://github.com/MelonixLoader/MelonixLoader.Installer/blob/master/README.md#how-to-install-re-install-or-update-MelonixLoader) |
| [UN-INSTALL](https://github.com/MelonixLoader/MelonixLoader.Installer/blob/master/README.md#how-to-un-install-MelonixLoader) |

---

## HOW TO MANUALLY USE MelonixLoader:

### UPDATE / RE-INSTALL:

1. Follow the Steps to [UN-INSTALL](#un-install)
2. Follow the Steps to [INSTALL](#install)


### INSTALL:

1. Make sure the Game is Closed and Not Running before attempting to Install.
2. Make sure you have all the [Requirements](#requirements) Installed before attempting to Install.
3. Download MelonixLoader [[x86](https://github.com/MelonixLoader/MelonixLoader/releases/latest/download/MelonixLoader.x86.zip)] [[x64](https://github.com/MelonixLoader/MelonixLoader/releases/latest/download/MelonixLoader.x64.zip)]
4. Extract the MelonixLoader folder from the MelonixLoader Zip Archive to the Game's Installation Folder.
5. Extract version.dll & dobby.dll from the MelonixLoader Zip Archive to the Game's Installation Folder.


### UN-INSTALL:

1. Make sure the Game is Closed and Not Running before attempting to UN-INSTALL.
2. Remove the version.dll & dobby.dll files from the Game's Installation Folder.
3. Remove the MelonixLoader folder from the Game's Installation Folder.

These additional steps below are OPTIONAL if you want to do a FULL UN-INSTALL.

4. Remove the Plugins folder from the Game's Installation Folder.
5. Remove the Mods folder from the Game's Installation Folder.
6. Remove the UserData folder from the Game's Installation Folder.

---

## START SCREEN CUSTOMIZATION:

- After Initial Launch the Start Screen will create a folder under `UserData/MelonStartScreen`
- Inside this folder it will create a `Themes` folder and a `Config.cfg` file for Customization Settings.
- You can also place Custom Themes in the created `Themes` folder.
- Inside `Config.cfg` you can set what Theme folder you would like to use.  
- If you set your Theme folder to `Random` it will randomly pick and load from existing Themes.  

- For Custom Themes you can place Custom Images in their Theme folder to further customize it.
- Listed below are the Compatible File Names and Extensions for the Custom Images.

| Compatible File Names |
| - |
| Background |
| Loading |
| Logo |

| Compatible Extensions |
| - |
| .gif |
| .png |
| .jpg |
| .jpeg |

---

## LAUNCH OPTIONS:

- These are additional Launch Options that MelonixLoader adds to the Game.
- These can be used to manipulate how MelonixLoader works.

| Argument | Description |
| - | - |
| --no-mods | Launches the Game without loading any Plugins or Mods |
| --quitfix | Fixes the Hanging Process Issue with some Games |
| --MelonixLoader.consolemode | Changes the Theme Display Mode of the Console [ Default = 0 ] |
| --MelonixLoader.consoleontop | Forces the Console to always stay on-top of all other Applications |
| --MelonixLoader.consoledst | Keeps the Console Title as Original |
| --MelonixLoader.hideconsole | Hides the Console |
| --MelonixLoader.hidewarnings | Hides Warnings from Displaying |
| --MelonixLoader.debug | Debug Mode |
| --MelonixLoader.maxlogs | Max Log Files [ Default: 10 ] [ NoCap: 0 ] |
| --MelonixLoader.loadmodeplugins | Load Mode for Plugins [ Default: 0 ] |
| --MelonixLoader.loadmodemods | Load Mode for Mods [ Default: 0 ] |
| --MelonixLoader.basedir | Changes the Proxy's Load Directory for the Bootstrap |
| --MelonixLoader.disablestartscreen | Disable the Start Screen |


- These ones below are Unity Engine specific Launch Options.

| Argument | Description |
| - | - |
| --MelonixLoader.unityversion | Allows you to Specify the Version of Unity Engine |
| --MelonixLoader.agfoffline | Forces Assembly Generator to Run without Contacting the Remote API |
| --MelonixLoader.agfregenerate | Forces Regeneration of Assembly |
| --MelonixLoader.agfregex | Forces Assembly Generator to use a Specified Regex |
| --MelonixLoader.agfvdumper | Forces Assembly Generator to use a Specified Version of Dumper |
| --MelonixLoader.disableunityclc | Disable Unity Console Log Cleaner |


- These ones below are Cpp2IL specific Launch Options.

| Argument | Description |
| - | - |
| --cpp2il.callanalyzer | Enables CallAnalyzer processor |
| --cpp2il.nativemethoddetector | Enables NativeMethodDetector processor |

---

## LOAD MODES:

- Load Mode Launch Options are a way to dictate how you want Mods or Plugins to Load.
- Below is the Compatible Values and what each of them do.

| Value | Action |
| - | - |
| 0 | Load Only if the File doesn't have the ".dev.dll" Extension |
| 1 | Load Only if the File has the ".dev.dll" Extension |
| 2 | Load All |

---

## CONSOLE DISPLAY MODES:

- Console Display Modes are built in Themes for the Console
- Below is the Compatible Values and what each of them do.

| Value | Mode |
| - | - |
| 0 | Normal |
| 1 | Magenta |
| 2 | Rainbow |
| 3 | Random Rainbow |

---

## PROXIES:

- The Proxy DLL is able to be Renamed to the Compatible File Names below.
- By Default the Proxy is named as "version.dll".
- For most Games the Default File Name should work perfectly fine.
- Some Games may have you use a different Proxy File Name depending on the Architecture, Operating System, version of the Engine used by the Game, etc.

| File Names: |
| - |
| version.dll |
| winhttp.dll |
| winmm.dll |

---

## LICENSING & CREDITS:

MelonixLoader is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/MelonixLoader/MelonixLoader/blob/master/LICENSE.md) for the full License.

Third-party Libraries used as Source Code and/or bundled in Binary Form:
- [Dobby](https://github.com/jmpews/Dobby) is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/jmpews/Dobby/blob/master/LICENSE) for the full License.
- [dobby-rs](https://github.com/RinLovesYou/dobby-rs) is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/RinLovesYou/dobby-rs/blob/master/LICENSE) for the full License.
- [dobby-sys](https://github.com/RinLovesYou/dobby-sys) is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/RinLovesYou/dobby-sys/blob/master/LICENSE) for the full License.
- [unity-rs](https://github.com/RinLovesYou/unity-rs) is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/RinLovesYou/unity-rs/blob/master/LICENSE.txt) for the full License.
- [Mono](https://github.com/Unity-Technologies/mono) is licensed under multiple licenses. See [LICENSE](https://github.com/Unity-Technologies/mono/blob/unity-master/LICENSE) for full details.
- [HarmonyX](https://github.com/BepInEx/HarmonyX) is licensed under the MIT License. See [LICENSE](https://github.com/BepInEx/HarmonyX/blob/master/LICENSE) for the full License.
- [MonoMod](https://github.com/MonoMod/MonoMod) is licensed under the MIT License. See [LICENSE](https://github.com/MonoMod/MonoMod/blob/master/LICENSE) for the full License.
- [Mono.Cecil](https://github.com/jbevain/cecil) is licensed under the MIT License. See [LICENSE](https://github.com/jbevain/cecil/blob/master/LICENSE.txt) for the full License.
- [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) is licensed under the MIT License. See [LICENSE](https://github.com/JamesNK/Newtonsoft.Json/blob/master/LICENSE.md) for the full License.
- [TinyJSON](https://github.com/pbhogan/TinyJSON) is licensed under the MIT License. See [LICENSE](https://github.com/MelonixLoader/MelonixLoader/blob/master/MelonixLoader/TinyJSON/LICENSE.md) for the full License.
- [Tomlet](https://github.com/SamboyCoding/Tomlet) is licensed under the MIT License. See [LICENSE](https://github.com/SamboyCoding/Tomlet/blob/master/LICENSE) for the full License.
- [AsmResolver](https://github.com/Washi1337/AsmResolver) is licensed under the MIT License. See [LICENSE](https://github.com/Washi1337/AsmResolver/blob/master/LICENSE.md) for the full License.
- [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) is licensed under the MIT License. See [LICENSE](https://github.com/MelonixLoader/MelonixLoader/blob/master/MelonixLoader/SharpZipLib/LICENSE.txt) for the full License.
- [Semver](https://github.com/maxhauser/semver) is licensed under the MIT License. See [LICENSE](https://github.com/maxhauser/semver/blob/master/License.txt) for the full License.
- [UnityEngine.Il2CppAssetBundleManager](https://github.com/MelonixLoader/UnityEngine.Il2CppAssetBundleManager) is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/MelonixLoader/UnityEngine.Il2CppAssetBundleManager/blob/master/LICENSE.md) for the full License.
- [UnityEngine.Il2CppImageConversionManager](https://github.com/MelonixLoader/UnityEngine.Il2CppImageConversionManager) is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/MelonixLoader/UnityEngine.Il2CppImageConversionManager/blob/master/LICENSE.md) for the full License.
- [Illusion Plugin Architecture](https://github.com/Eusth/IPA) is licensed under the MIT License. See [LICENSE](https://github.com/Eusth/IPA/blob/master/LICENSE) for the full License.
- [MuseDashModLoader](https://github.com/mo10/MuseDashModLoader) is licensed under the MIT License. See [LICENSE](https://github.com/mo10/MuseDashModLoader/blob/master/LICENSE) for the full License.
- [mgGif](https://github.com/gwaredd/mgGif) is licensed under the MIT License. See [LICENSE](https://github.com/gwaredd/mgGif/blob/main/LICENSE) for the full License.
- [AssetsTools.NET](https://github.com/nesrak1/AssetsTools.NET) is licensed under the MIT License. See [LICENSE](https://github.com/nesrak1/AssetsTools.NET/blob/master/LICENSE) for the full License.
- [AssetRipper.VersionUtilities](https://github.com/AssetRipper/VersionUtilities) is licensed under the MIT License. See [LICENSE](https://github.com/AssetRipper/VersionUtilities/blob/master/License.md) for the full License.
- Steam Library, VDF, and ACF Parsing from [SteamFinder.cs](https://github.com/Umbranoxio/BeatSaberModInstaller/blob/master/BeatSaberModManager/Dependencies/SteamFinder.cs) by [Umbranoxio](https://github.com/Umbranoxio) and [Dalet](https://github.com/Dalet).
- [bHapticsLib](https://github.com/HerpDerpinstine/bHapticsLib) is licensed under the MIT License. See [LICENSE](https://github.com/HerpDerpinstine/bHapticsLib/blob/master/LICENSE.md) for the full License. 
- [IndexRange](https://github.com/bgrainger/IndexRange) is licensed under the MIT License. See [LICENSE](https://github.com/bgrainger/IndexRange/blob/master/LICENSE) for the full License.  
- [ValueTupleBridge](https://github.com/OrangeCube/MinimumAsyncBridge) is licensed under the MIT License. See [LICENSE](https://github.com/OrangeCube/MinimumAsyncBridge/blob/master/LICENSE) for the full License.  
- [WebSocketDotNet](https://github.com/SamboyCoding/WebSocketDotNet) is licensed under the MIT License. See [LICENSE](https://github.com/SamboyCoding/WebSocketDotNet/blob/master/LICENSE) for the full License.
- [Pastel](https://github.com/silkfire/Pastel) is licensed under the MIT License. See [LICENSE](https://github.com/silkfire/Pastel/blob/master/LICENSE) for the full License.
- [Il2CppInterop](https://github.com/BepInEx/Il2CppInterop) is licensed under the LGPLv3 License. See [LICENSE](https://github.com/BepInEx/Il2CppInterop/blob/master/LICENSE) for the full License.
 
 
External Libraries and Tools that are downloaded and used at Runtime:
- [Cpp2IL](https://github.com/SamboyCoding/Cpp2IL) is licensed under the MIT License. See [LICENSE](https://github.com/SamboyCoding/Cpp2IL/blob/master/LICENSE) for the full License.
- Unity Runtime Libraries from [Unity-Runtime-Libraries](https://github.com/MelonixLoader/Unity-Runtime-Libraries) are part of Unity Software.  
Their usage is subject to [Unity Terms of Service](https://unity3d.com/legal/terms-of-service), including [Unity Software Additional Terms](https://unity3d.com/legal/terms-of-service/software).

See [MelonixLoader Wiki](https://melonwiki.xyz/#/credits) for the full Credits.

MelonixLoader is not sponsored by, affiliated with or endorsed by Unity Technologies or its affiliates.  
"Unity" is a trademark or a registered trademark of Unity Technologies or its affiliates in the U.S. and elsewhere.
