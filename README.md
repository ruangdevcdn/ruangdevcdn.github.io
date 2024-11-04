
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
## 📄 **Daftar Isi**

- [Proyek-Proyek oleh Ruang Dev Indonesia](#proyek-proyek-oleh-ruang-dev-indonesia)
  - [Pendahuluan](#pendahuluan)
  - [Kapan Menggunakan CDN?](#kapan-menggunakan-cdn)
  - [Manfaat Menggunakan CDN](#manfaat-menggunakan-cdn)
  - [Panduan Integrasi CDN dalam Proyek](#panduan-integrasi-cdn-dalam-proyek)
    - [Inputmask](#inputmask)
    - [Select2](#select2)
    - [Sweetalert2](#sweetalert2)
    - [Fontawesome5](#fontawesome5)

---
### Panduan Integrasi CDN dalam Proyek
Untuk menggunakan file JavaScript dan CSS dari Ruang Dev CDN, tambahkan kode berikut ke dalam tag `<head>` pada halaman web Anda.

#### Inputmask
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/inputmask/jquery.inputmask.min.js" integrity="sha512-jTgBq4+dMYh73dquskmUFEgMY5mptcbqSw2rmhOZZSJjZbD2wMt0H5nhqWtleVkyBEjmzid5nyERPSNBafG4GQ==" crossorigin="anonymous"></script>
  ```

---

#### Select2
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/css/select2/select2-bootstrap-5-theme.min.css" integrity="sha512-z/90a5SWiu4MWVelb5+ny7sAayYUfMmdXKEAbpj27PfdkamNdyI3hcjxPxkOPbrXoKIm7r9V2mElt5f1OtVhqA==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/css/select2/select2.min.css" integrity="sha512-aD9ophpFQ61nFZP6hXYu4Q/b/USW7rpLCQLX6Bi0WJHXNO7Js/fUENpBQf/+P4NtpzNX0jSgR5zVvPOJp+W2Kg==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/select2/select2.min.js" integrity="sha512-4MvcHwcbqXKUHB6Lx3Zb5CEAVoE9u84qN+ZSMM6s7z8IeJriExrV3ND5zRze9mxNlABJ6k864P/Vl8m0Sd3DtQ==" crossorigin="anonymous"></script>
  ```

---

#### Sweetalert2
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/css/sweetalert2/sweetalert2.min.css" integrity="sha512-Xxs33QtURTKyRJi+DQ7EKwWzxpDlLSqjC7VYwbdWW9zdhrewgsHoim8DclqjqMlsMeiqgAi51+zuamxdEP2v1Q==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/sweetalert2/sweetalert2.js" integrity="sha512-tWKcNRzXNTybB8ca0NSEyHlUl1mXPL/2xFjiUkUBGmJTRnAstcmyXtmv81vEennKVkH/FDDIH5l2+Jo0p1FObg==" crossorigin="anonymous"></script>
  ```

---

#### Fontawesome5
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/css/fontawesome/font-awesome5-all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/fontawesome5/font-awesome5-all.min.js" integrity="sha512-Tn2m0TIpgVyTzzvmxLNuqbSJH3JP8jm+Cy3hvHrW7ndTDcJ1w5mBiksqDBb8GpE2ksktFvDB/ykZ0mDpsZj20w==" crossorigin="anonymous"></script>
  ```

---

Dengan menggunakan link CDN ini, proyek Anda akan memperoleh akses cepat ke file-file statis yang dibutuhkan tanpa harus bergantung sepenuhnya pada server utama Ruang Dev Indonesia.