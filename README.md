# Game Pilah Sampah (HTML5/WebGL-ready)

Game ini sudah memiliki alur lengkap:
- **Menu** awal
- **Gameplay** dengan game loop (`requestAnimationFrame`)
- **Kondisi menang** (skor target tercapai)
- **Kondisi kalah** (nyawa habis / waktu habis)

## Jalankan lokal
```bash
python3 -m http.server 8080
```
Lalu buka `http://localhost:8080`.

## Export WebGL / HTML5 untuk itch.io
Karena proyek ini berbasis web (`index.html` + JS), format upload ke itch.io adalah **HTML5**.

1. Zip semua file proyek (minimal `index.html`).
2. Buka dashboard itch.io > **Create new project**.
3. Pilih project type **HTML**.
4. Upload file `.zip`.
5. Centang **This file will be played in the browser**.
6. Simpan dan publish.

Setelah dipublish, game bisa langsung playable dari URL itch.io.
