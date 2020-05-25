
![caspercku 15.6 nb i7 2630qm](https://cdn.istanbulbilisim.com/p/0/nirvana_cku-3120-4l05v-s_-casper-notebook_103186.jpg)\
\
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Casper CKU 15.6NB**\
\
***Donanım özellikleri***\
İşlemci: *I7 2630QM*\
Chipset: *HM76*\
Ram: *6GB 1600MHz*\
Ses kartı : *Realtek ALC269*\
LAN: *Realtek 8111*

![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Hata çözümleri**
AppleIntelFramebufferCapri.kext ile ilgili bir sorun yaşarsanız boot argümanları kısmına -s komutunu ekleyin ve sistemi başlatın, sonrasında şu komutları tek tek verin:
fsck -fy\
mount uw -i /\
mkdir /kext_yedek\
cd /System/Library/Extensions\
mv appleintelframebuffercapri.kext /kext_yedek\
rm ../Caches/com.apple.kext.caches/Startup/kernelcache\
reboot\
\
Sonrasında yeniden başlayacak ilk kısımda bir çok kext adı ekrana gelecek ve yine yeniden başlayacak, bu yeniden başlayışta direkt olarak yine bi' siyah ekrandan sonra sistem kurulum bitirme ekranı gelecek. 

Bu kext'i silmemizin nedeni IHD4000'ler için olmasıdır, IHD3000 kartların bazılarında hata vermekte.
\
\
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Çalışmayan aksanlar**\
Multimedya dokunmatik tu\uc0\u351 lar\u305 \
Wifi (Wifi adap\'f6r\'fc ya da LAN ba\uc0\u287 lant\u305 s\u305  i\u351  yapar)\
\
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Ses aktif etme**\
[Rehbere gitmek için tıkla](https://osxinfo.net/konu/voodoohda-2-9-2-guncel-ses-kurulum-paketi.9055/)\
\
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **İsteğe bağlı VRAM yükseltme (8GB ve üstü gerekir)**\
[Rehbere gitmek için tıkla](https://osxinfo.net/konu/high-sierra-icin-intelhd-3000-vram-yukseltme.2138/)

![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Yardım topluluğu**\
[osxinfo.net](https://osxinfo.net)

![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Desteklenen yazılımlar**\
High Sierra,
Sierra,
El Capitan,
Mountain Lion
Mojave ve üstünü Intel HD 3000 dolayısıyla desteklememekte.

