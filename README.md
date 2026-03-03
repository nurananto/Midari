# Midari ni Tsukasete wa Narimasen

> Tamotsu Sugawara, seorang karyawan yang tidak bisa menolak permintaan apa pun, mendapati dirinya tidak bisa lagi pergi ke kantor dan memutuskan untuk beristirahat sementara di kuil keluarganya. Suatu malam, hantu yang sangat mirip dengan Makoto Hiiragi, seorang mahasiswi yang bekerja part time di kuil itu pada siang hari, muncul di hadapannya. Komedi romantis yang terinspirasi dari horor ini menghubungkan mantan karyawan yang ngga bisa bilang tidak (yes-man) dengan mahasiswi yang dicurigai sebagai arwah hidup (!?) ♡

---

## Info

| | |
|---|---|
| Judul | Midari ni Tsukasete wa Narimasen |
| Judul Alternatif | みだりに憑かせてはなりません |
| Author | Kurita Aguri |
| Tipe | Manga (Hitam Putih) |
| Status | Hiatus |
| Genre | Drama · Shounen · Supernatural · Comedy · Romance · Slice of Life |
| Chapter | 17 chapter |

## Link

- [MangaDex](https://mangadex.org/title/3076dc1f-e6f2-418c-baa9-125694eb36cc/midari-ni-tsukasete-wa-narimasen)
- [Raw](https://comic-walker.com/detail/KC_006109_S)

---

## Struktur

```
Midari/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)