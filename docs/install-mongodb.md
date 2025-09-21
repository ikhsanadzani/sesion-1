cari paket MongoDB di AUR
yay -S mongodb-bin

Selama proses:

yay akan menanyakan apakah mau mengedit PKGBUILD → tekan N kalau tidak perlu.

Tunggu sampai selesai build & install.

2. Jika sudah bisa langsung cek status mongoDB
dengan perintah : "systemctl status mongodb"
3. lalu start service dengan perinta : "systemctl start mongodb"

4. Enable service agar otomatis jalan saat boot: "sudo systemctl enable mongodb"

5. Start service sekarang: "sudo systemctl start mongodb"

6. Uji MongoDB

Masuk ke shell MongoDB: mongosh

selesai
