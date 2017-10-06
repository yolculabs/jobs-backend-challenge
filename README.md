# Yolcu Backend Laravel Challenge

Senden temiz bir **Laravel** kurulumuna eklendiğinde çalışacak bir paket geliştirmeni istiyoruz. (kurulum için gereken artisan komutlarını da dökümante etmen gerekli)

Bu paket temiz kurduğumuz yazılıma asgari olarak şu şekilde bir veritabanı şeması ekleyecek:

### Hotels

- id
- hotel_name

### Countries

- id
- country_name

### Reviews

- id
- text


## Kurallar

* Her bir Country'in içersinde birden fazla **Hotel** olabilir.

* Her bir otel bir adet **Country**'e aittir.

* Hotel ve Country içersinde birden fazla **Review** eklenebilecektir, ve bu Review'lar aynı tablo'yu kullanacaktır(polimorfik ilişki)

bu değişiklikleri yapmak için yukarıda listelenen şemaya **bazı kolonlar eklemeniz** ve Eloquent Modellerine **bazı methodlar eklemeniz gerekecek**

Unit Testlerinin yazılması, laravel kod stilinin takip edilmesi, düzgün isimlendirme ve self-documenting kod yazımı artı puan olarak değerlendirilecektir. 
