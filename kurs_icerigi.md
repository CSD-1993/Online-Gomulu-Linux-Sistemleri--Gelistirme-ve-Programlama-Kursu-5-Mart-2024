# Online Gömülü Linux Sistemleri - Geliştirme ve Programlama Kursu (220 saat)

* __Giriş ve Temel Bilgiler__

   * Gömülü Sistemlere Genel Bir Bakış
   * Gömülü Sistemlerin Karakteristik Özellikleri  
   * Bir Kaynak Yöneticisi Olarak İşletim Sistemi
   * İşletim Sistemlerinin Alt Sistemleri
   * Linux Sistemlerinin Tarhihsel Gelişimi
   * Gömülü Linux Sistemi Ne Anlama Gelmektedir?
   * Gömülü Linux Sistemlerinin Masaüstü Linux Sistemlerinden Farklılıklları
   * Mikroişlemci, Mikrodenetleyici, SOC (System on Chip) ve SBC (Single Board Computer) Kavramları
   * Gömülü Linux Sistemleri için Kullanılan Donanımlar, Raspberry Pi, Beaglebobe ve Diğerleri
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
    * Dosya Sistemlerinin Aşağı Seviyeli Tasarımı
    * Dosya Sistemlerine Yönelik Aygıt Sürücüler
    * Dosya Sistemi İle İlgili Komutlar ve Utility Programlar
    * tmpfs ve ramfs Dosya Sistemleri ve Linux'ta Ramdisk Kullanımı

* __Ekran ve Görüntü Birimlerinin Programlanması__
   * Terminal Aygıt Sürücüleri
   * Terminal Aygıt Sürücülerinin Programlanması
   * Framebuffer Aygıt Sürücüleri
   * Framebuffer Kütüphanesinin Kullanımı
        
* __Çevre Birimlerinin Programlanması__
  
   * USB Arabiriminin Özellikleri 
   * libusb Kütüphanesinin Kullanımı
   * Raspberry Pi Donanımlarında GPIO Uçlarının Kullanımı
   * GPIO Uçlarının Programlanmasına İlişkin Örnekler
   * I2C ve SPI Arayüzlerinin Kullanılması
   * UART Kullanımı
   * Raspberry Pi İçin Tasarlanmış GPIO Uçlarını Kullanan Hazır Kartlar (Add-on Boards)
   * Sensörlerin İşlevleri ve Sensörlerin Kullanımına İlişkin Örnekler
   * LCD Kullanımına İlişkin Örnekler

* __Linux Çekirdeğinin Konfigüre Edilmesi ve Derlenmesi__
* 
    * Konfigürasyon İşleminin Anlamı
    * Önemli Konfigürasyon Parametreleri
    * Kernel Modülleri
    * Kernel Modüllerinin Bağımlılıkları
    * 

* __Gömülü Linux Sistemlerinde Kullanılan Ön Yükleyici (Boot Loader) Programlar__

  * Ön Yükleyici Kavramı ve Ön Yükleyicileri İşlevleri
  * Birinci ve İkinci Düzey Ön Yükleyiciler 
  * Raspberry Pi Ön Yükleyici Mekanizması
  * U-Boot (Das U-Boot) Önyükleyicisinin Kullanımı
    
* __Linux Sistemlerinin Başlatılma Süreci__
  
  * Masaüstü ve Gömülü Sistemlerde Linux Sisteminin Başlatılması
  * Kernel Konfigürasyon Parametrelerinin Anlamı ve Etkileri
  * Boot Süreci Sırasında Dosya Sistemlerinin Mount Edilmesi
  * Boot Sürecinde Kullanılan Script Dosyaları

* __Linux Sistemlerinde Kullanılan Init Paketleri ve Systemd Init Paketinin Kullanımı__

  * Init Paketlerinin İşlevi
  * SysVInit ve Upstart Paketleri Hakkında Temel Bilgiler
  * Systemd Paketinin Kurulumu
  * Systemd Paketinin İşlevleri
  * Servis Yöneticisi Olarak Systemd Paketi
  * Unit Dosyalarının Oluşturulması ve Servislerin Yönetilmesi
  * systemd Paketine İlişkin Komutların Kullanımı
  
* __Aygıt Ağacı (Device Tree)__
  
   * Aygıt Ağacı Nedir ve Ne Amaçla Kullanılmaktadır?
   * Aygıt Ağaçlarından Öncesindeki Durum 
   * Aygıt Ağaçlarının Genel Yapısı
   * Agıt Ağaçlarının Oluşturulması
   * Aygıt Ağaçlarının Derlenmesi ve Tersine Derlenmesi (Decompile Edilmesi)
   * Aygıt Ağaçları ve Boot Süreci
   * Aygıt Ağaçları ve Aygıt Dosyaları
   * Sistem Çalışırken Aygıt Konfigürasyonlarının Ayarlanması
 
* __Yocto Projesi__
  
    * Yocto Projesi Nedir?
    * Poky ve bitbake
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
    * Buildroot'a Yeni Paket Eklemek
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
  
    * proc Dosya Sisteminin Kullanımı
    * sys Dosya sisteminin Kullanımı
     
* __Linux Aygıt Sürücülerinin Yazımı__
    * Aygıt sürücülerin anlamı
    * Linux aygıt sürücü mimarisinin tanıtımı
    * Linux çekirdek modüllerinin yazımı
    * Çekirdek modüllerinin yüklenmesi ve boşaltılması
    * Karakter aygıt sürücülerinin yazımı
    * Aygıt sürücülerde senkronizasyon işlemleri
    * Aygıt sürücülerde bekleme kuyruklarının yaratılması ve bloke işlemlerinin sağlanması
    * Aygıt sürücülerde bellek tahsisatları
    * Aygıt sürücülerin IO portlarını kullanması
    * Aygıt sürücülerde kesme işlemlerinin yönetilmesi
    * Blok aygıt sürücülerinin yazımı
    * Blok aygıt sürücülerinde bellek haritalaması ve DMA kullanımı
    * USB aygıt sürücüleri
    * Kernel Thread'lerin Yaratılması ve Kullanımı
  
