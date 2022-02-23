**Modul 2**

**Software as a Service**

**LATIHAN**

```
Rangkuman
```

1.Apa perbedaan antara IaaS, SaaS, dan Paas?
SaaS
- Software as a Service didasarkan pada aplikasi yang dijalankan dari jarak jauh oleh vendor, dan tersedia untuk pelanggan melalui web atau intranet.
- Pelanggan tidak mengelola atau mengontrol infrastruktur cloud yang mendasarinya termasuk jaringan, server, sistem operasi, penyimpanan, atau bahkan kemampuan aplikasi individual, dengan kemungkinan pengecualian dari pengaturan konfigurasi aplikasi khusus pengguna yang terbatas.

PaaS
- Platform as a Service naik satu tingkat dari SaaS karena memungkinkan pelanggan untuk menyebarkan perangkat lunak mereka sendiri ke infrastruktur cloud.
- Pelanggan memiliki kendali atas sistem operasi, penyimpanan, aplikasi yang digunakan, dan kemungkinan modul server web (mis. mod\_perl). Mereka tidak mengontrol infrastruktur cloud yang mendasarinya tetapi mereka memiliki kontrol lebih besar daripada dalam model SaaS.

IaaS
- Infrastruktur sebagai Layanan adalah tingkat komputasi awan yang paling dasar dan paling tidak dapat dikontrol karena menyediakan sumber daya komputasi mentah seperti server virtual, volume penyimpanan, dan komponen jaringan.
- Pelanggan tidak memiliki kendali atas sistem operasi, volume penyimpanan, atau kemampuan aplikasi individual, tetapi mengontrol pengaturan jaringan (misalnya penetapan alamat IP), aplikasi yang diterapkan, modul server web (misalnya mod\_perl) dan kemungkinan kontrol terbatas atas pengaturan mesin virtual individual (misalnya memori dialokasikan ke VM).

Model layanan cloud dasar untuk IaaS, PaaS, dan SaaS

![](images/001.png)

Contoh aplikasi IaaS, PaaS dan SaaS

![](images/002.png)

Referensi : 

<https://www.quora.com/What-is-the-difference-between-IaaS-SaaS-and-Paas> 

2. Arsitektur Platform SAAS (Software as a Service)

Komputasi awan adalah gaya komputasi di mana sumber daya tersedia melalui internet. SaaS adalah salah satu kategori / metodologi komputasi awan. Dengan model ini, satu versi aplikasi, dengan konfigurasi tunggal digunakan untuk semua pelanggan. Di sini, aplikasi dibagikan di banyak klien menggunakan model "satu-ke-banyak". Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal).

Ada dua jenis arsitektur platform SaaS:

![](images/003.png)

- SaaS Vertikal

Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk perawatan kesehatan, pertanian, real estat, industri keuangan)

- SaaS Horisontal

Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

Referensi : 

<https://hackernoon.com/saas-software-as-a-service-platform-architecture-757a432270f5> 

<https://id.sawakinome.com/articles/technology/difference-between-saas-and-soa-2.html> 


3. Perangkat Lunak sebagai Arsitektur Platform Layanan SaaS 

SaaS adalah cara untuk memberikan perangkat lunak, penyedia perangkat lunak secara terpusat menghosting satu atau lebih aplikasi dan membuatnya tersedia untuk pelanggan melalui internet.

Model SaaS :

- Infrastruktur sebagai Layanan
- Platform sebagai Layanan
- Pembelajaran Mesin sebagai Layanan

Mengapa Menggunakan Arsitektur SaaS?

Dari sudut pandang konsumen, aplikasi SaaS adalah salah satu cara termudah dan dapat diandalkan untuk menggunakan layanan atau produk digital. Anda cukup mengaksesnya melalui web, membayar layanan, dan menggunakannya.

Dari perspektif bisnis, produk perangkat lunak yang disampaikan “sebagai layanan” memungkinkan bisnis menawarkan produk mereka dalam skala besar, secara global, sementara juga memungkinkan mereka untuk mempertahankan kontrol keseluruhan atas produk mereka. Beberapa manfaat lain dari penerapan arsitektur SaaS dalam bisnis termasuk, namun tidak terbatas pada:

- Mengurangi waktu ke pasar
- Biaya perawatan yang lebih rendah
- Peningkatan otomatisasi
- Upgrade lebih mudah
- Lebih hemat biaya
- Uji coba instans tunggal dapat dilakukan karena perusahaan tidak perlu menghabiskan banyak sumber daya keuangan untuk mencoba perangkat lunak.

Fitur Utama dan Manfaat Platform SaaS

- Kesederhanaan

Aplikasi perangkat lunak yang dirancang sebagai solusi SaaS biasanya diakses melalui web melalui berbagai jenis perangkat. Antarmuka web yang lebih intuitif  mudah digunakan.

- Ekonomis

Model pembayaran biaya berlangganan bulanan atau tahunan memudahkan bisnis melihat bagaimana memilih untuk menggunakan solusi SaaS dapat menghemat uang bisnis.

- Keamanan

Tidak perlu khawatir dengan bagaimana data Anda dikunci karena disimpan dengan aman di cloud.

- Kesesuaian

Pelanggan cukup masuk ke layanan yang sudah ditingkatkan.

Kekurangan Platform SaaS

- Kurang control

Karena aplikasi SaaS dihosting di lingkungan SaaS vendor, Anda hanya memiliki sedikit atau tidak ada kendali atas perangkat lunak yang Anda gunakan. 

- Ekosistem terbatas

Masih banyak aplikasi yang tidak menawarkan versi yang dihosting.

- Performa

Produk yang dikirimkan lewat internet memiliki performa lebih lambat daripada yang dipasang langsung di internal.

- Masalah Data

SaaS menyimpan data di cloud. Setiap yurisdiksi memiliki kebijakan dan tindakan legislatifnya sendiri ketika data sensitif sedang diproses atau disimpan.

Komponen Utama Platform SaaS

- Keamanan

Melindungi data pelanggan di platform SaaS Anda adalah yang paling penting.

- Privasi

Privasi data adalah komponen penting lainnya yang harus dipertimbangkan oleh platform SaaS Anda.

- Kustomisasi dan Konfigurasi

Mempertimbangkan ekstensibilitas ke arsitektur SaaS Anda adalah komponen penting lainnya untuk Anda pertimbangkan.

Pertimbangan Desain untuk Platform SaaS

- Skalabilitas

Akankah arsitektur SaaS Anda dapat menskalakan dan mengakomodasi ratusan, bahkan ribuan pengguna yang mengaksesnya secara bersamaan melalui web? Aplikasi SaaS yang dirancang dengan baik harus dapat melakukan ini.

- Nol downtime dan Perjanjian Tingkat Layanan

Pengguna biasanya mengharapkan produk tersedia hampir sepanjang waktu dan tanpa gangguan layanan.

- Multi-penyewaan

Produk Anda harus dapat mengakomodasi banyak pengguna sekaligus, memastikan bahwa data pengguna, privasi, dan semuanya masih diamati.

Referensi :

<https://www.devteam.space/blog/saas-software-as-a-service-platform-architecture/> 


4. Cara membangun aplikasi SaaS berbasis cloud

Saat membangun aplikasi SaaS kemungkinan besar Anda sedang membangunnya di cloud. Cloud memiliki banyak keuntungan tentang skalabilitas – yang berbeda dengan lingkungan server lokal.

Membangun produk untuk cloud berarti membangun produk dengan bahasa pemrograman modern. Python adalah bahasa pemrograman yang banyak digunakan, dirancang untuk menekankan pada keterbacaan kodenya. Python sangat bagus dan banyak pengembang menyukainya. Pengetikan dinamis, pemrograman meta, pembuatan prototipe cepat. Semuanya mungkin dengan Python.

Kemudian menentukan database. Kami merekomendasikan untuk menggunakan database berorientasi dokumen karena lebih banyak fleksibilitas, terutama ketika berhadapan dengan perubahan. MongoDB adalah database berorientasi dokumen yang memberikan kinerja tinggi, ketersediaan tinggi, dan skalabilitas mudah.

Kemudian menentukan sistem antrian untuk aplikasi SaaS Anda. Sistem antrian pesan adalah protokol komunikasi asinkron, memungkinkan pengirim dan penerima pesan tidak berinteraksi pada waktu yang sama. RabbitMQ adalah sistem antrian open source yang berjalan di semua sistem operasi utama. 

Referensi : 

<https://usersnap.com/blog/cloud-based-saas-architecture-fundamentals/> 


