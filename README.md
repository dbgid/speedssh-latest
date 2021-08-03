# speedssh latest version
*Note: Script ini tidak untuk di salah gunakan<br>
Gunakan script ini untuk pemakaian sewajar nya<br>
Dan selalu support dev https://www.speedssh.com agar server terus on<br>
Dan jangan sekali kali memperjual/belikan ssh gratisan dari speedssh<br>
Baik menggunakan script ini atau langsung via web<br>
# Script Dependicies
- Simple HTML DOM
- PHP Parser
- PHP Unit
# OS System Requirements
- Termux Only (Mohon maaf untuk windows, ubuntu, debian, centos dll saat ini blum support)
# Penting
Script ini di enkripsi menggunakan yakpro, dan beberapa build manual enkripsi dari DBG ID<br>
Script ini aman tanpa di sisipi program jahat, hanya saja script size nya terlalu besar<br>
Mohon maaf untuk kamu pengguna build-essential harus menghapus terlebih dahulu module m4<br>
Dikarnakan banyak nya bocil yang mendewakan <i>evalhook</i> jadi DBG ID antisipasi hal tsb<br>
Karna ada beberapa script di repo ini di jualbelikan pada bulan/tahun2 kmrin tanpa spengatuhan DBG ID<br>
Dan ada beberapa script yang berhasil di decode sama bocil bocil kematian<br>
Oleh sebab itu DBG ID skrng memasang bbrapa filter seperti<br>
```shell
php -d extension=evalhook.so script.php
```
Kami sudah memblock akses tersebut dengan beberapa native function dari php<br>
```php
if(extensions_loaded('evalhook')){
die("Error: Evalhook terdeteksi\n");
}
```
dan wajib harus menggunakan versi terbaru dari PHP yaitu versi <i>8.x</i><br>
