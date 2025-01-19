Kutuplaşma Analizi Projesi

Proje Açıklaması

Bu proje, Türkçe metinlerde kutuplaşma analizi yapar. Metinler "pozitif" veya "negatif" sınıflara ayrılır ve Zemberek kütüphanesi kullanılarak kelime kökleri ve ekler analiz edilir.

Kullanılan Teknolojiler

Python

Pandas

Zemberek (Türkçe Doğal Dil İşleme Kütüphanesi)

Gerekli Dosyalar

veri.xlsx: Analiz edilecek cümlelerin bulunduğu dosya.

polarization_keywords.xlsx: Pozitif ve negatif kelimelerin listesi.

Kurulum ve Çalıştırma

Gerekli kütüphaneleri yükleyin:

pip install pandas openpyxl

Zemberek kütüphanesini indirin ve kurun.

Kodun başında belirtilen Excel dosyalarını uygun şekilde hazırlayın.

Python dosyasını çalıştırın:

python analiz.py

Çıktılar

output.xlsx: İşlenmiş veriler ve sonuçlar.

"Cümle Verisi" sayfası: Her bir cümle için analiz sonuçları.

"Sonuç Sayıları" sayfası: DP, YP, YN, DN sayıları.

Performans Ölçütleri

Programın sonunda şu ölçütler hesaplanır:

Doğruluk

Kesinlik

Anma

F1 Ölçütü

Projeyi Grup Şeklinde Yaptık.
Mustafa Durmazer(Ben)
Busenur Yıldız
Aleks Dulda
Aybüke Eraydın

Tanıtım Videosu:
https://www.youtube.com/watch?v=5X0wS3CBCz0&t=22s

