---
layout: article
category: eliteva
subject: installation
description: A guide on how to install EliteVA
navigation: eliteva
---

# Installing EliteVA

This guide will help you install the EliteVA plugin in VoiceAttack.

## Checklist

- [x] Have VoiceAttack installed
- [x] Enable plugin support in VoiceAttack
- [x] Create a new folder in the VoiceAttack/Apps directory
- [x] Copy EliteVA.dll to the newly created folder

## Installing VoiceAttack

[VoiceAttack can be downloaded here](https://voiceattack.com/#download-1). Please keep in mind that the VoiceAttack trial only gives you one profile with up to twenty commands. If you'd like to purchase the full VoiceAttack version, you can so through [their website](https://voiceattack.com/purchase.aspx) or on [Steam](https://store.steampowered.com/app/583010/VoiceAttack/). For a full guide please see [this post by the VoiceAttack developers](https://forum.voiceattack.com/smf/index.php?topic=2667.0).

## Plugin support in VoiceAttack

Plugin support in VoiceAttack must be enabled in order for EliteVA to be invoked. Plugins can be enabled through the options page in VoiceAttack in the *General* tab. The option page also contains a plugin manager button; make sure EliteVA is checked.

VoiceAttack will have to be restarted after changing any of these settings.

## VoiceAttack/Apps folder

Each VoiceAttack plugin must be placed inside a sub-folder in the VoiceAttack/Apps directory. This Apps folder can be found in your installation directory. Depending on how you acquired VoiceAttack your installation folder may vary. This installation folder should contain an Apps folder, create a new EliteVA folder in this Apps directory.

If everything has gone correctly, the newly created EliteVA should look something like this.

|Platform|Path|
|---|---|
|Regular|`C:\Program Files (x86)\VoiceAttack\Apps\EliteVA`|
|Steam|`C:\Program Files (x86)\Steam\SteamApps\common\VoiceAttack\EliteVA`|

## Copying EliteVA.dll

The last step is to copy EliteVA.dll to the EliteVA folder. See [this guide](/eliteapi/voiceattack/getting-started/download.html) on how to download EliteVA.dll. Drop the EliteVA.dll file into the newly created EliteVA folder.

You should now be good to go to use the EliteVA plugin after a restart of VoiceAttack.
