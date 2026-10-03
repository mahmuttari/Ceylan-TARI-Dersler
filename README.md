# Ceylan-TARI-Dersler

1/C Sınıf Öğretmeni Ceylan Tarı'nın sınıf etkinlikleri.

## Dersler

| Ders | Konu | Dosya |
| --- | --- | --- |
| 🔎 A Harfi Bulma Oyunu | A / a harfini bulma | [dersler/a-harfi-bulma-oyunu.html](dersler/a-harfi-bulma-oyunu.html) |
| 🐠 N Harfi Akvaryumu | N / n harfini tanıma, büyük–küçük harf ayrımı | [n-harfi-akvaryum/index.html](n-harfi-akvaryum/index.html) |
| 🎩 Sihirbazın Şapkası | Öğrenilen harflerle hece okuma, 1 ve 2 sayıları | [hece-sihirbaz/index.html](hece-sihirbaz/index.html) |

Her ders tek bir HTML dosyasıdır; yazı tipi ve sesler dosyanın içine gömülüdür, internet olmadan da çalışır.
Ana sayfa (`index.html`) tüm dersleri listeler.

### N Harfi Akvaryumu

Akvaryumda yüzen rengarenk balıkların üzerinde harfler vardır. Olta su üstünde
bekler; öğrenci ekrana basılı tutarak (fare veya parmakla) kancayı suya indirir.
Parmak basılıyken kanca balığa takılmaz; kanca balığın üstündeyken parmak
bırakılınca balık takılır ve olta onu kendiliğinden su yüzeyine çeker. Balık
yoksa kanca su üstüne geri çıkar.

- Akvaryumda 20 balık yüzer (beta, japon balığı ve çatal kuyruklu türler); dipte salyangozlar, denizyıldızı ve midye, suda oltaya takılmayan deniz atları, karidesler (biri büyük ve siyah), küçük turuncu bir ahtapot ve pembe solungaçlı beyaz bir aksolotl vardır; balık dışında hiçbir canlı oltaya takılmaz; hem **büyük N** hem **küçük n** balıkları doğrudur.
- Balıklar ara sıra kendiliğinden hızlanır; kanca yaklaşınca bazen ürküp kaçar; takılan balık ara sıra yarı yolda kurtulur.
- Doğru balık yakalanınca su sıçrama ve baloncuk sesi gelir, o harfin sayacı 1 artar.
- Yanlış harfli balık (M, m, U, u, H, h, V, Z) yakalanırsa "yanlış" sesi gelir, büyük olan sayaçtan 1 düşer ve balık suya geri düşer. Ekranda yazılı uyarı çıkmaz.
- Hedef 15 büyük N ve 15 küçük n (toplam 30). Bir harf tamamlanınca yeni balıklar diğer harften gelir. İkisi de dolunca "Tebrikler" ekranı gösterilir ve alkış/tezahürat kaydı çalar.
- Efekt sesleri tarayıcı içinde üretilir; final alkışı Wikimedia Commons'taki kamu malı "Clapping hurray.ogg" kaydıdır (yükleyen: starlite) ve dosyaya gömülüdür. Sağ alttaki 🔊 düğmesi tüm sesleri kapatır.

### Sihirbazın Şapkası (Hece Okuma)

Smokinli sihirbazın masasındaki şapkadan heceler çıkar; öğrenciler heceyi okur,
öğretmen "Okudum, Sıradaki" düğmesine (ya da şapkaya) dokunur, yıldız kazanılır
ve yeni hece çıkar.

- Giriş ekranında öğrenilen harfler seçilir (varsayılan: **a** ve **n**). Seçili
  harflerden türetilebilen tüm heceler üretilir: a, an, na, nan; her biri küçük
  (an), baş harfi büyük (An) ve tamamı büyük (AN) biçimiyle çıkar.
- "Kelimeler de çıksın" (varsayılan açık) ile yalnızca seçili harflerden oluşan
  basit kelimeler de karışır (a ve n ile: ana, Ana, ANA).
- "1 ve 2 sayıları da çıksın" (varsayılan açık) ile arada mavi çerçeveli sayı
  kartları çıkar; sayının altında o kadar nokta vardır.
- Hece sayısı 10 / 20 / 30 seçilebilir; hedefe ulaşınca konfeti ve alkış.
- Heceler A Harfi oyunundaki gömülü "OkulHarf" yazı tipiyle (dik temel harfler,
  tek katlı "a") gösterilir.

## Yayın

Site GitHub Pages ile `gh-pages` dalından yayınlanır. `main` dalına her gönderimde
`.github/workflows/pages.yml` iş akışı `main` içeriğini `gh-pages` dalına kopyalar.

- Ana sayfa: https://mahmuttari.github.io/Ceylan-TARI-Dersler/
- A Harfi Bulma Oyunu: https://mahmuttari.github.io/Ceylan-TARI-Dersler/dersler/a-harfi-bulma-oyunu.html
- N Harfi Akvaryumu: https://mahmuttari.github.io/Ceylan-TARI-Dersler/n-harfi-akvaryum/
- Sihirbazın Şapkası: https://mahmuttari.github.io/Ceylan-TARI-Dersler/hece-sihirbaz/
