# 🏢 IT Service Desk Pro

Sistem manajemen tiket IT (Ticketing System) berbasis Web, lengkap dengan fitur AI Assistant, Real-time Chat, dan Manajemen Aset.

## 🚀 Fitur Utama
- **User:** Submit tiket, upload screenshot, tracking status real-time.
- **Admin:** Manajemen tiket, inventory aset, update status.
- **AI Support:** Integrasi Google Gemini untuk saran solusi teknis otomatis.
- **Real-time Chat:** Diskusi langsung antara User & Admin tanpa refresh halaman.
- **Inventory:** Manajemen data laptop/perangkat kantor.

## 🛠️ Teknologi
- Python (Streamlit)
- SQLAlchemy (SQLite Database)
- Google Gemini API (AI)
- Pandas (Data Processing)

## 📦 Cara Menjalankan (Lokal)
1. Clone repository ini.
2. Install library:
   ```bash
   pip install -r requirements.txt
3. Setup API Key di .streamlit/secrets.toml
4. Jalankan: 
   ```bash
   streamlit run app.py