# Türk Köyü — Yaşam Simülasyonu

Telefon tarayıcısında oynanan, 2D kuşbakışı küçük bir Türk köyü simülasyonu.
Tek dosyadır (`index.html`, HTML5 Canvas + JavaScript); kurulum ya da internet gerektirmez.

## Nasıl açılır
- `index.html` dosyasını telefon ya da bilgisayar tarayıcısında aç.
- Ya da GitHub Pages'i aç (Settings → Pages → Branch: `main`, klasör: `/ (root)`).

## Öne çıkanlar
- **10 kişilik, çoğu genç bir köy:** kahveci baba ve iki çocuğu, yeni evli bir çift, bakkal,
  öğretmen, çiftçi, genç bir kız ve askere gidecek bir delikanlı. Her oyunda isimler ve kişilikler değişir.
- **Konuşma baloncukları:** Köylüler yolda, kahvede, meydanda ya da evde karşılaşınca sohbet eder.
  Konular kişiliğe, ilişkiye, havaya ve köydeki son olaylara göre seçilir (okey, maç muhabbeti,
  dedikodu, iltifat, aşk itirafı, dertleşme, iş teklifi, borç isteme, laf sokma, barışma...).
  Sohbetlerin ilişkiye, itibara ve paraya gerçek etkisi vardır. 💬 düğmesi tüm sohbetleri gösterir.
- **Gerçekçi ayrıntılar:** "abi, abla, amca, teyze, kanka" hitapları, günlük hava durumu
  (yağmur, kar, sis), köylülerin aklında kalan anılar, profilde "şu an ne yapıyor" bilgisi.
- **Zaman:** 1x hızda 1 gerçek dakika = 1 oyun saati; 2x, 5x, 10x, 30x hız düğmeleri.
- Aşk, kız isteme → nişan → kına → düğün (köyde kız yoksa komşu köyden gelin gelir),
  doğum, yaşlanma, ölüm, miras; okul ve askerlik.
- Bakkal, kahvehane ve sonradan açılan dükkânlar, borç ve iflas, köy hazinesi, 5 yılda bir muhtarlık seçimi.
- **Oyuncu modları:** izleyici, karakter yönetme ("💬 Biriyle konuş", "📍 Bir yere git" dahil), Tanrı modu.
- Her 30 saniyede bir ve sayfadan çıkarken otomatik kayıt (localStorage).

Yeni bir sohbet konusu eklemek için kodda `T('anahtar', ağırlık, akış)` satırlarına bakın (10b bölümü).
