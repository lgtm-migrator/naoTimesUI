# naoTimes dan naoTimesUI
merupakan *pet-project* milik N4O.

Dibuat tahun 2019 lalu, naoTimes merupakan sebuah Bot yang mengambil inspirasi dari Aquarius untuk tracking garapan Fansub.
Website ini sendiri mulai dibuat Maret 2021 lalu, dengan niat sebagai alternatif bagi yang kurang ngerti pakai botnya gimana.
Dengan merilis website ini juga, semua orang dapat daftar ke fitur Showtimes tanpa perlu meminta ke saya sendiri 😊

Website ini telah melewati beberapa iterasi sebelum akhirnya nyantol sama salah satu framework:
- Next.js
- Svelte
- SSR Rendering w/ ExpressJS + EJS **[Versi lama]**
- Next.js (lagi) **[Versi sekarang]**

Versi yang sekarang anda liat merupakan versi Next.js, setelah belajar-belajar React dari buat web VTuber API (https://vtuber.ihateani.me)

Beberapa alasan pindah ke ReactJS gampang sih:
1. Lebih gampang kontrol perubahan
2. Berbasis Komponen, jadi bisa pake ulang lagi komponen yang sama untuk laman lain
3. Support komunitasnya lumayan banyak
4. ~~Bisa hosting gratis di Vercel, paling penting ini :)~~

Dan alasan gak mau pake ReactJS/Next.js:
1. RIBET ANJGGGGGGGGGGGGGGGGGGGGGGGGGGGGGGGG
2. Untuk session handling agak scuffed, tapi bisa pake [next-iron-session](https://github.com/vvo/next-iron-session)
3. Berat, Virtual DOM itu lumayan makan memori.

Walaupun ada beberapa hal negatif tentang React, pake React sendiri jadi mempermudah hidup.
Awalnya pengen nyoba Vue.js sih, tapi kurang cocok dengan use-case yang tak inginkan.

### Kredit
Website ini menggunakan teknologi berikut:
- [Next.js](https://nextjs.org/) oleh Vercel, sebagai Framework utama
- [ReactJS](https://reactjs.org/) oleh Facebook, sebagai library utama untuk buat website ini
- [TailwindCSS](https://tailwindcss.com/) oleh TailwindLabs, sebagai styling website
- [PostCSS](https://postcss.org/), sebagai engine CSS yang tak pakai
- [MongoDB](https://www.mongodb.com/) oleh MongoDB Inc. sebagai Database yang dipakai
- [Mongoose](https://mongoosejs.com/) oleh Automattic, sebagai connector database MongoDB dengan sistem ODM
- [TypeScript](https://www.typescriptlang.org/) oleh Microsoft, sebagai bahasa yang tak pakai untuk nulis website ini
- [Webpack](https://webpack.js.org/), sebagai bundler untuk website ini
- [ReactMarkdown](https://github.com/remarkjs/react-markdown) oleh Remark, sebagai Markdown engine yang tak pakai untuk render teks ini
- [Vercel](https://vercel.com), sebagai tempat hosting web ini :heart:

Makasih juga untuk manusia-manusia berikut:
- Kresendo (Bantuan pemilihan kata, ide, dan lain-lain)
- *Anon* 1 (Bantuan translasi untuk Embed versi Jawa)
- *Anon* 2 (Bantuan translasi untuk Embed versi Sunda)
- Semua orang yang mencoba dan menyebarkan naoTimes :heart:

:heart: {{currentYear}} - naoTimesDev a.k.a N4O
