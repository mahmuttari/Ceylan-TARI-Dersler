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

Akvaryumda yüzen rengarenk balıkların üzerinde harfler vardır. Olta su üstünde
bekler; öğrenci ekrana basılı tutarak (fare veya parmakla) kancayı suya indirir.
Parmak basılıyken kanca balığa takılmaz; kanca balığın üstündeyken parmak
bırakılınca balık takılır ve olta onu kendiliğinden su yüzeyine çeker. Balık
yoksa kanca su üstüne geri çıkar.

- Akvaryumda 30 balık yüzer (beta, japon balığı ve çatal kuyruklu türler); dipte salyangozlar, denizyıldızı ve midye vardır; hem **büyük N** hem **küçük n** balıkları doğrudur.
- Balıklar ara sıra kendiliğinden hızlanır; kanca yaklaşınca bazen ürküp kaçar; takılan balık ara sıra yarı yolda kurtulur.
- Doğru balık yakalanınca su sıçrama ve baloncuk sesi gelir, sayaç 1 artar.
- Yanlış harfli balık (M, m, U, u, H, h, V, Z) yakalanırsa "yanlış" sesi gelir, sayaç 1 azalır ve balık suya geri düşer. Ekranda yazılı uyarı çıkmaz.
- Sayaç 30 olunca "Tebrikler" ekranı gösterilir ve ıslıklı alkış sesi çalar.
- Sesler tarayıcı içinde üretilir; sağ alttaki 🔊 düğmesi ile kapatılabilir.
- Tarayıcıda Türkçe ses varsa yönergeler ve yanlış uyarısı sesli de söylenir.

## Yayın

Site GitHub Pages ile `gh-pages` dalından yayınlanır. `main` dalına her gönderimde
`.github/workflows/pages.yml` iş akışı `main` içeriğini `gh-pages` dalına kopyalar.

- Ana sayfa: https://mahmuttari.github.io/Ceylan-TARI-Dersler/
- A Harfi Bulma Oyunu: https://mahmuttari.github.io/Ceylan-TARI-Dersler/dersler/a-harfi-bulma-oyunu.html
- N Harfi Akvaryumu: https://mahmuttari.github.io/Ceylan-TARI-Dersler/n-harfi-akvaryum/
