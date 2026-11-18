# Quiz Arena | Tek ve Çok Oyunculu Bilgi Yarışması

**Quiz Arena**, herkesin bilgisini test edebileceği, tek başına pratik yapabileceği veya arkadaşlarıyla aynı oyun odasında canlı olarak yarışabileceği HTML tabanlı bir bilgi yarışmasıdır.

Sitemize Linke Tıklayarak Ulaşabilirsiniz.
https://bahacec.github.io/Quiz-Arena/

## Projenin Amacı

Farklı alanlardaki bilgileri soru çözerek pekiştirmeyi, arkadaş gruplarıyla eğlenceli bir rekabet ortamı kurmayı ve öğrenme sürecini oyunlaştırmayı destekler. Bireysel pratiklerde, arkadaş buluşmalarında veya etkinliklerde kolayca kullanılabilir.

## Öne Çıkan Özellikler

* **Geniş kategori havuzu** (teknoloji, yapay zekâ, genel kültür, dil, bilim, matematik ve daha fazlası) ile birlikte **kendi sorularını ekleme** seçeneği
* **Tek kişilik oyun** ve **canlı grup oyunu** modları
* **4 haneli grup kodu** ile oda kurma ve arkadaşların hızlıca katılması
* **Rastgele soru sıralaması** ve özelleştirilebilir tur uzunluğu
* **Süreli sorular**, puan hesaplama ve doğru cevap serisi (kombo) takibi
* **Cevap sonrası** doğru seçenek ve açıklama gösterimi
* **Tur sonu podyum**, başarı unvanları ve detaylı puan tablosu
* **Hareketli, oyun temalı arayüz**, ses efektleri ve son saniye geri sayımı
* **Telefon ve masaüstü ekranlarına tam uyum**

## Başlatma

`index.html` dosyasını güncel bir tarayıcıda açmanız yeterlidir.

* **Tek Kişilik Mod:** Tamamen tarayıcı içinde, ek bir kurulum gerektirmeden çalışır.
* **Çok Oyunculu Mod:** Canlı oda bağlantısı için internet bağlantısı gerekir. Oda kurucusu bir oda oluşturup ekrandaki 4 haneli kodu paylaşır; diğer oyuncular **Koda Katıl** sekmesinden aynı kodla odaya giriş yapar.

## Teknik Yapı

Proje, kurulum gerektirmeyen tek bir `index.html` dosyası içinde **HTML, CSS ve JavaScript** ile hazırlanmıştır. Tailwind CSS, MQTT istemcisi ve yazı tipleri CDN üzerinden yüklenir. Çok oyunculu oda iletişimi, WebSocket bağlantısı üzerinden **MQTT** protokolünü kullanır.

## İçeriği Değiştirme

* **Soru havuzu:** Mevcut kategorilerdeki soru ve cevaplar `index.html` içindeki JavaScript soru havuzunda yer alır. Ayrıca oyun içindeki **Kendi sorularım** seçeneğiyle doğrudan arayüzden de soru ekleyebilirsiniz.
* **Tasarım ve animasyonlar:** Görünüm ayarları aynı dosyanın `<style>` bölümünde bulunur.
* **Oyun akışı:** Puanlama, süre ve oda mantığı dosya sonundaki `<script>` bölümündedir.

## Not

Bu uygulama genel kullanıma yönelik bir bilgi yarışması projesidir. Özel veya teknik konulardaki soruları kendi kaynaklarınızla karşılaştırarak kullanmanız önerilir.
