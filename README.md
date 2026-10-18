# mood-tracker

Proje Gemini 4 Argon modeli ile oluşturulmuştur.

Gemini Prompt'u:
Aşağıdaki talimatlara göre bir duygu takip uygulaması geliştir.

MOOD TRACKER

FİKİR:
Gün içerisinde aynı saat içerisinde bile birden fazla duyguyu yaşayabiliyorum. Eskiden twit atardım ama şimdi twiter kullanmadığım için yazamıyorum, paylaşamıyorum. Yaşadığım duyguları somutlaştırmak ve takip etmek için bu uygulamayı geliştiriyorum.
Aynı işi yapan başka araçlar kullanmıyorum çünkü gizlilik ve kişiselleştirme.
PWA özellikli Web uygulaması.

İÇERİK:
Takvim üzerinden her güne gidilebilir. Günlük, haftalık ve aylık grafikler olacak. 

Anasayfa: Ekranın üstüne bitişik bir şerit geçiyor. En sağında “Grafikler” sayfasının butonu var. En solunda ise “Anasayfa” sayfasının butonu var. Bu şerit hangi sekmede olunursa olunsun sabit kalır. O şeritin altında bitişik olmayacak şekilde “Yeni duygu gir” butonu yer alır. Butona tıklandığında “Yeni duygu gir” sayfasına gidilir. O butonun altında yine bitişik olmayacak şekilde takvim görünümü yer alır. Takvimin altı takvim üzerinde herhangi bir güne tıklanmadığı sürece boştur. Takvimde bir güne tıklanması halinde seçilen günün girdileri liste formatında alt alta ilk girilenden son girilene doğru simge-duygu-saat-tarih bilgileri yer alacak şekilde sıralanır. O duygu girdisinin üstüne tıklanınca ilgili “duygu sayfası”na gidilir.

Yeni duygu gir: Butonu anasayfada “takvim”in üstünde yer alır, tıklandığında bu sayfaya ulaşılır. Sayfada sol üstte simge boşluğu yer alır. Simge boşluğuna emoji ya da galeriden bir fotoğraf eklenebilir. Simge boşluğunun sağında ekranın sonuna kadar hissedilen duyguyu girmek için boşluk bulunur. Bu boşluğun altında yine simge boşluğunun yanında kalıcak şekilde tarih gösterilir. Herhangi bi değişiklik hakkı tanınmaz. Sadece tarih “gün/ay/yıl - saat” formatında yazılır. Saat “Yeni duygu gir” butonuna tıklandığındaki saati gösterir. Bu ikisinin altında kategori seçme kutucuğu yer alır. Kategori seçme grafikler için önemli olacak. Kategori seçme kutucuğunun da altında ekranın sonuna kadar olan dikdörtgen metin boşluğu bulunur. Bu boşluk açıklama yazmak içindir. Ekranın sonunda “Kaydet” butonu bulunur. Butona basılınca duygu kaydedilmiş olur ve otomatik olarak kullanıcı anasayfaya atılır.

Duygu sayfası: “Yeni duygu gir” sayfasıyla aynı sayfa düzenine sahiptir sadece bir değişiklik yapılmadığı sürece kaydet butonu aktif değildir, soluk renkli gözükür. İlgili duygu hakkında girilen tüm bilgileri gözlemleme imkanı tanır. Eğer sembolde, hissedilen duyguda, kategoride veya açıklamada bir değişiklik yapılırsa ekran altındaki “kaydet” butonu renklenir, aktifleşir ve tıklanması halinde duygu sayfası o şekilde güncellenmiş olur.

Takvim: Takvim üzerinde seçtiğin bir günün girdileri liste halinde sunulur. Simge ve duygu yazılır üstünde tıklayınca o duygunun sayfasına gidilir ve açıklama da yazar. Anasayfada yer alır

Grafikler: Seçilen tarih aralığında duygu değişim grafikleri gösterilecek. Butonu ekranın sağ üstünde. Grafiklerin 1. Bölge x-y grafiği olacak; x ekseni: tarih, y ekseni: duygu kategorisi olacaktır. Grafik, çizgi grafiğidir. 

Girilen bilgiler belirli bir formatta uygulama içi depolanmalı.
