# Fuzzy Logic

## İçindekiler

1. [Giriş](#giriş)
2. [Fuzzy Logic Sistem Mimarisi](#fuzzy-logic-sistem-mimarisi)
[Kaynakça](#kaynakça)


## Giriş

#### Fuzzy Logic Nedir?

Fuzzy Logic, modern bilgisayarın dayandığı "true or false" (1 veya 0) boole mantığından ziyade "doğruluk derecelerine"([0,1]) dayalı bir hesaplama yaklaşımıdır.FL kavramı ilk olarak Lotfi A. Zadeh tarafından 1965 tarihinde yayımlanan “The Theory of Fuzzy Logic and Fuzzy Sets” (Bulanık Mantık ve Bulanık Kümeler Kuramı) adlı makalede ortaya atıldı.

FL yaklaşımı insalardaki Evet ve Hayır değerleri arasındaki tüm ara olasıkları içeren karar verme yöntemini taklit eder.Bir bilgisayarın anlayabileceği mantık bloğu insanın EVET veya HAYIR cevaplarına eşit olan TRUE ve FALSE olan kesin girdilerdir.

Lotfi Zadeh insanların karar verme şeklinin bilgiyarların aksine EVET ve HAYIR arasındaki bir dizi olasılığı içerdiğini gözlemledi.FL kesin çıktıyı elde etmek için girdilerin olasılık seviyeleri üzerinde çalışır.

Bunu örnekledirecek olursak;

<img width="472" alt="FL Login exsample" src="https://user-images.githubusercontent.com/34304850/95390176-aac94f80-08fd-11eb-8939-84e03d456b8b.png">

Örnekte görüldüğü gibi FL insanın karar verme şekline daha yakındır.FL "Oda sıcak (soğuk, ılık, vb.)" gibi belirsiz veya kesin olmayan ifadelerle mantıksal akıl yürütmeyi modellemeye yöneliktir.

Başka bir deyişle, bulanık mantığın bulanık olan mantık değil, bulanıklığı tanımlamak için kullanılan mantık olduğunu söyleyebiliriz.

#### Fuzzy Logic'in Kullanım Alanları İçin Bazı Örnekler

**ABS Fren Sistemi** : Aracın hızına, tekerlek hızına ve hızlanmaya bağlı olarak tehlikeli durumlarda frenleri kontrol etmek için bulanık mantık kullanır.

**Golf tehşiş Sistemi** : Kullanıcının fiziğine ve vuruşuna göre golf sopası seçer.

**Asansör Kontrolü**: Yolcu trafiğine bağlı olarak bekleme süresini azaltmak için kullanılır.

Kimya endüstrisinde pH kontrolü,kurutma ve kimyasal damıtma işlemeri için uygulamaları vardır.

## Fuzzy Logic Sistem Mimarisi

Dört ana bölümden oluşur;

<img width="960" alt="Fuzzy Logic Sistem Mimarisi" src="https://user-images.githubusercontent.com/34304850/95912557-a2fd2580-0dab-11eb-946b-cd5b863c8158.png">

**Fuzzification Module**: Girdileri, yani crips sayıları bulanık setlere dönüştürmek için kullanılır.

**Knowledge Base**: Karar verme sistemini yönetmek için uzmanlar tarafından sağlanan kurallar dizisini ve IF-THEN koşullarını içerir.

**Inference Engine**: Girdiler ve IF-THEN kuralları üzerinde belirsiz çıkarımlar yaparak insanın akıl yürütme sürecini simüle eder.

**Defuzzification Module**: Inference engine ile elde edilen bulanık kümeleri net bir değere dönüştürmek için kullanılır.


## Kaynakça
* Kocaeli Üniversitesi Bulanık Mantık Dersi Notları
* https://www.geeksforgeeks.org/fuzzy-logic-introduction/
* https://www.tutorialspoint.com/artificial_intelligence/artificial_intelligence_fuzzy_logic_systems.htm