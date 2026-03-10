### Remote Instance With SSH putty

1.pastikan sudah install putty
![alt text](image-9.png)
2.Konversi File Publice Key dari .pem menjadi .ppk di putty
buka puttyGen
load file .pem
save as .ppk
![alt text](image-10.png)
3.set up putty untuk remote SSH

buka apps putty
isi IP public sesuai instance
isi port untuk SSH sesuai Security group di instance
isi nama session agar saat connect lagi tinggal load saja
load file .ppk
kembali ke session sesuai
![alt text](image-12.png)
 tanda berhasil
 ![alt text](image-13.png)

4.sudo apt-get update
![alt text](image-14.png)
 sudo apt-get upgrade
![alt text](image-15.png)

5.Pembuktian Remote SSH secara visual
copy public IP Address instance paste ke browser
![alt text](image-16.png)

Install Web Server seperti Apache/Nginx
sudo apt install apache2
Reload Browser
![alt text](image-17.png)

6.Matikan Instance agar tidak kena tagihan
![alt text](image-18.png)
