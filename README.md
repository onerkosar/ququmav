# QUQUMAV — oyun sitesi

Statik site (GitHub Pages ile yayınlanabilir: Settings → Pages → Branch: bu dal, klasör: `/ (root)`).

| Sayfa | Yol |
|---|---|
| Ana sayfa (TR) | `index.html` |
| Ana sayfa (EN) | `en/index.html` |
| Genel gizlilik politikası + veri silme | `gizlilik/index.html` (`#veri-silme`, `#data-deletion`) |
| Oyun gizlilik politikaları (TR + EN) | `gizlilik/yeniceri.html`, `gizlilik/kizil-zambak.html`, `gizlilik/sledge-smash.html`, `gizlilik/block-core.html`, `gizlilik/oyuncak-atolyesi.html` |
| AdMob yetkili satıcı dosyası | `app-ads.txt` (ve `ads.txt`) — sitenin **kök** adresinde olmalı |

Mağaza formlarında "Gizlilik politikası URL'si" olarak ilgili oyunun `gizlilik/<oyun>.html` adresini,
"Geliştirici web sitesi" olarak sitenin kök adresini kullan (app-ads.txt orada aranır).
