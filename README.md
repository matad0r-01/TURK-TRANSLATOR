# 𐱅𐰇𐰼𐰜 (TURK)

**Sürüm:** 0.1

## Açıklama
𐱅𐰇𐰼𐰜, Türkçe dil desteği olmayan oyunlardaki İngilizce altyazıları otomatik okuyup Türkçeye çeviren ücretsiz bir masaüstü uygulamasıdır. Oyundaki altyazı bölgesini seçersin, program o bölgeyi düzenli aralıklarla fotoğraflayıp yazıyı okur (OCR) ve çeviriyi oyun üstünde duran bir pencerede gösterir.

## Sistem Gereksinimleri
- Windows 10 / 11 (64 bit)
- İnternet bağlantısı (çeviri çevrimiçi yapıldığı için zorunlu)
- ~200 MB boş disk alanı
- Python, Tesseract veya başka bir program kurmana gerek YOK — hepsi kurulumun içinde gömülü geliyor

## Kurulum
1. Sağdaki **Releases** bölümünden `TURK_Setup_1.0.exe` dosyasını indir.
2. Dosyaya çift tıkla.
3. Lisans sözleşmesini kabul et, kurulacağı klasörü seç, masaüstü kısayolu oluşsun mu seç ve **Kur**'a bas.
4. İlk açılışta Windows SmartScreen uyarı verirse **Ek bilgi > Yine de çalıştır** de.

## Kullanım
1. Oyunu aç, ayarlardan altyazıları aç (**Subtitles: ON**). Mümkünse oyunu **kenarlıksız pencere (Borderless)** modunda oyna.
2. 𐱅𐰇𐰼𐰜 programını aç, **Alan Seç** düğmesine bas ve oyunda altyazıların çıktığı bölgeyi fareyle kutu içine al.
3. **BAŞLAT**'a basıp oyuna geri dön.
4. Türkçe çeviri, ekranın altında her zaman üstte duran siyah pencerede görünür. Pencereyi sürükleyerek taşıyabilirsin.
5. İşin bitince programda **Durdur**'a bas.

## Notlar
- Okuma aralığını (varsayılan 1,2 sn) programdaki ayardan değiştirebilirsin.
- Altyazı bölgesini ne kadar dar seçersen okuma o kadar doğru olur.
- Hata olursa program klasöründeki `hata_log.txt` dosyasına yazılır.
