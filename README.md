# Praktikum Keamanan Sistem Informasi - P06

**NPM:** 24781078  
**Kasus:** LIVE-1  
**Default Model:** `gemini-2.5-flash`  

Proyek ini mendemonstrasikan pengujian keamanan sistem pada implementasi Chatbot Kantin Koperasi berbasis Google Gemini LLM terhadap serangan **Prompt Injection**.

---

## 📁 Struktur Berkas

- [`index.html`](index.html) - Halaman portal navigasi utama untuk mengakses versi Aman dan Rentan.
- [`24781078-kantin-voucher-aman.html`](24781078-kantin-voucher-aman.html) - Implementasi chatbot versi **AMAN** (memiliki mekanisme pertahanan terhadap manipulasi peran dan pembuatan voucher).
- [`24781078-kantin-voucher-rentan.html`](24781078-kantin-voucher-rentan.html) - Implementasi chatbot versi **RENTAN** (rentan terhadap prompt injection/jailbreak untuk menghasilkan voucher diskon ilegal).

---

## 🚀 Cara Penggunaan

1. Buka halaman versi yang ingin diuji melalui peramban web (atau melalui Netlify).
2. Masukkan Google Gemini API Key Anda pada kolom input yang tersedia.
3. Gunakan tombol **Isi payload serangan** untuk menguji ketahanan chatbot terhadap skenario prompt injection.
4. Gunakan tombol **Ekspor log** untuk mengunduh catatan pengujian.
