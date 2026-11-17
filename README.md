# MCBÜ Büyük Veri Analistliği | Ekipçe Ders Çalışma Oyunu

Bu proje, Manisa Celal Bayar Üniversitesi Büyük Veri Analistliği programındaki 1. sınıf öğrencileri için ders çalışmayı daha eğlenceli hâle getirmek amacıyla hazırlanmış HTML tabanlı bir bilgi yarışmasıdır. Öğrenciler test sorularını tek başına çözebilir veya ekip arkadaşlarıyla aynı oyun odasında yarışabilir.

## Projenin amacı

Ders konularını soru çözerek tekrar etmeyi, arkadaşlarla ekip hâlinde çalışmayı ve öğrenme sürecini oyunlaştırmayı destekler. Oyun, sınıf içi veya bireysel çalışma oturumlarında kullanılabilir.

## Öne çıkan özellikler

- 200 soruluk üretken yapay zekâ konu havuzu
- Tek kişilik çalışma ve canlı grup oyunu
- Oda kurma ve oda koduyla arkadaşların katılması
- Rastgele soru sıralaması ve tur uzunluğu seçimi
- Süreli sorular, puan ve doğru cevap serisi takibi
- Cevap sonrası doğru seçenek ve açıklama
- Tur sonu sonuçlar ve puan tablosu
- Hareketli, oyun temalı arayüz ve son saniye geri sayımı
- Telefon ve masaüstü ekranlarına uyum

## Başlatma

`index.html` dosyasını güncel bir tarayıcıda açın. Tek kişilik oyun tarayıcıda çalışır. Grup oyunu için internet bağlantısı gerekir. Oda kurucusu bir oda oluşturup kodu paylaşır; diğer oyuncular **Koda Katıl** seçeneğinden aynı kodla odaya girer.

## Teknik yapı

Proje tek bir HTML dosyası içinde HTML, CSS ve JavaScript ile hazırlanmıştır. Tailwind CSS, MQTT istemcisi ve yazı tipleri CDN üzerinden yüklenir. Çok oyunculu iletişim MQTT protokolünü WebSocket bağlantısı üzerinden kullanır.

## İçeriği değiştirme

Soru metinleri ve cevaplar `index.html` içindeki JavaScript soru havuzunda bulunur. Görünüm ve animasyonlar aynı dosyanın `<style>` bölümünde, oyun akışı ise JavaScript kodundadır.

## Not

Bu çalışma, öğrencilerin ders tekrarını desteklemek için hazırlanmış bir eğitim projesidir. İçerikteki cevapları ders materyalleriyle karşılaştırarak kullanın.
