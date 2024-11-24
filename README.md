# Sosyal Medya Reklam Veri Seti Analizi
Bu proje, sosyal medya reklamları ile ilgili bir veri setinin analizi üzerine odaklanmaktadır. Proje, reklam kampanyalarının etkinliğini değerlendirmek , müşteri edinim maliyetleri ve kampanya süreleri arasındaki ilişkiyi anlamak amacıyla çeşitli veri analizi teknikleri kullanmaktadır.


## Veri Seti Tanımı
Veri seti, sosyal medya platformlarında gerçekleştirilen reklam kampanyalarına ait çeşitli metrikleri içermektedir. Aşağıda veri setinin bazı önemli özellikleri yer almaktadır:
Değişken	Açıklama
1. kampanya_kimligi:	Kampanyanın benzersiz kimliği (tamsayı)
2. kampanya_amaci:	Kampanyanın amacı (kategorik)
3. kampanya_suresi:	Kampanyanın süresi (gün cinsinden, tamsayı)
4. kullanilan_kanal:	Kampanyada kullanılan iletişim kanalı (kategorik)
5. donusum_orani:	Kampanyanın dönüşüm oranı (ondalık)
6. edinim_maliyeti:	Müşteri edinim maliyeti (ondalık)
7. yatirim_getirisi:	Yatırımın getirisi (ondalık)
8. konum:	Kampanyanın hedeflendiği coğrafi konum (kategorik)
9. dil:	Kampanyanın dili (kategorik)
10. tiklama_sayisi:	Kampanya ile ilgili toplam tıklama sayısı (tamsayı)
11. gosterim_sayisi:	Kampanyanın toplam gösterim sayısı (tamsayı)
12. katilim_puani:	Kampanya katılım puanı (tamsayı)
13. musteri_segmenti:	Hedef müşteri segmenti (kategorik)
14. tarih:	Kampanya tarih bilgisi (datetime)
15. sirket:	Kampanyayı düzenleyen şirketin adı (metin)
16. hedef_cinsiyet:	Kampanyanın hedeflediği cinsiyet (kategorik)
17. hedef_yas:	Kampanyanın hedeflediği yaş grubu (kategorik)
18. ay:	Kampanya tarihinin ayı (tamsayı)
19. gun:	Kampanya tarihinin günü (tamsayı)
20. gun_ismi:	Kampanya tarihinin gün ismi (kategorik)


## **Kullanılan Teknikler ve Teknolojiler**
Veri Analizi: Pandas, NumPy, scipy kütüphaneleri kullanılarak veri analizi ve istatistiksel analizler gerçekleştirilmiştir.
Veri Görselleştirme: Matplotlib ve Seaborn kütüphaneleri ile verilerin görselleştirilmesi sağlanmıştır.
Korelasyon Analizi: Değişkenler arasındaki ilişkilerin incelenmesi için korelasyon matrisleri oluşturulmuştur.

## **Sonuç ve Tavsiyeler**
- Kampanya süresi edinim maliyeti üzerinde etkilidir.
- Müşteri edinim maliyetlerini düşük tutmak isteyen şirketler, kampanya sürelerini kısaltma yönünde adım atmalıdır.
- Kampanyanın süresinin uzaması, edinim maliyeti açısından anlamlı ve pozitif yönlü bir fark yaratmaktadır.
- Projenin ilerleyen adımlarında, belirli kampanya sürelerinde ve diğer parametrelerden de faydalanarak, müşteri edinim maliyet tahmini veya belirlenen bir müşteri edinim maliyeti temelinde, ideal kampanya süreleri tahmin edilebilir.
- Bu proje, müşteri edinim maliyetini yönetmek ve veriye dayalı bir şekilde karar almak isteyen şirketlerin, çeşitli parametreleri yönetmesi işlemlerinde de kullanılabilir.
- Bu veri seti üzerinde, verinin boyutu göz önüne alındığında, yapay sinir ağları kullanılabilir.

Proje ile ilgili veri setine Kaggle üzerinden buradan ulaşabilirsiniz:

https://www.kaggle.com/code/hanifekaptan/data-analysis-bootcamp-social-media-advertising

Projenizle ilgili daha fazla bilgi veya katkı sağlamak isterseniz, lütfen iletişime geçin.
