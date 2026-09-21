# DTB B2 Kelime Çalışması

Bu klasör GitHub Pages'e yüklemeye hazır. Android, iOS ve masaüstü tarayıcılarda çalışır;
telefonda "Ana Ekrana Ekle" ile normal bir uygulama gibi açılabilir, bir kez ziyaret
ettikten sonra internetsiz de kullanılabilir.

## Yayınlama adımları (GitHub Pages)

1. GitHub'da yeni bir repo oluşturun (örn. `dtb-vocab`), **Public** olsun.
2. Bu klasördeki 5 dosyayı (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`,
   `icon-512.png`) repo'nun kök dizinine yükleyin (sürükle-bırak ile de olur:
   repo sayfasında "Add file" → "Upload files").
3. Repo'da **Settings → Pages** sekmesine gidin.
4. "Build and deployment" altında **Source: Deploy from a branch** seçin,
   **Branch: main / (root)** seçip **Save**'e basın.
5. Birkaç dakika içinde şu adreste yayınlanır:
   `https://KULLANICI_ADINIZ.github.io/REPO_ADINIZ/`

## Telefona uygulama gibi ekleme

- **Android (Chrome):** Siteyi açın → sağ üstteki ⋮ menü → "Ana ekrana ekle" /
  "Uygulama yükle".
- **iPhone (Safari):** Siteyi açın → paylaş simgesi (kare + ok) → "Ana Ekrana Ekle".

Ekledikten sonra normal bir uygulama simgesi gibi görünür, tam ekran açılır.

## Güncelleme

Kelime listesini veya uygulamayı güncellersem, yeni `index.html` dosyasını aynı
şekilde repo'ya yükleyip eski dosyanın üzerine yazmanız yeterli — link değişmez.

## Notlar

- İlerleme (bildiğin/bilmediğin kelimeler, kaldığın yer) tarayıcının kendi
  hafızasında (localStorage) tutulur — yalnızca o cihazda/tarayıcıda geçerlidir,
  cihazlar arasında senkronize olmaz.
- "↺ Baştan Başla" butonu sadece kaldığın yeri sıfırlar, öğrenme ilerlemeni silmez.
