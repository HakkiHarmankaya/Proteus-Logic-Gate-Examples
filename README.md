# Proteus Logic Kapılar Basit Örnekler (Proteus #9)


🔗 [Web Siteme Bakmak İçin Tıkla](https://www.hakkiharmankaya.com/)  


---

## 🔎 Açıklama

Bir önceki yazımda mantık kapılarının temel prensiplerini ve nasıl çalıştıklarını detaylıca ele almıştım.  
Bu yazımda ise, **AND**, **OR**, **NOT**, **XOR** gibi temel mantık kapıları ile oluşturulabilecek birkaç **basit örnek devreyi** simülasyon ortamında nasıl kurabileceğinizi adım adım göstereceğim.

Bu örnekler, dijital elektronik mantığını kavramanızı kolaylaştıracak ve Proteus üzerinde mantık kapıları ile denemeler yapmanızı sağlayacaktır.

---

## 🧪 Temel Örnekler

### ✅ 1. AND Kapısı Örneği

- **Amaç:** İki anahtar açıkken LED’in yanması.
- **Bağlantı:**
  - Anahtar1 ve Anahtar2 → AND Gate girişlerine
  - AND Gate çıkışı → LED → GND
- **Gözlem:** Her iki giriş 1 olduğunda LED yanar.

---

### ✅ 2. OR Kapısı Örneği

- **Amaç:** Herhangi bir anahtar açık olduğunda LED’in yanması.
- **Bağlantı:**
  - Anahtar1 ve Anahtar2 → OR Gate girişlerine
  - OR Gate çıkışı → LED → GND
- **Gözlem:** Girişlerden biri 1 ise LED yanar.

---

### ✅ 3. NOT Kapısı Örneği

- **Amaç:** Giriş sinyalinin tersini çıkışta görmek.
- **Bağlantı:**
  - Switch → NOT Gate → LED → GND
- **Gözlem:** Switch kapalıysa (0), LED yanar; açık (1) ise LED sönük olur.

---

### ✅ 4. XOR Kapısı Örneği

- **Amaç:** Girişlerden yalnızca biri açık olduğunda LED’in yanması.
- **Bağlantı:**
  - Anahtar1 ve Anahtar2 → XOR Gate girişlerine
  - XOR Gate çıkışı → LED → GND
- **Gözlem:** Girişler farklıysa LED yanar; aynıysa LED sönük kalır.

---

## 🧰 Proteus’ta Devre Kurulumu

1. Yeni proje oluştur ve `P` tuşuna basarak gerekli bileşenleri ekle:
   - Mantık kapıları (AND, OR, NOT, XOR)
   - Switch (anahtar), LED, 5V güç kaynağı ve GND

2. Girişleri switch ile oluştur ve çıkışları LED ile bağla.

3. "Run" tuşuna basarak simülasyonu başlat ve farklı kombinasyonları test et.

---

Bu örnekler, dijital elektronik temellerini öğrenmek isteyen herkes için başlangıç seviyesinde öğretici devreler sunar. Daha fazla örnek ve proje detayları için GitHub sayfamı ziyaret edebilirsin.

