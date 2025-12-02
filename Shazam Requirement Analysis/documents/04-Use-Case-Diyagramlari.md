# **Use Case Diyagramları ve Formları**

## **Use Case Diyagramı**
![Use Case Diagramı](https://raw.githubusercontent.com/selmaadiyaman/Shazam-Requirement-Analysis/main/Shazam%20Requirement%20Analysis/diagrams/usecase.jpg)

---

## **Ad:** Uygulamayı Aç  
**Katılımcı Aktörler:** Kullanıcılar  
**Hedef:** Uygulamaya giriş yapmak  
**Tetikleyiciler:** Kullanıcının uygulamayı açma isteği  
**Ön Koşullar:** Uygulamanın indirilmiş olması, giriş izinlerinin verilmiş olması  
**Son Koşullar:** Kullanıcının uygulamayı açmış olması  
**Temel Akış:** Uygulamayı indirme, uygulamayı açma  
**Alternatif Akış:** Başka bir cihazdan uygulamayı kullanma  
**İstisnalar:** Giriş izinlerinin verilmemesi  
**Nitelikler:** Kolay arayüz, kullanım talimatı, hızlı açılma  

---

## **Ad:** Şarkıyı Tanıt  
**Katılımcı Aktörler:** Kullanıcılar  
**Hedef:** Uygulamanın şarkıyı tanıması  
**Tetikleyiciler:** Şarkıyı bulma isteği  
**Ön Koşullar:** Mikrofon izni, şarkının çalıyor olması  
**Son Koşullar:** Uygulamanın şarkıyı bulması  
**Temel Akış:** Şarkının çalması → mikrofonun açılması → şarkının bulunması  
**Alternatif Akış:** Kullanıcının şarkıyı mırıldanması  
**İstisnalar:** Mikrofon izninin verilmemiş olması  
**Nitelikler:** Şarkının 20 saniye içinde bulunması  

---

## **Ad:** Sonuç Görüntüleme  
**Katılımcı Aktörler:** Kullanıcılar  
**Hedef:** Çalan şarkıyı görüntülemek  
**Tetikleyiciler:** Şarkının adını öğrenme isteği  
**Ön Koşullar:** Şarkının uygulama tarafından bulunmuş olması  
**Son Koşullar:** Şarkı bilgilerinin görüntülenmesi  
**Temel Akış:** Sonuç ekranının gösterilmesi  
**Alternatif Akış:** Şarkının bulunamaması → yeniden tanıtma  
**İstisnalar:** Bilgilerin görüntülenememesi  
**Nitelikler:** Şarkı sözleri, sanatçı konserleri, popüler şarkılar, platform listesi  

---

## **Ad:** Şarkıyı Dinleme  
**Katılımcı Aktörler:** Kullanıcılar  
**Hedef:** Tanımlanan şarkıyı dinlemek  
**Tetikleyiciler:** Dinleme isteği  
**Ön Koşullar:** Dinleme platformlarının sunulması  
**Son Koşullar:** Şarkının dinlenmesi  
**Temel Akış:** Platform seçimi → şarkının dinlenmesi  
**Alternatif Akış:** Shazam üzerinden 1:30’luk kesiti dinleme  
**İstisnalar:** Kullanıcının vazgeçmesi  
**Nitelikler:** Ses düzeyi ayarlama, eş zamanlı şarkı sözleri  

---

## **Ad:** Kütüphane Görüntüleme  
**Katılımcı Aktörler:** Kullanıcılar  
**Hedef:** Önceden aratılan şarkıları görmek  
**Tetikleyiciler:** Eski şarkıları bulma isteği  
**Ön Koşullar:** Şarkıların daha önce aranmış olması  
**Son Koşullar:** Şarkıların listelenmesi  
**Temel Akış:** Kütüphanenin görüntülenmesi  
**Alternatif Akış:** Shazam tarafından oluşturulan çalma listeleri  
**İstisnalar:** Şarkının algılanmaması  
**Nitelikler:** Tarihe göre sıralama, kütüphaneden kaldırma, paylaşma  

---

## **Ad:** Platforma Şarkıyı Tanımlama  
**Katılımcı Aktörler:** Sanatçılar  
**Hedef:** Şarkıyı Shazam’a yüklemek  
**Tetikleyiciler:** Şarkının tanıtılması isteği  
**Ön Koşullar:** Net ve kaliteli bir kayıt  
**Son Koşullar:** Şarkının platforma tanımlanması  
**Temel Akış:** Kayıt → düzenleme → yükleme  
**Alternatif Akış:** Mevcut şarkıyı güncelleme  
**İstisnalar:** Sistem koşullarının sağlanmaması  
**Nitelikler:** Lisanslı şarkı olma  

---

## **Ad:** Alternatif Dinleme Platformu Sunma  
**Katılımcı Aktörler:** Platform sağlayıcı  
**Hedef:** Şarkının platform üzerinden dinlenmesi  
**Tetikleyiciler:** Kullanım sıklığını artırma isteği  
**Ön Koşullar:** Platform-sanatçı anlaşması  
**Son Koşullar:** Şarkının platformlarda sunulması  
**Temel Akış:** Anlaşma → yayınlama  
**Alternatif Akış:** Platform sunulmaması  
**İstisnalar:** Şarkının platformdan kaldırılması  
**Nitelikler:** Platform amblemlerinin görünmesi  

---

## **Ad:** Platforma Reklam Tanımlama  
**Katılımcı Aktörler:** Reklam verenler  
**Hedef:** Ürün veya hizmet satışını artırmak  
**Tetikleyiciler:** Marka bilinirliği isteği  
**Ön Koşullar:** Shazam ile reklam anlaşması  
**Son Koşullar:** Banner reklamı yayınlanması  
**Temel Akış:** Anlaşma → reklamın yayınlanması  
**Alternatif Akış:** Sponsor olunan etkinlik reklamlama  
**İstisnalar:** Anlaşmanın kabul edilmemesi  
**Nitelikler:** İlgi çekici tasarım, müzik endüstrisine uygunluk  

---
