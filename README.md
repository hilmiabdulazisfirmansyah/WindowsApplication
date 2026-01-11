# Disable "Show More Options" Windows 11

Alat sederhana namun efektif untuk mengembalikan menu klik kanan (Context Menu) klasik pada Windows 11 tanpa harus melalui klik tambahan "Show More Options".

## 📌 Deskripsi
Windows 11 memperkenalkan desain menu klik kanan yang baru, namun bagi banyak pengguna, hal ini dianggap memperlambat produktivitas karena fitur lama tersembunyi di balik opsi tambahan. Program ini dibuat untuk membantu pengguna mengembalikan fungsi klik kanan klasik secara instan.

<h2 align="center">📷 Tampilan: Sebelum vs Sesudah</h2>

<table align="center">
  <tr>
    <td align="center"><b>Sebelum (Standard Windows 11)</b></td>
    <td align="center"><b>Sesudah (Classic Menu)</b></td>
  </tr>
  <tr>
    <td>
      <img src="assets/before.png" width="400" alt="Menu Klik Kanan Windows 11">
    </td>
    <td>
      <img src="assets/after.png" width="400" alt="Menu Klik Kanan Klasik">
    </td>
  </tr>
</table>

<p align="center">
  <i>Program ini menghilangkan langkah ekstra "Show More Options" sehingga produktivitas Anda kembali lancar!</i>
</p>


## 🛡️ Jaminan Keamanan & Privasi
Program ini dibangun dengan prinsip transparansi penuh:
- **100% Aman:** Tidak mengandung spyware, malware, atau kode berbahaya lainnya.
- **Tanpa Pelacakan:** Tidak ada data user yang diambil, disimpan, atau dikirim ke server mana pun (Offline functionality).
- **Transparan:** Program ini bekerja murni dengan memodifikasi kunci registri Windows secara sah untuk mengubah preferensi tampilan menu.
- **Privasi Terjaga:** Menghargai privasi pengguna sepenuhnya tanpa melakukan modifikasi sistem yang tidak perlu.

## ✨ Fitur
- **Restore Classic Menu:** Mengaktifkan menu klik kanan klasik Windows 10 di Windows 11.
- **Easy Revert:** Jika Anda ingin kembali ke tampilan asli Windows 11, program menyediakan opsi untuk membatalkannya.
- **One-Click Solution:** Tanpa perlu repot membuka Registry Editor secara manual.

## 🚀 Cara Penggunaan
1. Unduh file `.exe` dari folder [dist](./dist).
2. Jalankan program dengan hak akses Administrator (klik kanan > *Run as Administrator*).
3. Pilih opsi yang tersedia pada menu program.
4. Program akan merestart `explorer.exe` secara otomatis agar perubahan langsung terasa.

## 🛠️ Teknis Singkat
Program ini melakukan modifikasi pada:
`HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32`

Modifikasi ini adalah metode standar yang diakui oleh komunitas teknis untuk mengubah perilaku *Context Menu* pada Windows 11.

## ⚖️ Lisensi
Dibuat untuk penggunaan pribadi dan umum. Silakan digunakan dan disebarkan untuk membantu produktivitas sesama pengguna Windows 11.
