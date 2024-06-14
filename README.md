# Custom-Rom-Guide-For-MT6785
## Hello Guys ! Here i guide you to the core installation of custom rom based on MT6785 device Here i was using Realme 7 the same steps for all realme devices (not for other mobile brands depends on their BL unlock methods)

## STEPS TO BE FOLLOW BEFORE FLASHING A CUSTOM ROM 
Every Phones Have Bootloader Locked First You Have To Unlock The Bootloader Of The Phone , Here I Was Using Realme 7 So There Is A Apk Called **Indepth Apk**  And You Have To Choose Firmware Based On To Flash Custom Rom For Ex _Ru1 Based Or Rui2 Or Rui3_ Ru Is Nothing But  (Realme Ui)

So here i choose rui2 based indepth apk to unlock bootloader so i can flash custom rom based on rui2  many custom roms are available for rui1 and rui3 i early mention i was going to use rui2 based crom so i gonna unlock bootloader on rui2 before that enable usb debugging and oem unlocking in developer options

 Enter the app known as indepth apk and start applying application after applying application start deeptesting and the phone will boot into fastboot mode thats the place were we can use command to unlock the bootloader


Open Your Pc And Download Google Android Platform Tools (Available For Linux Windows And Mac) (Https://Developer.Android.Com/Tools/Releases/Platform-Tools) Extract It And Open It With Command Prompt 


 Connect Your Mobile With Pc With The Usb Cable And Type The Following Command `Fastboot Flashing Unlock`  After It Opens A Option In Your Fastboot Mode Yes Or No By Using Volume Keys Choose The Option Here I Using Volume Up Key To Yes After That The Bootloader Has Been Unlocker After That Flash Recovery There Are Many Recovery And Get It From The Device Support Groups On Telegram Or Xda Forum , Here I Uing Pbrp(Pitch Black Recovery Project) Command For Flashing Recovery Is `Fastboot Flashing Recovery Recovery.Img` 

Boot Into Recovery By Using The Following Command  `Fastboot Reboot Recovery` After Boot Into Recovery Unplug The Usb And Do The Following Things  ( Wipe > Format Data > Yes ) And Done 

 There Are Two Ways To Flash Custom Rom Via Recovery (Adb Sideload Or Using Sd Card ) Here I Was Using Sd Card Come Back To Home ( Install > Select Sd Card > Select Rom > Swipe To Flash)  For The Guys Who Dont Have Sd Card Download The Rom And Keep It In The Place Where You Want And Open Terminal In Pc Plug The Usb With Your Mobile On Mobile Recovery (Advanced > Adb Sideload > Swipe To Sideload > `Adb Sideload  Rom.Zip ` And Its Done 

  AFTER FLASHING ROM REBOOT SYSTEM AND ENJOY !!!!

### THE COMMANDS I USED 
`fastboot flashing unlock`
`fastboot reboot`
`fastboot flash recovery recovery.img`
`fastboot reboot recovery `
`adb sideload rom.zip`

And We Can Flash Kernel The Same Way We Used To Flash Rom And We Can Root Device By Using Magisk And Kernel Su
