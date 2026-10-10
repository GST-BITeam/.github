Closes #<nomor issue>

## Ringkasan
<!-- Satu-dua kalimat: apa yang dilakukan PR ini dan kenapa. -->

## Jenis perubahan
- [ ] `feat` — fitur / modul baru
- [ ] `fix` — perbaikan bug
- [ ] `refactor` — struktur berubah, perilaku tidak
- [ ] `chore` / `docs` — pemeliharaan, dokumentasi

## Apa yang berubah
| Berkas / area | Perubahan | Alasan |
|---|---|---|
|  |  |  |

## Dampak ke database
- [ ] Tidak ada
- [ ] Ada migrasi: `nama_migrasi`
- [ ] Tabel baru punya kolom `uuid` (bagian 9)
- [ ] Tabel baru punya jejak (master berjejak / jejak audit), atau masuk daftar pengecualian
      beserta alasannya; nilai yang tampil di dokumen dibekukan (bagian 9, "Prinsip data")
- [ ] Mengganti nama / menghapus tabel atau kolom → view, ETL, dan aplikasi
      lain yang membaca tabel ini **sudah dicek**

## Hasil tes
<!-- Status `bukti-tes` di commit terakhir (bagian 12) dan tes yang ditambah atau diubah.
     Seluruh tes dijalankan saat rilis — tidak perlu di sini. -->
- `bukti-tes`: N tes terkait, 0 gagal, <durasi>
- Tes baru / diubah: `tests/…`

## Cara menguji
<!-- Langkah mencoba perubahan ini secara manual di aplikasi. -->
1.
2.

## Rencana rollback
<!-- Kalau rusak di produksi, apa langkahnya? Wajib diisi kalau ada migrasi. -->

## Checklist penulis
- [ ] Tidak ada `.env`, password, token, atau kunci di diff
- [ ] Tidak ada data pribadi (CSV/Excel berisi nama, HP, gaji, alamat)
- [ ] Tidak ada kalimat penjelas baru di tampilan yang tidak diminta issue (bagian 11)
- [ ] Pesan commit mengikuti Conventional Commits
- [ ] Cabang sudah diperbarui dari cabang tujuannya (`development`; perbaikan mendesak: `prod`)
- [ ] `HANDOFF.md` sudah dihapus — isinya dipindah ke deskripsi ini
- [ ] Label prioritas sama dengan issue-nya
- [ ] `bukti-tes` ✅ di commit terakhir (termasuk aturan repo)
- [ ] Setiap pemeriksaan di issue terpenuhi, dan buktinya ada di PR ini
