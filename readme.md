# Meme Coin Radar Live — Multi-Chain Radar, Anti-Scam Audit & Paper Trading

[](https://goblin1694.github.io/Meme-Coin-Radar-Live/)
[License: MIT](https://www.google.com/search?q=LICENSE)
[](https://teer.id/email_kantor3)

Aplikasi web *mobile-friendly* untuk memantau seluruh meme coin lintas jaringan (**Solana, Base, BSC, dan Ethereum**) secara *real-time*—dilengkapi skor kredibilitas, deteksi *scam/rug pull*, grafik *candlestick live*, kalkulator posisi *split-entry*, *paper trading* terisolasi per pengguna, serta dukungan kustomisasi AI.

🌐 **Akses Langsung (Live):** [https://goblin1694.github.io/Meme-Coin-Radar-Live/](https://goblin1694.github.io/Meme-Coin-Radar-Live/)

---

## Keamanan & Privasi

* **Zero Wallet Connection:** Aplikasi berjalan **100% di browser** tanpa pernah meminta koneksi dompet Web3, *private key*, atau *seed phrase*.
* **Isolasi Data Antar Pengguna:** Setiap pengguna otomatis mendapatkan **ID Sesi unik (`usr_...`)** di browser masing-masing (dan filter `X-User-ID` jika memakai backend `server.py`), sehingga data **Paper Trading**, **Jurnal**, dan **Pengaturan** tidak bercampur antar pengguna.

---

## Fitur Utama

1. **Radar Live 4 Bagan (`Trending`):**
   * **Top 20 Bullish (Prediksi Naik):** Koin dengan tekanan beli dan momentum volume tertinggi untuk proyeksi **Menit, Jam, Hari, dan Bulan**.
   * **Top 20 Baru Kredibel:** Koin baru rilis yang memiliki website/akun resmi konkret serta likuiditas layak.
   * **Prediksi Akan Turun / Koreksi:** Koin dengan tekanan jual dominan atau pelemahan jangka pendek.
   * **Indikasi Scam & Mendekati Rug Pull:** Koin anonim tanpa akun resmi, likuiditas kritis (<$3.000 atau <5% MCap), *wash-trade*, atau *dump* ekstrem.
2. **Sinyal Keputusan & Alasan Eksplisit:**
   * Setiap kartu menampilkan badge **`Beli`**, **`Layak Beli`**, **`Tidak Yakin`**, atau **`Jangan Beli`**, **Arah Sinyal (%)**, **Kredibilitas (%)**, **Confidence (%)**, **Liq/MCap (%)**, **Beli % / Jual %**, serta kalimat alasan spesifiknya.
3. **Chart Live, Audit Kontrak & Kalkulator Posisi (`Sizer`):**
   * **Chart Live Real-Time:** Grafik *candlestick* interaktif dari **DEX Screener** otomatis tampil saat profil koin diklik.
   * **Audit Kontrak & Kredibilitas:** Integrasi **RugCheck** (Solana), **GoPlus** (EVM), penyaring ketat domain/akun resmi konkret, serta tautan 1-klik ke **Bubblemaps**, **Arkham Intelligence**, **Jupiter / Uniswap / PancakeSwap**, **GMGN.AI**, dan **Sinyal Publik** (X, Telegram, Reddit, Jurnal Web, YouTube, CoinGecko).
   * **Kalkulator Posisi 40% / 60%:** Perhitungan ukuran *Scout Entry* dan *Confirmation Entry* lengkap dengan grafik Risk/Reward.
4. **Paper Trading (`Paper`):**
   * Uji coba beli/jual virtual memakai **harga pasar *live*** dengan saldo awal **$1,000**, opsi **TP/SL opsional** (*Virtual OCO* bisa aktif atau *Off*), tombol **Sesi Baru**, dan riwayat transaksi.
5. **Audit Model Live (`Audit`) & Jurnal (`Jurnal`):**
   * Evaluasi *hit-rate* sinyal *Bullish* vs *Bearish/Scam* secara *real-time* setelah `>= 60 detik`, serta pencatatan transaksi dengan peringatan **Daily Loss Guard**.
6. **Pengaturan AI & Strategi (`Pengaturan`):**
   * *Default* **AI Gemini Bawaan** (gratis tanpa API Key), opsi gratis **Pollinations AI**, dan dukungan API Key pihak ketiga (**Gemini Custom, OpenAI, Anthropic Claude, Groq, DeepSeek, OpenRouter, Mistral, Together AI, xAI Grok, Custom Endpoint**), plus multi-pilih strategi & **Strategy Manual via Text**.
7. **Dukungan Kreator (`Traktir`):**
   * Halaman khusus menuju [teer.id/email_kantor3](https://teer.id/email_kantor3).

---

## Tangkapan Layar

| Trending Radar | Audit Model | Audit & Sizer |
| :---: | :---: | :---: |
|  |  |  |

| Jurnal Trading | Traktir | Pengaturan AI |
| :---: | :---: | :---: |
|  |  |  |

---

## Menjalankan Secara Lokal / Full-Stack (Opsional)

Untuk penggunaan statis, cukup buka `index.html` atau aktifkan **GitHub Pages**. Jika ingin memakai backend **FastAPI + SQLite** (`server.py`) untuk *caching proxy* 3 detik dan penyimpanan database per `X-User-ID`:

```bash
pip install -r requirements.txt
uvicorn server:app --host 0.0.0.0 --port 8000
```

---

## Lisensi

Proyek ini dilisensikan di bawah **MIT License** — lihat file [LICENSE](https://www.google.com/search?q=LICENSE) untuk detailnya.
