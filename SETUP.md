# HikmetCTK profil kurulumu

## 1. Profil repository’sini oluştur

GitHub’da adı tam olarak `HikmetCTK` olan **public** bir repository oluştur. Bu repository’nin README’si profil sayfanın üst kısmında görünür.

## 2. Dosyaları yerleştir

- `README.md` dosyasını repository köküne koy.
- `.github/workflows/snake.yml` dosyasını aynı yol ve isimle ekle.

## 3. İlk Actions çalıştırmasını başlat

Repository’de **Actions → Generate contribution snake → Run workflow** yolunu izle. Workflow, contribution grafiğine göre iki SVG üretip `output` branch’ine yayınlar.

README’deki animasyonlar bundan sonra şu dosyalardan okunur:

- `output/github-snake.svg`
- `output/github-snake-dark.svg`

## 4. Profilde sabitleme

GitHub profilinde **Customize your pins** seçeneğiyle şu 3–5 projeyi öne çıkar:

1. `Star_Seeker_mcp`
2. `Voice_Customer_support_Assistant`
3. `Talk-With-your-data`
4. `RAG-Workspace`

Her repository için kısa bir açıklama, demo bağlantısı ve çalıştırma talimatı bulunan README ekle.

## Notlar

- Bu paket GitHub’a otomatik olarak gönderilmedi; güvenli biçimde yerel çıktı olarak hazırlandı.
- `HikmetCTK` kullanıcı adı veya repository isimleri değişirse README’deki bağlantıları güncelle.
- Dış SVG servisleri GitHub’da genellikle çalışır; servislerden biri erişilemez olursa içerik yine metin olarak kullanılabilir.

