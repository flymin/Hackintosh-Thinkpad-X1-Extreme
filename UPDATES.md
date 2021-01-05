# Hackintosh for Thinkpad X1 Extreme-Update History

## 2020

- [20201007] Update opencore to 0.6.2 and kexts.
- [20200926] Update to 10.15.7, everything works fine.
- [20200923] If hibernation battery drain still occur after update, try to reset your NVME through OC.
- [20200920] Update to 10.15.6. Solve the problem of hibernation battery drain. Using [OC-little/10-PTSWAK综合扩展补丁](https://github.com/daliansky/OC-little/tree/master/10-PTSWAK%E7%BB%BC%E5%90%88%E6%89%A9%E5%B1%95%E8%A1%A5%E4%B8%81)
- [20200911] Migrate to [Opencore](https://github.com/acidanthera/OpenCorePkg), now version is 0.6.1, everything still.
- [20200205] Update to 10.15.3, no change.

## 2019

## December Updates

- [20191213] Update to 10.15.2 and make a new folder. Update clover to 5100.

## November Updates

- [20191109] Make new 10.15.1 folder. Make iGPU with 2048MB Mem. Change model to MacBookPro15,1. Use new AppleALC, more stable with BT. And other minor update.

### October Updates

- [20191031] Updated to 10.15.1, nothing happens.
- [20191030] In case you find problem when using AirPods. See [known-issue#4](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme#known-issue).
- [20191021] Figured out how to control cpu fan, see [known-issue#3](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme#known-issue).
- [20191014] Headphone work unpleasantly. **Re**install ALCPlugFix resolve this issue, see [known-issue#2](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme#known-issue).
- [20191010] Headphone work unpleasantly. Uninstall ALCPlugFix resolve this issue, see [known-issue#2](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme#known-issue).
- [20191009] **:tada:** Welcome for Catalina, after Software Update from System Preferences, everything works fine. Make new [Release for 10.15 v1.0](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.15.1.0).
- [20191007] BIOS, PS2Controller and clover updates

### September Updates

- [20190910] change VoodooPS2 to acidanthera's version, [Release for 10.14.6 v1.2](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.6.1.2)

### August Updates

- [20190828] ALCPlugFix for headphone plug issue
- [20190819]I made my own DSDT patch, which is a little different. See [Release 10.14.6 v1.1](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.6.1.1).
- [20190815] [Release for 10.14.6 v1.0](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.6.1.0)
- [20190811] [Adjusted release 10.15.0-3.0](https://github.com/flymin/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.15.0.3.0.0)

> In original Repo

---

### July Updates

* [20190731] Added "Memory Issue" section for systems that has 64GB memory.
* [20190729] I was looking at [this post](http://bbs.pcbeta.com/viewthread-1823918-1-1.html) for updating to clover 5XXX and sleep issue to solve battery drain...
* [20190728] Added a guide to customize the "About This Mac" page.
* [20190725] Updated readme.MD with touchscreen and displaylink issues based on a [discussion](https://www.tonymacx86.com/threads/macos-10-15-0-thinkpad-x1-extreme-hackintosh.263916/post-1986487).
* [20190724] Updated BIOS to 1.23, no major issue or changes.
* [20190723] Released [v10.15.0.1.2](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.15.0.1.2) that disabled the integrated IR camera. Merged change in [Issue#33](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/33#issuecomment-514062099)
* [20190721] Released an incremental update v10.15.0.1.1, attempting to fix the sleep and hybernation issue.
* [20190720] Unknown issue of significant battery drain (40% in 8 Hours) during sleep in Catalina.
* [20190719] Just updated to Public Beta 3 and v10.15.0.1.0 still works for PB3.
* [20190717] So far so good, hadn’t encounter any bug in Catalina, which is very good for the first beta.
* [20190715] Do NOT upgrade Clover to 4988 or higher. It doesn't quite work. (Blackscreen after bootload)
* [20190710] Added badges for the versions. Yayyyyyy!!!
* [20190706] Achieved initial Catalina support :) Released v10.15.0.1.0.
* [20190703] Fixed an issue for AppleALC not working properly, released v10.14.5.1.3.
* [20190702] It seems like there is a Lenovo implementation of DL6950 ext display. [Issue](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/13#issuecomment-507499718)
* [20190701] Updated many extensions and released v10.14.5.1.2.

### June Updates
* [20190628] Studying abroad in Greece. Not gonna update so much. Will try Catalina if I got time.
* [20190615] Wrote a [Chinese Readme.MD](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/blob/master/README_zh_CN.md), to help my Chinese friends!
* [20190614] Released a minor update on clover bootloader. Version v10.14.5.1.1.
* [20190613] Sidenote: I got a Logitech G Pro Wireless yesterday and wow, awesome. (Not advertisement)
* [20190612] Hmmmmm so far...so good? I will be traveling during the summer, so probably won't update much.
* [20190604] Thanks for [zysuper's effort](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/11#issuecomment-498715154), you can actually buy a adapter card than soldering your own. Cheers!
* [20190603] Let's welcome macOS Catalina, shall we?
* [20190602] Added support for 10.14.5, released V1.0 for 10.14.5.
* [20190601] Happy children's day humans!

### May Updates
* [20190531] BCM94360CS2 is probably causing my laptop's macOS AND Windows (What???) to freeze, back to 2CS.
* [20190525] ~~Switched to BCM94360CS2, seems like there is no problem...?~~
* [20190524] ~~Due to there is no new features in 10.14.5, I will NOT upgrade. Please tell us how it goes if you do! :)~~
* [20190523] Let's take a moment to pay respect to our hero [Hongyu Wu](https://www.polygon.com/2016/7/1/12081430/overwatch-memorial-wu-hongyu-blizzard), heroes never die! 
* [20190522] Updated some minor things in Readme.MD.
* [20190520] Lenovo announced X1 Extreme 2nd Generation. This project is for the 1st generation.
* [20190510] [Some improvements in Bluetooth](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/11#issuecomment-491468609). Now I shall conclude this project is 100% perfect. 
* [20190503] Solved [Bluetooth Issue](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/11). [Pictures](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/blob/master/IMG/Readme.MD)
* [20190501] Happy labor day humans.

### April Updates
* [20190430] Made a ribbon cable to connect to smartcard reader. [See Pictures](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/11#issuecomment-488218838).
* [20190429] Released an optional update [v10.14.4-V1.2](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.4.1.2), more in description.
* [20190428] So far so good so no updates. It just works.
* [20190418] Oh so it turns out that you can use a USB BT adapter and use Airpods 2 as usual. Sweeeeeeeeeet.
* [20190417] Displaylink has its own [known limitations](http://assets.displaylink.com/live/downloads/release-notes/f1303_DisplayLink+USB+Graphics+Software+for+macOS+5.1-Release+Notes.txt) (cannot rescale 4K to 1080P in 60FPS). So just use native 4K.
* [20190416] Released [v10.14.4-V1.1](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.4.1.1). Fixed an issue with AppleALC.
* [20190415] Had [HDMI output working via USB Displaylink](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/13).
* [20190415] Released [10.14.4-V1.0](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.4.1).
* [20190414] macOS 10.14.4 is NOT a safe update. Will release 10.14.4 soon.
* [20190409] Addressed and closed some issues that other humans had in the issues module.
* [20190402] This work is now issued under the [996 License](https://github.com/996icu/996.ICU/blob/master/LICENSE).
### March Updates
* [20190327] Made a [note](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/15#issuecomment-477450037) in readme.MD about BCM94360CS2 and BCM943602CS.
* [20190326] Glad to be indexed by [Hackintosh Laptop Index](https://github.com/daliansky/Hackintosh). 
* [20190320] Released [v10.14.3.1.3](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.3.1.3), a stable update.
* [20190317] darkal presented a somewhat decent [external display workaround](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/13) if you have a 1080P screen. 
* [20190315] So far so good with USB BT. The only issue left is display output, which so far nothing we can do.
* [20190314] Happy pi day humans.
* [20190311] Updated readme.MD regarding on an [OpenGL issue on 10.14.3](https://www.tonymacx86.com/threads/macos-10-14-0-thinkpad-x1-extreme-hackintosh.263916/post-1900369). 
* [20190307] New [VoodooPS2 Driver](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3#issuecomment-470353880) add in multi-touch genture support. Released in [v10.14.3.1](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.3.1).
* [20190303] Updated to 10.14.3 and Clover v4895. 
### Feburary Updates
* [20190228] [AaronZYHK](https://github.com/AaronZYHK) presented yet another approach to get [BT working with an USB adapter](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3#issuecomment-468153492).
* [20190227] [darkal](https://github.com/darkal) presented a interesting research direction to [BT working wih 9260 with a WIFI adapter.](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3#issuecomment-467381308)
* [20190225] Lenovo is issueing me yet another replacement unit. Development paused.
* [20190224] F!ck. My laptop is not powering up...again.
* [20190215] Start to work on my researches in the wiki page [About Boot Issue](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/wiki/Unknown-Issue-for-booting-into-macOS).
* [20190215] There is an unknown issue to boot into macOS. [Temporary Fix](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.0.SE) Read more above. 
### Janurary Updates
* [20190120] Released [v10.14.0.2](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.0.2) according to andyy24 in [Issue#9](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/9) to fix a trackpoint issue.
* [20190111] Got BCM943602CS working. Turned out I didn't stuck it in enough.
* [20190105] I still cannot get BCM943602CS on adaptor working...
## 2018
### December Updates
* [20181225] Happy holiday humans.
* [20181222] I ordered ribbon cable for smartcard slot in China. Will need to design a PCB tho...
* [20181207] My laptop is dead due to I was stupid enough to tear it down without unplug the battery.
### November Updates
* [20181121] Added [Driver for BRCM943602CS in WINDOWS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602CS.1).
* [20181120] Added [Driver for DW1830 in WINDOWS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602BAED.1) Also had some [Discussion on getting bluetooth working](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3).
* [20181119] Uploaded [BOOT5.0](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/10.14.0/5.0-AllEnabled).
* [20181118] Modified and released [Configuration for macOS 10.14.0.1](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.0.1) based on [zysuper's work](https://github.com/zysuper/Thinkpad-X1-extreme-EFI).
* [20181121] Added [Driver for BRCM943602CS in WINDOWS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602CS.1).
* [20181120] Added [Driver for DW1830 in WINDOWS](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v943602BAED.1) Also had some [Discussion on getting bluetooth working](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/issues/3).
* [20181119] Uploaded [BOOT5.0](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/10.14.0/5.0-AllEnabled).
* [20181118] Modified and released [Configuration for macOS 10.14.0](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/releases/tag/v10.14.0.1) based on [zysuper's work](https://github.com/zysuper/Thinkpad-X1-extreme-EFI).
* [20181115] TB3 not working. Upgraded back to 10.14.0.
* [20181113] My laptop showed defects and I have to send it back to Lenovo to replace a new one...ugggh.
* [20181112] Got an eGPU but TB3 not enabled for macOS in 10.13. 
* [20181111] Still stuck at getting iGPU working. Tried to downgrade to 10.13.
### October Updates
* [20181030] Uploaded BOOT4.0 which installed most KEXT into S/L/E. See ["./KernalExtentions/"](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/KernalExtentions).
* [20181029] Uploaded [INSTALL5.0](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/10.14.0/INSTALL-5.0) installations. iGPU weird with injected io-reg and fakeid on intelGFX.
* [20181028] Clover have UEFI64Driver support FileVault2. Still, make sure you get everything else working first.
* [20181027] DO NOT USE FILEVAULT!!! 100% DISK BREAK AFTER REBOOT GUARANTEED.
* [20181027] Project Started. Initial [INSTALL1.0](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme/tree/master/10.14.0/1.0-Initlal_BootAble) posted.


