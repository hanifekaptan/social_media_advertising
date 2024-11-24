# Sosyal Medya Reklam Veri Seti Analizi
Bu proje, sosyal medya reklamları ile ilgili bir veri setinin analizi üzerine odaklanmaktadır. Proje, reklam kampanyalarının etkinliğini değerlendirmek , müşteri edinim maliyetleri ve kampanya süreleri arasındaki ilişkiyi anlamak amacıyla çeşitli veri analizi teknikleri kullanmaktadır.


## Veri Seti Tanımı
Veri seti, sosyal medya platformlarında gerçekleştirilen reklam kampanyalarına ait çeşitli metrikleri içermektedir. Aşağıda veri setinin bazı önemli özellikleri yer almaktadır:
Değişken	Açıklama
kampanya_kimligi:	Kampanyanın benzersiz kimliği (tamsayı)
kampanya_amaci:	Kampanyanın amacı (kategorik)
kampanya_suresi:	Kampanyanın süresi (gün cinsinden, tamsayı)
kullanilan_kanal:	Kampanyada kullanılan iletişim kanalı (kategorik)
donusum_orani:	Kampanyanın dönüşüm oranı (ondalık)
edinim_maliyeti:	Müşteri edinim maliyeti (ondalık)
yatirim_getirisi:	Yatırımın getirisi (ondalık)
konum:	Kampanyanın hedeflendiği coğrafi konum (kategorik)
dil:	Kampanyanın dili (kategorik)
tiklama_sayisi:	Kampanya ile ilgili toplam tıklama sayısı (tamsayı)
gosterim_sayisi:	Kampanyanın toplam gösterim sayısı (tamsayı)
katilim_puani:	Kampanya katılım puanı (tamsayı)
musteri_segmenti:	Hedef müşteri segmenti (kategorik)
tarih:	Kampanya tarih bilgisi (datetime)
sirket:	Kampanyayı düzenleyen şirketin adı (metin)
hedef_cinsiyet:	Kampanyanın hedeflediği cinsiyet (kategorik)
hedef_yas:	Kampanyanın hedeflediği yaş grubu (kategorik)
ay:	Kampanya tarihinin ayı (tamsayı)
gun:	Kampanya tarihinin günü (tamsayı)
gun_ismi:	Kampanya tarihinin gün ismi (kategorik)


## **Kullanılan Teknikler ve Teknolojiler**
Veri Analizi: Pandas, NumPy, scipy kütüphaneleri kullanılarak veri analizi ve istatistiksel analizler gerçekleştirilmiştir.
Veri Görselleştirme: Matplotlib ve Seaborn kütüphaneleri ile verilerin görselleştirilmesi sağlanmıştır.
Korelasyon Analizi: Değişkenler arasındaki ilişkilerin incelenmesi için korelasyon matrisleri oluşturulmuştur.


Proje ile ilgili veri setine Kaggle üzerinden buradan ulaşabilirsiniz:

https://www.kaggle.com/code/hanifekaptan/data-analysis-bootcamp-social-media-advertising

Projenizle ilgili daha fazla bilgi veya katkı sağlamak isterseniz, lütfen iletişime geçin.
