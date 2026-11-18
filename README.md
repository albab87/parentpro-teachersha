# ParentPro by Teacher Sha — Program Bimbingan Hidup 30 Hari

App Android oleh **Fun Learning with Teacher Sha**.

## Ciri-ciri
- 📅 Program 30 hari (pelajaran, tugasan & refleksi harian)
- 🧩 12 topik utama dengan kemajuan setiap topik
- 🔥 Statistik kemajuan & hari berturut-turut
- 😊 Semakan perasaan harian
- 🌿 Sudut Tenang (latihan pernafasan 1 minit + teknik BERHENTI)
- 📔 Jurnal refleksi (disimpan dalam telefon, berfungsi tanpa internet)

## Struktur fail
```
www/index.html                  ← kod app (ubah kandungan di sini)
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
