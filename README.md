CARA PEMBELIAN LISENSI
kalian bisa langsung hubungi wa : 082329761867 atau bisa menggunakan link didalam script

CARA INSTALL SCRIPT:
download aplikasi termux android di disini lalu buka aplikasinya ketikan perintah dibawah ini.

$ pkg update && pkg upgrade
$ pkg install python git
$ pip install requests bs4 futures cython rich
$ rm -rf zmbf
$ git clone https://github.com/Fall-Xavier/zmbf
CARA MENJALANKAN SCRIPT:
sekarang karena script sudah diinstall tinggal kita jalankan, ketikan perintah dibawah ini:

 $ cd zmbf
 $ cythonize -i zmbf.c
 $ python run.py
CARA MENGUPDATE SCRIPT:
jika ingin mengupdate script, ketikan perintah dibawah ini:

 $ cd zmbf
 $ git pull
 $ rm -rf *.so
 $ cythonize -i zmbf.c
 $ python run.py
 
