# HızlıCevap tanıtım sitesi

Bağımlılıksız HTML, CSS ve JavaScript. iPhone uygulamasına yönlendiren, mobil uyumlu Türkçe tanıtım sitesi.

## Yerel önizleme

```sh
python3 -m http.server 4173 --directory public
```

http://localhost:4173 adresini açın.

## Render'da ücretsiz Static Site

Bu klasörü GitHub deposuna yükleyin. Render → New → Static Site → depoyu seçin.

- Branch: `main`
- Build command: `test -f public/index.html`
- Publish directory: `public`

Alternatif olarak `render.yaml` ile Blueprint oluşturun. Ücretli Web Service, veritabanı veya ek hizmet gerekmez. Render ücretsiz kullanım limitleri geçerlidir. Özel alan adı satın almak gerekmez; Render bir onrender.com adresi sağlar.

## İçerik

- Metinler ve bağlantılar: `public/index.html`
- Örnek senaryolar ve üsluplar: `public/app.js`
- Tasarım ve animasyonlar: `public/style.css`
- Marka görselleri: `public/assets/`

Sitedeki konuşmalar tanıtım amaçlı örneklerdir. Sunucu, kullanıcı hesabı veya gerçek konuşma yükleme işlemi yoktur. Harici font, izleme betiği ve üçüncü taraf JavaScript kullanılmaz.
