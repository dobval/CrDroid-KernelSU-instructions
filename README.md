# CrDroid-KernelSU-instructions
## Steps needed for installing CrDroid custom ROM with KernelSU on Redmi Note 8 Pro

### First time installation:

WARNING: It is highly recommended to come from global miui 12.5 and to follow steps properly, expecially by using recommended recovery to avoid bricks or any kind of errors !

  1. Use [this recovery](https://t.me/RedmiNote8ProUpdates/999) 
  2. Wipe system, dalvik, cache, vendor, format data
  3. Install [Rom](https://forum.xda-developers.com/t/rom-official-begonia-13-crdroidandroid-v9-x.4492965/) (THIS MIGHT BE OUTDATED, CHECK TIMJOSTEN CRDROID RELEASES)
  4. Install gapps (Optional)
  5. Reboot

#### Update installation:

  1. Reboot to recovery
  2. Wipe Dalvik/Cache
  3. Install rom
  4. Install gapps (Optional)
  5. Reboot

### KernelSU (Root) installation (Optional)
go to the following [telegram](https://t.me/s/TimJostenFiles/191)

1. Update to the latest Version of crDroid (see above steps)
2. Flash [Stock Kernel zip](https://t.me/TimJostenFiles/293?single) in TWRP
3. Flash [kernelSU Installer zip](https://t.me/TimJostenFiles/294?single) in TWRP
4. Flash [KernelSU Updater zip](https://t.me/TimJostenFiles/295?single) in TWRP
5. Install [KernelSU Manager APK](https://t.me/TimJostenFiles/296?single) like any apk (not in TWRP)

#### Uninstall kernelSU:
1. Flash KernelSU Uninstaller in TWRP to get rid of kernelSU.

### Install MinMicroG (Optional)
1. Choose a version from the table (taken from [this github](https://github.com/FriendlyNeighborhoodShane/MinMicroG))
<table>
<thead>
<tr>
<th>Component \ Variant</th>
<th>Standard</th>
<th>NoGoolag</th>
<th>Minimal</th>
<th>MinimalIAP</th>
</tr>
</thead>
<tbody>
<tr>
<td>MicroG</td>
<td>x</td>
<td>x</td>
<td>x</td>
<td>x</td>
</tr>
<tr>
<td>Maps APIv1</td>
<td>x</td>
<td>x</td>
<td>x</td>
<td>x</td>
</tr>
<tr>
<td>Fake Store</td>
<td></td>
<td>x</td>
<td>x</td>
<td></td>
</tr>
<tr>
<td>Google Play Store</td>
<td>x</td>
<td></td>
<td></td>
<td>x</td>
</tr>
<tr>
<td>Aurora Store</td>
<td></td>
<td>x</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Aurora Droid</td>
<td>x</td>
<td>x</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Google Sync adapters</td>
<td>x</td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

2. Download a [release](https://github.com/FriendlyNeighborhoodShane/MinMicroG_releases/releases)
3. Flash in Recovery

#### Uninstall MinMicroG
1. Rename the release, add <code>uninstall-</code>
   (For example, <code>MinMicroG-variant-version-signed.zip</code> to <code>uninstall-MinMicroG-variant-version-signed.zip</code>)
2. Flash in Recovery
