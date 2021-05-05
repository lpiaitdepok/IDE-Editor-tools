# Saran pengaturan VSCode Todo Tree
https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree

* Buka Visual Studio Code
* Tekan “Ctrl+Shift+P” dan ketik “settings”.
* klik di "Preferences: Open Default Settings (JSON)"
* Cari pengaturan seperti di bawah ini:
```
todo-tree.tree.scanMode (workspace)
```
* Atur menjadi semua file yang terbuka (open files) atau hanya file yang aktif sekarang (current file). Jika tetap menggunakan (workspace) dapat memperlambat kinerja atau menyebabkan komputer hang dan cepat rusak.

**Catatan**:
* Daftar todo ada di Explorer bar sebelah kiri.
* Ingat! pastikan tidak ada task berat lain yang sedang bekerja atau ada window-window lain yang masih terbuka saat akan menampilkan todo.

# Saran pengaturan VSCode TODO Highlight
https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight

* Buka Visual Studio Code
* Tekan “Ctrl+Shift+P” dan ketik “settings”.
* klik di "Preferences: Open Default Settings (JSON)"
* Cari pengaturan seperti di bawah ini:
```
todohighlight.include	array	[
"**/*.js",
"**/*.jsx",
"**/*.ts",
"**/*.tsx",
"**/*.html",
"**/*.php",
"**/*.css",
"**/*.scss"
]
```
* Tambahkan extensi file **HANYA SESUAI KEBUTUHAN** 
contoh: "**/*.java"
Menjadi
```
todohighlight.include	array	[
"**/*.js",
"**/*.jsx",
"**/*.ts",
"**/*.tsx",
"**/*.html",
"**/*.php",
"**/*.css",
"**/*.scss", 
"**/*.java"
]
```

**Catatan:**
* Jika ingin bekerja menggunakan Visual Studio Code dengan extensi VSCode TODO Highlight, **JANGAN GUNAKAN** {**/*.*} karena akan memperlambat kinerja dan menyebabkan komputer hang dan cepat rusak.
* Daftar todo ada di Explorer bar sebelah kiri
* Ingat! pastikan tidak ada task berat lain yang sedang bekerja atau ada window-window lain yang masih terbuka saat akan menampilkan todo.

Referensi:
https://marketplace.visualstudio.com/
https://github.com/
