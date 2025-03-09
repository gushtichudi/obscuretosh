# macOS Big Sur for Samsung 370R

EFI files kept in for own usage for the Samsung Series 3 laptop model
`NT370R5E-A44S`.

> Usage of EFI made by other people is not good practice and can lead
> problems in the long run. This repository serves as a storage for
> these EFIs as they can't just stay on my USB forever.

### Working Features:

**Please check the Notes section for comments indicated by 
superscripts**

1. Audio
2. Battery readout
3. Full Graphics Acceleration with no setbacks
4. Touchpad<sup>a</sup>/keyboard
5. USB (surprisingly)
6. WiFi

### Not Working Features:

1. Bluetooth<sup>b</sup>
2. Brightness<sup>b, d</sup>
3. Camera
4. Ethernet<sup>c</sup>
5. Sleep (not entirely sure)

### Notes:

a. Touchpad works only when it feels like it. You might get success if
   you plug in an USB Mouse before booting.

b. This does not work and I am planning to fix these features soon.

c. This is untested. macOS doesn't detect the ethernet port and I will
   **NOT** fix this issue becasuse I don't find any good use of
   ethernet while I have functioning WiFi.

d. The Brightness, by the BIOS, is set to 100% all the times when on
   battery power. It dims to the lowest possible when unplugged.
   Readings might not be accurate at all times.

### Courtesy

Without these, I would never be able to get my first ever Hackintosh
on this laptop.

(order on how much they helped me)

| Name        | Work                                                                                                         | Comments                                                                                                                                                            |
|-------------|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| acidanthera | OpenCore and many Kexts                                                                                      | Made MANY tools that the entire Hackintosh community takes for granted. The single absolute reason why Hackintoshing seems less intimidating as it was 5 years ago. |
| Apple       | macOS                                                                                                        | Apple had GENIUSES working overtime to have the best UI out of any of it's competitors.                                                                             |
| jgtony      | [For this very outdated yet inspiring guide](https://jgtonys.github.io/hackintosh/2019/04/20/laptop-to-mac/) | Seeing he had the exact model as mine, and given it WAS in fact possible, gave me inspiration for this entire thing.                                                |
| ic005k      | OCAT                                                                                                         | Got ***HUMILIATED*** in the Discord server for saying that I use this even though it works wonders. Never tell anyone over there what you use to edit plists.       |
| CorpNewt    | ProperTree, MountEFI, along with many other scripts                                                          |                                                                                                                                                                     |
