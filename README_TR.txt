CEBİM · FİNANS PRO — iPhone PWA
================================

Bu klasör Cebim · Finans Pro adlı ayrı bir web uygulamasının dosyalarını içerir.

DOSYALAR
- index.html: uygulama arayüzü ve işlevleri
- manifest.webmanifest: iPhone ana ekranına ekleme / PWA adı ve görünümü
- sw.js: çevrimdışı önbellek ve uygulama güncellemesi
- icon-192.png / icon-512.png: uygulama simgeleri

ÖZELLİKLER
- Net mali durum ve varlık/borç toplamları
- Banka hesapları ve kredi kartlarını ayrı ayrı takip etme
- Kredi kartı limiti, kullanılan ve kalan limit takibi
- Altın, gümüş ve yatırım kayıtları
- Kişi bazında borç/alacak takibi
- Ödeme takvimi, vadesi yaklaşan ve geciken ödemeler
- Şifreli yedek oluşturma ve geri yükleme
- Telefon tarayıcısında yerel kayıt

YAYINLAMA / iPHONE KURULUMU
1. Bu ZIP dosyasını açın.
2. Dosyaların tamamını yeni bir GitHub deposunun kök dizinine yükleyin (ör. cebim-finans-pro).
3. Repository Settings > Pages bölümünde Deploy from a branch seçin; branch olarak main ve folder olarak /(root) seçin.
4. Yayınlanan HTTPS adresini Safari'de açın.
5. Safari paylaş menüsü > Ana Ekrana Ekle ile iPhone'a ekleyin.

ÖNEMLİ
- Bu paket App Store için imzalanmış yerel bir iOS .ipa değildir; Safari üzerinden ana ekrana eklenen PWA'dır.
- Uygulama verileri bu yeni uygulama için ayrı bir yerel depolama anahtarıyla tutulur; eski Cebim sürümünün kayıtlarını otomatik olarak devralmaz.
- Güncellemeden önce ve düzenli aralıklarla yedek alın. Şifreli yedek şifresini kaybederseniz yedeği geri açamazsınız.
- Altın/gümüş fiyatlarının otomatik ve canlı alınması için çalışan, izinli bir fiyat API'si gerekir; uygulama bunu garanti etmez.
- Tarayıcı verilerini temizlemek yerel kayıtları silebilir. Yedek dosyanızı güvenli bir yerde saklayın.
