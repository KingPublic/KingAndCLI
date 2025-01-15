# KingAndCLI
 
# Reimplementasi CLI Linux di Python

Selamat datang di Custom Python Command Line Interface (CLI)! CLI ini dirancang untuk mensimulasikan perintah dasar sistem file serta fitur menyenangkan untuk menampilkan seni ASCII karakter anime secara acak. Anda dapat berinteraksi dengan CLI ini menggunakan perintah seperti `ls`, `pwd`, `cd`, dan lainnya, layaknya terminal asli!

## Fitur

- **Seni ASCII**: Menampilkan seni ASCII selamat datang dan keluar serta karakter anime acak.
- **Perintah Sistem File Dasar**: Mensimulasikan operasi sistem file seperti `ls`, `pwd`, `cd`, `mkdir`, `rmdir`, `touch`, dan `rm`.
- **Perintah Kustom**: Termasuk perintah `random_anime` untuk menampilkan seni ASCII karakter anime binatang secara acak.
- **Perintah Bantuan**: Menampilkan semua perintah yang tersedia dan cara penggunaannya.

## Instalasi

### Persyaratan

Proyek ini membutuhkan Python 3.6+.

Untuk menjalankan CLI ini, Anda tidak memerlukan pustaka tambahan—hanya pustaka standar Python yang sudah ada.

### Cara Menjalankan

1. Clone repositori ini atau salin skripnya.
2. Jalankan skrip Python dengan perintah berikut:

   ```bash
   KingCLI.py
   ```

3. CLI akan dimulai dan menampilkan seni ASCII selamat datang.

## Perintah yang Tersedia (tidak semua ada disini - > check help untuk melihat semua)

Berikut adalah perintah-perintah yang dapat Anda gunakan dalam CLI:

### `help`
- **Deskripsi**: Menampilkan daftar perintah yang tersedia beserta cara penggunaannya.
- **Contoh**:
  ```bash
  >>> help
  ```

### `ls`
- **Deskripsi**: Menampilkan daftar file dan direktori di direktori saat ini (simulasi).
- **Contoh**:
  ```bash
  >>> ls
  ```

### `pwd`
- **Deskripsi**: Menampilkan direktori kerja saat ini (simulasi).
- **Contoh**:
  ```bash
  >>> pwd
  ```

### `cd <path>`
- **Deskripsi**: Mengubah direktori saat ini ke direktori `<path>` yang ditentukan (simulasi).
- **Contoh**:
  ```bash
  >>> cd /home/user/Documents
  ```

### `mkdir <name>`
- **Deskripsi**: Membuat direktori baru dengan nama `<name>` yang ditentukan (simulasi).
- **Contoh**:
  ```bash
  >>> mkdir new_folder
  ```

### `rmdir <name>`
- **Deskripsi**: Menghapus direktori dengan nama `<name>` yang ditentukan (simulasi).
- **Contoh**:
  ```bash
  >>> rmdir old_folder
  ```

### `touch <file>`
- **Deskripsi**: Membuat file baru dengan nama `<file>` yang ditentukan (simulasi).
- **Contoh**:
  ```bash
  >>> touch newfile.txt
  ```

### `rm <file>`
- **Deskripsi**: Menghapus file yang ditentukan `<file>` (simulasi).
- **Contoh**:
  ```bash
  >>> rm oldfile.txt
  ```

### `random_anime`
- **Deskripsi**: Menampilkan seni ASCII karakter anime binatang secara acak (seperti kelinci, kucing, atau anjing).
- **Contoh**:
  ```bash
  >>> random_anime
  ```

### `clear`
- **Deskripsi**: Menghapus tampilan terminal (simulasi).
- **Contoh**:
  ```bash
  >>> clear
  ```

### `exit`
- **Deskripsi**: Keluar dari CLI dan menampilkan seni ASCII keluar.
- **Contoh**:
  ```bash
  >>> exit
  ```

## Contoh Penggunaan

Berikut adalah contoh sesi penggunaan CLI:

```bash
>>> help
Daftar perintah:
def help():
    print("""
Available commands:
- ls: List files and directories
- pwd: Print current directory
- cd <path>: Change directory
- mkdir <name>: Create a directory
- rmdir <name>: Remove a directory (if empty)
- touch <file>: Create an empty file
- rm <file>: Remove a file
- cp <source> <destination>: Copy a file
- mv <source> <destination>: Move or rename a file/directory
- clear: Clear the terminal
- exit: Exit the CLI
- log <command>: Save command history to a log file
- joke: Display a random joke
- search <pattern>: Search for files/directories by name
- find_large <size>: Display files larger than the specified size (in bytes)
    """)


>>> random_anime
  ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣬
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠿⠿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠈⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣆⡐⠲⣤⣤⣄⣈⠉⠛⠿⣿⣿⣿⣿⣿⢸⣦⣌⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣄⠘⢿⣿⣿⣿⣿⣶⣦⣈⠙⢿⡟⢸⣿⣿⣧⡈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⠿⠿⠿⠿⠟⠛⠛⠿⠛⠛⠛⠿⠿⣷⡌⠻⣿⣿⣿⣿⣿⣿⣿⣦⡅⢻⣿⣿⣿⣗⠀⠹⣿⣿⣿⠋⢿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣶⣄⠀⠲⣶⣶⣿⣿⣿⣿⣿⣿⣿⣷⣶⣮⣄⣙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡄⢻⠟⢁⣆⠈⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣷⣤⡈⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣤⣴⣿⣿⠀⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣄⠈⠛⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠹⣿⣿⣿⣿⠀⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡿⠿⢛⣋⣥⣴⣶⣷⣿⣿⣿⣿⣿⣟⣛⣛⠿⣷⠘⣷⣮⣝⡛⢿⣿⣿⣿⣿⣿⡿⢃⣦⢹⣿⣿⣿⢰⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣭⣤⣈⡉⠩⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡈⣿⣿⣿⣿⣦⡙⣿⣿⣿⡟⣡⣿⣿⢸⣿⣿⣿⢘⣋⣩⣭⡵⢞⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⡿⠁⠀⠈⣹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⣿⣿⡟⣸⣿⣿⣿⣿⣿⠟⢁⣴⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⠟⠀⠀⣠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠟⠛⠋⠉⠀⠀⠀⠀⠀⠈⠙⠻⠳⣿⣿⣿⣿⡿⢋⣴⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡟⠁⠀⣠⠾⢻⣿⣿⣿⣿⣿⣿⣿⣿⡿⠟⠛⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠙⠛⢠⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⠏⠀⣀⣭⢆⡴⣿⣿⣿⣿⡿⠿⠛⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⢀⠀⠀⠀⠀⠀⠀⢿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣥⣶⣿⡿⠋⠀⣼⡿⠟⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠴⢟⡓⠂⠀⠈⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣥⡾⠘⠋⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡿⢁⣴⣿⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠰⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⠀⠀⠀⠀⠀⠀⠀⢀⣠⠄⢀⢻⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣀⣴⣶⣤⣀⣤⣤⣤⣤⣀⣀⣀⣀⣀⡀⠀⠀⣠⣴⣶⣦⣤⣀⣀⣤⣴⣶⣾⣿⣟⠠⡟⢸⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢀⣯⣴⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠿⠛⠛⠛⣿⣿⣿⣿⣿⣿⣿⣿⣷⢠⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠸⣿⣿⣧⢀⣿⣿⣿⣿⣿⣿⣿⣿⡟⠀⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣌⣉⣉⣩⡙⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠹⡿⠁⣼⣿⣿⣿⣿⣿⣿⣿⡟⢀⣼⣿⣿⣿⣿⣿⣿⣿
⠀⠈⠙⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣍⡛⠿⣿⠿⠿⠿⠿⠿⣛⢛⡓⢀⠚⠛⣛⣛⣋⢉⣉⣉⠉⢀⣛⠻⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠋⣩⣥⣴⣶⠖⣈⣿⣿⣿⢟⣡⠾⢡⡏⣴⡿⠟⣫⣴⡯⢕⣠⣶⢛⣿⢸⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⣿⣿⣿⣿⣿⣿⠀⣿⡟⡫⠀⣛⣵⡾⢛⣵⢟⣡⡎⣼⠘⣫⣴⡿⢟⣩⣶⠟⡫⢑⣥⠎⣸⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠙⣿⣿⣿⣿⣿⣿⣿⣦⠉⢫⡶⢋⡵⣫⡶⣋⠔⣫⣵⠆⡇⡾⢟⣩⡶⢛⡭⣒⣽⠾⠛⢡⣾⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠻⣿⣿⣿⣿⣿⣿⡷⠈⣿⣛⠛⠥⠮⠔⠫⠿⠷⠃⠃⣶⣋⡥⢚⣭⣼⡶⢖⣩⣾⢂⣿⣿⣿⣿⣿⣿⣿⣿⣿
⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⢿⣿⣿⣿⣿⣦⣀⠸⢟⡿⣫⠔⣻⡿⠟⠻⠀⠃⢋⡥⢔⡾⢟⣫⣶⡟⣫⠃⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣿⣿⣿⣿⣿⢁⡧⢚⢕⢋⣠⣶⢞⡵⣿⢀⠀⣶⣩⢖⠿⡋⣵⠾⣩⡃⠹⣿⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⠏⡾⡫⡀⣁⠵⡫⢔⣩⣾⣿⢸⠀⠏⡠⢔⠵⡪⢵⡾⡫⢎⡀⢻⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⣿⣿⣟⣰⣅⣤⣾⣷⣿⣶⣿⣿⣿⣿⣈⣼⣭⣮⣴⣿⣷⣥⣾⣶⣿⣿⡈⣿⣿⣿⣿⣿⣿⣿⣿
⠰⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣴⣿⣆⢠⣇⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⡩⠭⠿⢈⠛⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿

>>> mkdir new_folder
Direktori 'new_folder' telah dibuat.

>>> ls
new_folder

>>> cd new_folder
Sekarang di dalam direktori 'new_folder'.

>>> exit
Terima kasih telah menggunakan CLI. Selamat tinggal!
```

## Simulasi Sistem File

Meskipun CLI ini mendukung perintah sistem file umum, harap dicatat bahwa ini adalah simulasi atau dimodifikasi pada sistem Anda. Ini semua hanya untuk kesenangan dan tujuan pembelajaran OS.

## Kustomisasi

Anda dapat memodifikasi atau memperluas fungsionalitas CLI ini. Anda bisa:
- Menambahkan lebih banyak karakter seni ASCII.
- Menerapkan perintah simulasi sistem file tambahan.
- Mengubah pesan selamat datang/keluar.
