# Tes-fornt-end-Develop
# Hi pekenalkan saya Sendi Umbu Danga Elu

Currently working with Robotic Process Automation, but I love learn new thing in programming such as Javascript, Swift, Python.  

### Tools:
<p>
    <img src="https://img.shields.io/badge/OS-MacOS-blue?&logo=apple" />
    <img src="https://img.shields.io/badge/Code-Swift-blue?&logo=swift" />
    <img src="https://img.shields.io/badge/IDE-Xcode-blue?&logo=xcode" />
    <img src="https://img.shields.io/badge/Text%20Editor-Visual%20Studio%20Code-blue?&logo=visual%20studio%20code&logoColor=blue" />
   
</p>

### Stats:
<details>
 <summary><strong>hari saya akan mengerjakan tes logika yang merupakan persyaratan magang di finplan</strong></summary>
    <summary><strong>Buat fungsi dengan menampilkan bilangan cacah kelipatan 3 atau 7 sebanyak N, serta menampilkan huruf Z saat bilangan tersebut kelipatan 3 dan 7.
  Contoh :
  N = 13
  Output : 3, 6, 7, 9, 12, 14, 15, 18, Z, 24, 27, 28, 30 </strong></summary>
    - 🔭 jawaban : 
    Berikut adalah penjelasan singkat dari coding tersebut:
    1 Fungsi generate_numbers memiliki satu parameter input, yaitu N.
    2 Pada awalnya, dibuat sebuah list kosong dengan nama numbers untuk menyimpan hasil bilangan cacah.
    3 Dilakukan perulangan menggunakan for dari 1 hingga N+1.
    4 Di dalam perulangan, dilakukan pengecekan kondisi untuk setiap bilangan
    5 Jika bilangan tersebut kelipatan 3 dan 7 (habis dibagi 3 dan 7), maka 'Z' akan ditambahkan ke dalam list numbers.
    6 Jika bilangan tersebut hanya kelipatan 3 atau 7 (habis dibagi 3 atau 7), maka bilangan itu sendiri akan ditambahkan ke dalam list numbers.
    7 Setelah semua bilangan diperiksa, list numbers yang berisi bilangan cacah dan 'Z' (sesuai dengan kondisi) dikembalikan sebagai output dari fungsi.
    8 Dilakukan penggunaan fungsi dengan contoh penggunaan di mana N = 13.
    9 Output dari fungsi generate_numbers akan ditampilkan.
  <img src= "Tes Logika Front end Develop/menampilkan bilangan cacah.jpg"</br>
    <summary><strong>Buat fungsi pencarian ‘sang gajah’, ‘serigala’, ‘harimau’.
        Dengan contoh masukan dan keluaran sebagai berikut :
        Input	: Berikut adalah kisah sang gajah. Sang gajah memiliki teman serigala bernama DoeSang. Gajah sering dibela oleh serigala ketika harimau mendekati gajah.
        Output	: sang gajah - sang gajah - serigala - serigala - harimau </strong></summary>
    - 🌱 jawaban : Berikut adalah penjelasan singkat dari coding tersebut:
    Fungsi cari_kata memiliki satu parameter input, yaitu teks yang merupakan teks yang akan diperiksa,
    Pada awalnya, dibuat sebuah list kata_kunci yang berisi kata-kata kunci yang akan dicari dalam teks,
    Selanjutnya, dibuat list kosong hasil yang akan digunakan untuk menyimpan hasil pencarian kata-kata kunci,
    Dilakukan perulangan menggunakan for untuk setiap kata kunci dalam kata_kunci,
    Di dalam perulangan, dilakukan pencarian jumlah kemunculan kata kunci dalam teks menggunakan fungsi count(),
    Jika ditemukan kemunculan kata kunci, kata kunci tersebut akan ditambahkan sebanyak jumlah kemunculannya ke dalam list hasil menggunakan metode extend(),
    Setelah semua kata kunci diperiksa, list hasil diubah menjadi string dengan menggunakan metode ' - '.join(hasil), yang memisahkan setiap elemen dalam list dengan tanda "-",
    Hasil yang telah diubah menjadi string tersebut dikembalikan sebagai output dari fungsi,
    Dilakukan penggunaan fungsi dengan contoh penggunaan di mana teks adalah teks yang diberikan,
    Output dari fungsi cari_kata akan ditampilkan. 
    <img src= "Tes Logika Front end Develop/menampilkan huruf.jpg"</br>
    <summary><strong>Buatlah fungsi pengecekan kata sandi, dengan ketentuan sebagai 
        Kata sandi minimal 8 karakter
        Kata sandi maksimal 32 karakter
        Karakter awal tidak boleh angka
        Harus memiliki angka
        Harus memiliki huruf kapital dan huruf kecil </strong></summary>
    - 👯 Jawaban: Berikut adalah penjelasan singkat dari coding tersebut:
    Fungsi cek_kata_sandi memiliki satu parameter input, yaitu kata_sandi yang merupakan kata sandi yang akan diperiksa.
    Pertama, dilakukan pengecekan panjang kata sandi menggunakan len(kata_sandi). Jika panjang kata sandi kurang dari 8 karakter atau lebih dari 32 karakter, fungsi akan
    mengembalikan pesan "Kata sandi harus terdiri dari 8 hingga 32 karakter."
    Selanjutnya, dilakukan pengecekan karakter awal kata sandi menggunakan kata_sandi[0].isdigit(). Jika karakter awal adalah angka, fungsi akan mengembalikan pesan "Karakter awal tidak boleh angka."
    Dilakukan pengecekan apakah kata sandi mengandung angka menggunakan any(char.isdigit() for char in kata_sandi). Jika tidak terdapat angka dalam kata sandi, fungsi akan
    mengembalikan pesan "Kata sandi harus memiliki angka."
    Dilakukan pengecekan apakah kata sandi memiliki kombinasi huruf kapital dan huruf kecil menggunakan any(char.isupper() for char in kata_sandi) dan any(char.islower()
    for char in kata_sandi). Jika tidak terdapat huruf kapital atau huruf kecil, fungsi akan mengembalikan pesan "Kata sandi harus memiliki huruf kapital dan huruf kecil."
    Jika semua pengecekan di atas berhasil, fungsi akan mengembalikan pesan "Kata sandi valid."
    Dilakukan penggunaan fungsi dengan contoh penggunaan di mana kata_sandi1, kata_sandi2, dan kata_sandi3 adalah kata sandi yang diberikan.
    Output dari fungsi cek_kata_sandi akan ditampilkan.
   <img src= "Tes Logika Front end Develop/mengecek kata sandi.jpg"</br>
    <summary><strong>Buat fungsi pengecekan bilangan cacah terkecil yang tidak ada dari data yang diinputkan. Dengan contoh input dan output</strong></summary>
    - 🤔 jawaban: Berikut adalah penjelasan singkat dari coding tersebut:
    Fungsi cek_bilangan_terkecil memiliki satu parameter input, yaitu data yang merupakan list bilangan cacah.
    Pertama, list data diubah menjadi sebuah set menggunakan data_set = set(data). Set digunakan untuk memudahkan pencarian elemen yang ada dalam list.
    Selanjutnya, variabel i diinisialisasi dengan nilai 1.
    Dilakukan perulangan menggunakan while True untuk mencari bilangan cacah terkecil yang tidak ada dalam set data_set.
    Pada setiap iterasi, dilakukan pengecekan apakah bilangan i tidak ada dalam data_set menggunakan i not in data_set. Jika tidak ada, maka bilangan i merupakan bilangan
    cacah terkecil yang tidak ada dalam data, dan fungsi akan mengembalikan nilai i.
    Jika bilangan i ada dalam data_set, maka nilai i akan ditambahkan dengan 1 menggunakan i += 1 dan perulangan akan dilanjutkan.
    Dilakukan penggunaan fungsi dengan contoh penggunaan di mana data1, data2, dan data3 adalah list bilangan cacah yang diberikan.
    Output dari fungsi cek_bilangan_terkecil akan ditampilkan.
    <img src= "Tes Logika Front end Develop/mengecek bilangan cacah.jpg"</br>
    <summary><strong>Buat pola berikut sesuai inputan N, dengan N adalah bilangan ganjil</strong></summary>
    - 💬 Jawaban: Berikut adalah penjelasan singkat dari coding tersebut:
    Fungsi generate_pattern memiliki satu parameter input, yaitu N yang merupakan bilangan ganjil.
    Pertama, dilakukan pengecekan apakah N merupakan bilangan genap menggunakan if N % 2 == 0. Jika N adalah bilangan genap, maka fungsi akan mengembalikan pesan "Harus bilangan ganjil".
    Selanjutnya, dibuat sebuah list kosong bernama pattern yang akan menyimpan pola.
    Dilakukan perulangan dengan for i in range(N) untuk membentuk baris-baris pada pola.
    Pada setiap iterasi, dibuat sebuah variabel row yang awalnya berisi string kosong.
    Dilakukan perulangan lagi dengan for j in range(N) untuk membentuk karakter-karakter dalam satu baris pada pola.
    Pada setiap iterasi dalam perulangan j, dilakukan pengecekan apakah posisi (i, j) berada pada diagonal utama (i == j) atau diagonal sebaliknya (i == N - j - 1). Jika iya, maka karakter pada posisi tersebut adalah "X", jika tidak, maka karakternya adalah "O".
    Setelah selesai membentuk satu baris, baris tersebut ditambahkan ke dalam list pattern.
    Dilakukan penggabungan seluruh baris pada pola dengan menggunakan "\n".join(pattern) untuk menghasilkan output dalam bentuk tabel.
    Output pola yang dihasilkan akan dikembalikan oleh fungsi.
    Dilakukan penggunaan fungsi dengan contoh penggunaan di mana N1, N2, N3, dan N4 adalah bilangan ganjil yang diberikan.
    Output dari fungsi generate_pattern akan ditampilkan dalam bentuk tabel.
    <img src= "Tes Logika Front end Develop/Imputan N dengan N.jpg"</br>
</details>
<p>
    <img src="https://github-readme-stats.vercel.app/api?username=bagusfe&hide=contribs,prs&show_icons=true&hide_border=true&title_color=000" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bagusfe&layout=compact" height=180 />
</p>
