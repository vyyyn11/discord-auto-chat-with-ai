# Folder Structure

```
discord-auto-chat-with-ai/
├── bot.py              — Script utama selfbot Discord
├── README.md           — Panduan setup dan instalasi
└── requirements.txt    — Dependensi Python
```

## Keterangan

| File | Deskripsi |
|------|-----------|
| `bot.py` | Script utama selfbot Discord. Menjalankan bot yang auto-reply pesan di channel tertentu menggunakan AI lokal (Ollama + Gemma 2b). Fitur: auto-reply dengan interval random, auto-restart setiap 2 jam, filter respons AI buruk. |
| `README.md` | Panduan lengkap setup: instalasi screen, Ollama, discord.py-self fork, konfigurasi token + channel ID, dan cara menjalankan script. |
| `requirements.txt` | Dependensi Python yang dibutuhkan: discord.py-self, requests, aiohttp, dan library pendukung lainnya. |
