# FirmaLimanLojistik

                  VERI TABAN PROJESI 
     

##  Proje Konusu

* Bu proje, **fabrikalarda üretilen yüklerin limanlara taşınma sürecini yöneten** bir lojistik sistemini kapsamaktadır.
* Sistem, yüklerin hangi fabrikadan çıktığını, hangi limana gönderildiğini, taşıma işlemini hangi araç ve şoförün yaptığını takip eder.
* Sevkiyatın durumunu (**Planlandı**, **Yolda**, **Teslim Edildi**) takip eder.

---

##  Yapılacak İşlemler

* Her varlık için gerekli veri tabloları oluşturulacak.
* Sevkiyatlar listelenecek (üreten firma ve gönderen liman bilgileriyle).
* Siparişler ücreti hesaplanacak ve oluşturulacak.
* Şoför eklenecek / silinecek.
* Araç eklenecek / silinecek.

---

##  Varlıklar ve Nitelikleri

### Varlıklar

* Fabrika
* Liman
* Şoför
* Yük
* Araç
* Sevkiyat
* Çalışan
* Yonetici
* Muhasebeci

### Nitelikler (Veri Yapısı)

* **Fabrika:** FabrikaID, FabrikaAdı, Şehir, Adres, Telefon
* **Liman:** LimanID, LimanAdı, ArabaGirişÜcreti, Şehir, Adres
* **Şoför:** ŞoförID, EhliyetNo, AraçID
* **Yük:** YükID, YükTürü, Miktar, FabrikaID
* **Araç:** AraçID, Plaka No, Marka, Model
* **Sevkiyat:** SevkiyatID, SevkiyatDurumu, AraçID, YükID, LimanID, Tarih, Ücret
* **Çalışan:** CalisanID,Ad ,Soyad,TelefonNo
* **Yonetici:** YoneticiID ,Pozisyon
* **Muhasebeci:** MuhasebeciID ,Deneyim
  
