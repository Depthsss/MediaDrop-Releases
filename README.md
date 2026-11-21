# MediaDrop Releases

MediaDrop'un Windows kurulum dosyaları, uygulama içi güncelleme bilgisi (`latest.json`) ve doğrulama hash'leri burada yayımlanır.

## İndir

[**En son MediaDrop kurucusunu indir**](https://github.com/Depthsss/MediaDrop-Releases/releases/latest)

Açılan sayfada `MediaDrop-Setup-<sürüm>.exe` dosyasını indirip çalıştırın.

- Windows 10 22H2 ve Windows 11 (x64)
- Tarayıcı eklentisi ve gerekli medya araçları kurulumla birlikte gelir; Python veya FFmpeg ayrıca kurulmaz.
- Kurulumdan sonra uygulama yeni sürümleri kendisi bulur ve günceller.

## Güvenlik ve doğrulama

Kurucu şu anda Authenticode ile imzalı değildir; Windows SmartScreen "Bilinmeyen yayıncı" uyarısı gösterebilir ("Ek bilgi" → "Yine de çalıştır"). İndirdiğiniz dosyayı aynı release içindeki `SHA256SUMS.txt` ile doğrulayabilirsiniz. Uygulama içi güncellemeler ayrıca Tauri updater imzasıyla doğrulanır.
