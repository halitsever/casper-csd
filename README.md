
<p align="center">
<img src="https://www.casper-teknik.com/wp-content/uploads/2013/11/atrhyh.jpg">  
</p>
<b><img src="https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png"> Casper CKU ve CHY cihazları</b>
<br>
<br>

**Donanım Özellikleri**
<br>CKU<br>İşlemci: I7 2630QM<br>
Chipset: HM76<br>
Ram: *6GB 1600MHz<br>
Ses kartı : Realtek ALC269<br>
LAN: Realtek 8111<br>
<br>
CHY:
<br>
İşlemci : I5 3230M<br>
Ses kartı : Realtek ALC269
Internet/BT kartı: AR5B195
Chipset: HM76<br>
Ram: *6GB 1600MHz<br>
LAN: Realtek 8111<br>
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png)
**CKU için Hata çözümleri**\
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
Multimedya dokunmatik tu\uc0\u351 lar\u305 (Fixlendi artık çalışıyor!) \
Wifi (Wifi adap\'f6r\'fc ya da LAN ba\uc0\u287 lant\u305 s\u305  i\u351  yapar)\
\
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Ses aktif etme**\
[Rehbere gitmek için tıkla](https://osxinfo.net/konu/voodoohda-2-9-2-guncel-ses-kurulum-paketi.9055/)\
\
![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **İsteğe bağlı VRAM yükseltme (8GB ve üstü gerekir)**\
[Rehbere gitmek için tıkla](https://osxinfo.net/konu/high-sierra-icin-intelhd-3000-vram-yukseltme.2138/)

![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **Yardım topluluğu**\
[osxinfo.net](https://osxinfo.net)

![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **CKU için Desteklenen yazılımlar**\
High Sierra,\
Sierra,\
El Capitan,\
Mountain Lion\
Mojave ve üstünü Intel HD 3000 dolayısıyla desteklememekte.


![bilgi](https://i.ibb.co/tKz0q9b/Webp-net-resizeimage-2.png) **CHY için Desteklenen yazılımlar**\
High Sierra,\
Sierra,\
El Capitan,\
Mountain Lion\
Mojave,\
Catalina,\
Big Sur (Şuanlık desteklenmiyor)

# CHY Kurulumu
CHY kullanıyorsanız CHY klasörü içerisindeki EFI dosyalarını kullanın, multimedya tuşları artık CHY desteği ile beraber iki cihazda da çalışıyor.
Wifi çalışır durumda, güç yönetim ve usb port yamaları yapıldı. 
Intel HD 4000 framebuffer yamaları, VRAM ve 2K yamaları yapıldı.<br>
<img src="https://i.ibb.co/9q2R8Hm/Ekran-Resmi-2020-10-24-16-22-52.png">



