# 基于Gnome桌面定制kali Linux

```shell
# Live image
# You always want these:
kali-linux-core
kali-linux-headless
kali-linux-default
kali-linux-arm
kali-linux-nethunter
kali-linux-labs
kali-root-login


# Metapackages
# You can customize the set of Kali metapackages (groups of tools) to install
# For the complete list see: https://tools.kali.org/kali-metapackages

kali-tools-gpu
kali-tools-hardware
kali-tools-crypto-stego
kali-tools-fuzzing
kali-tools-802-11
kali-tools-bluetooth
kali-tools-rfid
kali-tools-sdr
kali-tools-voip
kali-tools-windows-resources
kali-tools-information-gathering
kali-tools-vulnerability
kali-tools-web
kali-tools-database
kali-tools-passwords
kali-tools-wireless
kali-tools-reverse-engineering
kali-tools-exploitation
kali-tools-social-engineering
kali-tools-sniffing-spoofing
kali-tools-post-exploitation
kali-tools-forensics
kali-tools-reporting
kali-linux-large
kali-linux-everything
kali-tools-top10
kali-desktop-live

# Graphical desktop
kali-desktop-core
kali-desktop-gnome
kali-desktop-i3
kali-desktop-kde
kali-desktop-xfce

# Kali applications
#<package>
i2p
kali-screensaver
hollywood-activate
docker
docker.io
virtualbox
flatpak
ibus-pinyin
tor
torbrowser-launcher
kaboxer
npm
gnome-software-plugin-flatpak
snapd
yubikey-personalization
scdaemon
ibus-pinyin
gnome-software-plugin-flatpak
torbrowser-launcher
tigervnc-standalone-server
novnc 
x11vnc
clinfo
likwid
obs-studio    
build-essential 
libncurses5-dev
fakeroot 
build-essential 
dkms
git
libelf-dev
conky
conky-all
qbittorrent
thunderbird
virt-manager
bleachbit
qemu-web-desktop
qemu-system*
qemu
conky-manager
scrcpy
adb
virt-manager
bleachbit
gnome-shell-extension-*
gnome-shell-extension-weather
gnome-shell-extension-system-monitor
gnome-shell-extension-easyscreencast
gnome-shell-extension-manager
gnome-shell-extension-hard-disk-led
gnome-shell-extension-caffeine
boxes 
snapper 
live-build 
simple-cdd 
cdebootstrap 
devscripts
stegosuite 
steghide
dnsmasq
stegosuite
gconf2
gconf-service 
libgconf-2-4
## 定义包
kali-defaults
kali-menu
kali-debtags
kali-archive-keyring
debian-installer-launcher
alsa-tools
locales-all
openssh-server
##
actiona
libappindicator1
libayatana-indicator7 
libdbusmenu-gtk4
dialog  
libgl1-mesa-glx 
libxcb-xinerama0-dev
shutter
uget 
aria2
fcitx
htop
dwarves
squashfs-tools 
mesa-utils 
##########################
#nvidia-driver
nvidia-cuda-toolkit
nvidia-xconfig
edid-decode
#####Install BTRSF########
btrfs-progs 
snapper 
snapper-gui 
grub-btrfs
####################### 
alsa-utils  
fcitx-bin 
fcitx-config-common 
fcitx-config-gtk 
fcitx-data 
fcitx-frontend-all 
fcitx-frontend-gtk2
fcitx-frontend-gtk3 
fcitx-frontend-qt5 
fcitx-frontend-qt6 
fcitx-module-dbus 
fcitx-module-kimpanel 
fcitx-module-lua
fcitx-module-quickphrase-editor5 
fcitx-module-x11 fcitx-modules  
ffmpeg 
fonts-wqy-microhei 
gconf-service 
gconf2
gconf2-common 
icewm 
icewm-common 
libatopology2 
libayatana-appindicator1 
libayatana-indicator7 
libb2-1 
libdbusmenu-gtk4
libfcitx-config4 
libfcitx-core0 
libfcitx-gclient1 
libfcitx-qt5-1 
libfcitx-qt5-data 
libfcitx-utils0 
libgconf-2-4 
libgettextpo0
libpresage-data 
libpresage1v5 
libqt6core6 
libqt6dbus6 
libqt6gui6 
libtinyxml2.6.2v5 
presage 
qt6-gtk-platformtheme 
xscreensaver
xscreensaver-data
libreoffice
firewalld
iptables
linuxlogo
screenfetch
sl
kodi
gnome-text-editor
krita
librecad
brasero
darktable
handbrake
scribus
mixxx
remmina
firewalld  
iptables
gimp
mono-utils
kicad
r-base 
octave
qgis
openscad
shotcut
octave
wxhexeditor
##### 
docbook 
docbook-dsssl 
docbook-xsl 
docbook-defguide 
libterm-readline-gnu-perl 
libterm-readline-perl-perl 
imagemagick-doc
autotrace
cups-bsd  
cups*
lpr 
lprng 
enscript  
gnuplot 
grads 
hp2xx 
html2ps 
libwmf-bin 
mplayer 
povray 
radiance
texlive-base-bin 
transfig 
ufraw-batch 
graphicsmagick-dbg 
seccomp 
libssl-doc 
cups-bsd 
gstreamer1.0-plugins-ugly
ttf-mscorefonts-installer 
scrot 
winbind 
python-natsort-doc 
wx3.0-doc 
sgml-base-doc 
perlsgml 
w3-recs 
opensp 
q4wine 
winetricks
wine-binfmt 
dosbox 
exe-thumbnailer  
kio-extras 
wine64-preloader 
debhelper
cabextract 
docbook-xml 
fonts-dejavu 
fonts-wine 
gnupg2 
icoutils 
imagemagick 
imagemagick-6.q16 
jq 
libcapi20-3 
libcolord-gtk1
libfaudio0 
libgles2 
libgraphicsmagick-q16-3 
libjq1 
liblensfun-data-v1 
liblensfun1 
liblua5.4-0 
libmediainfo0v5 
libmms0 
libmng1
libnautilus-extension1a 
libnemo-extension1 
libnetpbm11 
libonig5 
libosmesa6 
libosmgpsmap-1.0-1 
libportaudiocpp0 
libpugixml1v5
libseccomp-dev 
libssl-dev 
libstb0 
libtinyxml2-9 
libvkd3d1 
libwine 
libwxbase3.0-0v5 
libwxgtk3.0-gtk3-0v5 
libyelp0 
libz-mingw-w64
libzen0v5 
mesa-utils 
mesa-utils-bin 
netpbm 
python3-natsort 
python3-wxgtk4.0 
qt5-image-formats-plugins 
sgml-base 
sgml-data 
wine
wine64 
xml-core 
yelp 
yelp-xsl
arduino*
qt5* 
qt6*
squid
gis-*
ansible*
```



## 开发类软件

1. | 编号 |    软件名称    |                         软件下载地址                         |
   | :--: | :------------: | :----------------------------------------------------------: |
   |  1   | IntelliJ IDEA  | https://www.jetbrains.com/idea/download/download-thanks.html?platform=linux |
   |  2   |   Php Storm    | https://www.jetbrains.com/phpstorm/download/download-thanks.html |
   |  3   |    PyCharm     | https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=linux |
   |  4   |    WebStorm    | https://www.jetbrains.com/webstorm/download/download-thanks.html |
   |  5   |    RubyMine    | https://www.jetbrains.com/ruby/download/download-thanks.html?platform=linux |
   |  6   |     GoLand     | https://www.jetbrains.com/go/download/download-thanks.html?platform=linux |
   |  7   |     CLion      | https://www.jetbrains.com/clion/download/download-thanks.html?platform=linux |
   |  8   | Android Studio | https://redirector.gvt1.com/edgedl/android/studio/ide-zips/2022.1.1.9/android-studio-2022.1.1.9-linux.tar.gz |


## 集成类软件                                                                                                    

| 编号 | 项目名称                                                     | 下载地址 |
| :--: | :----------------------------------------------------------- | :------: |
|  1   | 1password                                                    |          |
|  2   | AfterShotPro3                                                |          |
|  3   | apifox                                                       |          |
|  4   | appimagelauncher                                             |          |
|  5   | atom                                                         |          |
|  6   | balena-etcher-electron                                       |          |
|  7   | CiscoPacketTracer                                            |          |
|  8   | cleash.deb                                                   |          |
|  9   | code-insiders                                                |          |
|  10  | com.alibabainc.dingtalk                                      |          |
|  11  | copytranslator                                               |          |
|  12  | crossover                                                    |          |
|  13  | darktable                                                    |          |
|  14  | dbeaver-ee                                                   |          |
|  15  | dbeaver-ue                                                   |          |
|  16  | deskreen                                                     |          |
|  17  | docker-compose                                               |          |
|  18  | dolphin-megasync-Debian_11_amd64.deb                         |          |
|  19  | drawio                                                       |          |
|  20  | edrawmax                                                     |          |
|  21  | edrawproject                                                 |          |
|  22  | fdns                                                         |          |
|  23  | FileZilla_Server                                             |          |
|  24  | freedownloadmanager                                          |          |
|  25  | GitHubDesktop                                                |          |
|  26  | gitlab-ee                                                    |          |
|  27  | google-chrome-stable                                         |          |
|  28  | google-earth-pro-stable                                      |          |
|  29  | grub-btrfs_4.11-0kali1_all.deb                               |          |
|  30  | grub-common_2.04-20kali1_amd64.deb                           |          |
|  31  | ieaseMusic                                                   |          |
|  32  | ipscan                                                       |          |
|  33  | libappindicator3-1_0.4.92-3.1_amd64.deb                      |          |
|  34  | libindicator3-7_0.5.0-2_amd64.deb                            |          |
|  35  | marktext                                                     |          |
|  36  | master-pdf-editor                                            |          |
|  37  | megasync-Debian_11_amd64.deb                                 |          |
|  38  | microsoft-edge-stable                                        |          |
|  39  | mindmaster                                                   |          |
|  40  | Motrix - 适用于RPC下载.deb'                                  |          |
|  41  | nautilus-megasync-Debian_11_amd64.deb                        |          |
|  42  | navicat16-premium-cs.AppImage                                |          |
|  43  | nemo-megasync-Debian_11_amd64.deb                            |          |
|  44  | Nessus                                                       |          |
|  45  | netboot.tar.gz                                               |          |
|  46  | nomachine                                                    |          |
|  47  | nordvpn-release_1.0.0_all.deb                                |          |
|  48  | notes_1.5.0_amd64-bionic.deb                                 |          |
|  49  | openstego                                                    |          |
|  50  | opentoonz                                                    |          |
|  51  | PlayOnLinux_4.3.4.deb                                        |          |
|  52  | protonvpn                                                    |          |
|  53  | qqmusic                                                      |          |
|  54  | ryzen-controller                                             |          |
|  55  | skypeforlinux-64.deb                                         |          |
|  56  | sogoupinyin                                                  |          |
|  57  | sublime_text                                                 |          |
|  58  | teams                                                        |          |
|  59  | TencentMeeting                                               |          |
|  60  | thunar-megasync-Debian                                       |          |
|  61  | todesk                                                       |          |
|  62  | trilium                                                      |          |
|  63  | typora                                                       |          |
|  64  | typora_1.3.3-dev                                             |          |
|  65  | ukylin-wxwork_1.0_amd64.deb                                  |          |
|  66  | veracrypt-1.25.9-Debian-11-amd64.deb                         |          |
|  67  | veracrypt-console-1.25.9-Debian-11-amd64.deb                 |          |
|  68  | weixin_2.1.1_amd64.deb                                       |          |
|  69  | windscribe_2.3.15_beta_amd64.deb                             |          |
|  70  | wkhtmltox_0.12.6-1.buster_amd64.deb                          |          |
|  71  | wps-office_11.1.0.11664_amd64.deb                            |          |
|  72  | XMind-for-Linux-amd-64bit-12.0.2-202204260703.deb            |          |
|  73  | XnViewMP-linux-x64.deb                                       |          |
|  74  | xournalpp-1.1.1-Debian-bullseye-x86_64.deb                   |          |
|  75  | 即时设计 Linux版.AppImage                                    |          |
|  76  | Deskreen-1.0.12.AppImage                                     |          |
|  77  | FreeCAD_0.19.3-Linux-Conda_glibc2.12-x86_64.AppImage         |          |
|  78  | Inkscape-dc2aeda-x86_64.AppImage                             |          |
|  79  | Kage.0.1.1-beta_linux_3611102855ceee050e2a06733a1b85f1.AppImage |          |
|  80  | kdenlive-22.04.0-1-x86_x64_3fff814de58d9714d7628e3d9e5cb36c.AppImage |          |
|  81  | LANDrop-latest-linux.AppImage                                |          |
|  82  | navicat16-premium-cs_1e8e6eee1542bd070eb49b6710ffe64e.AppImage |          |
|  83  | NetEase_Cloud_Music-1.1.3.2-x86_64.AppImage                  |          |
|  84  | OpenShot-v2.6.1-x86_64.AppImage                              |          |
|  85  | Todoist-1.0.7.AppImage                                       |          |
|  86  | wiznote-desktop-0.1.73-linux-x86_64.AppImage                 |          |
|  87  | Yakit-1.0.14-linux-amd64.AppImage                            |          |
|  88  | baidunetdisk_4.11.5_amd64.deb                                |          |
|  89  | cnkiexpress_0.1.22_amd64.deb                                 |          |
|  90  | EasyConnect_x64_7_6_7_3.deb                                  |          |
|  91  | TIB_js-studiocomm_6.19.1_linux_amd64.deb                     |          |

| 编号 | 项目名称                      | 下载地址                                                     |
| ---- | ----------------------------- | ------------------------------------------------------------ |
| 1    | fscan                         | https://github.com/shadow1ng/fscan                           |
| 2    | kscan                         | https://github.com/lcvvvv/kscan                              |
| 3    | AppInfoScanner                | https://github.com/kelvinBen/AppInfoScanner                  |
| 4    | frida-skeleton                | https://github.com/Margular/frida-skeleton                   |
| 5    | Packer-Fuzzer                 | https://github.com/rtcatc/Packer-Fuzzer                      |
| 6    | DarkEye                       | https://github.com/b1gcat/DarkEye                            |
| 7    | ALLiN                         | https://github.com/P1-Team/AlliN                             |
| 8    | FoFax                         | https://github.com/xiecat/fofax                              |
| 9    | OneForAll                     | https://github.com/shmilylty/OneForAll                       |
| 10   | wafw00f                       | https://github.com/EnableSecurity/wafw00f                    |
| 11   | Udork                         | https://github.com/m3n0sd0n4ld/uDork                         |
| 12   | NoXss                         | [https://github.com/lwzSoviet/NoXss      ](https://github.com/lwzSoviet/NoXss) |
| 13   | VuIFi                         | https://github.com/Accenture/VulFi                           |
| 14   | Savior                        | https://github.com/Mustard404/Savior                         |
| 15   | DuckMemoryScan                | https://github.com/huoji120/DuckMemoryScan                   |
| 16   | ASP.NET-Memshell-Scanner      | https://github.com/yzddmr6/ASP.NET-Memshell-Scanner          |
| 17   | Finger                        | https://github.com/EASY233/Finger                            |
| 18   | cSubsidiary                   | https://github.com/canc3s/cSubsidiary                        |
| 19   | pigat                         | https://github.com/teamssix/pigat                            |
| 20   | ENScan                        | https://github.com/wgpsec/ENScan                             |
| 21   | ENScan_GO                     | https://github.com/wgpsec/ENScan_GO                          |
| 22   | GoogleHackingTool             | https://github.com/r00tSe7en/GoogleHackingTool               |
| 23   |                               | https://www.exploit-db.com/google-hacking-database           |
| 24   | ipbulklookup.php              | https://www.infobyip.com/ipbulklookup.php                    |
| 25   | ip2domain                     | https://github.com/Sma11New/ip2domain                        |
| 26   |                               | https://github.com/broken5/WebAliveScan  web存活判断     https://github.com/fadinglr/EHole 红队重点攻击系统指纹探测工具     https://github.com/k8gege/K8CScan 漏洞扫描、密码爆破     https://github.com/b1gcat/DarkEye 主机发现+爆破     https://github.com/Adminisme/ServerScan 高并发网络扫描、服务探测工具     https://github.com/dean2021/titlesearch 批量抓取域名title工具     https://github.com/pmiaowu/PmWebDirScan 批量扫目录备份 |
| 27   | Caesar                        | https://github.com/0ps/Caesar                                |
| 28   | CrackQL                       | https://github.com/nicholasaleks/crackQL                     |
| 29   | fuxploider                    | https://github.com/almandin/fuxploider                       |
| 30   | Stowaway                      | https://github.com/lz520520/Stowaway                         |
| 31   | WEF                           | https://github.com/D3Ext/WEF                                 |
| 32   | Sylas                         | https://github.com/Acmesec/Sylas                             |
| 33   | Tsunami                       | https://github.com/google/tsunami-security-scanner           |
| 34   | GooFuzz                       | https://github.com/m3n0sd0n4ld/GooFuzz                       |
| 35   | InScan                        | https://github.com/inbug-team/InScan/                        |
| 36   | CS：Ola                       | https://github.com/d3ckx1/Ola                                |
| 37   | WebCrack                      | https://github.com/yzddmr6/WebCrack                          |
| 38   | ThinkphpGUI                   | https://github.com/Lotus6/ThinkphpGUI                        |
| 39   | GC2                           | https://github.com/looCiprian/GC2-sheet                      |
| 40   | siusiu                        | https://github.com/ShangRui-hash/siusiu                      |
| 41   | PortBrute                     | https://github.com/awake1t/PortBrute                         |
| 42   | POC2jar                       | https://github.com/f0ng/poc2jar                              |
| 43   | /Windows-Exploit-Suggester    | https://github.com/AonCyberLabs/Windows-Exploit-Suggester    |
| 44   | /linux-exploit-suggester      | https://github.com/mzet-/linux-exploit-suggester             |
| 45   | Sherlock                      | https://github.com/rasta-mouse/Sherlock                      |
| 46   | Caesar                        | https://github.com/0ps/Caesar                                |
| 47   | GoBypassAV                    | https://github.com/TideSec/GoBypassAV                        |
| 48   | ToolsFX                       | https://github.com/Leon406/ToolsFx                           |
| 49   | Sec-Tools                     | https://github.com/jwt1399/Sec-Tools                         |
| 50   | SatanSworld                   | https://github.com/Lucifer1993/SatanSword                    |
| 51   | scan4all                      | https://github.com/hktalent/scan4all                         |
| 52   | GoBP                          | https://github.com/awsaaaq/GoBP                              |
| 53   | Nim_Shellloader               | https://github.com/sh3d0ww01f/nim_shellloader                |
| 54   | iisScaner                     | https://github.com/VMsec/iisScaner                           |
| 55   | go-shellcode-loader           | https://github.com/HZzz2/go-shellcode-loader                 |
| 56   | MarsCTF                       | https://github.com/b1ackc4t/MarsCTF                          |
| 57   | All-Defense-Tool              | https://github.com/guchangan1/All-Defense-Tool               |
| 58   | QingTing                      | [https://github.com/StarCrossPortal/QingTing      ](https://github.com/StarCrossPortal/QingTing) |
| 59   | Hello-java-sec                | https://github.com/j3ers3/Hello-Java-Sec                     |
| 60   | fastfinder                    | https://github.com/codeyourweb/fastfinder                    |
| 61   | Fvuln                         | https://github.com/d3ckx1/Fvuln                              |
| 62   | 0day                          | https://github.com/pwntester/0day                            |
| 63   | NmapBrutes                    | https://github.com/CTF-MissFeng/NmapBrutes                   |
| 64   | Nimcrypt2                     | https://github.com/icyguider/Nimcrypt2                       |
| 65   | pystinger                     | https://github.com/FunnyWolf/pystinger                       |
| 66   | ProxyPool                     | https://github.com/Python3WebSpider/ProxyPool                |
| 67   | BerylEnigma                   | https://github.com/ffffffff0x/BerylEnigma                    |
| 68   | zinc                          | https://github.com/prabhatsharma/zinc                        |
| 69   | Yearning                      | https://github.com/cookieY/Yearning                          |
| 70   | Ninja                         | https://github.com/ahmedkhlief/Ninja/                        |
| 71   | railgun                       | https://github.com/lz520520/railgun                          |
| 72   | Assassin                      | https://github.com/b1ackc4t/Assassin                         |
| 73   | Vulmap                        | https://github.com/zhzyker/vulmap                            |
| 74   | MoveKit                       | https://github.com/0xthirteen/MoveKit.                       |
| 75   | POC bomber                    | https://github.com/tr0uble-mAker/POC-bomber                  |
| 76   | TorghostNG                    | https://github.com/githacktools/TorghostNG                   |
| 77   | WanLi                         | https://github.com/ExpLangcn/WanLi                           |
| 78   | StayKit                       | https://github.com/0xthirteen/StayKit                        |
| 79   | WindTerm                      | https://github.com/kingToolbox/WindTerm                      |
| 80   | NarThex                       | https://github.com/MichaelDim02/Narthex                      |
| 81   | Wifi-framework                | https://github.com/domienschepers/wifi-framework             |
| 82   | zuthaka                       | https://github.com/pucara/zuthaka                            |
| 83   | tofu                          | https://github.com/puckblush/tofu                            |
| 84   | Microsoft-365-Extractor-Suite | https://github.com/invictus-ir/Microsoft-365-Extractor-Suite |
| 85   | aiodnsbrute                   | https://github.com/blark/aiodnsbrute                         |
| 86   | gallia                        | https://github.com/Fraunhofer-AISEC/gallia                   |
| 87   | AutoPWN-Suite                 | https://github.com/GamehunterKaan/AutoPWN-Suite              |
| 88   | Nightingale                   | https://github.com/RAJANAGORI/Nightingale                    |
| 89   | ransomware-simulator          | https://github.com/NextronSystems/ransomware-simulator       |
| 90   | CRLFsuite                     | https://github.com/Nefcore/CRLFsuite                         |
| 91   | Jeeves                        | https://github.com/ferreiraklet/Jeeves                       |
| 92   | Octopus                       | https://github.com/mhaskar/Octopus/                          |
| 93   | LEAF                          | https://github.com/alex-cart/LEAF                            |
| 94   | Tornado                       | https://github.com/samet-g/tornado                           |
| 95   | lsarelayx                     | https://github.com/CCob/lsarelayx                            |
| 96   | rustpad                       | https://github.com/Kibouo/rustpad                            |
| 97   | LDAPFragger                   | https://github.com/fox-it/LDAPFragger                        |
| 98   | fuxploider                    | https://github.com/almandin/fuxploider                       |
| 99   | Goby                          | https://github.com/gobysec/Goby                              |
| 100  | xray                          | https://github.com/chaitin/xray                              |
| 101  | pocscan                       | https://github.com/DSO-Lab/pocscan                           |
| 102  | myscan                        | https://github.com/amcai/myscan                              |
| 103  | w9scan                        | https://github.com/w-digital-scanner/w9scan                  |
| 104  | pocsuite3                     | https://github.com/knownsec/pocsuite3                        |
| 105  | msmap                         | https://github.com/hosch3n/msmap                             |
| 106  | 360-bypass                    | https://github.com/wz-wsl/360-bypass                         |
| 107  | red-team-command-generator    | https://github.com/Ar3h/red-team-command-generator           |
| 108  | Lizard                        | https://github.com/wr0x00/Lizard                             |
| 109  | Ten-Thousand-Buddhas          | https://github.com/savior-only/Ten-Thousand-Buddhas          |
| 110  | AniYa                         | https://github.com/piiperxyz/AniYa                           |
| 111  | go-shellcode-loader           | https://github.com/HZzz2/go-shellcode-loader                 |
| 112  | Yosakura                      | https://github.com/m0sway/Yosakura                           |
| 113  | ShellcodeLoader               | https://github.com/ByPassAVTeam/ShellcodeLoader              |
| 114  | crayfish                      | https://github.com/feitu-dev/crayfish                        |
| 115  | satania                       | https://github.com/baimao-box/satania                        |
| 116  | Ruoyi-All                     | https://github.com/passer-W/Ruoyi-All                        |
| 117  | manjusaka                     | https://github.com/YDHCUI/manjusaka                          |
| 118  | taowu-cobalt-strike           | https://github.com/pandasec888/taowu-cobalt-strike           |
| 119  | AuxTools                      | [https://github.com/doimet/AuxTools](https://github.com/doimet/AuxTools) |
