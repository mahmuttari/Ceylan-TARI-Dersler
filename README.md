# Ceylan-TARI-Dersler

1/C Sınıf Öğretmeni Ceylan Tarı'nın sınıf etkinlikleri.

## Dersler

| Ders | Konu | Dosya |
| --- | --- | --- |
| 🔎 A Harfi Bulma Oyunu | A / a harfini bulma | [dersler/a-harfi-bulma-oyunu.html](dersler/a-harfi-bulma-oyunu.html) |
| 🐠 N Harfi Akvaryumu | N / n harfini tanıma, büyük–küçük harf ayrımı | [n-harfi-akvaryum/index.html](n-harfi-akvaryum/index.html) |

Her ders tek bir HTML dosyasıdır; yazı tipi ve sesler dosyanın içine gömülüdür, internet olmadan da çalışır.
Ana sayfa (`index.html`) tüm dersleri listeler.

### N Harfi Akvaryumu

Akvaryumda yüzen rengarenk balıkların üzerinde harfler vardır. Öğrenci oltanın
ucunu (fare veya parmakla) balığın üzerine götürür; kanca balığa değince balık
takılır ve olta onu kendiliğinden su yüzeyine çeker.

- Ekranın üstünde hangi harfin istendiği gösterilir: **Büyük N** veya **Küçük n**.
- Doğru balık yakalanınca su sıçrama ve baloncuk sesi gelir, yıldız kazanılır.
- Yanlış harfli balık (M, m, U, u, H, h, V, Z) yakalanırsa uyarı verilir ve balık suya geri düşer.
- 10 yıldız toplanınca "Tebrikler" ekranı ve N ile başlayan kelimeler gösterilir.
- Sesler tarayıcı içinde üretilir; sağ alttaki 🔊 düğmesi ile kapatılabilir.
- Tarayıcıda Türkçe ses varsa hedef harf sesli olarak da söylenir.

## Yayın

Site GitHub Pages ile `gh-pages` dalından yayınlanır. `main` dalına her gönderimde
`.github/workflows/pages.yml` iş akışı `main` içeriğini `gh-pages` dalına kopyalar.

- Ana sayfa: https://mahmuttari.github.io/Ceylan-TARI-Dersler/
- A Harfi Bulma Oyunu: https://mahmuttari.github.io/Ceylan-TARI-Dersler/dersler/a-harfi-bulma-oyunu.html
- N Harfi Akvaryumu: https://mahmuttari.github.io/Ceylan-TARI-Dersler/n-harfi-akvaryum/
