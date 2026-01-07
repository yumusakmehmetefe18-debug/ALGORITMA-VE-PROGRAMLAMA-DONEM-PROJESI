# ALGORITMA-VE-PROGRAMLAMA-DONEM-PROJESI
# 🌌 Uzay Simülasyonu (Space Simulation)

> **Bursa Teknik Üniversitesi - Bilgisayar Mühendisliği** > **Algoritma ve Programlama Dersi Dönem Projesi**

Bu proje, C programlama dili kullanılarak geliştirilmiş konsol tabanlı bir fizik simülasyonudur. Uygulama, Güneş Sistemindeki 8 farklı gezegenin yerçekimi ivmelerini baz alarak, kullanıcının seçtiği fiziksel deneylerin sonuçlarını hesaplar ve karşılaştırmalı olarak sunar.

## 🚀 Özellikler

Uygulama, "Bilim İnsanı" modunda çalışarak aşağıdaki 9 farklı fizik deneyini simüle etmektedir:

1.  **Serbest Düşme Deneyi:** Belirli bir sürede düşülen mesafenin hesaplanması.
2.  **Yukarı Atış Deneyi:** Dikey fırlatılan cismin maksimum yüksekliği.
3.  **Ağırlık Deneyi:** Kütlenin gezegenlerdeki ağırlık karşılığı.
4.  **Kütleçekimsel Potansiyel Enerji:** Konuma bağlı enerji değişimi.
5.  **Hidrostatik Basınç:** Sıvı basıncının yerçekimine göre değişimi.
6.  **Arşimet Kaldırma Kuvveti:** Sıvıların kaldırma kuvveti simülasyonu.
7.  **Basit Sarkaç Periyodu:** Sarkaç salınım hızının analizi.
8.  **Sabit İp Gerilmesi:** Asılı cisimlerdeki gerilme kuvveti.
9.  **Asansör Deneyi:** İvmelenen asansör içindeki etkin ağırlık değişimi.

## 🛠 Teknik Detaylar

Proje, dersin teknik gereksinimlerine tam uyum sağlayacak şekilde geliştirilmiştir:

* **Dil:** C
* **Bellek Yönetimi:** Dizi erişimlerinde **Pointer Aritmetiği** (`*(dizi + i)`) kullanılmıştır. Dizi indisi (`dizi[i]`) kullanımı yoktur.
* **Girdi Doğrulama:** Negatif fiziksel büyüklüklerin (zaman, kütle vb.) kontrolü `if-else` yerine **Ternary Operatörü** (`? :`) ile sağlanarak mutlak değer alınmıştır.
* **Modüler Yapı:** Her deney ayrı bir fonksiyon olarak tasarlanmış, veriler referans yoluyla (pass-by-reference) aktarılmıştır.
* **Matematiksel Fonksiyonlar:** `math.h` kütüphanesi aktif olarak kullanılmıştır.

## 💻 Kurulum ve Çalıştırma

Proje kaynak kodunu bilgisayarınıza indirdikten sonra herhangi bir C derleyicisi (GCC, Clang vb.) ile derleyebilirsiniz.
