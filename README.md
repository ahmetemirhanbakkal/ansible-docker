# ansible-docker


## Soru-1

Alpine işletim sisteminin üstüne curl ve htop komutları kurulması için Dockerfile yazılır. Bu Dockerfile son sürüm alpine'i çeker ve apt paket yöneticisi ile curl ve htop komutlarını ekler. Bu Dockerfile'ı build ettiğimizde karşımıza bir image gelir. Bu image'i interaktif bir şekilde çalıştırıp alpine sisteminin içine girebliriz.

### Dockerfile'ı build etme

Bulunduğu dizine build eder ve image oluşturur.
**Docker build -t <imagename> .**<br/>
### İmage'i çalıştırma ve terminaline bağlanma
**Docker run -it <imagename> /bin/sh**<br/>
Alpine'in içinde which curl ve which htop komutlarını çalıştırdığımızda /usr/bin klasörünün altında olduğunu görebiliriz ve execute edebiliriz.
  
## Soru-2
  
 Wordpress ve mysql imagelerini çalıştırabileceğimiz bir docker-compose dosyası yazılır. Gerekli çevre değişkenleri atanır ve bağlantılar sağlanır. 80 portunun tuttuğu değer yeni  bir port numarasına atanır. Artık bu port numarası sayesinde wordpress sayfası görüntülenebilir.
 
 ## Soru-3
  
  Ubuntu 20.04 focal versiyonuna otomatize bir şekilde docker kurmak için playbook dosyası yazılır. Bu dosyanın içinde etkilenecek ip adressleri, tasklerin hangi ayrıcalıkla ve   nasıl gerçekleşeceği ile alakalı bilgiler bulunur. Docker'ı indirmek için linkler belirlenir ve son olarak bağımlılıklar yüklenir. Playbook dosyamızı çalıştırmak için içinde etkilenecek ip adreslerini tuttuğumuz bir hosts dosyası bulunur ve burada görevlere göre gerekli başlıklamalar yapılabilir. Bunun haricinde ansible'ın konfigürasyon ayarlarını yapmak için bir ansible.cfg dosyası vardır.
  
 
