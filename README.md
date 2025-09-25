# CatsVsDogsProject
Bu repo, Kaggle üzerinde bulunan Cats vs Dogs veri seti kullanılarak geliştirilmiş bir görüntü sınıflandırma projesini içermektedir. CNN tabanlı derin öğrenme modelleri ile kedi ve köpek görselleri ayrıştırılmış ve projede açıklanmıştır.

## GİRİS
Bu projede, Kaggle Cats vs Dogs veri seti kullanılmıştır.
Veri seti eğitim, doğrulama ve test kısımlarına ayrılmıştır.
Amaç, bir görselin kedi mi yoksa köpek mi olduğunu tespit eden bir model geliştirmektir.

PROJE KAPSAMINDA;

- CNN tabanlı veri seti mimarisi kullanıldı.
- Veri setimiz eğitildi ve test edildi.
- Sonuçlar incelendi.
- Grad Cam yöntemi uygulandı.

## METRİKLER

- Elde edilen sonuçlara göre modelin doğruluk oranı %84 olarak çıktı.
- Confusion Matrix görselleştirildi.
- Overfitting'i azaltma amaçlı dropout uygulandı.



## EKLER

- Grad Cam ile model görselinin hangi bölgelere odaklandığı incelendi.

- İki tane CNN mimarisi denendi ve Grad Cam için last_conv katmanı eklendi.
   
<img width="427" height="184" alt="image" src="https://github.com/user-attachments/assets/475febd0-cf72-4296-a726-b465d3832740" />



## Sonuç ve Gelecek Çalışmalar

- Bu proje sonucunda CNN tabanlı görüntü sınıflandırma modeli oluşturuldu. %84 başarı elde edildi. 

- Gelecekteki çalışmalar için veri arttırma yöntemleri, daha yüksek doğruluk için hiperparametre optimizasyonunda geliştirmeler ve streamlit vb. tabanlı bir kullanıcı arayüzü ile modelin deploy edilmesi amaçlanmaktadır. 

## Linkler
- https://www.kaggle.com/code/emreciftcitr/catsvsdogs-al-mas


