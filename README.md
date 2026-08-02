# VR/AR Gözlüklerinin Evrimi ve Kullanıcı Deneyimi

Sanal ve artırılmış gerçeklik gözlüklerinin 1968''den 2024''e uzanan gelişimini
ve bu cihazların çözemediği kullanıcı deneyimi problemlerini anlatan tek sayfalık
interaktif bir sunum sitesi.

**Canlı:** https://yuceldayan.github.io/vr-ar-ux-presentation/

---

## İçerik

**Tarihsel çizgi** — Sutherland''ın 1968 tarihli ilk başüstü ekranından başlayıp
1995, 2012, 2016, 2018, 2019, 2020, 2022, 2023 ve 2024 kilometre taşlarıyla
bugüne gelen bir zaman akışı; her dönem kendi görseliyle.

**UX problemleri** — Cihazların hâlâ aşamadığı başlıklar ayrı ayrı ele alınıyor:
ergonomi ve ağırlık, denge bozukluğu, fiziksel rahatsızlık, karmaşık arayüz,
lens ve görüş sorunları, ses, dil desteği, bağlantı kopmaları, gizlilik ve
maliyet.

## Nasıl yapıldı

Tek bir `index.html` (88 KB) ve elle yazılmış `styles.css` (16 KB). Çerçeve
kullanılmadı; düzen, geçişler ve duyarlı davranışın tamamı saf CSS ile kuruldu.
30''dan fazla görsel `webp`, `avif`, `png` ve `jpg` biçimlerinde, sayfa ağırlığını
düşük tutacak şekilde seçildi.

```
.
├── index.html      sunumun tamamı
├── styles.css      düzen, tipografi, geçişler
└── images/         30+ görsel (webp / avif / png / jpg)
```

## Çalıştırma

Kurulum gerekmiyor. `index.html`''i tarayıcıda aç, ya da yukarıdaki canlı
adrese git.

## Rolüm

**Tek geliştirici.** Konu araştırması, içerik yazımı, görsel seçimi ve sitenin
tasarımı ile kodlaması bana ait.

## Lisans

MIT