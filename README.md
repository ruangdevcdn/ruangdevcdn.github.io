
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
    - [Jquery Min](#jquery-min)
    - [Starterkit Auth](#starterkit-auth)
    - [Starterkit Dashboard](#starterkit-dashboard)
    - [Inputmask](#inputmask)
    - [Select2](#select2)
    - [Sweetalert2](#sweetalert2)
    - [Fontawesome5](#fontawesome5)
    - [Datatables](#datatables)
    - [Datepicker](#datepicker)
    - [Previewimage](#previewimage)

---
### Panduan Integrasi CDN dalam Proyek
Untuk menggunakan file JavaScript dan CSS dari Ruang Dev CDN, tambahkan kode berikut ke dalam tag `<head>` pada halaman web Anda.

#### Jquery Min
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/datatables/js/jquery.min.js" integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ==" crossorigin="anonymous"></script>
  ```

---

#### Starterkit Auth
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/boxicons.css" integrity="sha512-dMNYt8oyGcGMYootKGiAdkrDyYgyWNGgTRtU7nmwebJOek7suG5gt2HxxAAD72nEqVf8vPVsBfVUUPslRIna2A==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/core.css" integrity="sha512-pnYsRB7mKLuwgeRjM6d27ImCoFfcmO0VuXC9JW3gxWTwaYWy4uqYqEbqUZD5HFAaUks/qMMcDjNKLbGFU01X+g==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/demo.css" integrity="sha512-jR/omOlI/7L6vHxzVV9fJiHYheixqNwDxH777Qxq9fD34UC8yn21E5P0CrIeAjAxMPQ3jNFrr07GdKH8Keq8QA==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/page-login.css" integrity="sha512-h39A68ukqSYSQQmhjQrmSKNfWDirJOdTYGkR5UyxopJ7w7d4QZ9P8j5jfUAxClfWcpHs88cELWYWxOZrkTvrfQ==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/perfect-scrollbar.css" integrity="sha512-1f/eQrQ/g+/r86r3S0s///7uEUyKzP1vrwOJh1P+ncqZzEiYCVsedkr7Q2gFybD90NPG2Gvl7H1hvWMBsF6rAw==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/theme-default.css" integrity="sha512-B5NVktYE2EFdcAxg8H7jyIxKQMzNHk7BP0iUy86wPF3Tb/jw9C4iTEpdtGmj0lFxCAjs1+dDEM1pgdSE34beKw==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/css/page-auth.css" integrity="sha512-GHAL9AzkSO8iwPLfzO0xqGp/XCptlFXJbro6Zb0oZAoySOJzDlwntxraz3Xl3mcKcFFLVvjoXjEXFfPmP97N8w==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/bootstrap.js" integrity="sha512-58Skp5/Lc9Va7aGH+XP5R+Qm4Yt8qI7kURnSsf2fgSTKhonm30qBb4VkZgfxuE2YVgtOK/16b+hLiGbG8/UWlQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/captcha.js" integrity="sha512-MvssGXK93T69xsmRFlw+Zrq2f5sbV+3u19+JWWMlUh8r4qTgCw7n/IeU6VxWf93P9cyNJJ9CgRPMJlIkSt3odQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/config.js" integrity="sha512-8V7NXvBBbl1Ry3wSibDR65p/HfaHuu1ZsQ+9Z6fl1UshAdo65dFIPJakOWYA7NCExLA1PluSvi5oEmNE/AyA+A==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/jquery.js" integrity="sha512-89uTEAAU9s+AG9aSjIDwlNDbSSymNSmsaO8bm08gZjZgo/Kq9HjsvGZGICnjNGooW2/9RVfd2Tvn59L3A9vhOw==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/main.js" integrity="sha512-U98ojlsH4ICl8hdwi/F7XsTW0ugRMZNCGkyI+h9rYCbq2Dt9jDESjVhMWbKspcB8GIzF2zcSxSDu2t7rsff0Dw==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/menu.js" integrity="sha512-0p64shxcXiIUhcuutdNTXzGl3f2tfW/Hh5GzKdXvNa+ld4GKf/YcAaSw3SpiCdpRYwMYt+9Mra7CWHK22jPSkg==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/password.js" integrity="sha512-G7zXQdyJ2a3/xfUAc2hDs4Bu6jJwX3HKe5/+RUO72tQaTA6DNYRMxeAHjh9u8V1Ht69H2LkuD0j6lyR+I+vYyQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/perfect-scrollbar.js" integrity="sha512-1G7EgZJK+gzxZghsEH/0MhkzHjbivPQWQjlNlQr6yg3MHruSAv3NUqgq08iXvMUTUaIqjsmeXNWXoM9qOYcICQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/popper.js" integrity="sha512-YlaDiPEzSotPTerG8gJwnEkN44q4y2YgUvPj1+8w5kRIzr4IE5C4DoWE7IdLsMa0X8kNUoJjo+BwEooCOrHXWQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/password-confirm.js" integrity="sha512-lpg6hEJ205OqyYqymCngnYz7VO2B4LgNdgrOTak+dSiS84C2J1vyYh1AQGiEJkeRDlA2CtDCHxfzAvu4aatPHg==" crossorigin="anonymous"></script>
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/auth/js/error.css" integrity="sha512-tSMu9/Nw5petw4epygAILFv4b9CuUwCzvTAZmEqrigs/w94gaMJORa3g3vKbqxsRD7YIoP9HZnCv6rfLeNXIlA==" crossorigin="anonymous">
  ```
---

#### Starterkit Dashboard
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/css/app-dark.css" integrity="sha512-BRNEkrBpsrKyIreKg/2pVeWgRy/8UmLWcLEVJ8IzlF4J++xljjERdRtbv73mCq8rGpouJQGl7/f6ActRVbTi+Q==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/css/app.css" integrity="sha512-tDo30oUmCj9tnLTo4pOh7G5nwADM0jnv2EFKRxUZzwnOUagtpYiXD5UCd9Pmr8dEMgZdb7bbeZps7JWNrvMlCA==" crossorigin="anonymous">
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/css/toastify.css" integrity="sha512-tA+z1mt8+hiZE9CgG95WPtakY4JPkTaYgIcM1Wyq/VCdKDttHhnJoIDRC9/eWo8mbK2MmIDcDeUBfIfI1J8nWA==" crossorigin="anonymous">
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/js/choices.js" integrity="sha512-McxoNDBJYOFe4JFCQuUuccQGic/xTQ+xPxS28tgJQbJbjZaffaJPiTSqucG6JZ96dMMTBQXeoAbpEv7Xd6AhCw==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/js/showpassword.js" integrity="sha512-s07o5REwpYHaR3sXgRQ8ukoiA2VzXsfDixf8cL+1Lj0htcAOnFrEuzQMzDgPW1apkVeuoL+aItLMlK03bDv6mQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/css/module.css" integrity="sha512-R3+tafkUdu9OeKtUH2tFP5Lc2dvMqUG4PkgtSHfxih7KpASMZumBmOtgeDcys1svGJQ5/2OjS1Pp6JOBzoYcNg==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/js/app.js" integrity="sha512-Yc/Abj16qIEm1T+95RzrYX0zECoUQAatWcK2Hw+OGQ4UAymq4LPDclNrg7JeIrIggzjTT6ZASjF5Ttd20H2tBw==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/js/bootstrap.js" integrity="sha512-GTXxDPa3h1BC/V1Xn/dkn8wBsmR9xz8l83o3UxutVGFwr+MnPXxv4ZIuw+oCaEAW/W1SzcKzkm6oxzYdaC7axQ==" crossorigin="anonymous"></script>
  ```
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/js/toastify.js" integrity="sha512-ZHzbWDQKpcZxIT9l5KhcnwQTidZFzwK/c7gpUUsFvGjEsxPusdUCyFxjjpc7e/Wj7vLhfMujNx7COwOmzbn+2w==" crossorigin="anonymous"></script>
  ```
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/dashboard/css/choices.css" integrity="sha512-YnbHRWZoSH9PCoOc5bKcCX5yyHA0IjXZvFV0N26hBeKWK3vaqwjAwGiDbwM9hZne6tfTRUMuagPDoaQN87L2pA==" crossorigin="anonymous">
  ```
---

#### Inputmask
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/inputmask/jquery.inputmask.min.js" integrity="sha512-jTgBq4+dMYh73dquskmUFEgMY5mptcbqSw2rmhOZZSJjZbD2wMt0H5nhqWtleVkyBEjmzid5nyERPSNBafG4GQ==" crossorigin="anonymous"></script>
  ```
  Example:
  ```php
  $(document).ready(function(){
    $('#contact').inputmask("[9]9[9]999999[9][9]", {
          placeholder: "_________",
          insertMode: false,
          showMaskOnHover: false,
      });
  });
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
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/css/fontawesome5/font-awesome5-all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/fontawesome5/font-awesome5-all.min.js" integrity="sha512-Tn2m0TIpgVyTzzvmxLNuqbSJH3JP8jm+Cy3hvHrW7ndTDcJ1w5mBiksqDBb8GpE2ksktFvDB/ykZ0mDpsZj20w==" crossorigin="anonymous"></script>
  ```

---
#### Datatables
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/datatables/css/dataTables.bootstrap5.min.css" integrity="sha512-DYpTY0Ub8eZR1nPIgYG0eNVCWim5dFXr834XUOfrVw/5NNRUrPMl8mpNyHvt+CUjG3TyfV898AYXg9eOS+ekmw==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/datatables/js/datatables.min.js" integrity="sha512-4qmoJLDdNz51vzA75oiktlu1NkJgOJKkDDCrSyg3joGHi8W0YR6jqlivtTwql84y7Q0wjbQtZMe2obI7pQ+vjQ==" crossorigin="anonymous"></script>
  ```

---
#### Datepicker
- **CDN CSS**
  ```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/datepicker/css/datepicker.css" integrity="sha512-n/98Hzv7vnNVN8bL5s+hajql1X8LVhS/kPJIMxpXinGzcIVcM+SKTG54IKnRVz8vPIJmWWtyRyP3p4aK3vLiZw==" crossorigin="anonymous">
  ```
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/starterkit/datepicker/js/datepicker.js" integrity="sha512-zTadvlTFbfS8sBJpRcCpwz5NobiDyGe3Tm39xRlDjHCitm1gKu0ciMq24Zl+BGX2oLqtK5sfKUprFNdRHVgWNA==" crossorigin="anonymous"></script>
  ```

---
#### Previewimage
- **CDN JavaScript**
  ```html
  <script src="https://cdn.jsdelivr.net/gh/ruangdev/cdn@idn/js/previewimage/img.preview.js" integrity="sha512-v4yg0eAx7DcsPFGDPc2LxS0EIriB4v6QWPMDTRlKhxBvnYAbmuRMhTr9PrcsdaxvbtRA3J3XLRCuDiZZagdbTg==" crossorigin="anonymous"></script>
  ```

---
Dengan menggunakan link CDN ini, proyek Anda akan memperoleh akses cepat ke file-file statis yang dibutuhkan tanpa harus bergantung sepenuhnya pada server utama Ruang Dev Indonesia.