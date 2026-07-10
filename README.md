# 📜 Daftar Isi

[⚙️ Instalasi PNETLAB](#pnetlab)
[⚙️ Instalasi Ishare2](#ishare2)
[⚙️ Instalasi Client Pack](#client)
[⚙️ Referensi](#referencias)

🛠️ Instalasi PNETLAB<a id="pnetlab"></a>

- Unduh Linux Ubuntu Server 20.04.6 LTS

```linux
https://releases.ubuntu.com/20.04.6/ubuntu-20.04.6-live-server-amd64.iso
```

- Instal Ubuntu Server pada lingkungan bare metal atau virtualisasi pilihan Anda (VMware Workstation, ESXI, Proxmox, Hyper-V, VirtualBox, QEMU, dll)
- Unduh installer offline PNETLAB v6 yang disesuaikan untuk PHP 7.4, pada tautan di bawah ini:

```linux
https://canalsecinfra.sharepoint.com/:u:/s/Arquivos/IQD-zLKcmrPlRYkfY6XwvvnvATe3ADydvjLVRNbIC7MW-IQ?e=UWCilP
```

- Unggah file tersebut ke VM Ubuntu, di folder /tmp
- Instal aplikasi "unzip"

```linux
sudo apt install unzip
```

- Masuk ke folder /tmp dan ekstrak file offline-pnetlab-v6-ajustado_php74.zip

```linux
cd /tmp
unzip offline-pnetlab-v6-ajustado_php74.zip
```

- Masuk ke folder offline-pnetlab-v6-ajustado_php74, berikan izin eksekusi pada file install_pnetlab_v6

```linux
cd offline-pnetlab-v6-ajustado_php74/
chmod +x install_pnetlab_v6.sh
```

- Jalankan installer

```linux
sudo ./install_pnetlab_v6.sh
```

- Restart server

```linux
sudo reboot
```

- Login dengan user root dan password pnet, lalu lanjutkan setup. Setelah itu, server akan direstart kembali, dan setelah restart, Anda dapat mengakses PNETLab melalui URL yang ditampilkan pada layar login awal Ubuntu.

## 🛠️ Instalasi Ishare2<a id="ishare2"></a>

- Perintah untuk menginstal Ishare2 (Download Images):

```linux
wget -O /usr/sbin/ishare2 https://raw.githubusercontent.com/ishare2-org/ishare2-cli/main/ishare2 && chmod +x /usr/sbin/ishare2 && ishare2
```

## 🛠️ Instalasi Client Pack<a id="client"></a>

- Anda dapat melakukan instalasi Client Pack dan mengakses aset laboratorium melalui putty, vnc, dll (jika Anda sudah memiliki milik EVE-NG, caranya sama):

- **Link**🔗 https://mega.nz/file/G5liXYzK#oaSC1Jrh5m0HaNkReirurtrXhIHGw6NOZX3jgus1xqo

## 📌 Referensi<a id="referencias"></a>

- **LABHUB:** 🔗 https://labhub.eu.org
- **ISHARE2:** 🔗 https://github.com/ishare2-org
