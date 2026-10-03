# 📊 Benchmarking & Stability Test Protocol

Setiap unit rakitan wajib melewati tahapan tes stabilitas minimal **30-60 menit** sebelum dinyatakan siap (*Passed QC*).

### 1. Thermal & Voltage Baseline (HWInfo64)
- Buka **HWInfo64** (Sensors Only).
- Catat suhu idle CPU & GPU (Standar normal idle: 35°C - 50°C tergantung pendingin & suhu kamar).

### 2. CPU Stress Test (Cinebench R23 / 2024 & Prime95)
- **Cinebench:** Jalankan *10-Minute Throttling Test* Multi-Core.
  * Catat skor Cinebench.
  * Catat suhu maksimum CPU (TjMax). Jika >95°C secara terus menerus, periksa montase cooler/pasta.
- **Prime95 (Opsional/Extreme):** Jalankan *Small FFTs* selama 15 menit untuk cek kestabilan daya VRM motherboard.

### 3. GPU & Power Supply Stress Test (FurMark + Prime95)
- **FurMark 2:** Jalankan stress test pada resolusi native monitor selama 20 menit.
  * Amati temperatur Hotspot GPU (Idealnya <90°C, Core <80°C).
- **Power Supply Stress (Combined Load):** Jalankan FurMark + Cinebench bersamaan selama 15 menit.
  * Jika PC mendadak mati / restart, PSU mengindikasikan Over Current Protection (OCP) atau kapasitas daya kurang.

### 4. RAM Stability Check (MemTest86)
- Boot ke USB MemTest86, jalankan minimal 1 Pass penuh.
- Pastikan hasilnya **0 Errors**. Jika ada error, matikan XMP/EXPO atau periksa posisi slot RAM.
