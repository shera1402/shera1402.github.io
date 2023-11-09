---
layout: post
title: Resume Arsikom
date: 2023-11-07
comments: true
---

# Bab 1

## CPU (Central Processing Unit)

CPU adalah bagian terpenting dari sebuah komputer yang bertanggung jawab untuk menjalankan instruksi-instruksi yang diberikan kepada komputer.

### Komponen CPU

- Control Unit: Mengendalikan operasi dasar CPU dan mengarahkan aliran data dan instruksi dalam prosesor.

- Arithmetic and logic unit (ALU): Untuk melakukan operasi aritmetika dan operasi logika berdasar instruksi yang ditentukan.

- Register: Penyimpanan sementara yang digunakan untuk menyimpan data yang sedang diproses atau hasil perhitungan sementara selama eksekusi instruksi komputer.

- CPU Interconnection: sistem koneksi dan bus yang menghubungkan komponen internal CPU dengan bus-bus eksternal Arithmetic Logic Unit

### ALU (Arithmetic Logic Unit) 

ALU (Arithmetic Logic Unit) adalah komponen penting dalam unit pemrosesan pusat (CPU) pada komputer. ALU bertanggung jawab untuk melakukan operasi aritmatika (seperti penjumlahan,pengurangan, perkalian, dan pembagian) serta operasi logika 
(seperti AND, OR, XOR,dan NOT) dalam sistem komputer.

#### Peran ALU

- Operasi Aritmatika

- Operasi Logika

- Perbandingan dan Pemrosesan Data

- Operasi Bitwise

- Penaganan Overflow dan Carry

#### Komponen ALU

- Register

- Pemilih(Multiplexer)

- Dekoder

- Rangkaian Aritmatika

- Rangkaian Logika

- Pembanding(Comparator)

- Rangkaian penanganan Overflow dan Carry

- Bus Data(Jalur Komunikasi)

### Register

Register adalah salah satu dari sekumpulan kecil tempat penyimpanan data yang merupakan bagian dari prosesor komputer. Register dapat menyimpan instruksi, alamat penyimpanan, atau jenis data apapun (seperti urutan bit atau 
karakterindividual).

#### Operasi Register

- Fetch: Operasi Fetch digunakan untuk mengambil instruksi yang diberikan oleh pengguna.

- Decode: Operasi Decode digunakan untuk menafsirkan instruksi.

- Execute: Operasi Execute dilakukan oleh CPU. Output yang dihasilkan oleh CPU kemudian disimpan ke dalam memori dan setelah itu ditampilkan di layar pengguna.

#### Jenis-Jenis Register

- MAR(Memory Address Register)

Register ini menyimpan alamat memori dari data dan instruksi. Register ini 
digunakan untuk mengakses data dan instruksi dari memoriselama fase eksekusi suatu instruksi.

- MDR(Memory Data Register)

MDR adalah register unit kontrol komputer yang berisi data yang akan disimpan di penyimpanan computer (misalnya RAM), atau data setelah diambil dari penyimpanan komputer.Register ini bertindak seperti buffer dan menyimpan apa pun yang disalin dari memori yang siap digunakan oleh prosesor. MDR menyimpan informasi sebelum masuk ke decoder.

- MBR(Memory Buffer Register)

Memory Buffer Register digunakan untukmenyimpan informasi dan data yang dapat dibaca atau ditulis dalam memori komputer.Fungsi utama MBR adalah untuk 
menyimpan berbagai jenis instruksi komputer dan data yang dapat ditransfer antarmemori komputer. Register MBR adalah register terkait memori utama untuk prosesor yang ada di unit pemrosesan karena register ini mampu melakukan operasi terkait memori dengan sangat cepat.

- PC(Program Counter)

Nama lain dari register Program Counter adalah Instruction Address Register (IAR) atau IC (instruction counter).Program Counter digunakan untuk menunjukkan posisi saat ini dari urutan program dalam sistem komputer.Ketika instruksi diambil 
dari memori, nilai Program Counter bertambah satu dan menunjuk ke instruksi berikutnya yang perlu dieksekusi oleh prosesor CPU. Program Counter digunakan untuk menyimpan alamat instruksi langsung yang perlu dieksekusi selanjutnya.

- Accumulator

Register Accumulator memiliki peran yang sangat penting karena jika register ini tidak ada, maka semua hasil sementara yang perlu disimpan dalam memori utama dapat menambah overhead pada memori. Hal ini karena operasi baca dan tulis yang tidak perlu akan meningkat. Hasil sementara yang diperoleh dari CPU dapat dengan 
mudah disimpan di register Accumulator. Kecepatan akses register Accumulator jauh lebih cepat dibandingkan dengan memori utama. Dalam banyak sistem modern, ada berbagai jenis accumulator yang dapat digunakan untuk menyimpan hasil sementara.

- Index Register

Index Register di CPU komputer adalah register prosesor yang digunakan untuk memodifikasi Alamat operan selama menjalankan program.Register ini banyak digunakan untuk melakukan operasi array atau vektor. Konten diambil dari register indeks dan ditambahkan atau dikurangi ke beberapa Alamat langsung untuk mendapatkan Alamat data yang efektif.

- Instruction Register

Instruction register merupakan jenis lain dari register CPU yang digunakan untuk menyimpan instruksi yang sedang dieksekusi atau yang akan didekodekan. Dalam prosesor, register ini menyimpan setiap instruksi di dalamnya, dan kemudian dapat dieksekusi oleh prosesor. Instruksi dapat dieksekusi dalam satu langkah atau dapat 
dieksekusi dalam beberapa langkah.

# Bab 2

## Sejarah Komputer

### Komputer Generasi 1

- Ditemukan pada tahun 1940-1956

- Menggunakan Vacuum Tube sebagai komponen digital

- Bahasa yang digunakan bahasamesin(0 dan 1)

- Membutuhkan ruangan yang luas

### Komputer Generasi 2

- Digunakan antara tahun 1956-1963

- Menggunakan Transistor sebagai komponen digitalnya

- Bahasa yang digunakan Bahasa assembly

- Ukuran tidak sebesar generasi 1

### Komputer Generasi 3

- Digunakan tahun 1964-1971

- Menggunakan IC (Integrated Circuits) sebagai komponen digital

- Ukuran lebih kecil dari generasi 2

### Komputer Generasi 4

- Digunakan pada tahun 1971-sekarang

- Menggunakan Mikroprosesor sebagai komponen digital

- Sudah terdapat layar monitor yang dapat menampilkan GUI

- Ukuran bervariasi

### Komputer Generasi Selanjutnya 

- Berupa cloud computing dan AI

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/vacum.png)</span>

## Logic Gate

Gerbang logika atau logic gates adalah proses pengolahan input bilangan biner
dengan teori matematika boolean. Logic gate ini direpresentasikanmenggunakan 
tabel kebenaran. Jika memiliki nilai benar (true) akan ditunjukan dengan angka “1”. Sebaliknya, jika memiliki nilai salah (false) akan ditunjukan dengan angka “0”.

### Fungsi Gerbang Logika

Gerbang logika memiliki fungsi untuk melakukan fungsi logika dasar untuk
membentuk sirkuit digital yang terintegrasi. Kebanyakan logic gate menggunakan bilangan biner 0 atau 1 bisa juga disebut true atau false. Biasanya terdiri dari dua buah nilai input dan satu nilai output.

### Tabel Kebenaran

Tabel kebenaran adalah tabel yang digunakan untuk melihat nilai kebenaran dari suatu pernyataan. Di sini tabel kebenaran dapat diartikan sebagai table yang berisi kombinasi-kombinasi variable masukan (input) yang menghasilkan keluaran (output) yang logis.

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/gerbang.png)</span>

# Bab 3

## Memory

Memory adalah perangkat atau sistem yang digunakan untuk menyimpan informasi untuk penggunaan langsung dalam komputer atau perangkat keras komputer dan perangkat elektronik digital yang terkait.

## Jenis Memory

- Memory Read Only (ROM)

tipe memori komputer yang berisi data yang tidak dapat diubah oleh pengguna. Data dalam ROM bersifat tetap dan digunakan untuk menyimpan firmware, instruksi komputer, dan data yang perlu ada selama perangkat hidup.

- Memory Read/Write

tipe memori komputer yang memungkinkan pengguna untuk membaca (mengambil 
data dari memori) dan menulis (menyimpan atau mengubah data ke dalam memori) sesuai kebutuhan. Memory R/W umumnya digunakan untuk penyimpanan data sementara (seperti RAM) yang memungkinkan komputer untuk bekerja dengan data secara dinamis selama operasi.

- Static Memory 

tipe memori komputer yang dapat menyimpan data tanpa memerlukan daya listrik berkelanjutan dan data yang disimpan bersifat tetap hingga diubah atau dihapus secara sengaja. Ini termasuk tipe memori seperti Static 
RAM (SRAM) dan non-volatile memory seperti Flash memory.

- Dynamic Memory

tipe memori yang digunakan untuk penyimpanan data yang dapat dibaca dan ditulis oleh perangkat lunak komputer. memerlukan penyegaran berulang untuk 
mempertahankan data dan bersifat volatil, artinya data hilang ketika daya mati. Ini digunakan sebagai memori utama dalam komputer untuk penyimpanan sementara data yang aktif saat komputer beroperasi.

- Volatile

suatu jenis memori atau data yang dapat hilang atau terhapus ketika daya listrik diputuskan atau perangkat dimatikan. Dengan kata lain, data dalam memori volatil akan lenyap saat daya mati. Contoh utama dari memori volatil adalah RAM (RandomAccess Memory) dalam komputer, yang kehilangan data yang tersimpan saat 
komputer dimatikan atau direstart.

- Non-volatile

suatu komponen atau memori untuk menjaga data atau informasi yang tersimpan bahkan ketika daya listrik dimatikan. data yang disimpan dalam media non-volatile akan tetap ada dan dapat diakses setelah komputer dimatikan atau restart,
Perkembangan Memory

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/memory.png)</span>

## Cara Kerja Memory

Memori dalam konteks komputer adalah tempat penyimpanan data dan instruksi 
yang diperlukan untuk operasi komputer. Terdapat beberapa jenis memori yang bekerja berbeda dalam komputer, seperti RAM, ROM, dan penyimpanan sekunder (seperti hard drive atau SSD).

Cara kerja memori di komputer melibatkan proses pembacaan dan penulisan data. Ketika komputer memerlukan data atau instruksi, ia membaca data tersebut dari media penyimpanan yang sesuai ke RAM untuk digunakan dalam operasi saat ini. Data 
dapat ditulis kembali ke media penyimpanan jika ada perubahan dalam data tersebut.

## Cara Optimalisasi Memory

- Pembersihan Aplikasi dan Proses yang Tidak Diperlukan

- Pengelolaan Cache

- Virtual Memory

- Meningkatkan RAM

- Optimasi Penggunaan Browser

- Mengelola Startup Aplikasi

- Menggunakan Software Optimalisasi Memori

- Menghapus File Sementara dan Sampah

- Mengaktifkan Trim (untuk SSD)

- Pemantauan Penggunaan Memori

# Bab 4

## Data

Data adalah fakta-fakta, angka, informasi,atau rekaman yang digunakan sebagai dasar untuk pengambilan keputusan,analisis, penelitian, atau tujuan lainnya. Data dapat berupa berbagai jenis, seperti teks, angka, gambar, audio, atau video,dan dapat mewakili berbagai jenis informasi.

## Data pada Komputer

### Data Numerik

Data Numerik merupakan data yang berupa angka maupun bilangan, bisa dalam bentuk integer, float dan sebagainya.

### Data Non Numerik 

Data Non Numerik adalah data yang bukan berupa angka maupun bilangan. Contohnya adalah data teks, gambar dan sebagainya.

### Data Numerik

#### Sistem Decimal 

Sistem desimal merupakan sistem bilangan yang digunakan sehari-hari.
Desimal terdiri dari angka: 0,1,2,3,4,5,6,7,8,9.

83 = (8x10) + 3

Desimal memiliki base atau radix 10, jadi dapat disimpulkan sebagai berikut :

- 83 = (8x10 <sup>1</sup>) + (3x10 <sup>0</sup>)

- 4728 = 4x10 <sup>...</sup> + 7x10 <sup>...</sup> + 2x10 <sup>...</sup> + 8x10 <sup>...</sup>

#### Sistem Biner 

Sistem biner merupakan system bilangan yang terdiri dari angka 0 dan 1.

- 1 = 0001

- 8 = 1000

Sistem biner memiliki base atau radix 2, jadi dapat disimpulkan sebagai
berikut :

Contoh berikut pada 4 bit

- 1 = 0x2 <sup>3</sup> + 0x2 <sup>2</sup> + 0x2 <sup>1</sup> + 0x2 <sup>0</sup>

- 3 = 0x2 <sup>3</sup> + 0x2 <sup>2</sup> + 1x2 <sup>1</sup> + 1x2 <sup>0</sup>

- 8 = 1x2 <sup>3</sup> + 0x2 <sup>2</sup> + 0x2 <sup>1</sup> + 0x2 <sup>0</sup>

- 9 = 1x2 <sup>3</sup> + 0x2 <sup>2</sup> + 0x2 <sup>1</sup> + 1x2 <sup>0</sup>

#### Integers

Integers atau bilangan bulat merupakan bilangan yang terdiri dari
nilai positif, negatif dan bukan berupa pecahan/desimal.
Contoh bilangan bulat adalah = –5, 0, 8

Pada pemrograman integers akan dinotasikan sebagai int dengan 8 bit data, maka nilai integers adalah sebagai berikut :

- 00000000 = 0

- 00000001 = 1

- 00101001 = 41

- 10000000 = 128

- 11111111 = 255

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/intergers.png)</span>

#### Bilangan Real 

Bilangan real adalah bilangan yang terdapat pecahan atau desimal.Contoh dari bilangan real adalah 3.14, -0.05, dan sebagainya. Pada bahasa pemrograman bilang real di notasikan sebagai float dan double

#### Bilangan Cacah 

Bilangan cacah adalah bilang bulat tanpa nilai negatif.

### Data Non-Numerik

#### TEXT

data teks pada komputer mengacu pada cara teks atau informasi berbasis teks 
direpresentasikan, disimpan,dan dikelola dalam sistem komputer. Representasi ini mencakup cara karakter, kata, kalimat, dan dokumen dalam bentuk teks direpresentasikan dalam format biner yang dapat dipahami dan diolah oleh komputer.

metode representasi data teks pada komputer

- Character Encoding

Character encoding adalah metode dasar untuk merepresentasikan karakter teks 
dalam bentuk kode numerik. Setiap karakter (termasuk huruf, angka, dan simbol) diberikan kode numerik yang unik.

- Plain Text

Teks mentah atau plain text adalah representasi dasar teks di komputer. Ini adalah urutan karakter yang direpresentasikan menggunakan karakter encoding tertentu, seperti ASCII atau UTF-8. Teks mentah tidak memiliki pemformatan khusus dan tidak mengandung tag atau markup.

- Markup Languages

Markup languages seperti HTML (Hypertext Markup Language) dan XML 
(eXtensibleMarkup Language) digunakan untuk merepresentasikan teks bersama 
dengan tag yang memberikan instruksi untuk pemformatan dan tampilan. Markup 
languages memungkinkan teks untuk dimunculkan dalam berbagai cara di web dan aplikasi.

- Word Processing Formats

Format dokumen pengolah kata seperti DOCX (Microsoft Word), ODT
(OpenDocument Text), dan RTF (Rich Text Format) digunakan untuk 
merepresentasikan teks dengan pemformatan lanjutan, seperti huruf tebal, miring, dan daftar.

- Plain Text Files

Teks mentah sering disimpan dalam file berformat .txt atau .csv. Ini adalah format dasar yang hanya berisi teks tanpa format atau struktur tambahan.

- Image

Representasi Citra Digital, semua gambar yang bisa disimpan/diolah pada 
komputer/piranti digital disebut dengan citra digital. Citra digital tersusun dari elemen‐elemen terkecil yang disebut Pixel (picture element).Banyaknya pixel pada sebuah 
citra disebut dengan Resolusi. Biasanya resolusi dinyatakan dalam 2 cara, yaitu:dimensi panjang x lebar, misal: 800×600,1024×768, dll; Banyaknya pixel, misal: 
2 Mega Pixel, 5 Mega Pixel,dll. 

Format bmp (bitmap) adalah format citra yang langsung memetakan intensitas RGB ke media penyimpanan dengan rincian setiap pixel:

- Red (R) : 8 bit , 0‐255

- Green (G): 8 bit , 0‐255

– Blue (B): 8 bit , 0‐255

Sehingga, 1 pixel citra dengan format bmp memerlukan alokasi sebesar 24 bit (3 Byte). 

Format lain dari citra antara lain: jpg, gif, png,dsb. Umumnya memiliki ukuran yang lebih kecil dari bmp untuk citra yang sama. Hal ini disebabkan format selain bmp merupakan format yang telah mengalami kompresi.

# Bab 5

## Bahasa Pemrograman

Bahasa pemrograman adalah sebuah bahasa yang digunakan untuk menulis atau menyusun kode yang dapat diterjemahkan oleh komputer menjadi instruksi-instruksi yang dapat dieksekusi. Hal ini sama saja dengan menjadikan Bahasa pemrograman 
sebagai cara yang bisa dipahami oleh komputer.

Bahasa pemrograman ada beberapa jenis antara lain : bahasa tingkat rendah, 
bahasa mesin, Bahasa tingkat menengah dan Bahasa tingkat tinggi.

### Fungsi Bahasa Pemrograman:

- Memudahkan Komunikasi Antara Komputer dan Pengguna

- Membuat Aplikasi yang Kompleks

- Membuat Kode Reusable

- Mempercepat Pengembangan Software

- Membuat Komputer Melakukan Banyak Tugas yang Berbeda

### Bahasa Mesin/Bahasa Assembly

Bahasa mesin adalah bentuk Bahasa pemrograman yang paling rendah dalam hal tingkat abstraksi. Bahasa mesin menggambarkan instruksi dalam kode biner yang secara langsung dapat dieksekusi oleh komputer. Setiap bahasa mesin terkait erat dengan arsitektur perangkat keras tertentu.

### Bahasa Tingkat Rendah 

Bahasa ini memberikan control yang lebih langsung atas perangkat keras 
komputer.Instruksi lebih dekat dengan bahasa mesin, tetapi lebih mudah dipahami oleh manusia. Contoh: C dan C++.

### Bahasa Tingkat Menengah

Bahasa ini menawarkan tingkat abstraksi yang lebih tinggi dibandingkan bahasa tingkat rendah. Biasanya, lebih mudah untuk memahami dan digunakan untuk mengembangkan perangkat lunak sistem. Contoh: Ada, Rust.

### Bahasa Tingkat Tinggi

Bahasa pemrograman yang sangat jauh dari bahasa mesin atau bahasa assembly 
adalah bahasa pemrograman tingkat tinggi atau high-level language. Bahasa ini sangat mudah dipahami oleh manusia dan lebih banyak digunakan untuk aplikasi web, aplikasi mobile, atau aplikasi data science. Contoh bahasa tingkat tinggi adalah Python, Ruby, atau JavaScript.

# Bab 6

## Translator

Dalam konteks bahasa pemrograman, "translator" biasanya merujuk kepada program atau perangkat lunak yang mengubah kode sumber dari satu bahasa pemrograman ke bahasa pemrograman lain. Ini biasanya dilakukan untuk beberapa tujuan seperti portabilitas,optimisasi, atau integrasi.

Ada 2 jenis translator utama pada bahasa pemrograman, yaitu Compiler dan Interpreter.

### Compiler
Compiler adalah jenis translator yang menerjemahkan seluruh kode sumber dalamsatu kali proses ke dalam bahasa mesin atau kode antara (intermediate code).

Compiler menghasilkan file biner atau kode antara yang dapat dieksekusi secara langsung oleh komputer.

Contoh bahasa yang menggunakan compiler adalah C, C++, dan Ada.

#### Fase Pada Compiler

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/compiler.png)</span>

### Interpreter 

Interpreter adalah jenis translator yang membaca dan mengeksekusi kode sumber baris demi baris saat program berjalan. Ini berarti kode sumber tidak diterjemahkan ke dalam bahasa mesin atau kode antara sebelum dieksekusi. Contoh bahasa yang menggunakan interpreter adalah Python,JavaScript, dan Ruby.

### Compiler VS Interpreter

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/interpreter.png)</span>

## Linker
Linker adalah bagian dari proses kompilasi dalam pengembangan perangkat lunak yang bertanggung jawab untuk menggabungkan berbagai modul kode sumber menjadi sebuah program eksekusi yang dapat dijalankan

<span style="display:block;text-align:center">![alt](https://ivanafirmansyah.github.io/assets/img/linker.png)</span>
