# gitGrok — Personal AI Brain

Ini adalah repositori otak jangka panjang untuk digunakan bersama Grok.

## Cara Kerja

Setiap chat baru, Grok akan membaca seluruh isi folder `brain/00_core/` terlebih dahulu sebelum berpikir dan menjawab.

### Struktur Otak

```
brain/
├── 00_core/          → Selalu dimuat (Core Memory)
├── 01_working/       → Memori kerja aktif
├── 02_episodic/      → Ingatan kejadian berwaktu
├── 03_semantic/      → Pengetahuan terstruktur
├── 04_procedural/    → Keterampilan & cara berpikir
└── 05_archive/       → Arsip ringkas
```

### Perintah Cepat

- `gunakan brain` / `load brain` / `otak` → Memuat Core Memory
- Grok boleh mengusulkan update ke otak ketika ada informasi penting.

---

Dibuat dan dikelola bersama Grok.