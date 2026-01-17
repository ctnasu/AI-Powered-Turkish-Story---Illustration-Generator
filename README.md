# 🪄 Türkçe Masal & Sahne Görselleştirme Üretici (LLM + Diffusion) — Gradio Uygulaması

Bu proje, kullanıcının verdiği **tek bir Türkçe başlangıç cümlesinden** yola çıkarak:
- Anlamlı ve tutarlı bir **masal / hikâye üretir** (Büyük Dil Modeli – LLM ile),
- Hikâyeyi kullanıcı tarafından belirlenen sayıda **sahneye böler** (1–8 arası),
- Her sahne için **yapay zekâ ile görsel üretir** (Text-to-Image Diffusion modelleri),
- Tüm çıktıları **Gradio tabanlı etkileşimli bir web arayüzünde** sunar.

Bu yapı; dijital hikâye anlatımı, çocuk kitabı tasarımı, storyboard hazırlama, yaratıcı yazarlık ve yapay zekâ destekli içerik üretimi için uçtan uca bir örnek sistemdir.

---

## ✨ Uygulamanın Yaptıkları

1. Kullanıcıdan bir **hikâye başlangıç cümlesi** alır.
2. Groq üzerinden çalışan bir **LLM** ile tam bir hikâye üretir.
3. Hikâyeyi otomatik olarak **sahnelere ayırır**.
4. Her sahne için uygun bir **görsel açıklama (prompt)** oluşturur.
5. HuggingFace üzerinde çalışan **görsel üretim modeli** ile her sahnenin resmini üretir.
6. Sonuçları:
   - Biçimlendirilmiş **hikâye metni**,
   - **Sahne listesi**,
   - **Görsel galeri**
   olarak kullanıcıya gösterir.

---

## 🚀 Özellikler

- Türkçe hikâye üretimi (Groq LLM)
- Sahne sayısını kullanıcı belirler (1–8)
- Her sahne için otomatik AI görsel üretimi
- Gradio tabanlı modern web arayüzü
- HTML formatlı hikâye çıktısı
- Galeri şeklinde sahne görselleri
- Çocuk kitabı, çizgi roman ve storyboard üretimine uygun yapı
---

## 🧠 Sistem Akışı
Kullanıcı Cümlesi
↓
LLM ile Hikâye Üretimi (Groq)
↓
Sahnelere Bölme
↓
Her Sahne İçin Görsel Prompt
↓
Diffusion Model ile Görsel Üretimi (HuggingFace)
↓
Gradio Arayüzünde Metin + Görsel Sunumu

## Örnek Çıktılar


[Türkçe Masal Kitabı3.pdf](https://github.com/user-attachments/files/24691828/Turkce.Masal.Kitabi3.pdf)



[Türkçe Masal Kitabı.pdf](https://github.com/user-attachments/files/24691842/Turkce.Masal.Kitabi.pdf)
