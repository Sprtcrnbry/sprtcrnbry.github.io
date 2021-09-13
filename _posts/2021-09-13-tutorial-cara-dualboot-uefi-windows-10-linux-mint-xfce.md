---
layout: post
title: (ID) Tutorial Cara Dualboot Windows & Linux Mint XFCE
date: 2021-09-13 15:54+0700
---

Setelah lama tidak memposting apapun, saya kembali dengan tutorial cara men-dualboot Windows & Linux Mint XFCE. Di sini saya menggunakan Windows 10 dalam mode UEFI dan Linux Mint 20.2 Uma ber-desktop XFCE.

Pertama, download dulu ISO Linux Mint nya: [https://linuxmint.com/](https://linuxmint.com/) ![Screenshot_20210913_162325.webp](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_162325.webp)

Pilih desktop yang diinginkan (saya disini menggunakan XFCE): ![Screenshot_20210913_162416](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_162416.webp)

Cari dan pilih Indonesia: ![Screenshot_20210913_162624](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_162624.webp)

Dan ketika sudah selesai, buat bootable ISOnya ke USB Flash Drive. Bisa menggunakan [Rufus]() (di Windows) dan [Ventoy]() (di Windows dan Linux).

Kedua, Apa itu UEFI? Dikutip dari Wikipedia bahasa Inggris (baca selengkapnya di [https://en.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface](https://en.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface)):
> The Unified Extensible Firmware Interface (UEFI) is a publicly available specification that defines a software interface between an operating system and platform firmware. UEFI replaces the legacy Basic Input/Output System (BIOS) firmware interface originally present in all IBM PC-compatible personal computers, with most UEFI firmware implementations providing support for legacy BIOS services. UEFI can support remote diagnostics and repair of computers, even with no operating system installed.

Bagaimana cara mengetahui komputer kita menggunakan UEFI atau tidak? Jika anda menggunakan Windows 7 kebawah, kemungkinan besar anda menggunakan BIOS. Tekan tombol Win+R dan ketik "msinfo32" dan tekan enter: ![Screenshot_20210913_191329](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_191329.webp)

![Screenshot_20210913_190941](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_190941.webp)

Ketika sudah, restart sistem dan masuk ke boot menu (silahkan cari di Google untuk masuk BIOS/boot menu komputernya): ![Screenshot_20210913_163153](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_163153.webp)

Pilih USB Flash Drive berisi Linux Mint tadi. ![Screenshot_20210913_163245](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_163245.webp)

Pilih "Start Linux Mint 20.2 Xfce 64-bit" (atau sesuaikan dengan versi yang anda download). ![Screenshot_20210913_163542](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_163542.webp)

Tunggu sampai sistem menyala, kemudian klik dua kali ikon Install Linux Mint di desktop: ![Screenshot_2021-09-13_12-39-28](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_12-39-28.webp)

Pilih bahasa yang ingin digunakan, disini saya menggunakan Bahasa Indonesia: ![Screenshot_2021-09-13_12-44-40](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_12-44-40.webp)

Tekan "Lanjutkan". ![Screenshot_2021-09-13_12-47-45](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_12-47-45.webp)

Sesuaikan layout keyboard anda. Jika tidak yakin, pilih "Deteksi Susunan Papan Ketik". ![Screenshot_2021-09-13_12-52-32](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_12-52-32.webp)

Pilih "Pasang codec-codec multimedia" dan tekan "Lanjutkan". ![Screenshot_2021-09-13_12-55-19](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_12-55-19.webp)

Pilih "Pasang Linux Mint bersama Windows Boot Manager", dan tekan "Lanjutkan". ![Screenshot_2021-09-13_12-58-22](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_12-58-22.webp)

Sesuaikan tempat penyimpanan yang ingin di bagi dengan Linux, disini saya menggunakan setengah dari tempat yang tersisa. ![Screenshot_2021-09-13_13-02-02](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_13-02-02.webp)

![Screenshot_2021-09-13_13-06-11](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_13-06-11.webp)

Tekan "Lanjutkan", Kemudian pilih zona waktu anda, disini saya memilih Jakarta: ![Screenshot_2021-09-13_13-25-27](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_13-25-27.webp)

Masukkan Nama dan Password masuk anda: ![Screenshot_2021-09-13_20-25-59](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_20-25-59.webp)

Jika sudah, anda hanya perlu menunggu sekitar 10-15 menit. Boleh ditinggal makan, ngopi, ngeteh, ngemil, ataupun rebahan. ![Screenshot_2021-09-13_20-26-28](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_20-26-28.webp)

Jika sudah selesai, tekan "Nyalakan Ulang Sekarang" ![Screenshot_2021-09-13_20-38-19](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_2021-09-13_20-38-19.webp)

Cabut USB Flash Drive anda dan tekan enter: ![Screenshot_20210913_210009](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_210009.webp)

Selamat!, jika anda melihat layar ini, berarti Linux Mint telah berhasil di install. Coba untuk masuk ke Linux dengan menekan enter.![Screenshot_20210913_210209](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_210209.webp)

![Screenshot_20210913_210535](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Screenshot_20210913_210535.webp)

![Cuplikan Layar_2021-09-13_21-07-16](/images/2021-09-13-tutorial-cara-dualboot-uefi-windows-10-linux-mint-xfce/Cuplikan Layar_2021-09-13_21-07-16.webp)
