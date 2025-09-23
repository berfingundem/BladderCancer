# BladderCancer Classification with Vision Transformers

**BladderCancer**, mesane kanseri görüntü sınıflandırması üzerine yapılmış bir proje olup Vision Transformer tabanlı modellerin performans kıyaslamasını amaçlamaktadır: 
**ViT, DeiT, CaiT, Swin Transformer** ve **MedViT**.

---

## 🔍 İçindekiler

- [Amaç](#amaç)  
- [Modeller](#modeller)  
- [Veri Kümesi](#veri-kümesi)  
- [Kurulum & Çalıştırma](#kurulum--çalıştırma)  
- [Deneyler & Sonuçlar](#deneyler--sonuçlar)  
- [Lisans](#lisans)

---

## 🏁 Amaç

Bu proje ile aşağıdakiler hedeflenmiştir:

- Mesane kanseri görüntülerinde farklı Vision Transformer mimarilerinin sınıflandırma performanslarını kıyaslamak.  
- Hangi modelin hangi veri kombinasyonlarında daha başarılı olduğunu gözlemlemek.  
- Görüntü ön işlemeden sonuç değerlendirmeye kadar tam bir pipeline sunmak.

---

## ⚙️ Modeller

Projede kullanılan modeller:

| Model | Açıklama |
|---|---|
| ViT | Vision Transformer (temel transformer tabanlı algılayıcı) |
| DeiT | Data-efficient Image Transformer |
| CaiT | Class-Attention in Image Transformers |
| Swin Transformer | Shifted Window Transformer (yerel-alan odaklı pencere tabanlı yaklaşım) |
| MedViT | Tıbbi görüntüler için optimize edilmiş transformer varyantı |

---

## 🧰 Veri Kümesi

- Görüntü tipi: **(örn: histopatoloji / mikroskopik görüntüler / MR?)**  
- Eğitim / test bölünmesi: **(örn: %80 eğitim, %20 test)**  
- Ön işleme adımları: yeniden boyutlandırma, normalizasyon, augmentasyon vs.  
- Görüntü formatı, boyutu vs. teknik detaylar  

---

## 🚀 Kurulum & Çalıştırma

Aşağıdaki adımları takip ederek projeyi kendi bilgisayarında çalıştırabilirsin:
- Bu çalışma **Google Colab** üzerinde gerçekleştirilmiştir. 
- bladder_set link : https://drive.google.com/file/d/1F8EdWmNaLIEDvKF-XnGhcYV5YI0UTUBu/view?usp=drive_link
