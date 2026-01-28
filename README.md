## Verimizin Hikayesi
Bu projenin amacı, sınav skorunu etkileyen "gizli değişkenleri" ortaya
çıkarmaktır. Ebeveyn eğitim düzeyi gerçekten kader midir? 
Günde 8 saat uyuyan bir öğrenci ile 4 saat uyuyan bir öğrenci arasındaki
performans farkı nedir? Yoksa asıl belirleyici faktör,
öğrencinin ruh sağlığı mıdır? 
Bu analiz, verilerin gürültüsü arasından en temiz ve yakın tahmini yapmayı 
amaçlamaktadır.

## Verimizdeki Değişkenleri Kısaca Anlatalım
student_id <- Öğrenci Numaraları 

gender <- Cinsiyet

social_media_hours <- Sosyal medyaya harcanan süre(günlük)

part_time_job <- Yarı zamanlı bir işi var mı?

sleep_hours <- Günlük uyku saati

exercise_frequency <- Günlük egzersiz sıklığı

internet_quality <- İnternet kalitesi

extracurricular_participation <- Okul dışı etkinliklere katılım sağlıyor mu?

age <- Öğrencinin yaşı

study_hours_per_day <- Günlük ders çalışma saati

netflix_hours <- Günlük Netflix izleme süresi(saat)

attendance_percentage <- Derslere katılım yüzdesi

diet_quality <- Beslenme kalitesi

parental_education_level <- Ebeveyn eğitim düzeyi

mental_health_rating <- Kişi akıl sağlığı puanı

exam_score <- Sınav puanı

- Bu değişkenler arasından bağımlı değişkenimiz exam_score'dur.
student_id değişkenini modelimize dahil etmeyeceğiz çünkü tahmin için işimizi
görecek bir değişken değil.

- Verimizde bolca kategorik değişken var, bunları da kodlar aracılığıyla 
inceleyeceğiz.

- Bakalım sınav puanını hangi değişkenler ne kadar etkiliyor, hangi değişkenler
sınav puanına anlamlı bir etki yapıyor.

## Projede Kullanılan Yöntemler
- Doğrusal Regresyon
- Train/Test Split
- Varsayım Kontrolleri
- Basit Görselleştirme
- Model Karşılaştırmaları

Not: Projede kullanılan data kaggle üzerinden alınmıştır. (student_habits_performance.csv)
