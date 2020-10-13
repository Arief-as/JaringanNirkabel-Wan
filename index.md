 | # Selamat datang di Arief_GitHub |    
                                                                                                                      13 Oktober 2020
 | # Keamanan Jaringan Nirkabel |


Jaringan nirkabel atau yang sering disebut dengan wireless network mulai semakin digemari dewasa ini. Hal tersebut karena kemudahan untuk instalasi dan juga terasa sangat nyaman dalam penggunaannya.

Namun, karena wireless menggunakan gelombang radio, maka akan lebih mudah untuk diretas (hack) dari pada koneksi yang menggunakan kabel. Ada beberapa tips di sini untuk mengamankan wireless network.


## Berikut adalah beberapa tips untuk mengamankan jaringan wireless:
### 1. Menggunakan Enkripsi.
Enkripsi adalah ukuran security yang pertama, Meskipun banyak AP telah memiliki Wired Equivalent Privacy (WEP) protocol, tetapi secara default tidak diaktifkan. seorang peretas yang berpengalaman pasti dapat membukanya, tetapi itu masih tetap lebih baik dari pada tidak ada enkripsi sama sekali. Pastikan untuk mengaktifkan metode WEP authentication dengan “shared key” daripada “open system”. Untuk “open system”, AP tidak melakukan enkripsi data, tetapi hanya melakukan otentifikasi client. Ubah WEP key sesering mungkin, dan pakai 128-bit WEP hindari menggunakan 40-bit. Karena kelemahan-kelemahan yang ada di WEP, maka dianjurkan untuk menggunakan Wi-Fi Protected Access (WPA) juga. Untuk memakai WPA, AP harus men-support-nya. Sisi client juga harus dapat support WPA tersebut. Namun, saat ini hampir semua Access Point maupun user/client sudah mendukung WPA.
### 2. Ganti Password Administrator standar.
 Kebanyakan pabrik menggunakan password administrasi yang sama untuk semua AP produk mereka. Default password tersebut umumnya sudah diketahui oleh peretas, yang nantinya dapat digunakan untuk merubah setting di AP Anda. Hal pertama yang harus dilakukan dalam konfigurasi AP adalah mengganti password default. Gunakan minimal 8 karakter, kombinasi antara huruf, function dan angka, dan tidak menggunakan kata-kata yang ada dalam kamus. 
### 3. Matikan SSID Broadcasting.
 Service Set Identifier (SSID) adalah nama dari wireless network kita. Secara default, SSID dari AP akan di-broadcast atau disiarkan. Hal ini akan membuat user mudah untuk menemukan network Anda, karena SSID akan muncul dalam daftar available networks yang ada pada wireless client. Jika SSID dimatikan, user harus mengetahui lebih dahulu SSID-nya agar dapat terkoneksi dengan network.
### 4. Matikan AP Saat Tidak Dipakai.
 Cara yang satu ini kelihatannya sangat mudah dan remeh, tetapi beberapa perusahaan atau individual tidak melakukannya. Jika kita mempunyai user yang hanya terkoneksi pada saat saat tertentu saja, tidak ada alasan untuk menjalankan wireless network setiap saat dan menyediakan kesempatan bagi penyusup untuk melaksanakan niat jahatnya. Kita dapat mematikan access point pada saat tidak digunakan.
### 5. Ubah default SSID.
 Pabrik menyediakan default SSID. Kegunaan dari mematikan broadcast SSID adalah untuk mencegah orang lain tahu nama dari network kita, tetapi jika masih memakai default SSID, tidak akan sulit untuk menerka SSID dari network kita. 
### 6. Memakai MAC Filtering.
 Kebanyakan AP akan memperbolehkan kita memakai filter Media Access Control (MAC). Ini artinya kita dapat membuat “white list” dari komputer-komputer yang boleh mengakses wireless network kita, berdasarkan dari MAC atau alamat fisik yang ada di network card masing-masing PC atau laptop. Koneksi dari MAC yang tidak ada dalam list akan ditolak. Metode ini tidak selamanya aman, karena masih mungkin bagi seorang hacker melakukan sniffing paket yang kita transmit via wireless network dan mendapatkan MAC address yang valid dari salah satu user, dan kemudian menggunakannya untuk melakukan spoof. Tetapi MAC filtering akan membuat kesulitan yang lumayan bagi seorang penyusup yang masih belum jago banget. 
### 7. Mengisolasi Wireless Network dari LAN.
 Untuk memproteksi internal network kabel dari ancaman yang datang dari wireless network, perlu kiranya dibuat wireless DMZ (Demiliterize Zone) atau perimeter network yang mengisolasi dari LAN. Artinya, memasang firewall antara wireless network dan LAN. Dan untuk wireless client yang membutuhkan akses ke internal network, dia haruslah melakukan otentifikasi dahulu dengan RAS server atau menggunakan VPN. Hal ini menyediakan extra layer untuk proteksi.
### 8. Mengontrol Signal Wireless.
 802.11b WAP memancarkan gelombang sampai dengan kira kira 300 feet. Tetapi jarak ini dapat ditambahkan dengan cara mengganti antenna dengan yang lebih bagus. Dengan memakai high gain antena, kita bisa mendapatkan jarak yang lebih jauh. Directional antenna akan memancarkan sinyal ke arah tertentu, dan pancarannya tidak melingkar seperti yang terjadi di antena omnidirectional yang biasanya terdapat pada paket AP standard. Selain itu, dengan memilih antena yang sesuai, kita dapat mengontrol jarak sinyal dan arahnya untuk melindungi diri dari penyusup. Sebagai tambahan, ada beberapa AP yang bisa di setting kekuatan sinyal dan arahnya melalui config WAP tersebut.
### 9. Memancarkan Gelombang pada Frekuensi yang Berbeda.
 Salah satu cara untuk bersembunyi dari peretas yang biasanya memakai teknologi 802.11b/g yang lebih populer adalah dengan memakai 802.11a. Karena 802.11a bekerja pada frekuensi yang berbeda (yaitu di frekuensi 5 GHz), NIC yang didesain untuk bekerja pada teknologi yang populer tidak akan dapat menangkap sinyal tersebut. Namun, tentu saja Anda akan mengalami penurunan kualitas kecepatan transmisi data pada jaringan wireless Anda. 
 

