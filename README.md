# eCampus & eSchool Releases

Repository publik ini hanya digunakan untuk mendistribusikan paket instalasi
eCampus dan eSchool. Source code aplikasi tetap dikelola pada repository
pengembangan terpisah.

## Unduh aplikasi

Buka halaman [Releases](../../releases/latest), lalu pilih paket sesuai
platform dan produk:

- `eCampus-Setup-*.exe` — installer eCampus untuk Windows x64.
- `eSchool-Setup-*.exe` — installer eSchool untuk Windows x64.
- `eCampus-Android-*.apk` — paket uji eCampus untuk Android.
- `eSchool-Android-*.apk` — paket uji eSchool untuk Android.

Paket berlabel **UAT/pre-release** ditujukan untuk pengujian dan belum boleh
dianggap sebagai rilis produksi. Cocokkan SHA-256 pada catatan release setelah
file selesai diunduh.

## Catatan keamanan

Installer Windows saat ini belum ditandatangani menggunakan sertifikat
code-signing sehingga Windows SmartScreen mungkin menampilkan peringatan.
APK UAT dapat menggunakan debug signing apabila credential release Android
belum tersedia; status signing selalu dijelaskan pada catatan release.
