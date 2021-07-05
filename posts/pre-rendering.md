---
title: 'Two Forms of Pre-rendering'
date: '2021-07-01'
---

Next.js memiliki dua bentuk pra-rendering: **Pembuatan Statis** dan **Server-side Rendering**. Perbedaannya terletak pada **kapan** ini menghasilkan HTML untuk sebuah halaman.

- **Pembuatan Statis** adalah metode pra-rendering yang menghasilkan HTML pada **waktu pembuatan**. HTML pra-render kemudian _digunakan kembali_ pada setiap permintaan.
- **Server-side Rendering** adalah metode pra-rendering yang menghasilkan HTML pada **setiap permintaan**.

Yang penting, Next.js memungkinkan Anda **memilih** formulir pra-rendering mana yang akan digunakan untuk setiap halaman. Anda dapat membuat aplikasi Next.js "hibrida" dengan menggunakan Static Generation untuk sebagian besar halaman dan menggunakan Server-side Rendering untuk halaman lainnya.