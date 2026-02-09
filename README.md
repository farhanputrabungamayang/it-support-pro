# 🏢 IT Service Desk Pro (AI-Powered)

Sistem Manajemen Layanan IT (ITSM) modern yang terintegrasi dengan **Google Gemini AI**, **Supabase Cloud Database**, dan **Real-time Chat System**.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.31-red)
![Supabase](https://img.shields.io/badge/Database-PostgreSQL%20(Supabase)-green)
![AI](https://img.shields.io/badge/AI-Google%20Gemini%202.0-orange)

## 🔥 Fitur Unggulan
1.  **🤖 AI Assistant Integration:** Menggunakan Google Gemini 2.0 Flash Lite untuk memberikan saran solusi teknis otomatis kepada Admin.
2.  **☁️ Cloud Database (Supabase):** Data tersimpan aman di PostgreSQL (Server Singapore), bisa diakses dari mana saja.
3.  **💬 Real-time Chat Support:** Diskusi langsung antara User & Admin tanpa perlu refresh halaman (menggunakan Streamlit Fragments).
4.  **📦 Asset Management:** Admin bisa mendata inventaris IT (Laptop, PC, dll) dan User bisa memilih aset yang bermasalah saat melapor.
5.  **⏰ WIB Timezone:** Sistem waktu otomatis sinkron dengan Asia/Jakarta.
6.  **📱 Multi-Platform Notifications:** Integrasi notifikasi ke Telegram & Link WhatsApp.
7.  **📊 Excel Reporting:** Download laporan tiket selesai dalam format Excel rapi.

## 🛠️ Tech Stack
* **Frontend:** Streamlit
* **Backend:** Python
* **Database:** PostgreSQL (via Supabase & SQLAlchemy)
* **AI Engine:** Google Generative AI (Gemini)
* **Drivers:** `psycopg2-binary`, `pytz`

## 🚀 Cara Menjalankan (Local)
1.  Clone repository ini.
2.  Buat file `.streamlit/secrets.toml` dan isi kredensial (API Key & DB URL).
3.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4.  Jalankan aplikasi:
    ```bash
    streamlit run app.py
    ```

---
*Developed by Farhan*
