# Proje Başlığı

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          		   | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1200505803 | Harun Özdemir		| Yazılım Mühendisliği     | PROJE_8       | [Github](https://github.com/hrnozdm)     	   |
| 1200505065 | Yusuf  Balık   		| Yazılım Mühendisliği     | PROJE_8       | [Github](https://github.com/Yusuf4916)    	   |
| 1200505072 | Bilal Can Bal  | Yazılım Mühendisliği     | PROJE_8       | [Github](https://github.com/BilalCanBal)   	   |

---

## Proje Açıklaması

	Bu proje, önceden eğitilmiş bir derin öğrenme modelini kullanarak muzların görüntülerini sınıflandıran bir uygulamayı içermektedir. Temel amacı, muz görüntülerindeki olası durumları tanıyarak sınıflandırmaktır. Proje, tıbbi görüntü sınıflandırma problemlerine pratik bir uygulama sunmak amacıyla tasarlanmıştır.

**Kapsam:**
- Önceden eğitilmiş VGG16 modeli, transfer öğrenme için temel alınmıştır. Bu model, geniş bir nesne sınıflandırma görevi üzerinde eğitilmiş ve muz görüntülerinde farklı durumları tanıma yeteneği kazanmıştır.
- TensorFlow ve Keras kütüphaneleri, derin öğrenme modelinin oluşturulması, eğitimi ve değerlendirmesi için kullanılmıştır.
- Proje, eğitim, doğrulama ve test veri setleri üzerinde performans değerlendirmesi yaparak modelin gerçek dünya muz görüntülerinde nasıl performans gösterdiğini değerlendirmiştir.

**Kullanılan Teknolojiler:**
- TensorFlow ve Keras derin öğrenme kütüphaneleri: Model oluşturma, eğitim ve değerlendirme için.
- VGG16 modeli: Transfer öğrenme için temel alınan önceden eğitilmiş model.
- Python programlama dili: Uygulamanın temel programlama dili.

**Nasıl Çalıştırılır:**
1. Gerekli kütüphaneleri yükleyin: `pip install tensorflow matplotlib`.
2. Proje dosyalarını indirin veya klonlayın.
3. Ana çalıştırılabilir dosyayı çalıştırarak uygulamayı başlatın.
4. Uygulama, önceden eğitilmiş model kullanarak muz görüntülerini sınıflandıracaktır.

**Proje Yapısı:**
- main.py: Ana çalıştırılabilir dosya.
- model_building.py: Modelin oluşturulması ve derlenmesi ile ilgili işlevleri içerir.
- data_preprocessing.py: Veri setlerinin yüklenmesi ve ön işleme adımlarını içerir.
- utils.py: Yardımcı işlevleri içerir.
- best_transfer_learning_model.h5: En iyi modelin kaydedildiği dosya.



---



## Proje Dosya Yapısı

	- **/DerinOgrenme**
	  - **/Bananas**
		- **/overripe**
		  - `musa-acuminata-mold-e1a4d2b8-1d0a-11ec-af1f-d8c4975e38aa_jpg.rf.49b2874813b9606a2e643b694212cfc1.jpeg`
			.
			.
			.
		- **/ripe**
		  - `musa-acuminata-mold-e1a4d2b8-1d0a-11ec-af1f-d8c4975e38aa_jpg.rf.49b2874813b9606a2e643b694212cfc1.jpeg`
			.
			.
			.
		- **/rotten**
		  - `musa-acuminata-mold-e1a4d2b8-1d0a-11ec-af1f-d8c4975e38aa_jpg.rf.49b2874813b9606a2e643b694212cfc1.jpeg`
			.
			.
			.
		- **/unripe**
		  - `musa-acuminata-mold-e1a4d2b8-1d0a-11ec-af1f-d8c4975e38aa_jpg.rf.49b2874813b9606a2e643b694212cfc1.jpeg`
			.
			.
			.
	  - `Harry70.ipynb`
	  - `Harry80.ipynb`
	- `README.md`

---

## Kurulum


	Görüntü Dosyalarını İndirme:
	Projenin görüntü dosyalarını içeren Google Drive bağlantısına giderek dosyaları indirin.
	https://drive.google.com/file/d/1XPDysSSQsPlSpA8CNzwHOZM5EYZhQQOQ/view

	Proje Kodları İçin Kaynak Kodu Alma:
	Projeyi içeren GitHub reposuna giderek projenin kodlarını indirdik. Visual Studio veya Jupyter Notebook kullanarak kodları açacabilirsiniz.
	Bunun için projenin GitHub sayfasındaki "Preview" düğmesini kullanabilir veya doğrudan bu bağlantıyı kullanabilirsiniz.
	https://github.com/balfatih/YAZ20411_Derin_Ogrenme/blob/main/Week%20%2311/19122023_Derin_Ogrenme_Online_Dersi.ipynb

		VSCode'da Jupyter Notebook'u Başlatma:
		1. VSCode'u açın.
		2. Sol taraftaki "Explorer" sekmesine gidin.
		3. Projeye ait ana dizine sağ tıklayın.
		4. "Open with Code" veya "Open Folder as Workspace" seçeneğini kullanarak projeyi VSCode'da açın.
		5. Sağ üst köşede bulunan "Extensions" simgesine tıklayarak "Python" eklentisini yükleyin.

		Proje Dosyalarını Açma:
		1. Sol taraftaki "Explorer" sekmesinde projenin bulunduğu dizini açın.
		2. Proje dosyalarını içeren dizine gidin.
		3. İlgili Jupyter Notebook dosyasını seçin (örneğin, .ipynb uzantılı dosyalar).
		4. Seçili dosyayı açmak için çift tıklayın veya sağ tıklayarak "Open with Jupyter" seçeneğini kullanın.

		Not: Eğer "Open with Jupyter" seçeneğini görmüyorsanız, "Python" eklentisini ve "Jupyter" eklentisini yüklediğinizden emin olun.

		VSCode içinde Python eklentisi yüklendikten sonra, Jupyter Notebook'u VSCode içinde kullanabilir ve projenizi rahatça yönetebilirsiniz.

		---

## Kullanım
	
	1. Dataların olduğu dizine gidin.
	2. Üstteki dizin girme kısmında veya mouse sol tuşunda o dizine ait terminale girin.
	3. Terminal ekranında jupyter lab kodu yazıp enter tuşuna basın.
	4. Çıkan local jupyter sayfasında yeni bir notebook oluşturun.
	5. Import edilecek kütüphaneleri ekleyin.(Eğer kütüphaneler mevcut değil ise pip install ile terminali açıp teker teker kurabilirsiniz)
	6. Projemiz için gereken kodları teker teker girip çalıştırın.
	7. Datalar çok yüksek veride olduğu için kod kısmında dataların %10 ununu kullanarak çalıştırın.
	8. Sonuçlar için bekleyin.
---

## Katkılar

	1. https://chat.openai.com/
	2. https://github.com/balfatih/YAZ20411_Derin_Ogrenme/blob/main/Week%20%2311/19122023_Derin_Ogrenme_Online_Dersi.ipynb
	3. https://github.com/anjanatiha/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning
	4. https://www.kaggle.com/code/mellonixie/image-classification-cnn-hyperparameter-tuning
	5. https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/
	
---

## İletişim

Proje ile ilgili iletişim bilgileri veya bağlantılarınızı ekleyin. Örneğin, e-posta adresleri, sosyal medya hesapları vb.
