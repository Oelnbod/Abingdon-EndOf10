# Abingdon-EndOf10 Volunteer information, if not a volunteer please visit [oelnbod.github.io/eo10](oelnbod.github.io/eo10).
If you have storage available could you list it in storage.md? **We need lots of fast storage and lots of large storage.** Fast for installing, and large for the odd backups. 
  
Also, if you have any laptops, could you bring them - so we can demonstrate the various distros. Feel free to load VMs onto them. I have created some custom backgrounds: [https://mia.nl.tab.digital/s/TTgk6m3obHfgaAp](https://mia.nl.tab.digital/s/TTgk6m3obHfgaAp), that you can load onto these computers so people can know what distro it is. 
Don't bother loading up chromeos as the library computers are chromeboxes - so we can just direct people there.


### Some notes on distro

- **zorin** ~3.8GB [https://zorin.com/os/](https://zorin.com/os/), https://zorin.com/os/download/17/core/ Probably one of the distros that I want to push people towards, due to its rising popularity and its similarity to Windows. 

- **fedora KDE** ~2.8GB (I'm thinking about dropping this, as it doesn't offer much over kubuntu - which is slightly more mainstream. Please give me your opinions. I am open to dropping kubuntu and keeping this.) https://fedoraproject.org/kde/, https://download.fedoraproject.org/pub/fedora/linux/releases/42/KDE/x86_64/iso/Fedora-KDE-Desktop-Live-42-1.1.x86_64.iso 

- **fedora kionite** ~3.7GB https://fedoraproject.org/atomic-desktops/kinoite/ , https://download.fedoraproject.org/pub/fedora/linux/releases/42/Kinoite/x86_64/iso/Fedora-Kinoite-ostree-x86_64-42-1.1.iso  This is immutable, so has some security and stability advantages. 

- **mint** ~3GB https://www.linuxmint.com/ , https://www.linuxmint.com/edition.php?id=319 (not direct link, as multiple servers).  A lot of people seem to like the Cinnamon DE, but I'm not such a fan. 

- **Ubuntu** ~5.9GB [https://ubuntu.com/](https://ubuntu.com/desktop), https://releases.ubuntu.com/24.04.2/ubuntu-24.04.2-desktop-amd64.iso  A bit different and very popular if people want to try the GNOME DE (that isn't heavily customised like Zorin), its popularity and community size is a benefit as well.  

- **kubuntu** ~4.2GB https://kubuntu.org/ , https://cdimage.ubuntu.com/kubuntu/releases/24.04.2/release/kubuntu-24.04.2-desktop-amd64.iso  More mainstream than fedora KDE, so I will only bring one. But it is a much larger image. We could bring both and just swap the relevant one in depending on installer availability. 
  
- **xubuntu** ~4.0GB https://xubuntu.org/ , https://xubuntu.org/download/#lts (same issue as mint). The lightweight option for *very* old computers.   
   
- **ChromeOS Flex** ~*6.8*GB (the .bin it provides needs to be renamed as a .img) prefer not as not in the spirit of endOf10 and FOSS and *very* large file https://dl.google.com/chromeos-flex/images/latest.bin.zip  For the people who *really* want chromeOS. 

- **solus budgie** ~3GB https://getsol.us/ https://downloads.getsol.us/isos/2025-01-26/Solus-Budgie-Release-2025-01-26.iso  Another lightweight -ish option, Budgie DE.  
  
- **Pop_OS!** ~ 3.0GB with nvidia drivers - seems trivial to install kde on it and easier than nvidia drivers on others with our low bandwidth https://iso.pop-os.org/22.04/amd64/nvidia/54/pop-os_22.04_amd64_nvidia_54.iso https://system76.com/pop/ Also so people can try COSMIC, which is quite a nice DE. 

When installing distros onto USB sticks, make sure that they are DVD images (i.e., all files are available on the drive), we have very limited bandwidth (I think ~30Mb/s) and I want to prioritise this for packages. Also, flash the drives using Ventoy (even if three is only 1 distro on the drive), this allows us to re-image the drive by only copying files and not requiring us to flash it normally. If Ventoy uses up too much space, as to prevent flashing the drive, then don't use it. 

### My current plan for the day:
1. With some **demo computers** (use vms) we can demonstrate some Linux distros, we need a distribution of GNOME/KDE/other desktop environments. This is to help them pick distro. We can also use https://distrochooser.de/ or similar. To help perusade, have a look at: https://invent.kde.org/websites/endof10-org/-/issues/131 for user testimony.
    
3. We then walk them through **backing up their data**, probably to one of our drives. I hope that they have backed up data already. We do need to check as on Windows you can upgrade or reinstall without losing their /home equivalent. We also need to ensure that saved passwords are backed up, as many people only save them to their web browser.We can also get them to sign a waiver.  

4. We **check the above** and remind them about data loss. Also note: stuff that appears in the onedrive may just be in a folder called onedrive that has the logo, but *does not sync to onedrive*. We can validate this by asking them to sign in online (office.com) and checking that the files appear there.
   
6. If the distro is on a vm, we can live boot them (note: prioritise non-live systems, i.e., fedora kionite, on demo laptops) to **check that they are happy**. We then **walk them through installing it** (we tell them what to do and not us do it - I know that they probably won't do it again, but the inspiration is important). 
   
8.  We can then **restore files** - just copy the contents of the folders before (we can encourage them to sort the files - but it is slower for us). We must then delete it from our storage. 
   
10.  We then have to **help them learn how to use Linux**. I have some pointers on a card here: https://collaborate.kde.org/s/Yr89DANzaJ9gmxC (I'll print some off beforehand and the library has printers if we're in a pinch). I'll also print off some EndOf10, GNU/Linux promo stuff.
    
12.  **Installing software**, we can install bottles/wine for them if they need MS Office apps (this looks good for onedrive syncing: https://github.com/bpozdena/OneDriveGUI). Remind them of the disadvantages of bottles/wine (also on card). If they find LibreOffice to unfamilliar, OnlyOffice is also available and FOSS (it looks more like MS Office), it is also on the chromeboxes in the Library. Any other software we can help install. I might bring a drive with some common .deb and .rpm files (straight from the apt/rpm repos to support automatic updates) on it to help ease bandwidth. Also note: *do not install update*, we should make them do them at home due to the **limited bandwidth.**
    

#### If you want to chat, use the discussions feature above. If you would prefer matrix/whatsapp/signal/etc, please let me know and we can switch.
#### Could you also let me know of what drives you have available as installation medium so that we can manage distro distribution. 


# Thank You! ❤️
p.s. Sorry if I am micromanaging. 
