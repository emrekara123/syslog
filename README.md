# 📌 Linux Syslog Okuyucu  

Bu proje, **Linux işletim sisteminde syslog dosyasını okuyarak tek yönlü bağlı liste yapısı kullanarak terminalde görüntüleyen bir C programıdır.**  

## 📂 Proje Açıklaması  

- **Syslog**, Linux sistemlerinde olayları kaydetmek için kullanılan bir günlük (log) sistemidir.  
- Bu program, **/var/log/syslog** dosyasını satır satır okur ve her satırı **tek yönlü bağlı liste** yapısında saklar.  
- Bağlı liste, **dinamik bellek yönetimi** ile çalıştığı için log kayıtlarını esnek bir şekilde saklamaya olanak tanır.  
- Liste, terminal üzerinde sıralı şekilde yazdırılır.  

## 🛠️ Kullanılan Veri Yapıları  

- **`struct Node`**: Her düğüm bir syslog satırını içerir.  
- **`yeniDugum()`**: Yeni bir düğüm oluşturur.  
- **`sonaEkle()`**: Bağlı listenin sonuna yeni düğüm ekler.  
- **`syslogOku()`**: Syslog dosyasını okuyup bağlı listeye ekler.  
- **`listeYazdir()`**: Bağlı listeyi terminalde sıralı olarak görüntüler.  
- **`main()`**: Programın çalışmasını sağlar.  

## 📌 Gereksinimler  

- **Linux İşletim Sistemi**  
- **GCC Derleyicisi**  


