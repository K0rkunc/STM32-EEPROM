# STM32-EEPROM

STM32 tüm serilerde kullanılabilir.

STM32f103c8tx serisine göre rom sektorleri ayarlanmıştır 1kb kapasite belirtilmiştir. Eğer başka bir seri ile kullanılacak ise EEconfig.h içerisindeki sektör/page değer datasheet üzerindeki adreslerle değiştirilmelidir.

# EEPROM Kayıt
kayıt edilecek veri char dizisine kayıt edilir.

 ee_writeToRam(kayıt başlangıç adresi sıfır yazılabilir, dizi uzunluğu , char dizi);
 ee_commit(); // Ramden roma aktarır.


# EEPROM Okuma
 ee_read(Başlangıç adresi kayıtta kullandığınız adres olmalıdır, dizi uzunluğu,char formatında dizi değişkeni yazılır)

www.elektronikatolyem.com daha fazlası için sizemi ziyaret etmeyi unutmayın.
