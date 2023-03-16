# Football-Players-Potential-Prediction
## PROBLEM
Bir oyuncunun potansiyel olarak ne kadar iyi seviyede olduğunu tahmin etmek.
## VERİ SETİ
Veri seti Kaggle'dan alınmıştır. Veri seti Football Manager oyununun 2020 serisinde bulunan 144750 futbolcunun verilerini içermektedir ve 64 değişkenden oluşmaktadır.

**Kaynak:https://www.kaggle.com/datasets/ktyptorio/football-manager-2020**
### DEĞİŞKENLER
**Not: Belirtilenler hariç diğer özellikler 1-20 arasındadır.**
* **Name**: Oyuncunun ismi.
* **Club**: Oyuncunun forma giydiği kulüp.
* **Division**: Oyuncunun forma giydiği lig.
* **Height**: Oyuncunun boyu (cm).
* **Weight**: Oyuncunun kilosu (kg).
* **Age**: Oyuncunun yaşı.
* **Preferred Foot**: Oyuncunun ayak tercihi.
* **Best Pos**: Oyuncunun pozisyonu.
* **PA**: Oyuncunun potansiyel olarak ulaşabileceği maksimum seviye (0-200).
* **Wor**: Oyuncunun tam kapasitesini ortaya koyarak çalışma arzusunu, bu konuda kendini aşabilmesini ve kendini adama yeteneğini gösterir.
* **Vis**: Oyuncunun başka futbolcuların göremediği, tehlike yaratabilecek açıkları görme yeteneğini gösterir.
* **Thr**: Kalecinin topu oyuna elle sokarken ne kadar isabetli olduğunu gösterir.
* **Tec**: Oyuncunun topla birlikte ne kadar estetik olduğunu gösterir. Zor, değişik ve oyunun yönünü değiştiren paslar vermek için önemli bir özelliktir.
* **Tea**: Oyuncunun taktiksel talimatlara ne kadar uyduğunu ve takım arkadaşlarıyla birlikte ne kadar uyumlu çalıştığını gösterir.
* **Tck**: Oyuncunun faul yapmadan topu rakibinden sökme yeteneğini gösterir.
* **Str**: Oyuncunun fiziksel gücünü rakibini alt etme konusunda ne kadar yararlı kullanabildiğini gösterir.
* **Sta**: Oyuncunun yüksek seviyedeki fiziksel hareketlilikte ne kadar dayanıklı olduğunu gösterir.
* **TRO**: Kalecinin yapılan ortalarda veya defansın arkasına sarkıtılan toplarda kalesini terkedip ileri çıkma eğilimini gösterir.
* **Ref**: Kalecinin beklenmedik anlarda gelen toplara karşı olan tepkisinde ne kadar başarılı olduğunun oranını gösterir.
* **Pun**: Kalecinin topu yakalayabileceği anlarda da olsa yumrukla uzaklaştırmayı tercih etme eğilimini gösterir.
* **Pos**: Oyuncunun savunma yaparken oyunu okuyup, buna göre hareket edip kendini olabilecek en iyi yere konuşlandırma yeteneğini gösterir. Bir oyuncunun tehlikeyi ne kadar iyi süzeceği, bu tehlikeye ne zaman müdahele edeceğine karar vereceğini o anki duruma göre uygun bir mevkide olup olmadığını tartma yeteneğini belirler. Oyuncunun hücum yaparken nasıl bir pozisyon alacağını belirlemez.
* **Pen**: Oyuncunun penaltı kullanma kabiliyetini gösterir.
* **Pas**: Oyuncunun topu arkadaşına ne kadar isabetli bir şekilde aktarabileceğini gösterir.
* **Pac**: Oyuncunun topla birlikte ve topsuz ulaşabileceği en yüksek hızı gösterir.
* **1v1**: Kalecinin rakiple karşı karşıya kaldığı durumlardaki yeteneğini gösterir.
* **OtB**: Oyuncun tehlike yaratabilecek bir pas alabilmesi için topsuz alanda kendini boşa çıkarabilme yeteneğini gösterir.
* **Nat**: Oyuncunun sakat değişken veya antrenman yapmamışken ne kadar iyi şekilde fit kalabildiğini gösterir. Ayrıca yaşlanmaya başladıklarında fiziksel özelliklerini yeterli seviyede tutup tutamayacaklarını, böylece de maç programını ne kadar iyi şekilde karşılayacaklarını yansıtır.
* **Mar**: Oyuncunun savunma yaparken rakibine yakın durma, rakibini tutma yeteneğini gösterir.
* **Lon**: Oyuncunun ceza sahası dışından kaleyi yoklama konusundaki yeteneğini gösterir.
* **Ldr**: Oyuncunun sahada ne kadar sözünü geçirebildiğini gösterir.
* **Kic**: Kalecinin oyun durmuşken topu ayağı ile uzağa ne kadar isabetli gönderebileceğini temsil eder. Aynı şekilde bu özellik, kalecinin eli ile de ne kadar iyi isabetli pas verebileceğini gösterir.
* **Jum**: Oyuncunun boyununda avantajını kullanarak ne kadar yükseğe zıplayabileceğini gösterir.
* **Hea**: Oyuncunun kafa vuruşlarında ne kadar üstün olduğunu gösterir.
* **Han**: Kalecinin kurtarış yaparken topu tutabilme özelliğini gösterir.
* **Fre**: Oyuncunun kaleye yakın veya uzak duran toplarda topu oyuna sokma yeteneğini veya kaleyi yoklama yeteneğini gösterir.
* **Fla**: Oyuncunun yeteneğini, yaratıcılığını ve beklenmedik hareketler yapabilme kabiliyetini gösterir.
* **Fir**: Oyuncunun ayağına pas gelir gelmez topu kontrol edebilme özelliğini gösterir.
* **Fin**: Oyuncunun gol fırsatı yakaladığında son vuruşlardaki yeteneğini gösterir.
* **Ecc**: Kalecinin toplu veya topsuz şekilde beklenmedik hareketler yapma kapasitesini gösterir.
* **Dri**: Oyuncunun topla birlikte koşu yeteneğini ve bunu yaparken topa ne kadar hakim olduğunu gösterir.
* **Det**: Oyuncunun sahaya elinden geleni koyma yeteneğini yansıtır.
* **Dec**: Oyuncunun topla ve topsuz alanda doğru karar verme yetisini gösterir.
* **Cro**: Oyuncunun uzak mesafeden ne kadar isabetli orta yapabildiğini gösterir.
* **Cor**: Oyuncunun kornerleri ne kadar isabetli kullanabilme yeteneğini gösterir.
* **Cnt**: Oyuncunun saha içinde gelişen olaylara mental olarak ne derecede odaklanabildiğini gösterir.
* **Cmp**: Oyuncunun topla veya topsuz alanda sakin kalarak, akıllıca kararlar verebilme yeteneğini gösterir.
* **Com**: Kalecinin defans hattıyla iletişimini ve defans hattının organizasyonunu ne kadar iyi yaptığını gösterir.
* **Cmd**: Kalecinin ceza sahasına gelen ortaları çıkıp alma ve defans hattını düzenleme yeteneğini gösterir.
* **Bra**: Oyuncunun sakatlığa mal olma ihtimaline rağmen kendini riskli müdahelelerde bulma eğilimini gösterir.
* **Bal**: Oyuncunun topla ve topsuz şekilde ayakta kalabilme yeteneğini gösterir.
* **Ant**: Oyuncunun çevresinde olup biteni ne kadar süzdüğünü ve buna göre hareket ettiğini gösterir.
* **Agi**: Oyuncunun aniden durması ve hareketlenmesi; ani bir hareketle, hızlı bir şekilde, toplu ve topsuz olarak farklı yönlere kırabilmesi özelliğini yansıtır.
* **Agg**: Oyuncunun çirkefliğini, sert müdahelelerde bulunma yatkınlığını ve belki de biraz fazla faul yapabilme özelliğini yansıtır.
* **Aer**: Oyuncunun hava toplarındaki fiziksel yeteneğini gösterir.
* **Acc**: Oyuncunun kendi hızına ne kadar çabuk ulaşabildiğini gösterir.
