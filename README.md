# MediaDrop Releases

MediaDrop'un resmi Windows kurulum dosyaları, güncelleme manifesti ve doğrulama hash'leri bu depoda yayımlanır. Uygulamanın kaynak kodu için [Depthsss/MediaDrop](https://github.com/Depthsss/MediaDrop) deposunu ziyaret edin.

## İndir

[**MediaDrop 1.0.0 kurucusunu indir**](https://github.com/Depthsss/MediaDrop-Releases/releases/latest/download/MediaDrop-Setup-1.0.0.exe)

- Windows 10 22H2 ve Windows 11 (x64)
- Masaüstü uygulaması, yerel tarayıcı köprüsü ve companion eklenti dosyaları dâhildir.
- Opera, Opera GX, Chrome ve Edge için eklenti kurulum rehberi kurucunun içinde bulunur.
- Kurulumdan sonra gerekli medya araçları ayrıca Python veya FFmpeg kurulumu istemeden hazır gelir.

## Güvenlik ve doğrulama

Windows kurucusu şu anda Authenticode ile imzalı değildir; bu nedenle SmartScreen “Bilinmeyen yayıncı” uyarısı gösterebilir. İndirdiğiniz dosyanın bütünlüğünü aynı release içindeki `SHA256SUMS.txt` ile doğrulayabilirsiniz. Uygulama içi güncellemeler ayrıca Tauri updater imzasıyla doğrulanır.

`latest.json`, MediaDrop'un uygulama içi güncelleyicisi tarafından kullanılır. Bu depoda yalnız güncel sürüm ile desteklenen son önceki sürüm tutulur.

## Desteklenen platformlar

- YouTube ve MP3
- Instagram
- X / Twitter
- TikTok

Sorun bildirirken hassas URL, cookie veya token paylaşmayın. Güvenlik açığı bildirmek için kaynak depodaki [özel security advisory](https://github.com/Depthsss/MediaDrop/security/advisories/new) sayfasını kullanın.
