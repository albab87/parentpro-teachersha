# ParentPro by Teacher Sha — Program Bimbingan Hidup 30 Hari

App Android oleh **Fun Learning with Teacher Sha**.

## Ciri-ciri
**Interaksi harian ibu bapa & anak (10 minit sehari)**
- 💗 Semakan emosi harian anak (8 emosi + tip respons untuk ibu bapa + sejarah 7 hari)
- 💬 Soal jawab harian: 5 soalan setiap hari bagi setiap anak, pemasa 10 minit, catat jawapan
- 📚 Buku Kenangan: semua jawapan anak disimpan mengikut tarikh
- 🎯 Misi Ikatan Harian (checklist 5 misi + hari berturut-turut)
- 🎲 Permainan keluarga mingguan (12 permainan bergilir), rekod skor & Carta Juara Keluarga
- 🌈 20 idea masa bersama keluarga

**Untuk ibu bapa**
- 📅 Program Bimbingan Hidup 30 Hari (12 topik), jurnal refleksi & Sudut Tenang

Semua data disimpan dalam telefon dan app berfungsi tanpa internet.

## Struktur fail
```
www/index.html                  ← kod app
www/kids.js                     ← soalan, emosi, permainan, idea (ubah kandungan di sini)
www/program.js                  ← kandungan Program 30 Hari
www/keluarga.jpg                ← gambar di skrin utama
icon.png                        ← ikon app (512x512)
.github/workflows/build-apk.yml ← arahan GitHub untuk bina APK
```

## Muat turun APK terkini
https://github.com/albab87/parentpro-teachersha/releases/latest/download/ParentPro.apk

## Cara bina APK sendiri
1. Buat repo baharu di github.com (contoh: `ibubapa-tenang`).
2. **Add file → Upload files**, seret SEMUA fail & folder ini (termasuk folder `.github`) → **Commit**.
3. Buka tab **Actions** → tunggu "Bina APK" siap (~5 minit, tanda ✅ hijau).
4. Klik run tersebut → bahagian **Artifacts** → muat turun `ParentPro-APK` (zip).
5. Ekstrak zip, pindahkan `ParentPro.apk` ke telefon dan buka untuk install
   (benarkan "Install unknown apps" jika diminta).

Setiap kali anda ubah `www/index.html` dan commit, APK baharu akan dibina automatik.

## Nota
- APK ini versi *debug* — sesuai untuk diuji dan dikongsi terus. Untuk Google Play Store
  anda perlukan APK/AAB *release* yang ditandatangani (signed).
