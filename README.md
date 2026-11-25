# Lumiwisp — Destek ve gizlilik sayfaları

Lumiwisp (ucansogan games) için herkese açık destek, gizlilik ve veri silme sayfaları.

Destek: ucansogan.games@gmail.com

## GitHub Pages

1. GitHub → + → New repository. Owner: karamane. Repository name: **lumiwisp-pages**. Visibility: Public.
2. Bu klasördeki `index.html`, `privacy.html`, `delete-data.html`, `styles.css`, `icon.png`, `.nojekyll` ve `README.md` dosyalarını repo köküne yükleyip commit edin.
3. Settings → Pages → Build and deployment → Source: Deploy from a branch → main → / (root) → Save.

Beklenen adresler:
- Ana sayfa (Play Console "Web sitesi"): https://karamane.github.io/lumiwisp-pages/
- Gizlilik (Play Console "Gizlilik politikası"): https://karamane.github.io/lumiwisp-pages/privacy.html
- Veri silme (Play Console "Veri güvenliği → hesap/veri silme"): https://karamane.github.io/lumiwisp-pages/delete-data.html

Adresler dağıtım bitince çalışır. Play Console'a girmeden önce gizlilik adresini oturum açılmamış (gizli) bir tarayıcı penceresinde kontrol edin.

## app-ads.txt

AdMob, `app-ads.txt` dosyasını mağaza kaydındaki web sitesinin **alan adının kökünde** arar (`https://karamane.github.io/app-ads.txt`), bu klasörde değil. Yani dosya `karamane.github.io` reposunun kökünde durmalı. Tengrova ve Lumiwisp aynı AdMob yayıncı hesabını kullandığı için tek satır ikisine de yeter:

```
google.com, pub-8045922385291385, DIRECT, f08c47fec0942fa0
```

Bu satır zaten varsa bir şey yapmanıza gerek yok. AdMob yayınlandıktan sonra AdMob → Uygulamalar → app-ads.txt bölümünden doğrulayın.

## Kapsam

Gizlilik politikası şu sürümü anlatır: Google AdMob reklamları (ödüllü + seviye arası), Google Play uygulama içi satın alımları, 6+ karma hedef kitle (13 yaş altına çocuğa yönelik reklam, ilk açılışta yaş sorusu). Google Play Games sıralamaları (sadece 13+). Analiz, hesap ve bulut kaydı yok. Bu tür bir hizmet eklenmeden ya da hedef kitle değişmeden önce metin güncellenmelidir. Site yalnızca yerel stil ve görsel kullanır, izleme betiği ya da dış font yok.

Oyun kaynak kodu ve imzalama dosyaları bu siteye konmaz.
