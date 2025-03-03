# 🥁 JS Drum Kit

Bu proje, klavyedeki belirli tuşlara basarak davul sesleri çıkarmanızı sağlayan bir JavaScript uygulamasıdır. HTML, CSS ve JavaScript kullanılarak oluşturulmuştur.


# 🚀 Özellikler

- 🎵 Klavyedeki belirli tuşlara basıldığında ilgili davul sesi çalar.
- 🎨 Tuşa basıldığında görsel bir efekt oluşur.
- ⏳ Efekt, animasyon tamamlandığında sıfırlanır.


# 🛠 Kullanılan Teknolojiler

- **HTML**: Sayfa yapısını oluşturmak için.
- **CSS**: Tuşların ve animasyonların stilini belirlemek için.
- **JavaScript**: Tuşlara basıldığında ses oynatmak ve animasyonu kontrol etmek için.


# 🔧 Nasıl Çalışır?

- ⌨️ Tuşa Basma (keydown event)

Kullanıcı belirli bir tuşa bastığında, ilgili ses çalınır ve görsel efekt eklenir.


- 🔊 Ses Çalma

JavaScript, basılan tuşa karşılık gelen `<audio>` elemanını bulur ve sesi oynatır.


- 🎬 Animasyon

Tuşa basıldığında ilgili butona `.playing` sınıfı eklenir.


- 🎭 Animasyonu Sıfırlama

CSS geçiş efekti tamamlandığında `.playing` sınıfı kaldırılır.
