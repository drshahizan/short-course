# Senarai Sistem Digital Digunakan oleh PBT Malaysia (Pentadbiran Harian)

| Bidang Operasi PBT                                               | Sistem / Aplikasi Digunakan                    | Fungsi Utama                                                                      | Taraf PBT Lazim Mengguna       | Contoh PBT                   |
| ---------------------------------------------------------------- | ---------------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------ | ---------------------------- |
| **Kutipan Cukai Taksiran (Cukai Pintu)**, sewaan, hasil pelbagai | **Sistem ePBT 2.0**                            | Pengurusan akaun pegangan, pengiraan cukai, bil, hasil, kompaun, laporan kewangan | Bandaraya, Perbandaran, Daerah | DBKL, MBPJ, MBJB, MPK, MPS   |
| Bayaran cukai taksiran, sewaan, kompaun secara digital           | **PBTPay / PBTPay Mobil**                      | Bayaran tanpa tunai, semakan bil, resit digital, notifikasi pembayaran            | Semua taraf (meluas)           | Hampir semua PBT Semenanjung |
| Akses awam perkhidmatan PBT (front-end)                          | **Portal ePBT Online**                         | Semakan cukai, bayaran, permohonan perkhidmatan PBT dalam satu gerbang            | Bandaraya, Perbandaran         | MBSA, MBPP, MBMB             |
| **Cukai iklan** & kawalan iklan luar                             | Modul Lesen Iklan (dalam ePBT / eLesen)        | Permohonan, pembaharuan, pemantauan lesen iklan                                   | Bandaraya, Perbandaran         | DBKL, MBPJ, MBSA             |
| **Penguatkuasaan undang-undang kecil** (kompaun, saman)          | Sistem Kompaun Berkomputer (modul dalaman PBT) | Rekod kesalahan, pengeluaran kompaun, integrasi bayaran                           | Semua taraf                    | MPK, MDK, MDB                |
| Penguatkuasaan pintar & pemantauan lesen                         | **myPATIL (IoT-based Licensing)**              | Lesen digital, pemantauan masa nyata, cegah pemalsuan lesen                       | Perbandaran, Daerah            | MPM Manjung, PBT Perak       |
| **Lesen Perniagaan** (premis, penjaja, sementara)                | **eLesen / Sistem Pelesenan PBT**              | Permohonan & pembaharuan lesen secara atas talian                                 | Semua taraf                    | DBKL, MBPJ, MBJB, MD         |
| Lesen perniagaan bersepadu (akses mudah alih)                    | **PBTPay Mobil – Modul eLesen**                | Semakan status lesen, bayaran, pembaharuan                                        | Semua taraf                    | PBT yang guna PBTPay         |
| **Perancangan Guna Tanah Setempat**                              | **OSC 3.0 Plus Online (KPKT)**                 | Kebenaran merancang, ulasan teknikal, kelulusan pelan                             | Semua PBT Semenanjung          | Semua PBT Semenanjung        |
| Kelulusan pelan bangunan & infrastruktur                         | OSC 3.0 Plus (modul dalaman)                   | Pelan bangunan, jalan, parit, landskap                                            | Bandaraya, Perbandaran         | MBPJ, MBPP, MBJB             |
| **Aduan awam** (sampah, longkang, bunyi, dll.)                   | Sistem e-Aduan PBT / Aplikasi PBT              | Terima & jejak aduan awam secara digital                                          | Semua taraf                    | iResponz MBPJ, Adu@MBMB      |
| GIS & pemetaan bandar                                            | **Sistem GIS PBT**                             | Pemetaan zon guna tanah, aset, utiliti, perancangan                               | Bandaraya, Perbandaran         | DBKL, MBSA, MBPP             |
| Pengurusan parkir bandar                                         | Sistem e-Parkir / Smart Parking                | Kutipan parkir tanpa tunai, sensor parkir                                         | Bandaraya, Perbandaran         | DBKL, MBPJ                   |
| Pemantauan bandar & keselamatan                                  | CCTV Bandar Pintar / Command Center            | Pemantauan trafik, keselamatan, insiden                                           | Bandaraya                      | DBKL, MBJB, MBPJ             |
| Pentadbiran dalaman (HR & kewangan)                              | HRMIS, SPEKS, ePerolehan                       | Gaji, perolehan, aset, sumber manusia                                             | Semua PBT                      | Semua PBT                    |

## Nota Analitik (untuk penulisan Blueprint)

**1. Corak penggunaan mengikut taraf PBT**

* **Majlis Bandaraya**: Sistem lebih kompleks & bersepadu (GIS, command center, IoT, AI awal).
* **Majlis Perbandaran**: Fokus pada e-perkhidmatan, pelesenan, hasil & OSC.
* **Majlis Daerah**: Sistem teras sahaja (hasil, lesen, aduan), kurang teknologi pintar.

**2. Tahap kematangan digital**

* Tinggi: Kutipan hasil & OSC (hampir seragam nasional)
* Sederhana: Lesen perniagaan & aduan awam
* Rendah / tidak sekata: AI, IoT, analitik masa nyata

**3. Isyarat penting untuk Blueprint 2026–2040**

* Keperluan **penyatuan sistem (single digital backbone PBT)**
* Peralihan daripada *transactional systems* → *predictive & intelligent systems*
* Standard nasional diperlukan supaya PBT Daerah tidak ketinggalan
