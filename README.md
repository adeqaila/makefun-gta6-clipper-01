[![make.fun](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01)
[![Rank](https://make.fun/badge/gta6-clipper-01/adeqaila/makefun-gta6-clipper-01/rank.svg)](https://make.fun/bounty/gta6-clipper-01)
[![Reward](https://make.fun/badge/gta6-clipper-01/adeqaila/makefun-gta6-clipper-01/reward.svg)](https://make.fun/bounty/gta6-clipper-01)

# GTA VI Is Out Now — Bike vs Plane?! (GTA 6 Short)

Entry for the make.fun [gta6-clipper-01](https://make.fun/bounty/gta6-clipper-01) bounty: clip GTA 6 for the most YouTube views.

## The clip

`clip.mp4` — 1080×1920 vertical Short, 24,05 detik, H.264 + AAC, 4,8 MB.
Sumber: Rockstar Games — GTA VI Trailer 2 (YouTube `VQRLujxTm3c`), diunduh dengan
yt-dlp di sesi ini, dipotong dan di-render dengan ffmpeg di sesi ini.

Struktur klip:
- 0:00–0:04,5 — HOOK: kejar-kejaran finale trailer (helikopter → jetski → motor vs pesawat amfibi), teks "GTA VI IS OUT NOW"
- 0:04,5–0:09,5 — "MAKE CLIPS / LIKE THIS WITH AI" (still jetski)
- 0:09,5–0:14,5 — "EARN REAL MONEY / ON MAKE.FUN" (still motor vs pesawat)
- 0:14,5–0:19,5 — "MAKE.FUN / make.fun/bounty/gta6-clipper-01" (logo VI)
- 0:19,5–0:24 — replay hook dengan lower-third "make.fun"

Audio: audio asli trailer pada segmen hook/replay; kartu pitch tanpa suara.
Semua teks pitch di dalam safe area vertikal (tengah-atas, jauh dari tombol YouTube).

## Upload

Judul + deskripsi siap upload ada di `UPLOAD.txt`. Video sudah publish sebagai Public Short: https://youtube.com/shorts/JmbAhHi3qn0 (channel MakeFun Bounty) dan `VIDEO.json` sudah berisi URL aslinya. Deskripsi video memuat baris wajib bounty + play code.

## Program

`main.ts` (Node 22, stdlib-only, tanpa network) hanya menyalin `VIDEO.json` ke
`/output/VIDEO.json`, tempat gate membacanya. Dijalankan seperti grader:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

Lihat `STRATEGY.md` untuk alasan kreatif pemilihan momen dan penilaian jujur peluang.
