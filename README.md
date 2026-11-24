# Meme Coin Radar Live — Multi-Chain Prediksi, Kredibilitas & Anti-Scam

Aplikasi web *mobile-friendly* berbasis **client-side** untuk memantau meme coin secara *real-time* di berbagai jaringan (**Solana, Base, BSC, dan Ethereum**), lengkap dengan skor kredibilitas, audit kontrak *on-chain*, kalkulator posisi *split-entry*, jurnal *trading*, dan dukungan kustomisasi AI.

🌐 **Link Publik Live:** [https://goblin1694.github.io/Meme-Coin-Radar-Live/](https://goblin1694.github.io/Meme-Coin-Radar-Live/)

---

## Fitur & Fungsi Utama Website

1. **Radar Live 4 Bagan (Auto-Refresh Aman 3 Detik):**
   * **Top 20 Bullish (Prediksi Naik):** Menampilkan koin berlikuiditas layak dengan tekanan beli dan momentum volume tertinggi untuk proyeksi **Menit, Jam, Hari, dan Bulan**.
   * **Top 20 Baru Kredibel:** Memeringkat koin yang baru rilis berdasarkan kelengkapan website/akun resmi konkret, likuiditas, serta potensi kenaikan.
   * **Prediksi Akan Turun / Koreksi:** Menyaring koin yang mengalami tekanan jual dominan atau pelemahan harga jangka pendek.
   * **Indikasi Scam & Mendekati Rug Pull:** Menandai koin anonim tanpa akun resmi, likuiditas kritis (<$3.000 atau <5% Market Cap), *wash-trade*, atau *dump* ekstrem.
2. **Sinyal Keputusan & Alasan Transparan:**
   * Setiap koin dilengkapi badge **`Beli`**, **`Layak Beli`**, **`Tidak Yakin`**, atau **`Jangan Beli`**, **Arah Sinyal (%)**, **Kredibilitas (%)**, **Confidence (%)**, rasio **Likuiditas/MCap (%)**, komposisi **Beli % / Jual %**, serta kalimat alasan spesifiknya.
3. **Audit Mendalam & Eksekusi 1-Klik (`Sizer`):**
   * Audit kontrak otomatis lewat **DEX Screener**, **RugCheck** (Solana), dan **GoPlus** (EVM).
   * Tautan 1-klik ke **Bubblemaps** (cek klaster *insider*), **Arkham Intelligence** (*smart money*), **Jupiter / Uniswap / PancakeSwap**, **GMGN.AI**, serta **Sinyal Publik** (X/Twitter, Telegram, Reddit, Jurnal Web, YouTube, CoinGecko).
   * **Kalkulator Posisi Split-Entry (40% Scout / 60% Confirm)** dengan cadangan *gas fee* dan grafik skenario Risk/Reward.
4. **Audit Model Live (`Audit`):**
   * Melacak akurasi prediksi *Bullish* vs *Bearish* secara *real-time* setelah sinyal berjalan minimal 1 menit.
5. **Jurnal Trading & Daily Loss Guard (`Jurnal`):**
   * Mencatat hasil transaksi (tersimpan di `localStorage` browser) dan memberi peringatan batas rugi harian.
6. **Pengaturan AI & Strategi (`Pengaturan`):**
   * *Default* menggunakan **AI Gemini** bawaan (gratis tanpa API Key), plus opsi **Pollinations AI** (gratis tanpa API Key) atau provider ber-API Key (**Google Gemini API, OpenAI, Anthropic Claude, Groq, DeepSeek, OpenRouter, Mistral, Together AI, xAI Grok, dan Custom Endpoint**).
   * Konfigurasi target prediksi, filter akurasi, dan pilihan strategi trading (termasuk **Strategy Manual via Text**).
7. **Dukungan Kreator (`Traktir`):**
   * Halaman khusus menuju [teer.id/email_kantor3](https://teer.id/email_kantor3).

---

## Cara Penggunaan Singkat

1. Buka [https://goblin1694.github.io/Meme-Coin-Radar-Live/](https://goblin1694.github.io/Meme-Coin-Radar-Live/) dari browser HP atau desktop.
2. Gunakan bilah navigasi bawah (**Trending**) untuk memilih bagan **Naik (20)**, **Baru (20)**, **Prediksi Turun**, atau **Scam & Mendekati Rug**, atau ketik nama koin / tempel **Contract Address (CA)** di kotak pencarian atas.
3. Ketuk salah satu koin untuk membuka halaman **Sizer**—periksa **Website & Akun Resmi (Konkret)**, hasil audit kontrak, klaster **Bubblemaps**, dan hitung ukuran masuk **40% / 60%** sebelum menekan tombol beli.
4. Pantau performa model di tab **Audit**, catat hasil transaksi di tab **Jurnal**, dan sesuaikan target atau mesin AI di tab **Pengaturan**.

---

## Tangkapan Layar Setiap Halaman

### 1. Halaman Trending & Radar Live
![Halaman Trending Radar](screenshots/01-trending-radar.png)

### 2. Halaman Audit Model (Akurasi Live)
![Halaman Audit Model](screenshots/02-audit-model.png)

### 3. Halaman Audit Detail & Kalkulator Posisi (Sizer)
![Halaman Audit dan Sizer](screenshots/03-audit-sizer.png)

### 4. Halaman Jurnal Trading & Daily Loss Guard
![Halaman Jurnal Trading](screenshots/04-jurnal-trading.png)

### 5. Halaman Traktir (Dukung Kreator)
![Halaman Traktir](screenshots/05-traktir.png)

### 6. Halaman Pengaturan AI & Strategi
![Halaman Pengaturan](screenshots/06-pengaturan.png)

---

## Struktur File Repository

```text
.
├── index.html                  # Aplikasi utama (single-file HTML)
├── README.md                   # Dokumentasi cara penggunaan & fungsi website
└── screenshots/                # Gambar tangkapan layar setiap halaman
    ├── 01-trending-radar.png
    ├── 02-audit-model.png
    ├── 03-audit-sizer.png
    ├── 04-jurnal-trading.png
    ├── 05-traktir.png
    └── 06-pengaturan.png
```
