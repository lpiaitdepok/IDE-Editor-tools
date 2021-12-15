# Cara Compile dan Run Program Java dengan Visual Studio Code

 1. Download dan Install VS Code.
 2. buka program VS Code tersebut kemudian ketikkan program di bawah ini. Lalu save dengan nama halo.java, pada tutorial ini saya menyimpannya pada direktori D:\Belajar Java.
 
## Menggunakan Shortcut CMD
 3. Pada tampilan utama VS Code, tekan tombol F1 atau Ctrl + Shift + P secara bersamaan untuk membuka command palette.
 4. Lalu kalian ketik command dan pilih Open New Command Prompt atau Open New External Terminal untuk membuka cmd yang secara default terbuka pada direktori aktif file Java kalian. Atau, kalian juga bisa menggunakan shortcut Ctrl + Shift + C, dan cmd pun akan langsung terbuka.
## Menggunakan Integrated Terminal
Hampir sama dengan cara sebelumnya, kalian juga bisa menggunakan integrated terminal untuk melakukan command-command yang digunakan di cmd, seperti cd untuk pindah direktori, javac untuk compile dan java untuk run.

5. Caranya cukup tekan tombol Ctrl + ` (backtick), 
6. dan integrated terminal sudah muncul pada bagian bawah VS Code kalian. (note: Tombol backtick berada di sebelah kiri angka 1)
## Menggunakan Extensions Java Debug
Dari 2 cara sebelumnya yang sudah saya jelaskan, ini adalah salah satu cara yang menurut saya sangat mudah. Tetapi sebelum itu, kalian harus menginstall extensions tambahan terlebih dahulu.
1. Caranya cukup mudah, tekan tombol Ctrl + P,
2. kemudian ketik ext install java-debug, lalu enter. Setelah itu, pada sidebar sebelah kiri kalian akan terdapat beberapa pilihan yang tersedia di VS Code marketplace, pilih Java Debug yang di publish oleh DSnake (lihat detail), lalu klik install. Tunggu beberapa saat, klik enable dan restart VS Code kalian.

Untuk menggunakan extensions tersebut caranya cukup mudah, berikut 3 perintah utama yang dapat digunakan:
 1. Ctrl + Shift + U = untuk menampilkan bagian output.
 2. Alt + C = Shortcut untuk compile (sama seperti perintah javac)
 3. Alt + R = Shortcut untuk run (sama seperti perintah java)
## Menggunakan Extensions Code Runner
Ini merupakan salah satu extensions yang tidak hanya dapat digunakan untuk bahasa pemrograman Java saja, melainkan juga beberapa bahasa pemrograman lain seperti C, C++, JavaScript, Python, dan lain sebagainya. Ini juga merupakan salah satu cara yang sangat mudah dari beberapa cara yang sudah dijelaskan sebelumnya. Untuk menggunakan cara ini sangatlah mudah. 
1. Caranya tekan tombol Ctrl + P, 
2. kemudian ketik ext install code-runner, lalu enter.
3. Pilih Code Runner yang di publish oleh Jun Han (lihat detail), kemudian klik Install dan aktifkan.

Terdapat 3 cara untuk menggunakan extensions ini.
- Pertama, buka command palette dengan menekan tombol F1 atau Ctrl +
   Shift + P. Kemudian ketik run code, lalu enter.
- Kedua, gunakan shortcut Ctrl + Alt + N.
- Ketiga, tekan tombol segitiga dekat tab file pada masing-masing editor group di sisi kanan.
- Dan yang terakhir, cukup klik kanan pada workspace kalian, dan pilih Run Code.

### Catatan:
CodeRunner tidak mendukung java package?
