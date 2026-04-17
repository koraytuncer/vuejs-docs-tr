# 📖 Vue.js Türkçe Terminoloji Sözlüğü (Glossary)

Bu sözlük, Vue.js dokümantasyon çevirilerinde dil birliğini ve teknik tutarlılığı sağlamak amacıyla oluşturulmuştur. Lütfen çeviri yaparken bu karşılıklara sadık kalın.

| İngilizce Terim | Türkçe Karşılığı | Notlar |
| :--- | :--- | :--- |
| **Component** | Bileşen | Uygulamanın en küçük yapı taşı. |
| **Directive** | Yönerge | `v-if`, `v-for` gibi Vue'ya özel HTML nitelikleri. |
| **Props** | Props | Teknik terim olarak korunmuştur. |
| **State** | Durum | Bileşenin sahip olduğu veri. |
| **Reactivity** | Tepkisellik | Veri değiştiğinde arayüzün güncellenme sistemi. |
| **Template** | Şablon | HTML yapısının tanımlandığı bölüm. |
| **Hook** | Kanca (Hook) | Yaşam döngüsü olayları için kullanılır. |
| **Event** | Olay | Kullanıcı etkileşimleri (tıklama, form gönderme vb.). |
| **Composable** | Composable | Mantık paylaşımı sağlayan fonksiyonlar. |
| **Provide / Inject** | Sağlamak / Enjekte Etmek | Veri iletim mekanizması. |
| **Slot** | Yuva | Dışarıdan içerik kabul eden alanlar. |
| **Teleport** | Işınlama | İçeriği DOM hiyerarşisinde başka yere taşıma. |
| **Single File Component** | Tek Dosyalı Bileşen | `.vue` uzantılı dosyaların genel adı. |
| **Instance** | Örnek | Bir uygulama veya bileşen kopyası. |
| **Bundler** | Paketleyici | Vite, Webpack gibi araçlar. |

---

## 💡 Genel Çeviri Prensipleri

1. **Teknik Terimlerin Korunması:** Eğer bir terimin Türkçesi yazılım dünyasında kafa karıştırıyorsa (örn: `Props`), olduğu gibi bırakmak veya parantez içinde belirtmek daha iyidir.
2. **Eylem Odaklı Dil:** Kullanıcıya yönelik talimatlarda emir kipi veya geniş zaman kullanın (Örn: "Düğmeye tıklayın" veya "Düğmeye tıklanır").
3. **Bilişsel Yük:** "Zaten", "basitçe", "sadece" gibi kelimelerden kaçınarak okuyucunun motivasyonunu koruyun.