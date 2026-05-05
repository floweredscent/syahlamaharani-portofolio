# Execution — Syahla's Portfolio Website

## Step 1: Membuat Landing Page

### Prompt
Buatkan sebuah landing page untuk website portfolio berdasarkan hasil brainstorm dan details di atas

### RTCC-O Check
- R: ❌
- T: ✅
- C: ✅
- C: ❌
- O: ✅

### AI Response
![prompt1-1](..\assets\execution-prompt1-1.png)
![prompt1-2](..\assets\execution-prompt1-2.png)
![prompt1-3](..\assets\execution-prompt1-3.png)
![prompt1-4](..\assets\execution-prompt1-4.png)
![prompt1-5](..\assets\execution-prompt1-5.png)
![prompt1-6](..\assets\execution-prompt1-6.png)

Landing page portfolio telah berhasil dibuat berdasarkan hasil brainstorm dan details yang Anda berikan. Saya telah membuat file index.html dan styles.css dengan fitur-fitur berikut:

Fitur Utama:
Semantic HTML5: Menggunakan elemen seperti <header>, <nav>, <main>, <section>, <article>, dan <footer> untuk struktur yang benar.
Mobile-first Design: Layout responsif yang dimulai dari mobile, dengan grid dan flexbox untuk desktop.
Color Palette: Menggunakan kombinasi teal (#00BFA5) dan purple (#6A0DAD) sesuai Option C.
Typography: Plus Jakarta Sans untuk heading, Inter untuk body, dan JetBrains Mono untuk skills/code.
Single-page Layout: Navigasi smooth scroll ke setiap section.
Hero Animation: SVG animasi sederhana yang menunjukkan transformasi dari ECG waveform ke data bars.
Sections: Hero, About, Skills (dikelompokkan), Projects, Experience, Contact.
CTA Buttons: "View Projects" dan "Contact Me" yang jelas.
Server Lokal:
Saya telah menjalankan server HTTP lokal di port 8000. Anda dapat mengakses portfolio di: http://localhost:8000

Untuk melihat perubahan atau mengedit lebih lanjut, buka file di editor. Jika ada masalah atau perlu penyesuaian, beri tahu saya!

Grok Code Fast 1 • 1x

### Review
- [❌] Sesuai constraints? (tidak mobile-first)
- [✅] Format sesuai?
- [✅] Bisa dipahami?
- Changes: -

---

## Step 2: Memperbaiki Tampilan Mobile

### Prompt
Dalam mode mobile, tampilan navigasi website masih terlihat berantakan (navigasi terpotong dan tulisan terlalu rapat satu sama lain), tolong perbaiki agar tampilan website rapi saat dibuka dengan mode mobile. Sertakan keterangan bagian mana saja yang diubah.

### RTCC-O Check
- R: ❌
- T: ✅
- C: ✅
- C: ✅
- O: ✅

### AI Response
![prompt2-1](..\assets\execution-prompt2-1.png)
Memperbaiki tata letak navigasi mobile dengan menyesuaikan flex wrapping dan spacing pada CSS. Saya juga menambahkan aturan khusus untuk ukuran layar kecil agar header tidak menutupi konten.

Replacing 26 lines with 33 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css)

```

Replacing 10 lines with 30 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css)

Mengecek bagian akhir CSS agar perubahan mobile dapat disisipkan dengan tepat.

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css#150-150), lines 150 to 260

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css#260-260), lines 260 to 326

Perbaikan tambahan untuk tampilan mobile sudah siap: menambah aturan khusus kecil agar navigasi rapi dan konten tidak tersembunyi.

Replacing 10 lines with 29 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css)

Replacing 10 lines with 29 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css)

Replacing 9 lines with 28 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css)

```

Perbaikan Mobile Navigation

File yang diubah
- styles.css

Apa yang diperbaiki
- `nav` sekarang menggunakan `flex-wrap: wrap` agar daftar menu tidak terpotong pada layar kecil.
- `.nav-links` diubah menjadi:
  - `flex-wrap: wrap`
  - `justify-content: center`
  - `gap: 0.75rem`
  - `margin-top: 0.5rem`
- Link navigasi diberi padding tambahan agar teks tidak terlalu rapat dan lebih mudah disentuh.

Penyesuaian khusus mobile
Ditambahkan media query:
- `@media (max-width: 767px) { ... }`
  - `main` diberi `margin-top: 110px` untuk mengakomodasi header yang lebih tinggi.
  - `nav` dipusatkan ulang.
  - `.nav-links` diperlebar ke `width: 100%` dan jarak antar item dikurangi agar tetap rapih.
  - `.nav-links a` dibuat `white-space: nowrap` supaya teks menu tidak pecah menjadi dua baris tidak teratur.

Hasilnya: navigasi mobile kini rapi, tidak terpotong, dan jarak antar menu lebih nyaman.


### Review
- [✅] Sesuai constraints?
- [✅] Format sesuai?
- [✅] Bisa dipahami?
- Changes: Tampilan navigasi website yang sebelumnya masih mengikuti default desktop (meskipun dibuka dalam mode mobile), kini sudah rapi.


---

## Step 3: [Nama]

[Same format...]

---

## Step 4: [Nama]

[Same format...]