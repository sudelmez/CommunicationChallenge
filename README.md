# SKYSIS-Communication-Challenge

Bu challenge içerisinde iletişim protokollerini temel alan proje listesi verilmiştir. Verilen projeler tinkerCAD üzerinde simule edilerek bu repoda paylaşılacaktır. TinkerCAD üzerinde gerçeklenemeyecek olanlar ise Kulüp odasında gerçekelemanlar ile gerçeklenecek ve ortak olarak paylaşılacaktır. Başarılar dilerim.

TinkerCAD üzerinde yapılacak olan projeler:

  *[x] TinkerCAD'daki I2C ile çalışan LCD ekrana veri yazdırma: I2C LCD kullanarak herhangi bir sensörden okuduğunuz veriyi LCD ekrana yansıtmanız gerekmektedir. Okuma yapmak için kuracağınız sistem kendi insiyatifinize bırakılmıştır.

   *[ ] 2 adet Arduino arasında Handshake kullanan bir UART veri iletişimi: 2 adet arduino arasında UART tabanlı bir veri iletimi gerçekleştirilecektir. Buradaki dikkat edilmesi gereken nokta iletişimin handshake içermesidir. Bu handshake modelinde haberleşme 'SR' komutuyla başlayacak olup 'ST' komutu ile son bulacaktır. Bu komutları gönderici taraf kullanacaktır. Alıcı taraf ise karşı taraftan her komut ya da veri aldığında karşı tarafa 'ACK' gönderecektir. Böylece daha güvenilir bir iletim sağlanacaktır.

   *[ ] SPI protokolü ile ayrık sistemleri bir arada çalıştırma: Bu görevde ise 2 adety birbirine bağlı Arduinolardan bir tanesinde potansiyometreden pozisyon verisi alınıp karşıya iletilir. Karşı taraftan alınan veriye göre servo motor belirli bir pozisyona getirilir.
