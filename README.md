# OmniBip

Crafting New Watchface to Amazfit Bip

![](https://i.imgur.com/Q7Og5no.png)  ![](https://i.imgur.com/3HMQ2R3.gif) 

### Installing watchface

Download [**OmniBip** Watchface](https://github.com/OmniMir/OmniBip/releases/latest)



Copy `7e7cca472cb21cebb9a4b6fcd030fd9c.bin` to

`\Android\data\com.xiaomi.hm.health\files\watch_skin_local\7e7cca472cb21cebb9a4b6fcd030fd9c\` on your phone



In some versions use `\Android\data\com.xiaomi.hm.health\files\watch_skin\` instead that



In **Mi Fit** go to Profile->Amazfit Bip->Themes and select very similar black watchface with big numbers (Digit series 2)



Wait and rejoice!



### Create or edit watchface

Extract resources of any downloaded watchface with CLI **Amazfit Bip Tools**

`.\WatchFace.exe path\to\watchface\any_watchface_name.bin`



Use GUI **Watchface Editor** and your favorite graphic software to create design



Generate new and edited resources with main JSON


Use CLI **Amazfit Bip Tools**

`.\WatchFace.exe path\to\OmniBip\OmniBip.json`



If all is OK, you have files for installing

`OmniBip_packed.bin`

`OmniBip_packed.gif`

`OmniBip_packed.png`

`OmniBip_packed.txt`



Rename `OmniBip_packed.bin` to `7e7cca472cb21cebb9a4b6fcd030fd9c.bin`



### Software

[Amazfit Bip Tools](https://bitbucket.org/valeronm/amazfitbiptools/downloads/)

[Bip Watchface Editor](https://forum.gizchina.it/index.php?/topic/1489-bip-wf-editor-by-ilgruppotester/)

[Mi Fit](https://play.google.com/store/apps/details?id=com.xiaomi.hm.health&hl=ru)