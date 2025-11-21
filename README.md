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


----------------------------------------------------------------------

Polarization Analysis Project
Project Description

This project performs polarization analysis on Turkish texts. Sentences are classified as either positive or negative, and the Zemberek library is used to analyze word stems and suffixes. The goal is to detect sentiment tendencies in the given text data.

Technologies Used

Python

Pandas

Zemberek (Turkish Natural Language Processing Library)

Required Files

veri.xlsx – The file containing the sentences to be analyzed.

polarization_keywords.xlsx – List of positive and negative keywords.

Setup & Execution

Install the required libraries:

pip install pandas openpyxl


Download and install the Zemberek library.

Prepare the Excel files as specified at the beginning of the script.

Run the Python script:

python analiz.py

Outputs

output.xlsx – Contains processed data and analysis results.

“Cümle Verisi” sheet – Analysis results for each sentence.

“Sonuç Sayıları” sheet – Counts of DP, YP, YN, and DN categories.

Performance Metrics

At the end of the program, the following metrics are calculated:

Accuracy

Precision

Recall

F1 Score

Project Team

This project was developed as a group:
Mustafa Durmazer (Me), Busenur Yıldız, Aleks Dulda, Aybüke Eraydın

Demo Video

YouTube: https://www.youtube.com/watch?v=5X0wS3CBCz0&t=22s

