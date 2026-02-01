<a href="https://github.com/drshahizan/short-course/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/short-course" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/short-course/network/members"><img src="https://img.shields.io/github/forks/drshahizan/short-course" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/short-course/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/short-course" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/short-course"><img src="https://img.shields.io/github/issues/drshahizan/short-course" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/short-course/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/short-course?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2Fshort-course&labelColor=%23d9e3f0&countColor=%23697689&style=flat)


# AI untuk Penyediaan Slaid & Bahan Multimedia


# A. Cara Kerja Langkah Demi Langkah

## Langkah 1 — Tetapkan “spesifikasi slaid” (1 minit)

Sebelum guna AI, cikgu tentukan parameter ini (boleh copy template di bawah):

**Template spesifikasi (isi sahaja):**

* Subjek: Sains Tahun 6
* Topik: Daya
* Tempoh: 30–40 minit
* Bilangan slaid: 10–12
* Tahap murid: Tahun 6 (12 tahun)
* Gaya bahasa: ringkas, jelas, mesra murid
* Penekanan: contoh harian, aktiviti ringkas, keselamatan



## Langkah 2 — Guna AI untuk bina “Rangka Slaid” (Outline) (3–5 minit)

Tujuan: AI bina struktur yang betul dahulu (tajuk slaid + poin penting + aktiviti).

**Prompt asas (untuk semua platform):**

```
Anda ialah guru Sains Tahun 6.

Bina rangka slaid (10–12 slaid) untuk topik “Daya”.
Keperluan:
- Nyatakan tajuk setiap slaid
- Berikan 3–5 isi penting setiap slaid dalam Bahasa Melayu mudah
- Masukkan 2 aktiviti kelas ringkas (hands-on) dan 1 soalan KBAT
- Masukkan 1 slaid kuiz (5 soalan objektif + jawapan)
- Pastikan susunan logik: pengenalan → konsep → contoh → aplikasi → latihan → rumusan

Output dalam format:
Slaid 1: Tajuk
- Isi
- Nota guru (1–2 ayat)
- Cadangan visual (ikon/gambar yang sesuai)
```



## Langkah 3 — Automasi kandungan (10 minit)

Daripada outline, minta AI hasilkan:

1. **Nota guru** (skrip ringkas)
2. **Aktiviti PdP** (bahan & langkah)
3. **Penilaian** (kuiz + rubrik ringkas)
4. **Bahan multimedia** (idea infografik, animasi ringkas, demonstrasi)

**Prompt automasi kandungan:**

```
Berdasarkan rangka slaid yang anda hasilkan tadi, lengkapkan setiap slaid dengan:
1) Nota guru 2–3 ayat (apa yang cikgu sebut)
2) Contoh situasi harian yang dekat dengan murid
3) 1 soalan semak pemahaman (cek cepat) untuk setiap 2 slaid
4) Aktiviti murid: arahan langkah demi langkah (mudah dibuat dalam kelas)

Pastikan Bahasa Melayu baku dan sesuai untuk murid Tahun 6.
```



## Langkah 4 — Penyeragaman grafik (Standard Grafik) (3–5 minit)

Cikgu perlu “design rules” supaya **semua slaid nampak seragam**.

**Prompt penyeragaman grafik (boleh guna di ChatGPT/Gemini):**

```
Cipta panduan penyeragaman grafik untuk slaid Sains Tahun 6 topik “Daya”.

Sertakan:
- Tema warna (3 warna utama + 1 warna aksen)
- Jenis fon (tajuk + isi)
- Gaya ikon (flat/outline) dan penggunaan ikon konsisten
- Layout standard: (tajuk di atas, isi kiri, visual kanan)
- Gaya ilustrasi yang sesuai untuk murid
- Peraturan ringkas: maksimum 5 poin setiap slaid, 1 visual utama setiap slaid

Output sebagai “Slide Style Guide” yang ringkas dan jelas.
```

> Nota praktikal: Walaupun platform berbeza, “style guide” ini memastikan output konsisten bila cikgu jana di ChatGPT, Gemini atau NotebookLM.



## Langkah 5 — Format “untuk AI slide generator”

Sesetengah alat “slide generator” lebih mudah jika kita beri format khusus (contoh: markdown berstruktur).

**Prompt format akhir (seragam):**

```
Tukar kandungan slaid kepada format markdown yang sesuai untuk dijadikan slaid.

Keperluan:
- Gunakan tajuk besar untuk setiap slaid (## Slaid X: ...)
- Isi dalam bullet
- Nota guru dalam blok “Nota Guru:”
- Visual dalam baris “Visual: ...”
- Aktiviti dalam “Aktiviti: ...”
- Kuiz dalam “Kuiz:” dan sertakan jawapan

Pastikan ringkas dan kemas.
```



# B. 3 Latihan Hands-on (Untuk Peserta Bengkel)

## ✅ Latihan 1 — “Jana set slaid lengkap (10–12 slaid)”

**Output yang dikehendaki:** set slaid berstruktur + nota guru + visual cadangan

**Prompt (terus guna):**

```
Anda ialah guru Sains Tahun 6.

Hasilkan set slaid lengkap (10–12 slaid) bertajuk “Daya”.
Mesti ada:
- Definisi daya
- Jenis daya (tolak, tarik, geseran, graviti)
- Kesan daya (ubah arah, laju, bentuk)
- Contoh harian murid (basikal, bola, pintu, pemadam, magnet)
- 2 aktiviti mudah (bahan kelas biasa)
- 1 slaid kuiz (5 soalan + jawapan)
- 1 slaid rumusan + kerja rumah ringkas

Format output:
## Slaid 1: ...
- ...
Nota Guru: ...
Visual: ...
```

**Cara semak (checklist cepat):**

* Ada aktiviti? Ada kuiz? Ada rumusan? Bahasa mudah? Susunan logik?



## ✅ Latihan 2 — “Automasi kandungan multimedia & variasi”

**Output yang dikehendaki:** bahan tambahan automatik (infografik, skrip video pendek, lembaran aktiviti)

**Prompt:**

```
Berdasarkan slaid topik “Daya” yang anda hasilkan,
jana bahan multimedia sokongan berikut:

1) Skrip video 60 saat (Bahasa Melayu mudah) menerangkan konsep daya
2) Cadangan infografik 1 halaman (tajuk + bahagian + poin ringkas)
3) Lembaran aktiviti murid (1 muka surat):
   - 5 soalan isi tempat kosong
   - 3 soalan aplikasi harian
   - 1 soalan KBAT
4) Senarai semak (checklist) keselamatan untuk aktiviti kelas berkaitan daya

Pastikan semua bahan selaras dengan Tahun 6 dan topik Daya.
```



## ✅ Latihan 3 — “Penyeragaman grafik + versi untuk 3 platform”

**Output yang dikehendaki:** style guide + arahan eksport/format + 3 prompt khusus (ChatGPT, Gemini, NotebookLM)

### (A) Prompt Style Guide

```
Bina “Slide Style Guide” untuk Sains Tahun 6 topik Daya supaya semua slaid konsisten.

Sertakan:
- Skema warna
- Fon
- Layout standard
- Gaya ikon/ilustrasi
- Gaya jadual/diagram
- Contoh 1 slaid (tajuk + isi + visual) ikut guide ini
```

### (B) Prompt “Versi ChatGPT” (jana slaid terus dalam chat)

```
Gunakan Slide Style Guide yang anda cipta tadi.

Jana semula slaid topik Daya (10–12 slaid) dalam format markdown,
dan pastikan setiap slaid mematuhi style guide (layout, bilangan bullet, visual).
```

### (C) Prompt “Versi Gemini” (gaya lebih visual & ringkas)

```
Anda ialah pereka slaid pendidikan.

Hasilkan slaid Sains Tahun 6 topik Daya (10–12 slaid) yang sangat visual.
Keperluan:
- Setiap slaid maksimum 4 bullet
- 1 visual/diagram cadangan per slaid
- Ikut style guide: warna, fon, layout

Output dalam format markdown slaid.
```

### (D) Prompt “Versi NotebookLM” (guna bahan sumber)

*(NotebookLM biasanya paling kuat bila cikgu beri sumber: nota buku teks, modul, atau artikel ringkas. Jika ada teks rujukan, masukkan dahulu.)*

```
Berdasarkan sumber rujukan yang saya muat naik tentang topik Daya (Tahun 6),
hasilkan:
1) Rangka slaid 10–12 slaid
2) Nota guru bagi setiap slaid (2–3 ayat)
3) Kuiz 5 soalan + jawapan
4) Aktiviti hands-on 2 set dengan langkah dan bahan

Pastikan Bahasa Melayu baku dan sesuai untuk murid Tahun 6.
```



# C. Tip Penting untuk Pastikan “Hasil Akhir Betul-betul Seragam”

1. **Gunakan satu “Slide Style Guide” yang sama** untuk semua platform
2. **Hadkan panjang**: maksimum 4–5 bullet/slide
3. **Ulang arahan format** (“markdown slaid” + Nota Guru + Visual) setiap kali jana
4. Buat **pusingan semakan**: minta AI semak sendiri keseragaman

**Prompt semakan automatik:**

```
Semak semua slaid ini dan pastikan:
- Format konsisten
- Bilangan bullet seimbang
- Bahasa sesuai untuk Tahun 6
- Visual dicadangkan untuk setiap slaid
Senaraikan 5 pembetulan paling penting dan baiki slaid berkaitan.
```



### 🙌🏻 Connect with Me
<p align="left">
    <a href="https://github.com/drshahizan" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/-@drshahizan-181717?style=flat-square&logo=GitHub&logoColor=white"></a>
    <a href="https://www.linkedin.com/in/drshahizan" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/-drshahizan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/drshahizan/"></a>
    <a href="mailto:shahizan@utm.my" target="_blank"><img alt="Email" src="https://img.shields.io/badge/-shahizan@utm.my-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:shahizan@utm.my.com"></a>
    <a href="https://www.researchgate.net/profile/Mohd-Othman-28" target="_blank"><img alt="ResearchGate" src="https://img.shields.io/badge/-ResearchGate-00CCBB?style=flat-square&logo=ResearchGate&logoColor=white"></a>
    <a href="https://orcid.org/0000-0003-4261-1873" target="_blank"><img alt="ORCID" src="https://img.shields.io/badge/-ORCID-A6CE39?style=flat-square&logo=ORCID&logoColor=white"></a> 
 <a href="https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan" target="_blank"><img alt="A" src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic"></a>
 
![](https://hit.yhype.me/github/profile?user_id=81284918)
</p>

