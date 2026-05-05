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

## Step 3: Menyempurnakan Hero Animation

### Prompt
Hero animation pada website hanya berjalan satu kali. Buat agar animasi tersebut berjalan berulang (waveform-data bars-waveform-data bars dan seterusnya). Sertakan keterangan bagian mana saja yang diubah.

### RTCC-O Check
- R: ❌
- T: ✅
- C: ✅
- C: ✅
- O: ✅

### AI Response
![prompt3-1](..\assets\execution-prompt3-1.png)
Mengecek bagian animasi SVG dan stylesheet untuk memperbarui loop secara tepat.

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/index.html#1-1), lines 1 to 120

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css#70-70), lines 70 to 180

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/index.html#120-120), lines 120 to 170

Menyesuaikan animasi agar berganti secara terus-menerus, termasuk path dan bar.

Replacing 11 lines with 14 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css)

```

Replacing 17 lines with 17 lines in [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/index.html)

```

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css#90-90), lines 90 to 140

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css#140-140), lines 140 to 190

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/styles.css#190-190), lines 190 to 220

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/index.html#170-170), lines 170 to 170

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/index.html#170-170), lines 170 to 170

Searched for regex `window.addEventListener|transformToData|growBar` (`**/index.html`), 3 results

Read [](file:///d%3A/Kareerr%20Mini%20Bootcamp%20IT/syahlamaharani-portofolio/index.html#146-146), lines 146 to 170

Perubahan untuk animasi looping

File yang diubah
- styles.css
- index.html

Detail perubahan

1. styles.css
   - Diperbarui `@keyframes transformToData` supaya:
     - mulainya dari waveform
     - berubah ke garis datar
     - kembali lagi ke waveform
   - Diperbarui `@keyframes growBar` supaya:
     - bar muncul dengan `height` dan `opacity`
     - kemudian hilang kembali
     - sehingga siap diulang terus

2. index.html
   - Script animasi diubah dari sekali jalan (`forwards`) menjadi:
     - `transformToData 4s ease-in-out 0s infinite`
     - `growBar 3s ease-in-out ${delay}s infinite`
   - Setiap bar sekarang menggunakan delay bertahap agar animasi bergantian secara lebih natural.

Hasil

Animasi hero sekarang berulang terus: waveform → data bars → waveform → data bars → dan seterusnya.

Made changes.

### Review
- [✅] Sesuai constraints?
- [✅] Format sesuai?
- [✅] Bisa dipahami?
- Changes: Hero animation yang sebelumnya berjalan hanya satu kali kini berulang terus.


---

## Step 4: Membuat Scroll Navigasi Lebih Mulus

### Prompt
Buat agar saat website discroll menjadi mulus, terutama untuk ketika user menekan tombol navigasi (auto-scroll)

### RTCC-O Check
- R: ❌
- T: ✅
- C: ✅
- C: ❌
- O: ✅

### AI Response
Saya telah menambahkan JavaScript untuk membuat scroll navigasi lebih mulus dengan offset yang tepat untuk header fixed. Sekarang saat menekan tombol navigasi, scroll akan berjalan halus ke bagian yang tepat tanpa melompat, dan bagian atas section tidak akan tertutup oleh header.

Untuk melihat hasilnya, buka index.html di browser dan klik link navigasi seperti "About" atau "Contact". Jika masih ada masalah, beri tahu saya!

### Review
- [✅] Format sesuai?
- [✅] Bisa dipahami?
- Changes: Scroll navigasi yang sebelumnya kaku (seperti loncat-loncat) kini menjadi lebih mulus.