1. Aşama:

Çalışma verisi olarak “data.xlsx” kullanılacaktır. Veri setini Eğitim ve test olarak ayırarak “Fiyat” Kategorisi sütununa göre sınıflandırılması
ve test edilmesi yapılacaktır. Ödevin ikinci aşaması için eğittiğiniz modellerden en yüksek doğruluk oranı bulunan modelin  kaydedilmesi gerekmektedir.

2. Aşama:

Kaydedilen  modeli  “test.xlsx” verisi üzerinde test etmelisiniz.
Test edilme işlemi yapılmadan önce eğitim verisine uygulanan veri ön işleme
adımlarının test verisine de uygulanması gerekmektedir.
• Bu adımları gerçekleştiren bir FONKSİYON yazılarak“test.xlsx”
verisinin yolu yüklendiğinde veri ön işleme adımlarının gerçekleştirilmesi önerilir.
-
Notlar:
Model eğitiminde sadece data.xlsx dosyası kullanılmalıdır. 
Modelin pickle dosyası olarak kayıt edilmesi önerilir.
test.xlsx dosyası sadece model kayıt edildikten sonra okunmalı ve kayıt edilen modelde test edilmelidir.
-
Daha yüksek bir doğruluk oranı için ipucu:
train_test_split yaptıktan sonra en yüksek doğruluk oranını veren model bulunduğunda model kayıt edilmeden önce; train_test_split yapmadan ön işlemeden geçirdiğiniz data.xlsx dosyasının tamamını tekrar fit etmeniz ve o modeli kayıt etmeniz önerilir. Çünkü train_test_split yaptığınızda ayırdığınız test verisi model eğitiminde kullanılamayacaktır ve boşa gidecektir. Dosyayı yalnızca x(Bağımlı değişkenler) ve y(Fiyat sütunu) olarak ayırarak fit etmeniz önerilir. 
-

EKSTRA NOT:
Modeli kayıt etme ve test.xlsx dosyasını test etmede çok zorlananlar;
Yalnızca 1. aşamayı uygulayarak ödevi teslim edebilirler. O çözümler de kabul edilecektir. Fakat asıl istenen çözüm 2 aşamanın da yapılmasıdır. 
