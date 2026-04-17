# Vue.js Türkçe Dokümantasyon Katkı Rehberi

Vue.js Türkçe çeviri projesine hoş geldiniz! Bu proje, Vue.js resmi dokümantasyonunu Türkçeye kazandırmayı ve güncel tutmayı amaçlar. Katkıda bulunmadan önce lütfen bu rehberi dikkatlice okuyun.

## 🚀 Başlarken

1. **İletişim Kurun:** Bir sayfa üzerinde çalışmaya başlamadan önce [Discussions](https://github.com/poyrazavsever/vuejs-docs-tr/discussions) sekmesinde niyetinizi belirtin veya mevcut bir [Issue](https://github.com/poyrazavsever/vuejs-docs-tr/issues) üzerinden görevi üstlenin.
2. **Projeyi Çatallayın (Fork):** Ana depoyu fork'layın ve bilgisayarınıza klonlayın. Ardından terminalde proje dizinine girerek `pnpm install` ile bağımlılıkları kurun. Çevirilerinizi yaparken `pnpm run dev` ile projeyi yerelde çalıştırarak anlık önizleme yapabilirsiniz.
3. **Görevi Üstlenin:** Project Board veya Issue'lar üzerinden boşta olan bir sayfayı seçin ve ilgili Issue altına "I'm working on this" yazın.

## ✍️ Yazım Kuralları (Önemli!)

Yazarken bir "teknik yazar" gibi düşünün ve empati kurun:

- **Bilişsel Yükü Azaltın:** "Sadece", "Kolayca", "Basitçe" gibi kelimeleri kullanmaktan kaçının. Bu kelimeler, o adımda zorlanan okuyucunun kendini kötü hissetmesine neden olur.
- **Terim Tutarlılığı:** Mutlaka `GLOSSARY.md` dosyasındaki terim karşılıklarını kullanın. (Örn: Component -> Bileşen).
- **ID'leri Koruyun:** Başlıklardaki `{#anchor-id}` yapılarını asla değiştirmeyin. Bu bağlantılar sitenin iç link yapısını sağlar.
- **Kod Blokları:** Kodun kendisini değiştirmeyin, ancak kod içindeki açıklama satırlarını (comments) Türkçeye çevirin.

## 🛠 Teknik Süreç

- Her sayfa çevirisi için ayrı bir **Branch** (dal) açın.
- Çevirinizi bitirdiğinizde **Pull Request (PR)** oluşturun.
- PR'ınız en az bir başka çevirmen tarafından gözden geçirilip onaylanmalıdır.
- Tarihçenin temiz kalması için "Squash and Merge" yöntemini kullanıyoruz.

Teşekkürler! Birlikte Vue topluluğunu büyütelim. 🚀