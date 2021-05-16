## Belajar Membuat Aplikasi Back-End untuk Pemula
<p align="justify">
<b>Front-End</b> merupakan bagian dari aplikasi yang terlihat dan digunakan langsung oleh pengguna (end-user). Orang yang menggeluti bidang ini disebut <b>Front-End Developer</b>. Aplikasi yang dibuat oleh seorang Front-End Developer dapat berupa web, mobile native, desktop, atau platform lainnya. Di mana pun aplikasi berjalan, fokus utama seorang Front-End Developer adalah membangun aplikasi yang memiliki performa baik, mudah diakses, serta memiliki tampilan yang menarik.</br></br>
Sedangkan <b>Back-End</b> merupakan bagian dari aplikasi yang bertanggung jawab untuk menyediakan kebutuhan yang tak terlihat oleh pengguna (tidak berintaraksi langsung dengan pengguna), seperti bagaimana data disimpan, diolah, serta ditransaksikan secara aman. Itu semua bertujuan untuk mendukung aplikasi Front-End bekerja sesuai dengan fungsinya. Sosok yang menggeluti bidang ini disebut <b>Back-End Developer</b>.</br></br>
Sistem aplikasi bekerja mirip seperti sistem bisnis pada dunia nyata. Agar lebih mudah memahami peran Back-End dan Front-End, mari analogikan sistem aplikasi layaknya sebuah bisnis kedai kopi. Anggaplah Anda ingin membeli kopi di kedai kopi. Setelah sampai di kedai, hal pertama yang Anda lakukan adalah menuju kasir dan berbicara “Hallo, saya ingin memesan kopi.” Dengan ramah kasir menunjukan daftar kopi yang tersedia untuk Anda. “Saya mau kopi tubruk panas ukuran sedang.” ujar Anda, lalu kasir menulis pesanan Anda untuk diserahkan ke barista dan membuat tagihan pembayaran. Sambil menunggu kopi selesai dibuat, Anda duduk di kursi yang tersedia, dan menikmati alunan lagu yang diputar melalui speaker di sudut atap kedai kopi tersebut. Tak sampai 10 menit menunggu, seorang pelayan menghampiri tempat duduk Anda. Akhirnya kopi yang Anda pesan tiba! Pelayan tersebut meletakan kopi beserta tagihan pembayaran yang harus Anda bayarkan.
Dari skenario tersebut apakah Anda bisa mengetahui bagian kedai kopi mana merupakan peran depan (front-end) dan peran belakang (back-end)? Jika masih bingung, ayo kita cari tahu.</br></br>
Front-End berperan pada seluruh hal yang dapat Anda lihat, rasakan, dan interaksikan, termasuk pengalaman Anda saat berada di kedai kopi tersebut. Contohnya seperti susunan interior, kemudahan untuk memesan kopi, sifat ramah seorang kasir dan pelayan, hingga alunan musik yang Anda nikmati saat menunggu kopi datang. Di sini Front-End fokus memastikan Anda termudahkan, senang, dan nyaman saat berada di dalam kedai kopi. Pada sistem aplikasi pun demikian. Kenyamanan, keindahan, kemudahan akses, dan performa aplikasi yang baik menjadi tanggung jawab dari seorang Front-End Developer.</br></br>
Lalu di mana peran Back-End? Karena Anda konsumen, tentu peran Back-End tak terlihat dan tidak diketahui oleh Anda. Contohnya seperti teknik barista membuat kopi, apa dan bagaimana cara mengoperasikan mesin kopi, laporan keuangan, biaya sewa kedai, dan hal-hal dapur tak terlihat pelanggan lainnya. Tentu Anda tak tahu menahu kan? Yang penting, kopi yang Anda pesan sampai di meja Anda. Walaupun tak terlihat oleh konsumen secara langsung, peran Back-End sangatlah vital untuk menunjang kedai kopi dapat tetap beroperasi. Dalam sebuah sistem aplikasi, segala urusan yang tak terlihat oleh pengguna seperti bisnis logic, database, keamanan data, kestabilan server menjadi tanggung jawab Back-End Developer.
</p>

### Server
<p align="justify">Meskipun Back-End dan Front-End terpisah dalam hal peran dan konsentrasi, namun keduanya harus saling terhubung secara lancar (seamless) agar aplikasi dapat berjalan dengan baik.Pada kedai kopi, penghubung itu adalah seorang pelayan. Pelayan mencatat pesanan yang Anda inginkan kemudian mengirimnya ke barista. Setelah barista selesai membuat kopi, pelayan juga yang mengantarkan kopi dari barista ke meja Anda. Semua transaksi yang terjadi menggunakan perantara. Sebagai pelanggan, Anda tidak bisa masuk ke dapur dan meminta kopi langsung ke barista, karena hal tersebut tentu menyalahi prosedur.</br></br>
Begitu pula dengan transaksi yang terjadi pada sistem aplikasi. Kita harus merancang sistem aplikasi dengan prosedur yang benar. Transaksi yang dilakukan Back-End ke Front-End harus melalui perantara. Front-End tidak boleh memiliki akses terhadap database secara langsung, begitu pula dengan Back-End yang sama sekali tidak boleh diakses secara langsung oleh pengguna (end-user). Pada sistem aplikasi, perantara tersebut dinamakan “server” yang posisinya serupa pelayan di kedai kopi.</br></p>
<img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103282214562ca5be6287f6943d4bfa480b84f66d25.png">

### Apa itu Server?
<p align="justify">Server merupakan sebuah sistem yang dapat menyediakan sumber daya berupa data, layanan, atau program untuk disajikan ke komputer lain. Pengertian dari server bukanlah sebuah perangkat keras ataupun komputer, namun server sendiri lebih merujuk kepada sistem yang dapat membuat perangkat (termasuk komputer) dapat melayani sebuah permintaan dari perangkat lain. Jika diterjemahkan ke dalam Bahasa Indonesia, server memang berarti penyaji, atau pelayan. </br></br>
Server bertugas untuk melayani sebuah layanan (services) atau jasa. Dalam dunia komputer ada banyak service yang dapat dilayani oleh server. Berikut beberapa tipe server sesuai dengan layanan yang baik untuk Anda ketahui.</p>
<ol align="justify"><li>File Server : melayani penyimpanan dan pendistribusian berkas.</li>
<li>Application Server : melayani hosting sebuah program atau aplikasi.</li>
<li>DNS Server : mengubah nama domain (contoh: dicoding.com) ke dalam bentuk IP Address (contoh: 75.2.21.170).</li>
<li>Web Server : melayani hosting sebuah program atau aplikasi (seperti Application Server) yang dapat diakses oleh client melalui internet maupun intranet.</li>
<li>Database Server : melayani penyimpanan dan pendistribusian data terstruktur.</li></ol>

### Web Server dan Web Service
<p align="justify"><b>Web Server</b> : Server yang dapat menjalankan program dan dapat diakses melalui internet atau intranet. <b>Web Service </b>: Program yang dijalankan di web server agar kebutuhan bisnis terpenuhi. Web service berjalan di dalam web server sehingga ia dapat diakses melalui internet. Melalui web service inilah aplikasi Front-End (client) dan Back-End dapat bertransaksi.</p>

### Komunikasi Client-Server
<p align="justify"><b>HTTP/HTTPS</b> merupakan salah satu protokol yang dapat digunakan untuk berinteraksi dengan web server. Protokol tersebut terkenal dengan pola request-response, artinya untuk mendapatkan sesuatu (response) kita perlu melakukan permintaan terlebih dahulu (request). Lagi-lagi ini menjadi pola yang sama ketika kita hendak memesan kopi di kedai kopi.</br></br>
Ketika Anda ingin membeli kopi, tentu kopi yang diinginkan tidak secara ajaib datang sendiri. Anda sebagai pelanggan perlu mendatangi kasir atau pelayan untuk meminta (request) kopi yang diinginkan, pelayan meneruskan permintaan Anda ke barista, kemudian barista membuatkan kopi, dan memberikannya kembali (respons) ke pelayan untuk dihidangkan kepada Anda.</p>
<img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/2021032822185030c44bb079d1e9cbf90f94695bab4bba.png">
<p align="justify">Pola yang sama dengan komunikasi client dengan server (untuk memudahkan pemahaman, sebutlah client adalah Front-End, server adalah Back-End) bila menggunakan protokol HTTP/S. Server tidak akan mengirimkan data apa pun apabila tidak ada permintaan dari client. Ketika client meminta sesuatu, barulah server akan menanggapi.</p>
<img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103282219021e4f35ec4c61af5791fb99152a1df7e9.png">
<p align="justify">protokol HTTP di mana request yang diajukan client harus memiliki informasi-informasi yang cukup agar dapat dieksekusi oleh server. Informasi pada request dapat mengandung:</p><ol align="justify"><li>
Request line : berisikan method/verb seperti GET (mengambil data), POST (menambahkan/mengirim data), PUT (memperbaharui data), atau DELETE (menghapus data); path atau alamat yang diminta; dan versi HTTP yang digunakan.</li>
<li>Header : memuat informasi yang dilampirkan terkait request seperti format dokumen (contoh application/json, text/html, dsb), kunci akses, dsb.</li>
<li>Body (opsional) : mengandung data yang dibutuhkan oleh server, bisa dalam bentuk teks, JSON, dll. Body tidak wajib dilampirkan bila server tidak membutuhkan data apapun.</li></ol>

<p align="justify">Apabila informasi yang dilampirkan pada request tidak jelas/sesuai, maka server akan menolaknya dengan respons negatif. Respons negatif? Apa itu?
Setiap request yang dilakukan, baik dengan informasi yang sesuai ataupun tidak, akan mendapatkan respons. Respons atau tanggapan yang dikirimkan dari server untuk client juga mengandung informasi. Berikut beberapa informasi yang dilampirkan oleh respons</p>
<ol align="justify"><li>
Status line : berisikan HTTP versi yang digunakan; status code berupa tiga digit angka yang menandakan keberhasilan dari permintaan; reason phrase atau status text yang merupakan pesan berdasarkan status code dalam bentuk teks sehingga lebih mudah dimengerti.</li>
<li>Header : mengandung informasi yang dilampirkan terkait response seperti format dokumen.</li>
<li>Body (opsional, namun biasanya selalu dilampirkan) : memuat data yang dikirimkan oleh server. Data dapat berupa HTML, JSON, gambar, dsb</li></ol>

<p align="justify">Respons negatif merupakan respons dari server ketika sebuah permintaan dari client gagal dipenuhi. Sama seperti di dunia nyata, ketika kita meminta kopi tubruk di kedai, namun permintaan kita tidak dapat kedai kopi penuhi sebab alasan teknis. Alih-alih mendapatkan kopi kita hanya mendapatkan pesan “maaf stok kopi habis” atau “maaf mesin kopi sedang rusak.”</br></br>
Begitu pula dengan protokol HTTP. Bila kita meminta sesuatu yang tidak dapat server proses, maka kita tidak akan mendapatkan data yang diinginkan. Server akan memberikan respons negatif dengan alasan mengapa ia tidak bisa memenuhi permintaannya, contohnya seperti “Not Found”, “Bad Request” atau pesan lainnya. </br></br>Kita dapat mengetahui sebuah request berhasil atau tidak melalui status code yang dikirim oleh response. Sebuah request berhasil bila status code response diawali dengan huruf 1, 2 atau 3, selain itu request gagal dieksekusi.</p>

<p align="justify"><b>cURL atau Client URL </b>merupakan software berbasis command line yang dapat melakukan transaksi data melalui beberapa protokol internet, salah satunya HTTP/S. cURL dapat diakses secara langsung tanpa proses install melalui Terminal (Linux dan Mac) atau CMD (Windows)</br></br>
Kita akan melakukan tiga skenario berikut:</p>
<ol align="justify"><li>
Meminta daftar kopi tersedia.</li>
<li>Membeli kopi yang tersedia.</li>
<li>Membeli kopi yang tidak tersedia.</li></ol>

<p align="justify">Masuk ke skenario pertama, buatlah request untuk mendapatkan daftar kopi yang tersedia, tulislah kode berikut pada CMD atau Terminal Anda.</br></br>
<i>curl -X GET https://coffee-api.dicoding.dev/coffees -i</i></br></br>
Kita bedah kodenya yuk: </p>
<ol align="justify"><li>
curl : merupakan perintah untuk menggunakan program cURL pada Terminal atau CMD.</li>
<li>-X GET : menetapkan HTTP method/verb yang kita gunakan. GET berarti kita ingin mendapatkan sebuah data.</li>
<li>https://coffee-api.dicoding.dev/coffees : merupakan alamat request yang dituju.</li>
<li>-i : memberikan informasi detail terhadap response yang diberikan (HTTP response headers).</li></ol>

<p align="justify">Setelah menuliskan kode tersebut, tekan enter. Anda akan mendapatkan respons dari web server seperti ini:</p>
  
<div class="highlight highlight-text-html-php position-relative" data-snippet-clipboard-copy-content="HTTP/1.1 200 OK
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
X-Powered-By: Express
Access-Control-Allow-Origin: *
ETag: W/"bc-+nGU6AB86aQxzJjdtoq2u1HQvyU"
X-Cloud-Trace-Context: 15ccf145d9c0d899c01b59c50e0f2e31;o=1
Date: Sun, 03 Jan 2021 00:41:28 GMT
Server: Google Frontend
Content-Length: 188
Alt-Svc: h3-29=":443"; ma=2592000,h3-T051=":443"; ma=2592000,h3-Q050=":443"; ma=2592000,h3-Q046=":443"; ma=2592000,h3-Q043=":443"; ma=2592000,quic=":443"; ma=2592000; v="46,43"
 {"message":"Berikut daftar kopi yang tersedia","coffees":[{"id":1,"name":"Kopi Tubruk","price":12000},{"id":2,"name":"Kopi Tarik","price":15000},{"id":3,"name":"Kopi Jawa","price":18000}]}
">

<p align="justify">Voila! Anda berhasil mendapatkan response pertama dari server. Fokus terhadap kode yang ditebalkan yah. Mari kita bedah sekarang.</p>
<ol align="justify"><li>
HTTP/1.1 : merupakan HTTP version yang digunakan oleh web server dalam menanggapi permintaan.</li>
<li>200 : merupakan status code dari request. Karena status code diawali dengan angka 2, berarti request kita berhasil dilakukan.</li>
<li>OK : merupakan pesan teks dari status code, 200 berarti “OK”.</li>
<li>Content-Type: application/json; : merupakan tipe konten yang digunakan web server dalam memberikan data. Karena nilainya application/json, itu berarti server menggunakan format json.</li>
<li>JSON Data (kode di bagian bawah) : merupakan data yang diberikan oleh web server. Kita bisa melihat web server memberikan informasi kopi yang tersedia beserta harganya menggunakan format JSON.</li></ol>

<p align="justify">Lanjut ke skenario kedua yuk. Buat permintaan membeli kopi yang tersedia dengan menuliskan perintah berikut:</p>

```plantuml
curl -X POST -H "Content-Type: application/json" 
-d "{\"name\": \"Kopi Tubruk\"}" https://coffee-api.dicoding.dev/transactions -i
```

<p align="justify">Jika dilihat, kode yang dituliskan memiliki struktur yang sama, namun ada beberapa perbedaan. Mari kita bedah:</p>
<ol align="justify"><li>
-X POST : dalam request kali ini kita menggunakan method POST. Karena membeli bukan hanya meminta data, tapi akan mengubah jumlah stok kopi yang ada. Selain itu kita juga melampirkan data berupa kopi apa yang akan dipesan. Sehingga tidak masuk akal bila kita menggunakan GET request.</li>
<li>-H “Content-Type: application/json” : Menetapkan nilai “Content-Type: application/json” pada Header request. Fungsinya untuk memberitahu server bahwa kita melampirkan data dalam bentuk JSON.</li>
<li>-d <JSON Content> : merupakan data yang dilampirkan pada request. Data ini berformat JSON dan memiliki informasi kopi apa yang ingin dipesan.</li>
<li>https://coffee-api.dicoding.dev/transactions : Merupakan alamat request yang dituju untuk membeli kopi.</li></ol>

<p align="justify">Setelah menuliskan perintah di atas. Anda akan mendapatkan respons seperti ini dari web server:</p>

```plantuml
HTTP/1.1 200 OK
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
X-Powered-By: Express
Access-Control-Allow-Origin: *
ETag: W/"2e-a65Yb2UyToE5h4vnZNUuPzDX90c"
X-Cloud-Trace-Context: 59cdf8e8238b684818cd4315bd9b7ef6;o=1
Date: Sun, 03 Jan 2021 02:45:21 GMT
Server: Google Frontend
Content-Length: 46
Alt-Svc: h3-29=":443"; ma=2592000,h3-T051=":443"; ma=2592000,h3-Q050=":443"; ma=2592000,h3-Q046=":443"; 
ma=2592000,h3-Q043=":443"; ma=2592000,quic=":443"; ma=2592000; v="46,43"
{"message":"Pesanan berhasil!","success":true}
```

<p align="justify">Lanjut ke skenario terakhir, yakni membeli kopi yang tidak tersedia. Tuliskan perintah yang sama seperti sebelumnya. Namun dengan tipe kopi yang tentunya tidak tersedia pada daftar. Contohnya Kopi Luwak.</p>

```plantuml
curl -X POST -H "Content-Type: application/json" 
-d "{\"name\": \"Kopi Luwak\"}" https://coffee-api.dicoding.dev/transactions -i
```

<p align="justify">Silakan tulis perintahnya, kemudian tekan enter. Kali ini Anda akan mendapatkan response seperti ini.</p>

```plantuml
HTTP/1.1 404 Not Found
Content-Type: application/json; charset=utf-8
Vary: Accept-Encoding
X-Powered-By: Express
Access-Control-Allow-Origin: *
ETag: W/"42-WP2gTxT4eLOmvee44xnev3QcFoE"
X-Cloud-Trace-Context: cee054c7dd8147e341d0c509ca7f6768;o=1
Date: Sun, 03 Jan 2021 03:01:51 GMT
Server: Google Frontend
Content-Length: 66
Alt-Svc: h3-29=":443"; ma=2592000,h3-T051=":443"; ma=2592000,h3-Q050=":443"; 
ma=2592000,h3-Q046=":443"; ma=2592000,h3-Q043=":443"; ma=2592000,quic=":443"; ma=2592000; v="46,43"
```

<p align="justify">Lihat status code-nya, kali ini Anda mendapatkan respons negatif lho! Request yang Anda lakukan tidak dapat diproses oleh server karena kopi luwak tidak ada (not found) pada daftar kopi. Nah melalui latihan tadi, semoga Anda semakin mengerti yah bagaimana client dan server berkomunikasi melalui protokol HTTP.
{"message":"Pesanan gagal, kopi tidak ditemukan!","success":false}</p>

<p align="justify"><b>REST Web Service</b></br>
Dalam mengembangkan web service Anda perlu menetapkan arsitektur apa yang hendak diadaptasi. Dengan menetapkan arsitektur, client, dan server lebih mudah dalam berkomunikasi karena memiliki pola atau gaya yang konsisten. Salah satu arsitektur web service yang banyak digunakan saat ini adalah REST. </br></br>
<b>REST atau REpresentational State Transfer</b> adalah salah satu gaya arsitektur yang dapat diadaptasi ketika membangun web service. Arsitektur ini sangat populer digunakan karena pengembangannya yang relatif mudah. REST menggunakan pola request-response dalam berinteraksi, artinya ia memanfaatkan protokol HTTP seperti yang sudah kita pelajari di materi sebelumnya. </br></br>
Dalam implementasinya arsitektur REST benar-benar memisahkan peran client dan server, bahkan keduanya tidak harus saling mengetahui. Artinya ketika terjadi perubahan besar di sisi client, tidak akan berdampak pada sisi server, begitu juga sebaliknya.</br></br>
<b>REST API</b>
Sebagian dari kalian mungkin mengenal REST dengan sebutan RESTful API. Yups, memang benar! RESTful merupakan sebutan untuk web services yang menerapkan arsitektur REST. REST juga merupakan API (application program interface) karena ia digunakan untuk menjembatani antara sistem yang berbeda (client dan server).</br></br>
<b>API atau Application Program Interface</b> merupakan antarmuka yang menjadi perantara antara sistem aplikasi yang berbeda. API tak hanya dalam bentuk Web Service, bisa saja berupa SDK (Software Development Kit) ataupun lainnya.</br></br>
Berikut beberapa sifat yang menjadi kunci pada REST API.</p><ol align="justify"><li>
Client-Server : Ini merupakan hal yang paling mendasar dalam membangun REST API. Server harus bisa merespons permintaan yang dilakukan client, baik itu respons berhasil ataupun gagal. Komunikasi client dan server dilakukan melalui protokol HTTP.</li>
<li>Stateless : REST API tidak boleh menyimpan keadaan (state) apa pun terkait client. Seluruh state harus tetap disimpan di client. Artinya, tidak ada session di REST API. Permintaan yang dilakukan client harus mengandung informasi yang jelas. Jangan berharap RESTful API akan menyimpan informasi dari permintaan sebelumnya untuk digunakan di permintaan selanjutnya.</li>
<li>Cacheable : Agar dapat merespons permintaan dengan cepat, sebaiknya REST API menerapkan prinsip cache. Sehingga setiap permintaan tidak melulu mengambil dari database.</li>
<li>Layered : Ketika REST API server memiliki arsitektur yang kompleks, client seharusnya tidak perlu tahu bagaimana server melayaninya.</li></ol>

<p align="justify">Selain itu, sebelum membangun REST API, kita perlu mengenal dahulu bagaimana konsep-konsep penting yang harus diterapkan dalam membangun arsitektur ini. Apa saja? </br>Singkatnya, ketika membangun REST API kita harus memperhatikan empat poin berikut:</p>
<ol align="justify"><li>
Format request dan response.</li>
<li>HTTP Verbs/Methods.</li>
<li>HTTP Response code.</li>
<li>URL Design.</li></ol>

<p align="justify"><b>Format Request dan Response</b></br>
REST API seringnya menggunakan JavaScript Object Notation atau JSON sebagai format data baik itu pada request ataupun response. JSON merupakan salah satu format standar dalam transaksi data. Bahkan, saat ini JSON menjadi format terpopuler mengalahkan pendahulunya yaitu XML.</br></br>
Sebenarnya Anda bisa menggunakan XML pada REST API, namun sebaiknya gunakan JSON agar lebih mudah dibaca dan efisien dalam transaksi data. Agar REST API selalu merespons dengan format JSON, pastikan setiap respons terdapat properti Content-Type dengan nilai application/json. Seperti namanya, JSON memiliki struktur seperti JavaScript Object yakni menggunakan key-value. Bedanya, key pada JSON selalu dituliskan menggunakan tanda kutip dua (“”). Value pada JSON dapat menampung nilai primitif seperti string, number, boolean, atau nilai non primitif seperti object atau array. Pada latihan sebelumnya Anda sudah melihat bagaimana bentuk JSON ketika mengirimkan data pembelian kopi dan data pada body respon dari server. Berikut contoh struktur JSON ketika melakukan GET request terhadap url https://coffee-api.dicoding.dev/coffees</p>


```plantuml
{
  "message": "Berikut daftar kopi yang tersedia",
  "coffees": [
    {
      "id": 1,
      "name": "Kopi Tubruk",
      "price": 12000
    },
    {
      "id": 2,
      "name": "Kopi Tarik",
      "price": 15000
    },
    {
      "id": 3,
      "name": "Kopi Jawa",
      "price": 18000
    }
  ]
}
```

<p align="justify">Walaupun memiliki nama JavaScript Object Notation, bukan berarti kita harus menggunakan JavaScript untuk mengolah data dengan format JSON. Format JSON dapat digunakan oleh hampir semua bahasa pemrograman yang ada.</br></br>
<b>HTTP Verbs/Methods</b></br>
Karena REST API menggunakan protokol HTTP, kita dapat memanfaatkan HTTP verbs untuk menentukan aksi.</br></br>
GET untuk mendapatkan data, POST untuk mengirimkan data baru, PUT untuk memperbarui data yang ada, dan DELETE untuk menghapus data. Verbs tersebutlah yang umum digunakan dalam operasi CRUD.</br></br>
<b>HTTP Response Code</b></br>
Status-Line merupakan salah satu bagian dari HTTP Response. Di dalam status line terdapat response code yang mengindikasikan bahwa permintaan yang client lakukan berhasil atau tidak. Karena itu, ketika membangun REST API kita perlu memperhatikan dan menetapkan response code secara benar.</br></br>
Status code bernilai 3 digit angka. Pada REST API, berikut nilai-nilai status code yang sering digunakan:</p>
<ol align="justify"><li>
200 (OK) - Permintaan client berhasil dijalankan oleh server.</li>
<li>201 (Created) - Server berhasil membuat/menambahkan resource yang diminta client.</li>
<li>400 (Bad Request) - Permintaan client gagal dijalankan karena proses validasi input dari client gagal.</li>
<li>401 (Unauthorized) - Permintaan client gagal dijalankan. Biasanya ini disebabkan karena pengguna belum melakukan proses autentikasi.</li>
<li>403 (Forbidden) - Permintaan client gagal dijalankan karena ia tidak memiliki hak akses ke resource yang diminta.</li>
<li>404 (Not Found) - Permintaan client gagal dijalankan karena resource yang diminta tidak ditemukan.</li>
<li>500 (Internal Server Error) -  Permintaan client gagal dijalankan karena server mengalami eror (membangkitkan Exception).</li></ol>

<p align="justify">Ketika permintaan client gagal dijalankan, kita harus mengembalikan status code yang sesuai dengan kesalahan yang terjadi. Penggunaan response code yang tepat dapat meminimalisir kebingungan client/user dalam memanfaatkan API.</br></br>
<b>URL Design</b></br>
URL, Path, atau Endpoint merupakan salah satu bagian terpenting yang harus diperhatikan ketika membangun REST API. Dengan merancang endpoint yang baik, penggunaan API akan lebih mudah dipahami. Dalam merancang endpoint, ikutilah aturan umum atau convention agar penggunaan API kita memiliki standar yang diharapkan oleh banyak developer. Lalu, seperti apa standar dalam merancang endpoint? </br></br>
<b>Gunakan Kata Sifat daripada Kata Kerja pada Endpoint Path</b></br>
Hindari penggunaan kata kerja dalam menetapkan nama endpoint (titik akhir path). Contohnya /getArticles atau /addArticles. Karena aksi dapat ditentukan secara jelas melalui HTTP Verb, kita tidak perlu lagi menambahkan kata kerja di endpoint. Dengan adanya HTTP verbs Anda cukup memberikan endpoint GET /articles untuk mendapatkan data artikel atau POST /articles untuk menambahkan artikel.</br></br>
<b>Gunakan Kata Jamak pada Endpoint untuk Resource Collection</b></br>
Selalu gunakan kata jamak (plural) saat memberikan nama endpoint. Ini karena jarang ada data yang hanya memiliki satu item. Dengan menggunakan kata jamak, kita menjadi konsisten dengan apa yang ada di database. Karena tabel pada database pun biasanya memiliki lebih dari satu record (data).</br></br>
Lalu, bagaimana bila ingin mengakses satu data saja? Contohnya mendapatkan satu artikel secara spesifik?</br></br>
Gunakan path parameter untuk mendapatkan data spesifik. Endpoint /articles/:id merupakan contoh yang baik untuk mendapatkan artikel secara spesifik berdasarkan id. Kita akan membahas dan menggunakan path parameter nanti ketika latihan membuat web server.</br></br>
<b>Gunakan Endpoint berantai untuk resource yang memiliki hirarki/relasi</b></br>
Endpoint dari resource yang memiliki hirarki/relasi sebaiknya dituliskan secara berantai. Contohnya untuk mendapatkan daftar komentar dari sebuah artikel, endpoint GET /articles/:id/comments merupakan contoh yang tepat.</br></br>
Penggunaan endpoint tersebut masuk akal karena untuk mendapatkan comments pada respons, kita perlu tahu komentar pada artikel mana yang akan ditampilkan. Prinsip ini juga memperjelas permintaan dari client hanya dengan melihat endpoint yang dituju,  daripada menggunakan endpoint GET /comments kemudian memberikan nilai id artikel pada request body.</br></br>
Tidak hanya GET, prinsip ini juga cocok diterapkan pada HTTP verb POST, PUT, maupun DELETE.</p>

<p align="justify"><b>Tools Belajar Dasar-Dasar Node.js untuk Back-End</b></br>
Modul kali ini memiliki prasyarat sebelum Anda mengikutinya. Selain kemampuan JavaScript, terdapat dua tools yang perlu Anda siapkan, yakni Text Editor dan Node.js. Bila Anda sudah mengikuti seluruh latihan pada kelas Belajar Dasar Pemrograman JavaScript, tools ini seharusnya sudah terpasang pada komputer Anda. Bila belum, silakan unduh dan pasang dulu yah.</br></br>
<b>Text Editor</b></br>
Selama mengikuti kelas ini, kami merekomendasikan Anda untuk menggunakan VSCode. Inilah text editor yang sangat populer dan gratis untuk digunakan. Selain itu, text editor ini memiliki plugin berlimpah yang dapat membuat fungsionalitas menjadi lebih kaya lagi. Visual Studio Code dapat dijalankan pada  sistem operasi Windows, macOS, ataupun Linux. Untuk mengunduhnya, silakan kunjungi laman unduh visual studio code.</br></br>
<b>Node.js</b></br>
Pastikan komputer Anda sudah terpasang Node.js, jika belum silakan simak tautan bagaimana cara memasang Node.js pada komputer Anda. Pastikan juga Node.js yang terinstal memiliki versi minimal 12 ke atas. Untuk mengetahui versi Node.js yang Anda pasang, silakan tuliskan perintah ini pada Terminal atau CMD.</br></br>

```plantuml
node -v
```

<p align="justify"><b>Apa itu Node.js</b></br></br>
Dari dulu hingga kini, browser menjadi tempat satu-satunya yang dapat mengeksekusi kode JavaScript. Karenanya, Web Developer perlu mempelajari bahasa pemrograman yang berbeda untuk mengembangkan aplikasi Front-End dan Back-End. Meskipun secanggih dan sekuat apa pun JavaScript berkembang, ia hanya akan digunakan di sisi Front-End saja.</br></br>
Sebenarnya banyak developer yang mencoba membuat teknologi agar JavaScript dapat dijalankan di luar browser. Namun belum ada yang berhasil. Hingga pada tahun 2009, Ryan Dahl berhasil menciptakan Node.js, teknologi yang diharapkan oleh banyak web developer. Tak disangka saat ini teknologi yang diciptakannya menuai popularitas tinggi. Node.js banyak digunakan oleh perusahaan besar sekelas Netflix, Uber, Paypal, dan eBay.  </br></br>
Node.js berhasil menjadi JavaScript Runtime yang dapat mengeksekusi kode JavaScript di luar browser. Node.js seolah-olah menjadi gerbang bagi para JavaScript Developer untuk mengembangkan sistem di luar dari browser. JavaScript menjadi bahasa multiplatform yang banyak menggiring developer untuk menggunakannya. Popularitas JavaScript pun meroket! Pada tahun 2014 hingga 2020 JavaScript menjadi bahasa pemrograman nomor satu yang banyak digunakan oleh developer.</br></br>
JavaScript menjadi salah satu pilihan tepat dalam membangun web server, terlebih bila Anda adalah seorang Front-End Web Developer. Anda tentu tidak perlu menggunakan bahasa yang berbeda dalam membangun Back-End. Anda bisa menjadi Full-Stack Developer dengan mempelajari satu bahasa pemrograman saja.</br></br>
<b>Node.js Basic</b></br>
Setelah mengenal Node.js kini saatnya kita belajar cara menggunakannya. Kita akan mulai dari membuat proyek Node.js, menjalankan kode JavaScript menggunakan Node.js, hingga mempelajari berbagai API yang ada di dalamnya. Jadi sekali lagi pastikan prasyarat yang ada sudah Anda penuhi yah. Siapkan Text Editor, dan kita akan mulai menuliskan kode JavaScript.</br></br>
<b>Membuat Proyek Node.js</b></br>
Sebelum membuat proyek, buatlah folder baru terlebih dahulu. Folder ini akan digunakan sebagai tempat penyimpanan berkas proyek dan JavaScript yang kita tulis nanti. Kami sarankan, Anda buat folder tersebut di alamat C -> javascript-projects -> nodejs-basic bagi pengguna Windows; home -> javascript-projects -> nodejs-basic bagi pengguna Linux atau macOS.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103072108289f5ecc28055c6260cdf366d0a046568a.png"></p>


<p align="justify"><b>Apa itu Web Framework?</b></br>
Web Framework adalah sebuah kerangka yang dapat membantu mempermudah pengembangan web termasuk dalam membuat web server. Dengan menggunakan framework, penulisan kode akan lebih terstruktur, mudah dipelihara, dan gampang dikembangkan.  </br></br>
Web Framework menyediakan sekumpulan tools dan library yang dapat menyederhanakan hal-hal yang sering dilakukan dalam pengembangan web, seperti pembuatan server, routing, menangani permintaan, interaksi dengan database, otorisasi, hingga meningkatkan ketahanan web dari serangan luar. </br></br>
<b>Expressjs</b> merupakan web framework tertua dan terpopuler di Node.js saat ini. Framework ini sangat ringan, mudah diintegrasikan dengan aplikasi web front-end, dan penulisan kodenya tidak jauh beda dengan Node.js native.  </br></br>
Namun karena sifat ringannya tersebut, ia menjadi framework yang unopinionated alias tidak memiliki aturan untuk menggunakannya. Express tidak menyediakan struktur atau kerangka kerja yang baku untuk diikuti oleh developer. Sehingga, developer menjadi sulit menentukan seperti apa kode yang optimal. </br></br>
Framework lainnya seperti Hapi menyediakan environment yang lengkap untuk mengembangkan web server yang kompleks. Bila menggunakan Hapi, kita tak perlu tools lain untuk menerapkan layer authentication, tokenize, cors, dan lain sebagainya. </br></br>
Kelemahan Hapi adalah abstraksinya yang terlalu jauh dari Node.js native. Kita perlu belajar secara dalam, untuk menguasai framework ini. Penggunaan framework menjadi pilihan personal. Salah satu faktornya adalah kasus yang hendak Anda hadapi. Ketika ingin membangun server yang sederhana, katakanlah untuk mendukung aplikasi front-end di-render di sisi server, express adalah pilihan yang tepat. </br></br>
Namun, bila Anda ingin membangun web server yang kompleks tanpa membutuhkan effort yang besar, Hapi adalah pilihan yang tepat. Kita akan membangun web server dengan arsitektur REST yang kompleks ke depannya. Agar Anda selalu “Hapi” ketika mengikuti alur belajar, kita akan gunakan Hapi dalam membangun web server.
</br></br>Ketahuilah bahwa Hapi memiliki environment yang cukup luas. Kelas ini tidak akan mengajarkan secara dalam tentang API yang ada di Hapi, melainkan hanya fitur-fitur yang menjadi dasar pembuatan REST API. Jadi, bila Anda ingin mendalami terkait framework Hapi, sempatkan waktu untuk eksplorasi di dokumentasi Hapi yang disediakan yah. </br></br>
<b>Membangun Web Server menggunakan Hapi</b></br></br>
<b>Menyiapkan Project</b></br></br>
Mari kita awali dengan membuat proyek baru. Silakan buat folder di C -> javascript-projects (Windows) atau home -> javascript-projects (Linux dan macOS) dengan nama “hapi-web-server”.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/2021030808581482aa4f57ef392e47c0f741c117c79558.png"></p>
 <p align="justify"> Buka folder menggunakan VSCode, kemudian inisialisasi proyek pada Terminal dengan menggunakan perintah:</p>
 
```plantuml
npm init --y
```

<p align="justify">Lanjut, kita atur NPM runner pada package.json menjadi seperti ini:</p>

```plantuml
"scripts": {
   "start": "node server.js"
},
```

<p align="justify">Lalu, buatlah berkas JavaScript baru dengan nama server.js. Kemudian, tuliskan kode berikut:</p>
server.js

```plantuml
console.log('Halo, kita akan belajar membuat server menggunakan Hapi');
```

<p align="justify">Simpan perubahan pada berkas server.js dan coba jalankan perintah berikut pada Terminal:</p>

```plantuml
npm run start
```

<p align="justify">Bila Anda melihat pesan “Halo, kita akan belajar membuat server menggunakan Hapi”, maka proyek telah siap digunakan.
</p>

<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103080900413ad7b514c3d8e08284204e68ef0b8521.png"></p>

<p align="justify"><b>Node.js Basic</b></br>
Setelah mengenal Node.js kini saatnya kita belajar cara menggunakannya. Kita akan mulai dari membuat proyek Node.js, menjalankan kode JavaScript menggunakan Node.js, hingga mempelajari berbagai API yang ada di dalamnya. Jadi sekali lagi pastikan prasyarat yang ada sudah Anda penuhi yah. Siapkan Text Editor, dan kita akan mulai menuliskan kode JavaScript.</br></br>
Membuat Proyek Node.js</br>
Sebelum membuat proyek, buatlah folder baru terlebih dahulu. Folder ini akan digunakan sebagai tempat penyimpanan berkas proyek dan JavaScript yang kita tulis nanti. Kami sarankan, Anda buat folder tersebut di alamat C -> javascript-projects -> nodejs-basic bagi pengguna Windows; home -> javascript-projects -> nodejs-basic bagi pengguna Linux atau macOS.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103072108289f5ecc28055c6260cdf366d0a046568a.png"></p>
<p align="justify">Selanjutnya, buka folder nodejs-basic menggunakan VSCode. Caranya, pada Visual Studio Code pilih menu File -> Open Folder -> [pilih foldernya]. Folder pun berhasil terbuka melalui VSCode.</p>

<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307210936b0b8bcc6a21cefcba8c016c32a0d21bb.png"></p>
<p align="justify">Untuk membuat proyek JavaScript, silakan buka Terminal pada VSCode. Pilih menu Terminal -> New Terminal, kemudian tuliskan perintah:</p>

```plantuml
npm init
```

<p align="justify">NPM alias Node Package Manager merupakan JavaScript Package Manager bawaan dari Node.js. Melalui NPM ini kita dapat membuat Node.js package (proyek) dan mengelola penggunaan package eksternal yang digunakan. Kita akan membahas NPM lebih detail nanti. Jika Anda yang tidak menggunakan Visual Studio Code, gunakan Terminal/Command Prompt usungan OS Anda. Namun, sesuaikan lokasinya pada folder proyek ya. Setelah menuliskan perintah di atas, Anda akan diberikan beberapa pertanyaan untuk mengisi nilai package name, version, description. Semua itu merupakan informasi dasar dari aplikasi yang Anda buat.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307211050feace6bbb9a457c79f2976711cf6b5a3.png"></p>

<p align="justify">Nilai yang berada di dalam tanda kurung merupakan nilai default. Anda dapat menggunakan nilainya dengan langsung menekan tombol Enter. Untuk saat ini, cukup berikan semua pertanyaan dengan nilai default.Setelah mengisi seluruh pertanyaan yang diberikan, Anda akan diberitahu untuk melihat hasil akhir yang dibuat pada berkas package.json.</p>

<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/2021030721113864ddc9dcc8f83976e0d1ba9b79d3854d.png"></p>

<p align="justify">Jika nilai yang ditampilkan sudah sesuai, langsung saja tekan tombol Enter. Berkas package.json pun telah berhasil dibuat pada proyek kita.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/2021030721120884038d77d87e77f08344d51993a98e90.png"></p>
<p align="justify">Voila! Anda berhasil membuat proyek Node.js.</p>

<p align="justify"><b>Menjalankan JavaScript Menggunakan Node.js</b></br>
Terdapat dua cara dalam menjalankan kode JavaScript menggunakan Node.js. Yang pertama dengan memanfaatkan Node REPL dan yang kedua dengan mengeksekusi berkas berekstensi JS. Mari kita kupas keduanya!</br></br>
The Node.js REPL</br>
Node.js memiliki fitur REPL atau Read-Eval-Print Loop. Sesuai namanya, fitur ini berfungsi untuk membaca kode JavaScript, mengevaluasi kode tersebut, kemudian mencetak hasil evaluasinya ke console. Nah, untuk loop, berarti proses tersebut selalu berulang.</br></br>
REPL merupakan fitur bawaan dari Node.js. Anda bisa mengaksesnya menggunakan perintah node pada Terminal. </p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307211701bc3951a9a61b134c80f92c85c905c8a5.png"></p>
<p align="justify">Tanda > pada Terminal menunjukan Anda sudah masuk ke mode Node REPL. Sekarang, Anda bisa menuliskan kode JavaScript dan mengeksekusinya dengan menggunakan enter.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103072117272306a7ec5f5d9d801b682acfc9975cc2.png"></p>

<p align="justify">Lihat gambar di atas. Ketika mengeksekusi console.log(‘Hello NodeJS REPL’), selain pesan “Hello NodeJS REPL”, nilai undefined juga tercetak. Hal tersebut karena REPL selalu menampilkan nilai evaluasi pada console. Karena method console.log() tidak mengembalikan nilai, jadi undefined-lah yang tercetak pada console. Untuk membuktikan hal itu, cobalah Anda tuliskan statement yang mengembalikan nilai. Contoh sederhananya 2+2. Maka nilai 4 akan tercetak pada console.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103072118187da7efed07238b8aa0e59fd1118ebfd9.png"></p>
<p align="justify">Cukup asik kan fitur REPL? Tapi kok terkesan hanya dapat mengeksekusi kode satu baris saja ya? Bila Anda beranggapan seperti itu, sebenarnya tidak tepat karena di dalam REPL terdapat mode editor yang berfungsi untuk menuliskan kode JavaScript lebih dari satu baris. Untuk menggunakan mode editor, Anda bisa tuliskan perintah .editor.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307211914160c477c2db7c2fca5d068bf69fcf2ea.png"></p>
<p align="justify">Ketika masuk ke mode editor, Anda bisa secara leluasa menuliskan kode JavaScript lebih dari satu baris menggunakan enter. Fungsi untuk mengeksekusi kode digantikan dengan kombinasi tombol CTRL+D. Untuk keluar dari mode editor, gunakan kombinasi CTRL+C.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307211945e8145bbb3a6045823053151cabe80c4b.png"></p>
<p align="justify">Nilai variabel yang Anda buat di REPL dapat diakses selama Anda masih berada di dalam REPL. Jika Anda menutup Terminal atau keluar dari REPL menggunakan perintah .exit, variabel yang sudah Anda buat sebelumnya tidak bisa diakses kembali. Itu artinya, REPL hanya menyimpan memory ketika session masih berlangsung.</br></br>
Fitur REPL sangat berguna ketika Anda hendak melakukan kalkulasi sederhana, bereksperimen, atau belajar potongan kode JavaScript. Karena melalui REPL Anda bisa mengeksekusi kode JavaScript dan mendapatkan hasil dengan cepat tanpa harus membuat berkas JavaScript terlebih dahulu.</br></br>
Running JavaScript File using Node.js</br>
Cara lain untuk mengeksekusi kode JavaScript menggunakan Node.js adalah melalui berkas JS. Silakan buat berkas JavaScript pada proyek nodejs-basic. Gunakan VSCode agar lebih mudah yah.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307212030f5a4999b60aace8990751fe742db8abc.png"></p>
<p align="justify">Buatlah berkas JavaScript dengan nama “index.js”.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/20210307212047235f4350207e571d984a344c43c1d76a.png"></p>
<p align="justify">Di dalam berkas index.js, Anda bisa menuliskan kode JavaScript sesuka Anda. Pastikan kode yang Anda tulis menampilkan nilai di console yah, jadi Anda bisa melihat nilai yang tampak pada console. Jika bingung, silakan tuliskan saja kode berikut.</p>

index.js

```plantuml
const message = (name) => {
   console.log(`Hello ${name}`);
}
 
message('JavaScript');
```

<p align="justify">Untuk mengeksekusi kode tersebut, silakan buka kembali Terminal. Kemudian, tuliskan perintah:</p>

```plantuml
node index.js 
```

<p align="justify">Node.js pun akan mengeksekusi berkas ‘index.js’. Bila Anda menuliskan kode seperti yang dicontohkan di atas, maka akan muncul teks ‘Hello JavaScript’ pada console.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103072122113b419a5e06a8fa864c9f0d5db55591c0.png"></p>
<p align="justify">Node.js Global Object</br>
JavaScript hanyalah bahasa pemrograman. Ia tidak mengetahui apakah Anda menjalankannya menggunakan browser atau Node.js. Di browser, JavaScript dapat mengontrol fungsionalitas browser seperti mengunjungi halaman, memuat ulang, menutup tabs, serta menampilkan alert dialog. JavaScript mampu melakukan itu karena browser menambahkan objek window pada JavaScript.</br></br>
Di Node.js pun demikian, ia menambahkan objek global guna memberikan fungsionalitas lebih pada JavaScript. Hal ini bertujuan untuk mendukung pengembangan pada environment-nya. Contoh, melalui objek global kita dapat melihat berapa CPU yang digunakan pada komputer, modularisasi berkas JavaScript, menampilkan nilai pada console, dan hal lainnya.</br></br>
Objek window pada browser dan objek global pada Node.js merupakan Global Object. Seluruh fungsi atau properti yang menjadi member dari global object dapat diakses di mana saja alias memiliki cakupan global. Pada Node.js Anda bisa melihat apa saja yang termasuk member dari global objek dengan menggunakan kode berikut:</p>

```plantuml
Object.getOwnPropertyNames(global);
```

<p align="justify">Coba jalankan pada REPL. Ia akan mengembalikan semua member-nya.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Membuat-Aplikasi-Back-End-untuk-Pemula/blob/main/202103072125327328c5e8400805e3501eafb2ed05c284.png"></p>
<p align="justify">
Banyak sekali yah member dari global objek. Namun dilansir dari website Node.js, sebenarnya mereka hanya menambahkan beberapa objek saja. Objek tersebut dinamakan dengan ‘true globals’. </br></br>
Berikut adalah daftarnya:</p>
<ol align="justify"><li>global : Global namespace. Member apa pun di dalam object ini dapat diakses pada cakupan global.</li>
<li>process : menyediakan interaksi dengan proses Node.js yang berjalan.</li>
<li>console : menyediakan berbagai fungsionalitas STDIO.</li>
<li>setTimeout, clearTimeout, setInterval, clearInterval.</ol>
<p align="justify">Ada juga objek yang merupakan ‘pseudo-globals’ atau objek global semu. Objek ini tidak terlihat bila dicetak menggunakan Object.getOwnPropertyName(global) sebab ia bukan member langsung dari objek global, melainkan diturunkan dari cakupan module. Karena pada Node.js semua berkas JavaScript adalah module [3], jadi pseudo-globals dapat diakses layaknya global objek.</br></br>
Berikut adalah daftarnya:</p><ol align="justify"><li>
module : digunakan untuk sistem modularisasi pada Node.js.</li>
<li>__filename : keyword untuk mendapatkan lokasi berkas JavaScript yang dieksekusi. Keyword ini tidak tersedia pada Node.js REPL.</li>
<li>__dirname : keyword untuk mendapatkan root directory dari berkas JavaScript yang dieksekusi.</li>
<li>require : digunakan untuk mengimpor module JavaScript.</li></ol>
