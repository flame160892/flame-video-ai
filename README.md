# FLAME Video AI

Pembuat video faceless untuk Shorts / Reels / TikTok:
judul → gaya visual → naskah (Gemini) → suara (Google AI Studio) → potong jeda → transkrip & scene → gambar AI → render MP4.

- Versi web: https://flame-video-ai.vercel.app
- Kode aplikasi: `www/index.html` (satu file)
- APK Android: dibangun otomatis oleh GitHub Actions setiap push ke `main`.
  Download di tab **Releases** → `FLAME-Video-AI.apk`.

## Cara update
Edit `www/index.html`, commit ke `main`. APK baru muncul di Releases sekitar 5–8 menit kemudian.

## Pertama kali dipakai
Buka ⚙️ Pengaturan, isi API key Gemini gratis dari https://aistudio.google.com/apikey.
