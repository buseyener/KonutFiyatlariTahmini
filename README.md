# KonutFiyatlariTahmini
 Bu proje, İstanbul'daki konut fiyatlarını tahmin etmek amacıyla geliştirilen bir yapay zeka modelinin tüm aşamalarını kapsamaktadır. Projede veri toplama, düzenleme, modelleme ve kullanıcı arayüzü geliştirme süreçleri yer almaktadır.

İçindekiler
Proje Hakkında
Veri Toplama
Veri Ön İşleme
Modelleme
Değerlendirme
Kullanıcı Arayüzü
Gereksinimler
Sonuç
Proje Hakkında:
Bu proje, İstanbul'daki konut fiyatlarını tahmin etmek için geliştirilmiştir. Farklı regresyon modelleri kullanılarak en iyi performansı gösteren model seçilmiş ve bu model üzerinden bir tahmin arayüzü geliştirilmiştir. Projede kullanılan tüm adımlar Jupyter Lab ortamında gerçekleştirilmiştir.

Veri Toplama :
Projenin veri toplama aşamasında, emlakjet.com sitesinden İstanbul'un tüm ilçelerinden yaklaşık 3600 veri çekilmiştir. Bu veriler konutların fiyatlarını ve diğer özelliklerini içermektedir.

Veri Ön İşleme :
Toplanan veriler üzerinde düzenleme ve etiketleme işlemleri yapılmıştır. Bu aşamada eksik veriler doldurulmuş, hatalı veriler düzeltilmiş ve veriler analiz için hazır hale getirilmiştir.

Modelleme:
Proje kapsamında kullanılan regresyon modelleri şunlardır:

Gradient Boosting Regressor
Multilinear Linear Regression
Random Forest Regressor
Support Vector Regression
Polynomial Regression
Her bir model üzerinde eğitim yapılmış ve performansları değerlendirilmiştir.

Değerlendirme:
Yapılan değerlendirmeler sonucunda en iyi performansı Gradient Boosting Regressor modeli göstermiştir. Bu model ile eğitim süreci tamamlanmış ve model, gelecekteki tahminler için kullanıma hazır hale getirilmiştir.

Kullanıcı Arayüzü:
Kullanıcıların kolayca konut fiyat tahmini yapabilmeleri için bir kullanıcı arayüzü tasarlanmıştır. Bu arayüz, kullanıcıların çeşitli konut özelliklerini girmelerine olanak tanır ve bu özelliklere göre tahmin edilen fiyatı gösterir.

Gereksinimler:
Projenin çalışabilmesi için aşağıdaki yazılımların kurulu olması gerekmektedir:

Python 3.x
Jupyter Lab
Gerekli Python kütüphaneleri (requirements.txt dosyasında belirtilmiştir)

Sonuç:
Bu proje, İstanbul'daki konut fiyatlarını tahmin etmek için etkili bir yapay zeka modeli geliştirmiştir. Gradient Boosting Regressor modelinin en iyi performansı gösterdiği tespit edilmiştir ve kullanıcı dostu bir arayüz ile bu modelin kullanımını kolaylaştırılmıştır.
