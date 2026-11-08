# Ramazan Sofrası

İftar ve sahur davetlerini kolayca organize etmek için kişiye özel bir Ramazan takvimi. Kim, hangi gün davet veriyor — tek bakışta görülebilir, istersen çıktı alıp buzdolabına asabilirsin.

## Özellikler

- 🔐 **Kişiye özel** — sadece davet ettiğin e-postalarla paylaşılır (Firebase Authentication)
- 💌 **Davet sistemi** — eşini/ailenizi davet et, birlikte düzenleyin
- 📋 **Liste** ve 📅 **Takvim** (gerçek duvar takvimi) görünümü arasında geçiş
- 🌙 İftar + 🌃 Sahur ayrı ayrı takip edilebilir
- ⭐ **Kadir Gecesi** ve **Arefe Günü** otomatik işaretlenir
- 🎉 **Ramazan Bayramı** günleri takvime otomatik eklenir
- 🖨️ Tek A4 sayfasına sığan, güzel bir çıktı alma özelliği
- 🎨 Takvim adı, kullanılan kelimeler ve renk teması özelleştirilebilir
- 📅 Ramazan tarihleri Diyanet'in resmi takvimine göre **otomatik** geliyor, elle girmene gerek yok

## Teknik

Tek dosyalık bir web uygulaması (vanilla JS), Firebase Firestore + Authentication kullanıyor. GitHub Pages üzerinde barındırılıyor.

## 📋 Sürüm Geçmişi

| Sürüm | Değişiklik |
|---|---|
| 1.0 | İlk sürüm — kişiye özel takvim, davet sistemi, liste görünümü |
| 1.1 | Gerçek duvar takvimi görünümü eklendi (hafta/gün ızgarası), Liste/Takvim geçişi |
| 1.2 | İftar + Sahur ayrı takip, takvim adı/kelime/renk teması özelleştirme |
| 1.3 | Ramazan tarihleri Diyanet'in resmi takvimine göre otomatik geldi, elle girme sadece istisnai durumlar için |
| 1.4 | Kadir Gecesi ve Arefe Günü özel olarak işaretlendi (görsel + etiket) |
| 1.5 | Ramazan Bayramı günleri takvime otomatik eklendi, kendine özgü renk/görselle ayrıştırıldı |
| 1.6 | Çıktı alma özelliği eklendi, tek A4 sayfasına sığacak şekilde optimize edildi |
| 1.7 | Görsel tasarım: gerçek fon görseli, kandil/bayram illüstrasyonları, dolu/boş/hafta sonu renk ayrımı, giriş sonrası önemli tarihler özeti |
