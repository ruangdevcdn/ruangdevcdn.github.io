Berikut perbaikan yang lebih rapi dan konsisten untuk dokumentasi Anda:

---

# 📄 **Dokumentasi CDN Ruang Dev Indonesia**
## Proyek-Proyek oleh Ruang Dev Indonesia

### Pendahuluan
CDN (Content Delivery Network) adalah jaringan server yang tersebar secara geografis, yang bertujuan untuk menyampaikan konten kepada pengguna dengan lebih cepat dan efisien. Dengan memanfaatkan CDN, proyek-proyek yang dikembangkan oleh Ruang Dev Indonesia dapat memberikan akses yang lebih cepat dan mengurangi beban pada server utama.

### **Kapan Menggunakan CDN?**

Gunakan CDN untuk:
- Menyajikan file statis (CSS, JavaScript, gambar) dengan lebih cepat.
- Mengurangi beban pada server utama.
- Memastikan pengguna dari berbagai lokasi mendapatkan konten dengan waktu muat yang optimal.

---

### Manfaat Menggunakan CDN
- **Kecepatan:** Menyediakan konten lebih cepat dengan lokasi server yang lebih dekat dengan pengguna.
- **Keandalan:** Meningkatkan ketersediaan konten dan mengurangi risiko downtime.
- **Skalabilitas:** Mampu menangani lonjakan lalu lintas dengan lebih efisien.

---

### Panduan Integrasi CDN dalam Proyek
Untuk menggunakan file JavaScript dan CSS dari Ruang Dev CDN, tambahkan kode berikut ke dalam tag `<head>` pada halaman web Anda.

#### Inputmask
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn/js/inputmask/jquery.inputmask.min.js" integrity="sha512-jTgBq4+dMYh73dquskmUFEgMY5mptcbqSw2rmhOZZSJjZbD2wMt0H5nhqWtleVkyBEjmzid5nyERPSNBafG4GQ==" crossorigin="anonymous"></script>
  ```

---

#### Select2
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn/css/select2/select2.min.css" integrity="sha512-aD9ophpFQ61nFZP6hXYu4Q/b/USW7rpLCQLX6Bi0WJHXNO7Js/fUENpBQf/+P4NtpzNX0jSgR5zVvPOJp+W2Kg==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn/js/select2/select2.min.js" integrity="sha512-4MvcHwcbqXKUHB6Lx3Zb5CEAVoE9u84qN+ZSMM6s7z8IeJriExrV3ND5zRze9mxNlABJ6k864P/Vl8m0Sd3DtQ==" crossorigin="anonymous"></script>
  ```

---

#### Sweetalert2
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn/css/sweetalert2/sweetalert2.min.css" integrity="sha512-Xxs33QtURTKyRJi+DQ7EKwWzxpDlLSqjC7VYwbdWW9zdhrewgsHoim8DclqjqMlsMeiqgAi51+zuamxdEP2v1Q==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn/js/sweetalert2/sweetalert2.js" integrity="sha512-tWKcNRzXNTybB8ca0NSEyHlUl1mXPL/2xFjiUkUBGmJTRnAstcmyXtmv81vEennKVkH/FDDIH5l2+Jo0p1FObg==" crossorigin="anonymous"></script>
  ```

---

Dengan menggunakan link CDN ini, proyek Anda akan memperoleh akses cepat ke file-file statis yang dibutuhkan tanpa harus bergantung sepenuhnya pada server utama Ruang Dev Indonesia.