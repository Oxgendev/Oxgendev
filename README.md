# Merhaba, ben Oğuzhan 👋

Full‑Stack geliştiriciyim. FiveM (Lua) ve modern web teknolojileri (JavaScript, React, Vue, Next.js) ile oyun sunucuları ve yönetim panelleri geliştiriyorum. Veritabanı tarafında SQL, MySQL, PostgreSQL ve MongoDB üzerinde şema tasarımı, migration/rollback akışları, indeksleme ve performans iyileştirme konularında çalışıyorum. Amacım: hızlı, güvenilir ve geliştirilebilir sistemler üretmek.

## 🚀 Öne Çıkan Projeler
- fivem-personal-scripts — QBCore/ESX uyumlu, modüler ve düşük tick kullanan script seti. Kolay kurulum, temiz yapı ve iyi dokümantasyon odaklı.
- fivem-api — Sunucu istatistikleri, whitelist ve kullanıcı yönetimi için REST API. Node.js + Express, PostgreSQL/MongoDB, Redis caching.
- nextjs-dashboard — Sunucu metrikleri, whitelist yönetimi ve script kontrol için yönetim paneli. Next.js + Tailwind + Prisma/Knex.

## 🧰 Teknoloji Yığını
`Lua` `Python` `JavaScript` `TypeScript` `React` `Vue` `Next.js` `Node.js` `Express`  
`SQL` `MySQL` `PostgreSQL` `MongoDB` `Redis` `Prisma` `Knex` `Mongoose`  
`Docker` `GitHub Actions`

## 📈 Ölçülebilir Sonuçlar
- Tick optimizasyonu ile ortalama ms 6.8 → 3.1 (FiveM script’lerinde düşük kaynak kullanımı)
- Redis caching + uygun indeksleme ile API p95 120ms → 70ms
- Migration/rollback disiplinleriyle sürüm geçişlerinde sıfır veri kaybı; bağlantı havuzu ayarıyla DB yükü %30–35 azalma

## 🗂 Veritabanı ve Migration Yaklaşımım
- Şema Tasarımı: İlişkiler net, kritik alanlarda unique/index (ör. `steamHex`), audit alanları (`createdAt`).
- Migration/Rollback: Prisma veya Knex ile versiyonlanmış migration; CI içinde otomatik çalıştırma; güvenli rollback senaryoları.
- İndeksleme ve Sorgu Planı: `EXPLAIN/EXPLAIN ANALYZE` ile plan doğrulama; btree/unique indeks kombinasyonları; N+1 ve tam tablo taramalarını önleme.
- Seed ve Yedekleme: Minimum ama anlamlı seed; `pg_dump/mysqldump/mongodump` ile sürüm etiketli yedekler.
- Bağlantı Havuzu ve Cache: Pool `max` ve timeout ayarları; okunabilir sorgular için cache katmanı; invalidation stratejileri.

## 🧪 Kalite ve Süreç
- Test ve CI: Lint, test ve build adımlarını otomasyona bağlıyorum (Lua için luacheck, Node/Next için lint/test).
- Dokümantasyon: Kurulum, konfig ve örnek senaryolarla anlaşılır README’ler.
- Sürümleme: Semantic versioning ve açıklayıcı release notları.

## 📫 İletişim
- LinkedIn: https://www.linkedin.com/in/o%C4%9Fuzhan-salih-622744374/
- GitHub: https://github.com/Oxgendev
- E-posta: brenfrank827@gmail.com
- Discord: oxgendev
