# Senior-Backend-PHP-Challenge

Senden temiz bir **Laravel** kurulumuna eklendiğinde çalışacak bir paket (kurulum için gereken artisan komutlarını da dökümante etmen gerekli), 5 ayrı php dosyasına da random ürün listesi eklenmiş json data istiyoruz.

Bu paket temiz kurduğumuz yazılıma asgari olarak şu yapı ve tabloları ekleyecek:

## TABLOLAR

### Jobs

id (int)

JobId char(16)

### SearchData

id

name



## CLASSES

### Product Search

* 5 PHP dosyasından ürün listesini çekecek. Ve veritabanına kaydedecek.

### Itinerary

* Farklı yapılardaki 5 JSON datayı tek bir biçime dönüştürüp kaydedecek.

### Search Results

* Database'den Jobs tablosunu ve searchdatayı relation olarak getirecek bir model kurulacak.




## Kurallar

* Her bir PHP dosyasında farklı yapılarda ürün listesi dataları yer alacak.

* Her bir ürün listesi için curl ile veri çekilecek ve her PHP dosyasında 5-9 sn arası sleep() yer alacak.

* Ürün aramaları 5 dosya ile aynı anda başlayacak ve arama başlamadan JobId üretilecek

* SearchData için sorgu yapıldığında get işlemi tamamlananlar sonuç olarak dönülebilecek.

bu değişiklikleri yapmak için yukarıda listelenen şemaya **bazı kolonlar eklemeniz** ve Eloquent Modellerine **bazı methodlar eklemeniz gerekecek**

Unit Testlerinin yazılması, laravel kod stilinin takip edilmesi, düzgün isimlendirme ve self-documenting kod yazımı artı puan olarak değerlendirilecektir. 
