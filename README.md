Projemde “tiktok_dataset.csv” adlı veri setini inceledim. Çalışmamda; veri setine ait bilgiler, sütun isimleri, veri tipleri,  veri setine ait ilk 5 satır ve son 5 satırın görüntülenmesi, boş değer
sayıları, bulunan boş değerlerin doldurulması, grafiklerle veri görselleştirme işlemleri ve korelasyon analizi yer almaktadır.

Öncelikle gerekli kütüphaneleri tanımlayıp projeye dahil ettim. Kullandığım kütüphaneler:

Pandas: Verilerin tablolaştırılması, analiz edilmesinde kullanılan kütüphanedir.
Matplotlib: Veri görselleştirmede kullanılan kütüphanedir.
Numpy: Matematiksel işlemlerde kullanılan kütüphanedir.
Seaborn: Veri görselleştirmede kullanılır daha gelişmiş bir kütüphanedir.

Veri setime ait bilgiler:

VERİ SETİ:
claim_status: Videonun herhangi bir görüş veya iddia edip etmediğini belirtir.
video_id: Her bir video için benzersiz tanımlayıcı.
video_duration_sec: Video süresi (saniye).
video_transcription_text: Video içeriğinin açıklaması.
verified_status: Doğrulanma durumu.
author_ban_status: Yazar veya içerik üreticinin yasak durumu.
video_view_count: Video görüntülenme sayısı.
video_like_count: Video beğeni sayısı.

#İçerik

Veri Setinin Yüklenmesi: TikTok verileri "tiktok_dataset.csv" dosyasından okunmaktadır.
Veri Keşfi: Sütun isimlerinin incelenmesi ve veri tiplerinin kontrolü.
Veri Görselleştirme: Seaborn ve Matplotlib kullanarak grafikler oluşturma.

#
Temel İstatistikler: Video izlenme, beğeni, paylaşım ve yorum sayılarının analizi.
video_share_count: Video paylaşım sayısı.
video_download_count: Video indirme sayısı.
video_comment_count: Video yorum sayısı.

#Kullanılan Teknoloji ve Kütüphaneler

Python
Pandas
NumPy
Matplotlib
Seaborn

#Kurulum ve Kullanım
--pip install numpy pandas matplotlib seaborn

