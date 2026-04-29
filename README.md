<div align="center">

# 🔐 Veri Güvenliği

### *Klinik araştırma verisinde kimliksizleştirme ve güvenlik rehberi*

[![Site](https://img.shields.io/badge/Site-drmuammer.github.io%2Fveri--seti--guvenligi-14B8A6?style=for-the-badge)](https://drmuammer.github.io/veri-seti-guvenligi/)
[![License](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
![Status](https://img.shields.io/badge/Status-Aktif-success?style=flat-square)
![Lang](https://img.shields.io/badge/Dil-Türkçe-red?style=flat-square)

</div>

---

## Bu Rehber Ne İşe Yarar?

Gerçek hasta verisi ile çalışan klinik araştırmacılar için **kimliksizleştirme ve veri güvenliği** rehberi. Akademik standartlara dayalı, kaynakçalı, uygulamalı.

İçerik:

1. **Kimliksizleştirme** — HIPAA, GDPR, KVKK çerçevesinde anonimleştirme; anahtar dosya / çalışma dosyası mimarisi; Excel ve R uygulamaları; SHA-256 + salt hashleme; BitLocker / 7-Zip / VeraCrypt şifreleme

> 🚧 Yeni bölümler eklenmeye devam edecek.

## 🌐 Online Olarak Okuma

Rehberin online sürümü: **<https://drmuammer.github.io/veri-seti-guvenligi/>**

## 💻 Yerel Olarak Çalıştırma

### Önkoşul

[Quarto](https://quarto.org/docs/get-started/) kurulu olmalı.

### Adımlar

```bash
git clone https://github.com/drmuammer/veri-seti-guvenligi.git
cd veri-seti-guvenligi
quarto preview    # canlı önizleme (localhost:4848 açar)
quarto render     # statik HTML üretir → _site/ klasörüne
```

## 📂 Klasör Yapısı

```
veri-seti-guvenligi/
├── _quarto.yml                  ← Site yapılandırma
├── index.qmd                    ← Ana sayfa
├── styles.css                   ← Tema CSS
├── references.bib               ← BibTeX kaynakça (17 akademik kaynak)
├── rehber/
│   └── 01-kimliksizlestirme.qmd
├── ornek-veri/
│   └── ornek-tanimlayici-veri.csv
└── .github/workflows/
    └── publish.yml              ← Otomatik GitHub Pages deploy
```

## 🎓 Akademik Kaynaklar

Rehber, alanın **17 öncü akademik kaynağına** atıf yapar:

- Sweeney L. — k-anonymity (1998, 2002)
- El Emam K. et al. — Yeniden tanımlama saldırı meta-analizi (2011)
- Narayanan A. & Shmatikov V. — Netflix Prize de-anonymization (2008)
- HIPAA Safe Harbor (45 CFR §164.514)
- GDPR (Regulation EU 2016/679)
- KVKK 6698 sayılı Kanun
- ISO/IEC 20889:2018
- NIST SP 800-188

## 🤝 Katkı

Hata, eksik ya da öneriniz varsa [Issue](https://github.com/drmuammer/veri-seti-guvenligi/issues) açın veya [Pull Request](https://github.com/drmuammer/veri-seti-guvenligi/pulls) gönderin.

## 📜 Lisans

Tüm içerik [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) altında paylaşılmaktadır.

**Önerilen atıf:**

> Beslen, M. (2026). *Veri Güvenliği: Klinik araştırma verisinde kimliksizleştirme ve güvenlik rehberi*. https://drmuammer.github.io/veri-seti-guvenligi/

## 📫 İletişim

🌐 [muammerbeslen.com](https://muammerbeslen.com)  
🧹 [Veri Temizliği Rehberi](https://drmuammer.github.io/veri-temizligi/)  
📚 [Diğer notlar](https://github.com/drmuammer/notes)

---

<div align="center">

*"Veri olmadan sen sadece görüşünü olan başka bir insansın — ama veri başkalarının emanetiyse, onu korumak da senin görevindir."*

</div>
