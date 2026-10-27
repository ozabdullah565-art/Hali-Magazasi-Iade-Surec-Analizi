# 🧶 Halı Mağazası İade ve Değişim Süreç Analizi & Python Otomasyonu

Bu proje, halı perakendeciliğinde karşılaşılan özel ölçü (kesme halı) ve standart ölçü iade/değişim süreçlerindeki karmaşıklığı çözmek, mağaza müdürünün üzerindeki operasyonel yükü hafifletmek ve şirket finansal güvenliği ile müşteri memnuniyetini dengelemek amacıyla geliştirilmiş bir **YBS (Yönetim Bilişim Sistemleri) İş Analizi ve Otomasyon** çalışmasıdır.

---

## 🎯 Projenin Amacı ve İş Değeri
* **Operasyonel Verimlilik:** Rutin iade ve değişim kararlarının müdüre gerek kalmadan personel (kasiyer/satış elemanı) seviyesinde standart kurallarla çözülmesi.
* **Finansal Koruma:** Fabrika tarafından geri alınmayan özel ölçü (kesme/overloklu) halılarda mağazanın doğrudan zarar etmesinin önüne geçilmesi.
* **Yasal Yönlendirme & Müşteri İlişkileri:** Özel ölçü iade taleplerinde müşteriyi mağdur etmeden, Tüketici Hakem Heyeti (THH) mekanizması üzerinden fabrikanın ürünü geri almasını sağlayacak nazik bilgilendirme protokolü.

---

## 📊 BPMN Süreç Haritası (Draw.io)

Aşağıdaki süreç haritası, mağazaya gelen bir müşteri iadesinin adım adım karar ağacını ve yetki matrisini göstermektedir:

![BPMN Akış Şeması](iade_sureci_bpmn.png)

---

## 💻 Python İade Otomasyonu Kodu

Süreç haritasındaki karar düğümleri iç içe koşullu yapılar (`Nested If-Else`) kullanılarak Python ortamında simüle edilmiştir.

```python
# Koda ulaşmak için depodaki iade_otomasyonu.ipynb dosyasını inceleyebilirsiniz.
