# Online Gömülü Linux Sistemleri - Geliştirme ve Programlama Kursu (320 saat)

* __Giriş ve Temel Bilgiler__

   * Gömülü Sistemlere Genel Bir Bakış
   * Gömülü Sistemlerin Karakteristik Özellikleri  
   * Bir Kaynak Yöneticisi Olarak İşletim Sistemi
   * İşletim Sistemlerinin Alt Sistemleri
   * Linux Sistemlerinin Tarhihsel Gelişimi
   * Gömülü Linux Sistemi Ne Anlama Gelmektedir?
   * Gömülü Linux Sistemlerinin Masaüstü Linux Sistemlerinden Farklılıklları
   * Mikroişlemci, Mikrodenetleyici, SOC (System on Chip) ve SBC (Single Board Computer) Kavramları
   * Gömülü Linux Sistemleri için Kullanılan Donanımlar, Raspberry Pi, Beaglebone ve Diğerleri
   * Gömülü Sistemlerin Çevre Birimleri
   * Gömülü Sistemlerde Bellek Birimleri
   * Gömülü Sistemler İçin Emülatörler ve QEMU

* __Single Board Bilgisayarlar__

    * Single Board Bilgisayar Nedir?
    * Yaygın Kullanılan Single Board Bilgisayarlar
    * Single Board Bilgisayarların Uygulama Alanları
    * Single Board Bilgisayarların Sınırlılıkları ve Handikapları

* __Raspberry Pi Donanımının Özellikleri__
    
    * Raspberry Pi Donanımındaki CPU, GPU ve RAM Özellikleri
    * ARM İşlemcilerinin Özellikleri
    * ARM işlemcilerinde Cortex Türleri ve Komut Kümeleri Çeşitliliği
    * SD Kart Arabirimi
    * GPIO Arabirimi
    * I2C ve SPI Veri Yolları
    * USB Arabirimi
    * Video/Audio Özellikleri
    * Ethernet ve Wireless Birimleri
    * HDMI ile Bağlantı
    * Güç Kaynağının Olması Gereken Özellikleri ve Soğutucu Gereksinimi
    * Raspberry Pi Donanımında Kullanılan Soketler ve Kablolar

* __BeagleBone Black Donanımının Özellikleri__
    
    * BeagleBone Black Donanımındaki CPU, GPU ve RAM Özellikleri
    * SD Kart Arabirimi
    * GPIO Arabirimi
    * I2C ve SPI Veri Yolları
    * USB Arabirimi
    * Video/Audio Özellikleri
    * Ethernet ve Wireless Birimleri
    * HDMI ile Bağlantı
    * Güç Kaynağının Olması Gereken Özellikleri ve Soğutucu Gereksinimi
    * BeagleBone Donanımında Kullanılan Soketler ve Kablolar
      
* __Gömülü Sistemlere Linux İşletim Sisteminin Yüklenmesi ve Kullanıma Hazır Hale Getirilmesi__

    * Uygun Linux Dağıtımının Belirlenmesi
    * Gömülü Linux Sistemleri İçin Kullanılan Dağıtımlar ve Özellikleri
    * Raspberry Pi Donanımlarında Kullanılan Yaygın Dağıtımlar
    * Linux Dağıtımlarının Gömülü Sisteme Yüklenmesi
    * Diskin Bölümlendirilmesi ve Buna İlişkin Komutlar ve Utility Programlar
    * Toolchain Kavramı
    * Doğal (Native) ve Çapraz (Cross) Toolchain'ler
    * Gömülü Sistemler İçin Çapraz Derleyiciler (Cross Compilers)
    * Ethernet ve Wireless Network Bağlantılarının Sağlanması 

* __Linux Sistemlerinde Dosya Sistemleri__

    * ext2, ext3, ext4, xfs Dosya Sistemlerinin Genel Özellikleri
    * Dosya Sistemlerinin Mount Edilmesi
    * Dosya Sistemlerindeki Temel Dizinler ve Anlamları
    * Dosya Bloklerı, i-node Kavramı
    * Linux'ta Kullanılan Dosya Sistemlerinin Aşağı Seviyeli Tasarımları
    * Dosya Sistemlerine Yönelik Aygıt Sürücüler
    * Dosya Sistemi İle İlgili Komutlar ve Utility Programlar
    * tmpfs ve ramfs Dosya Sistemleri ve Linux'ta Ramdisk Kullanımı

* __Ekran ve Görüntü Birimlerinin Programlanması__
  
   * Terminal Aygıt Sürücüleri
   * Terminal Aygıt Sürücülerinin Programlanması
   * X Window Sistemleri
   * X Window Sistemlerinin Tasarımı ve Programlanmasıne İlişkin Temel Bilgiler
   * Qt Framework hakkında Temel Bilgiler ve Basit Örnekler
   * Framebuffer Kavramı ve Kullanım Alanları
   * Framebuffer Aygıt Sürücüleri
   * Linux'ta Framebuffer Kütüphanesinin Kullanımı
        
* __Çevre Birimlerinin Programlanması__
  
   * USB Arabiriminin Özellikleri 
   * libusb Kütüphanesinin Kullanımı
   * Raspberry Pi ve BeagleBone Donanımlarında GPIO Uçlarının Kullanımı
   * GPIO Uçlarının Programlanmasına İlişkin Örnekler
   * I2C ve SPI Arayüzlerinin Kullanılması
   * UART Kullanımı
   * Raspberry Pi ve BeagleBone Black İçin Tasarlanmış GPIO Uçlarını Kullanan Hazır Kartlar (Add-on Boards)
   * Sensörlerin İşlevleri ve Sensörlerin Kullanımına İlişkin Örnekler
   * LCD Kullanımına İlişkin Örnekler

* __Linux Çekirdeğinin Konfigüre Edilmesi ve Derlenmesi__
* 
    * Konfigürasyon İşleminin Anlamı
    * Önemli Konfigürasyon Parametreleri
    * Kernel Modüllerinin Çekirdeğe Eklenmesi
    * Kernel Modüllerinin Bağımlılıkları
    * Kernel Modülleri ile İlgili Araçlar, Komutlar ve Utility Programlar
    * GNU Make Aracının Temel Düzeyde Kullanımı ve Make Dosyalarının Oluşturulması
    * Linux Çekirdeğinin Derlenmesi

* __Gömülü Linux Sistemlerinde Kullanılan Ön Yükleyici (Boot Loader) Programlar__

  * Ön Yükleyici Kavramı ve Ön Yükleyicileri İşlevleri
  * Birinci ve İkinci Düzey Ön Yükleyiciler 
  * Raspberry Pi ve BeagleBone Black Ön Yükleyici Mekanizması
  * U-Boot (Das U-Boot) Önyükleyicisinin Genel Yapısı ve Kullanımı
    
* __Linux Sistemlerinin Başlatılma Süreci__
  
  * Masaüstü ve Gömülü Sistemlerde Linux Sistemlerinin Başlatılması
  * Kernel Konfigürasyon Parametrelerinin Boot Sürecindeki Etkileri
  * Linux Çekirdeğinin Yüklenmesine İlişkin Aşamalar
  * Boot Süreci Sırasında Dosya Sistemlerinin Mount Edilmesi
  * Boot Sürecinde Etkili Olan Script Dosyaları

* __Linux Sistemlerinde Kullanılan Init Paketleri ve Systemd Init Paketinin Kullanımı__

  * Init Paketlerinin İşlevi
  * SysVInit ve Upstart Paketleri Hakkında Temel Bilgiler
  * Systemd Paketinin Kurulumu
  * Systemd Paketinin İşlevleri
  * Daemon Kavramı 
  * Unit Dosyalarının Oluşturulması ve Servislerin Yönetilmesi
  * Systemd İle Servis Yönetiminin Ayrıntıları
  * Systemd Paketine İlişkin Komutların Kullanımı
  
* __Aygıt Ağacı (Device Tree)__
  
   * Aygıt Ağacı Nedir ve Ne Amaçla Kullanılmaktadır?
   * Aygıt Ağaçlarına Neden Gereksinim Duyulmuştur? 
   * Aygıt Ağaçlarının Genel Yapısı
   * Agıt Ağaçlarının Oluşturulması
   * Aygıt Ağaçlarının Derlenmesi ve Tersine Derlenmesi (Decompile Edilmesi)
   * Aygıt Ağaçları ve Boot Süreci
   * Aygıt Ağaçları ve Aygıt Dosyaları
   * Sistem Çalışırken Aygıt Konfigürasyonlarının Ayarlanması
 
* __Yocto Projesi__
  
    * Yocto Projesi Nedir?
    * Poky ve bitbake Kavramları
    * Katman (Layer) Kavramı ve Kullanımı
    * Image Kavramı ve Kullanımı
    * Image İsimleri
    * Recipe Kavramı ve Kullanımı
    * Log Mekanizması
    * Build İşlemi
   
* __Buildroot Projesi__
  
    * Buildroot Projesi Nedir?
    * Buildroot Çalışma Mekanizması
    * Buildroot Konfigürasyonu
    * Sistemin İsteğe Göre Özelleştirilmesi (Customization)
    * Buildroot'a Yeni Paketlerin Eklenmesi
    * Build İşlemi

* __Linux Sistemlerinde Kullanılan Log Sistemi__

    * log Mesajlarının User Mod ve Kernel Modda Oluşturulması
    * syslod Daemon Programın İşlevi
    * Loglamanın User Modda Programlama Yoluyla Yapılması

* __Linux Daemon (Servis) Programlarının Yazımı__

    * Daemon Programların Anlamı
    * Daemon Programların Oluşturulması ve Devreye Sokulması
    * Daemon Programların Konfigüre Edilmesi
    * User Mod ve Kernel Mod Daemon Kavramı
    * Linux Kernel İçerisindeki Kernel Mod Daemon'lar ve İşlevleri 

* __procfs ve sysfs Dosya Sistemlerinin Kullanımı__
  
    * proc Dosya Sisteminin Genel Yapısı ve Kullanımı
    * sys Dosya sisteminin Genel Yapısı ve Kullanımı
     
* __Linux Aygıt Sürücülerinin Yazımı__
  
    * Aygıt Sürücülerinin Anlamı
    * Linux Aygıt Sürücü Mimarisinin Tanıtımı
    * Linux Çekirdek Modüllerinin Yazımı
    * Çekirdek Modüllerinin Yüklenmesi ve Boşaltılması
    * Karakter Aygıt Sürücülerinin Yazımı
    * Aygıt Sürücülerde Senkronizasyon İşlemleri
    * Aygıt Sürücülerde Bekleme Kuyruklarının Yaratılması ve Bloke İşlemlerinin Sağlanması
    * Aygıt Sürücülerde Bellek Tahsisatları
    * Aygıt Sürücülerin IO Portlarını Kullanması
    * Aygıt Sürücülerde Kesme İşlemlerinin Yönetilmesi
    * Blok Aygıt Sürücülerinin Yazımı
    * Blok Aygıt Sürücülerinde Bellek Haritalaması ve DMA Kullanımı
    * USB Aygıt Sürücüleri
    * Kernel Thread'lerin Yaratılması ve Kullanımı
  
