# Praktikum: Membuat Project Pertama ReactJS

### Nama : Brian Mohamad Safiudin
### NIM : 2141720133
### Kelas : TI-3F

## Langkah 1 - 2
#### Buatlah folder baru bernama belajar-react lalu di dalam folder tersebut, buatlah project baru bernama hello-world
![Screenshot P1](assets-report/praktikumlangkah1dan2.jpg)

## Soal 1
#### Pada gambar tersebut, silakan Anda browsing apa yang dimaksud dengan:

```bash
TypeScript
ESLint
Tailwind CSS
App Router
Importalias
```

- `TypeScript:`
TypeScript adalah sebuah bahasa pemrograman open-source yang dikembangkan oleh Microsoft. Ini adalah sebuah super-set dari JavaScript yang menambahkan static typing (pengetikan statis) ke dalam bahasa tersebut. Dengan menggunakan TypeScript, pengembang dapat menentukan tipe data untuk variabel, parameter fungsi, dan nilai kembali fungsi, yang membantu dalam mendeteksi kesalahan lebih awal dalam siklus pengembangan dan meningkatkan keamanan dan keandalan kode.

- `ESLint:`
ESLint adalah utilitas linting untuk JavaScript. Ini membantu dalam mengidentifikasi dan memperbaiki pola kode yang tidak sesuai dengan pedoman atau standar penulisan yang ditetapkan. Dengan menggunakan ESLint, tim pengembangan dapat memastikan bahwa kode JavaScript mereka konsisten, mudah dibaca, dan mematuhi praktik terbaik.

- `Tailwind CSS:`
Tailwind CSS adalah sebuah framework CSS yang memungkinkan pengembang untuk mendesain tata letak web dengan cepat menggunakan kelas-kelas bawaan. Berbeda dengan framework CSS tradisional yang menyediakan komponen-komponen siap pakai, Tailwind CSS fokus pada utility-first approach, yang berarti pengembang membangun desain mereka dengan menggabungkan kelas-kelas utilitas yang telah ditetapkan.

- `App Router:`
App Router (atau sering disebut sebagai aplikasi router) adalah bagian dari framework atau perpustakaan yang mengatur rute (routing) di dalam aplikasi web atau aplikasi berbasis web. Ini memungkinkan navigasi antara halaman-halaman atau tampilan-tampilan yang berbeda dalam aplikasi tanpa harus memuat ulang halaman utama.

- `Import alias:`
Import alias adalah cara untuk membuat alias atau nama singkat untuk modul atau berkas yang diimpor di dalam sebuah skrip JavaScript atau TypeScript. Ini membantu dalam meningkatkan keterbacaan dan pemeliharaan kode dengan menggantikan path panjang atau kompleks dengan nama yang lebih singkat atau deskriptif saat mengimpor modul atau berkas tersebut. Misalnya, daripada menuliskan import ModuleName from '../../some/long/path/ModuleName';, dapat menggunakan alias seperti import ModuleName from '@/components/ModuleName';, dengan @ sebagai penunjuk direktori root aplikasi.

## Langkah 3
#### Setelah selesai proses langkah sebelumnya, ketik per baris di terminal seperti berikut untuk masuk ke folder project dan dibuka dengan VS Code. Maka VS Code akan membuka project react Anda yang telah dibuat bernama hello-world.
```bash
cd hello-world
```
```bash
code . 
```
![Screenshot P1](assets-report/praktikumlangkah3.jpg)

## Soal 2
#### Pada struktur project tersebut, jelaskan kegunaan folder dan file masing-masing tersebut!

![Screenshot P1](assets-report/soal2.jpg)

- `node_modules:` Folder ini berisi semua paket dan dependensi yang diperlukan oleh proyek React. Ketika menggunakan npm (Node Package Manager) atau Yarn untuk mengelola dependensi proyek, paket-paket ini akan diunduh dan disimpan di folder node_modules. Ini termasuk pustaka-pustaka pihak ketiga yang digunakan dalam proyek React, seperti React itu sendiri, React Router, Redux, dll.

- `public:` Folder ini berisi file-file statis yang akan disajikan langsung oleh server web. Misalnya, file index.html, favicon.ico, dan gambar-gambar statis lainnya dapat ditempatkan di sini. File index.html adalah titik awal dari aplikasi React dan biasanya berisi elemen root tempat React akan di-mount.

- `src:` Folder ini adalah tempat utama di mana kode sumber aplikasi React berada. Ini biasanya berisi file-file JavaScript dan komponen React yang merupakan bagian inti dari aplikasi. Struktur di dalam folder src dapat bervariasi tergantung pada kompleksitas dan organisasi proyek.

- `.eslintrc.json:` Berkas ini adalah berkas konfigurasi yang digunakan oleh ESLint, sebuah utilitas linting untuk JavaScript. Ini berisi preferensi dan aturan yang digunakan oleh ESLint saat memeriksa kode sumber, seperti aturan penulisan, aturan kualitas, dan aturan lainnya.

- `.gitignore:` Berkas ini adalah berkas konfigurasi yang digunakan oleh Git untuk menentukan file dan folder mana yang harus diabaikan saat melakukan operasi Git, seperti git add, git commit, dan git push. Ini biasanya berisi daftar file dan folder yang dihasilkan secara otomatis atau tidak perlu disertakan dalam repositori Git, seperti node_modules, file konfigurasi lokal, dan file sementara.

- `next-env.dts:` Berkas ini adalah berkas yang digunakan oleh Next.js, sebuah kerangka kerja React untuk membuat aplikasi web. Ini berisi definisi tipe untuk lingkungan pengembangan Next.js, seperti variabel lingkungan, konfigurasi, dan pengaturan lainnya.

- `next.config.mjs:` Berkas ini adalah berkas konfigurasi yang digunakan oleh Next.js untuk mengonfigurasi berbagai aspek aplikasi web, seperti pengaturan server, pengaturan rute, pengaturan tata letak, dan pengaturan lainnya.

- `package-lock.json:` Berkas ini adalah berkas yang dihasilkan oleh npm untuk memastikan bahwa versi paket yang diinstal di lingkungan pengembangan lokal sesuai dengan versi paket yang diinstal di lingkungan produksi. Ini memastikan bahwa proyek akan berperilaku konsisten di berbagai lingkungan.

- `package.json:` Berkas ini adalah berkas konfigurasi proyek yang berisi informasi tentang proyek, dependensi, skrip, dan konfigurasi lainnya. Ini juga berisi daftar dependensi yang diperlukan oleh proyek, versi Node.js yang digunakan, dan skrip yang dapat dijalankan untuk memulai, menguji, atau membangun proyek.

- `package-lock.json:` Berkas ini adalah berkas yang dihasilkan oleh npm untuk memastikan bahwa versi paket yang diinstal di lingkungan pengembangan lokal sesuai dengan versi paket yang diinstal di lingkungan produksi. Ini memastikan bahwa proyek akan berperilaku konsisten di berbagai lingkungan.

- `postcss.config.js` Berkas ini adalah berkas konfigurasi yang digunakan oleh PostCSS, sebuah alat pengolahan CSS. Ini berisi preferensi dan aturan yang digunakan oleh PostCSS saat memproses dan mengonversi kode CSS, seperti aturan penulisan, aturan kualitas, dan aturan lainnya.

- `README.md:` Berkas ini adalah berkas yang berisi dokumentasi proyek.

- `tailwind.config.ts:` Berkas ini adalah berkas konfigurasi yang digunakan oleh Tailwind CSS, sebuah framework CSS. Ini berisi preferensi dan aturan yang digunakan oleh Tailwind CSS saat memproses dan mengonversi kode CSS, seperti aturan penulisan, aturan kualitas, dan aturan lainnya.

- `tsconfig.json:` Berkas ini adalah berkas konfigurasi yang digunakan oleh TypeScript, sebuah bahasa pemrograman. Ini berisi preferensi dan aturan yang digunakan oleh TypeScript saat memeriksa dan mengonversi kode JavaScript, seperti aturan penulisan, aturan kualitas, dan aturan lainnya.

## Langkah 4
#### Sekarang kita coba running project pertama kita dengan menjalankan perintah berikut di terminal VS Code.
```bash
npm run dev
```
#### Tunggu proses kompilasi hingga selesai. Lalu Anda dapat membuka alamat localhost di browser: http://localhost:3000/ Jika di browser telah tampil, Selamat!
![Screenshot P1](assets-report/praktikumlangkah4.jpg)


## Soal 3
#### Gantilah teks pada bagian atas dengan Nama - NIM Anda
#### Ketika Anda telah berhasil mengganti teks tersebut, Anda tidak perlu menjalankan perintah npm run dev dan tidak juga diperlukan me-reload halaman di browser. Tiba-tiba perubahan itu tampil, Mengapa terjadi demikian? Jelaskan!
![Screenshot P1](assets-report/soal3.jpg)

- Perubahan terjadi karena fitur yang disebut `"Hot Module Replacement" (HMR) atau "Fast Refresh"` dalam lingkungan pengembangan React.

- `HMR` adalah fitur dalam lingkungan pengembangan yang memungkinkan perubahan kode sumber untuk langsung direfleksikan dalam aplikasi tanpa perlu me-reload halaman secara keseluruhan. Ini berarti bahwa ketika membuat perubahan pada kode sumber, server pengembangan (seperti webpack-dev-server) secara otomatis mendeteksi perubahan tersebut dan hanya memperbarui modul yang berubah, tanpa memuat ulang seluruh aplikasi.

- Ini dimungkinkan karena `webpack` (atau bundler lain yang mendukung fitur ini) secara cerdas menggantikan modul lama dengan yang baru di saat runtime, sambil mempertahankan keadaan aplikasi yang sedang berjalan. Ini memungkinkan pengembangan yang lebih cepat karena pengembang tidak perlu menunggu reload halaman setiap kali mereka membuat perubahan kecil.

- Selain itu, React memiliki fitur serupa yang disebut `"Fast Refresh"`, yang memungkinkan penggantian komponen secara langsung tanpa perlu me-reload seluruh halaman. Ini memungkinkan pengembangan yang lebih cepat dan alur kerja yang lebih mulus.
