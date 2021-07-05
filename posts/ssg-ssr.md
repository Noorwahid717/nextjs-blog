---
title: 'When to Use Static Generation v.s. Server-side Rendering'
date: '2021-07-02'
---

Kami merekomendasikan penggunaan Static Generation (dengan dan tanpa data) bila memungkinkan karena halaman Anda dapat dibuat sekali dan dilayani oleh CDN, yang membuatnya jauh lebih cepat daripada meminta server merender halaman pada setiap permintaan.

Anda dapat menggunakan Static Generation untuk berbagai jenis halaman, termasuk:

halaman pemasaran
Postingan blog
Daftar produk e-niaga
Bantuan dan dokumentasi
Anda harus bertanya pada diri sendiri: "Dapatkah saya melakukan pra-render halaman ini sebelum permintaan pengguna?" Jika jawabannya ya, maka Anda harus memilih Static Generation.

Di sisi lain, Pembuatan Statis bukanlah ide yang baik jika Anda tidak dapat melakukan pra-render halaman sebelum permintaan pengguna. Mungkin halaman Anda menampilkan data yang sering diperbarui, dan konten halaman berubah pada setiap permintaan.

Dalam hal ini, Anda dapat menggunakan Rendering Sisi Server. Ini akan lebih lambat, tetapi halaman pra-render akan selalu up-to-date. Atau Anda dapat melewati pra-rendering dan menggunakan JavaScript sisi klien untuk mengisi data.