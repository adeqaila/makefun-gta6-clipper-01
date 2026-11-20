# STRATEGY — gta6-clipper-01 slot 1: "Bike vs Plane"

## Momen yang dipilih

**Kejar-kejaran finale GTA VI Trailer 2 (Rockstar Games, YouTube `VQRLujxTm3c`),
detik 139,0–143,5.** Satu rangkaian aksi berkesinambungan dari klimaks trailer:
helikopter di atas rawa → kokpit helikopter mengejar jetski → Jason & Lucia di
jetski hijau → Jason di atas motor chopper, pesawat amfibi terbang tepat di
belakangnya. Saya putuskan ini sebagai SATU momen (satu kejar-kejaran, bukan
montase adegan tak berhubungan).

## Kenapa momen ini

1. **Langsung terbaca dalam <1 detik.** Frame motor vs pesawat itu absurd dan
   lucu dengan cara yang paling GTA: pria berkacamata naik chopper, pesawat
   amfibi di belakangnya. Penonton Shorts berhenti scroll karena otaknya
   bertanya "itu beneran?" — persis yang dibutuhkan hook.
2. **Terang dan terbaca di vertikal.** Siang hari, langit biru, subjek di
   tengah frame — tidak ada yang hilang saat di-crop/blur-fill ke 9:16.
   Kandidat lain kalah: adegan Lucia di atap mobil (~111 dtk) terlalu gelap
   dan singkat (~1,5 dtk); adegan ruang tamu (~135 dtk) lucu tapi lambat dan
   bukan aksi; aerial Leonida (~5 dtk) indah tapi tanpa energi.
3. **Emosi = kagum + ngakak.** Bukan kekerasan berdarah, bukan glitch — murni
   "GTA itu gila", yang paling mudah dibagikan dan paling aman dari
   Content ID strike yang agresif (ini footage trailer resmi, bukan gameplay
   bocor).

## Keputusan kreatif

- **Hook dulu, pitch kemudian.** 4,5 detik pertama murni aksi + satu baris
  "GTA VI IS OUT NOW" di atas — penonton bertahan karena aksinya, bukan
  karena disuruh.
- **Pitch 3 kartu, 5 detik tiap kartu (2–3 detik per baris, sesuai kit):**
  "MAKE CLIPS / LIKE THIS WITH AI" → "EARN REAL MONEY / ON MAKE.FUN" →
  "MAKE.FUN / make.fun/bounty/gta6-clipper-01". Nama make.fun disebut 2× di
  layar, URL bounty lengkap 1×. Tanpa voiceover — teks saja sudah memenuhi
  syarat kit ("text on screen, a voice or both").
- **Replay hook di akhir** (4,5 detik, lower-third "make.fun") supaya video
  berakhir di aksi, bukan di kartu statis — dan URL tetap terlihat.
- **Blur-fill, bukan center-crop.** Tidak ada yang terpotong dari sisi frame;
  footage sinematik (letterbox 2.22:1) di-crop bar hitamnya dulu (1920×864),
  lalu blur-fill ke 1080×1920.
- **Audio asli trailer** pada segmen aksi (energi musiknya yang menjual);
  kartu pitch senyap supaya teksnya yang bicara.

## Judul & deskripsi

Lihat `UPLOAD.txt`. Judul: "GTA VI IS OUT NOW — Bike vs Plane?!". Deskripsi
memuat baris wajib bounty kata-per-kata + placeholder play code `[PLAY CODE]`
(yang diisi parent dengan kode asli) + tagar #GTA6 #GTAVI #Shorts #ViceCity
#Leonida.

## Verifikasi (di sesi ini)

- `clip.mp4`: 1080×1920, 30 fps, H.264 + AAC, 24,05 dtk (<60 dtk = Short),
  4.812.833 byte, sha256 `1b04fe460492ee30951158d6887b05954e515f8c2831dd7972aade371f3373d3`.
- 5 frame cek (detik 2 / 4,2 / 7 / 12 / 17 / 22 / 23,5): semua teks terbaca,
  di safe area (tengah-atas, jauh dari tombol YouTube kanan-bawah), tidak ada
  yang terpotong.
- `main.ts` grader-sim: `mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts`
  → `out/VIDEO.json` tersalin, byte-identical dengan `VIDEO.json` repo.
- Sumber footage: `work/trailer2.mp4` (34.213.908 byte, 166,75 dtk, 1920×1080,
  AV1+Opus), diunduh dengan yt-dlp di sesi ini dari channel Rockstar Games.
  Klip jadi buatan orang lain TIDAK dipakai.

## Penilaian jujur peluang

RENDAH–SEDANG. Metric-nya views nyata di YouTube — tidak bisa di-grind seperti
kode. Channel tanpa audiens realistis dapat 0–puluhan views organik dalam ~3
hari; tempat 11–20 ($14) masih mungkin kalau algoritma Shorts mengangkat klip
atau dipromosikan lewat X @qaila_ade; top 3 butuh viral sungguhan. Risiko:
klaim Content ID atas footage Rockstar tetap mungkin walau bounty secara
eksplisit meminta klip dari footage GTA 6.

## Serah-terima

Klip + judul + deskripsi di atas **SIAP DI-UPLOAD** dan diserahkan ke parent
(user) untuk di-upload ke channel YouTube-nya sebagai video Public — sesuai
kit: "upload it or hand it to the person to upload". Saya TIDAK meng-upload
ke YouTube. Setelah upload, parent mengisi URL Shorts ke `VIDEO.json`,
lalu repo + submit.
