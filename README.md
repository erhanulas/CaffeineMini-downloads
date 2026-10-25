# Caffeine Mini

Türkçe macOS menü çubuğu uygulaması. Pilde ve şarja bağlıyken ayrı profillerle sistem ve ekran uykusunu yönetir. macOS 13 ve üzeri; Apple Silicon ve Intel için universal paket.

## İndir ve kur

**[Son sürümü indir](https://github.com/erhanulas/CaffeineMini-downloads/releases/latest)**

1. `CaffeineMini-Kurulum.pkg` dosyasını indirip çalıştırın.
2. macOS yönetici onayını tamamlayın. Uygulama ve sistem yardımcısı birlikte kurulur.
3. **Uygulamalar → Caffeine Mini** yolundan açın.

Sol tık mevcut profilde uyku engellemeyi açar/kapatır; sağ tık ayarları açar. Uygulama her açılışta pasif başlar. Ekran davranışı ve oturum açılışı tercihleri korunur.

## Uygulama içinden güncelleme

1.8.0 ve sonrasında sağ tık → **Güncellemeleri kontrol et…** → **İndir ve kur**. Uygulama paketi indirip SHA-256 özetini doğrular. macOS yönetici onayından sonra kurulum tamamlanır ve uygulama yeniden açılır; tarayıcı açılmaz. Önceki sürümlerden geçişte buradaki kurulum paketini kullanın.

## Paketler

- `CaffeineMini-Kurulum.pkg`: uygulama ve eşleşen sistem yardımcısı; önerilen indirme.
- `CaffeineMini-macOS.zip`: uygulama, kurulum ve yardımcı kaldırma paketleri.
- `CaffeineMini-Yardimci-Kaldir.pkg`: sistem yardımcısını kaldırır. Uygulamayı ayrıca Uygulamalar klasöründen silebilirsiniz.
- `SHA256SUMS`: indirilen dosyaların doğrulama özetleri.

Paketle aynı klasörde `shasum -a 256 -c SHA256SUMS` ile dosyaları doğrulayabilirsiniz.

## Bilinmesi gerekenler

Uyku engelleme sistem genelindeki uyku ayarını etkiler; elle Uyut seçimini de etkileyebilir. Çantaya koymadan önce kapatın. Pil %10 ve altındayken koruma kapatılır. VPN bağlantısı garanti edilmez.

Paketler ad hoc imzalıdır; Apple Developer ID imzası ve notarizasyonu bulunmaz. İlk indirmede macOS güven onayı gerekebilir.

Bu repo yalnızca indirmeler, kullanım bilgileri ve sürüm notları içindir. Uygulamanın kaynak kodu bu repoda yayımlanmaz. GitHub'ın otomatik “Source code” arşivleri yalnızca bu reponun belgelerini içerir.
