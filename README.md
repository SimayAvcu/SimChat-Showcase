# SimChat-Showcase
Web tabanlı Duygu Analizi ve Metin Özetleme sistemi olan SimChat'in vitrin ve tanıtım sayfasıdır. Projenin ana özelliklerini ve görsel çıktılarını sergiler.

# SimChat – Web Tabanlı Duygu Analizi ve Metin Özetleme Platformu

> **⚠️ Önemli Not:** Bu projenin kaynak kodları, fikri mülkiyet ve ticari potansiyeli nedeniyle özel (private) bir GitHub deposunda tutulmaktadır. Bu sayfa sadece projenin görsel ve fonksiyonel yeteneklerini sergilemek amacıyla oluşturulmuştur.

---

## Proje Hakkında

SimChat, kullanıcılar arası sosyal etkileşimi yönetirken, aynı zamanda NLP (Doğal Dil İşleme) modelleri aracılığıyla anlık duygu analizi ve metin özetleme yetenekleri sunan web tabanlı bir platformdur.

---

## 1. Ana Sayfa ve Kullanıcı Arayüzü (Frontend)

**Açıklama:**
SimChat'in **Ön Yüz (Frontend)** katmanı **HTML, CSS ve JavaScript** teknolojileri kullanılarak geliştirilmiştir. Arayüz; **kullanıcı dostu, sade ve sezgisel** bir deneyim sunacak şekilde tasarlanmıştır. Kullanıcılar uygulama ile temel olarak iki ana web arayüzü üzerinden etkileşim kurar: **Mesaj Giriş Sayfası** ve **Mesaj Görüntüleme & Analiz Sayfası.**


---
### Ana Sayfa Görünümü

#### Görsel 1: Üst Bölüm (Başlık ve Menü)
<img src="homepage_ust.png" alt="SimChat Ana Sayfa Üst Bölüm">

#### Görsel 2: Alt Bölüm (Ana Özellikler)
<img src="homepage_alt.png" alt="SimChat Ana Sayfa Alt Bölüm">


---

---

## 2. Duygu Analizi ve Uygulama Akışı

### 2.1. Genel Uygulama Akışı (General Application Flow)

SimChat kullanıcıları, sisteme İngilizce mesajlarını yükleyerek iki temel hizmetten yararlanabilirler:

* **Duygu Analizi (Emotion Analysis):** Kullanıcının mesajında bulunan duyguyu (emotion) tespit eder.
* **Metin Özetleme (Text Summarization):** Yüklenen uzun metinleri kısaltır.

Bu bölümde, Duygu Analizi modülünün çalışma akışı üç aşamalı görsel ile sunulmuştur:

---

### 2.2. Duygu Analizi Modülü Akışı

#### Görsel 1: Mesaj Girişi

Kullanıcı, arayüz üzerinden mesajını yazar ve gönderir.

<img src="message_input_interface.png" alt="Mesaj Giriş Ekranı" width="450px">

#### Görsel 2: Mesajın Sisteme Kaydedilmesi

Gönderilen mesaj, bir sonraki analiz ve görüntüleme aşaması için sisteme kaydedilir.

<img src="message_display_interface.png" alt="Mesaj Görüntüleme Ekranı" width="600px">

#### Görsel 3: Anlık Duygu Analizi Sonucu

Kayıt edilen mesaj, arka planda NLP modeline iletilir ve mesajın baskın duygusu anlık olarak etiketlenir ve görüntülenir.

<img src="sentiment_analysis_result.png" alt="Duygu Analizi Ekranı" width="800px">

---

## 3. Metin Özetleme Modülü (Text Summarization)

### 3.1. Genel Akış ve Özellik

Bu modül, kullanıcıların yüklediği uzun metinlerin ana fikrini kaybetmeden hızlı ve verimli bir şekilde özetlenmesini sağlar. Bu özellik, kullanıcıların yoğun mesaj trafiğini veya uzun haber metinlerini kolayca sindirmesine yardımcı olur.

---


## 3. Metin Özetleme Modülü (Text Summarization)

### 3.1. Genel Akış ve Özellik

Bu modül, kullanıcıların yüklediği uzun metinlerin ana fikrini kaybetmeden hızlı ve verimli bir şekilde özetlenmesini sağlar. Bu özellik, kullanıcıların yoğun mesaj trafiğini veya uzun haber metinlerini kolayca sindirmesine yardımcı olur.

---

### 3.2. Metin Özetleme Modülü Akışı

#### Görsel 1: Metin Girişi

Kullanıcı, özetlenmesini istediği uzun metni ilgili alana yapıştırır.

<img src="message_input_interface.png" alt="Metin Özetleme Giriş Ekranı" width="600px">

#### Görsel 2: Metnin Sisteme Kaydedilmesi ve Görüntülenmesi

Gönderilen orijinal metin, sisteminize kaydedilir ve kullanıcının takip edebilmesi için görüntülenir.

<img src="message_display_interface.png" alt="Metin Görüntüleme Ekranı" width="600px">

#### Görsel 3: Özetleme Sonucu (Çıktı)

Sistem, orijinal metni arka plandaki **BART** modeline ileterek kısa, öz ve akıcı bir özet metin oluşturur ve kullanıcıya sunar.

<img src="text_summarization_module_output.png" alt="Metin Özetleme Sonucu" width="600px">

