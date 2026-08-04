# Çetele — web

[Çetele](https://github.com/yerdekalmazer/cetele) iOS uygulamasının tanıtım ve
gizlilik sayfası. Bağımlılığı yok: iki statik HTML dosyası.

```
index.html      tanıtım sayfası
gizlilik.html   gizlilik politikası (App Store kaydında zorunlu alan)
img/            uygulama ekran görüntüleri ve simge
vercel.json     cleanUrls — /gizlilik uzantısız çalışsın diye
```

## Yayın

Vercel'e bağlıdır; `main` dalına push otomatik dağıtır.
Alan adı: `cetele.tahayerdekalmazer.com`

Ekran görüntüleri uygulama deposundaki `tanitim/appstore/` klasöründen
gelir; tasarım değişince oradan yeniden kopyalanır.

## Yerel önizleme

```bash
python3 -m http.server 8080
```
