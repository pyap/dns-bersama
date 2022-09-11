Rewrite ip halaman peringatan DNS Bersama

DNS Bersama menggunakan ip 203.119.13.75 dan 203.119.13.76 untuk menampilkan halaman peringatan. Berikut cara mengalihkan halaman peringatan tersebut menggunakan web server sendiri. Sebagai contoh, digunakan domain postpi.org.

Catatan:
Dnsmasq tidak bisa rewrite ke cname, harus ke ip, sebagai contoh, diarahkan ke ip 192.168.11.1 dan 192.168.11.2.
